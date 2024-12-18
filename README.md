# Eludris Client Themes

This repository contains custom themes for the [official eludris client](https://github.com/eludris/client).
You can create a Pull Request to this repository to have your theme displayed inside the client!

## How do I add my theme?

To add your theme, open a Pull Request that adds a new object to the array in [themes.json](https://github.com/eludris/theme-store).
A valid theme entry contains:

- `name`: The name of your theme, between 2 and 32 characters long;
- `author`: The author name you want to show in the client;
- `description`: A description that is between 16 and 128 characters long;
- `cover_url`: A URL to a cover image, ideally with aspect ratio 16:9;
- `repo_url`: A URL to your theme's external repository or website;
- `readme_url`: A URL to the **raw** description markdown file;
- `style_url`: A URL to the **raw** style css file.

All of these URLs must be on trusted domains. For example, the cover image has to be an Effis URL; and the repo, readme, and style URLs ideally link to a well-known public host such as Github, Gitlab, Codeberg, etc.

Please use the existing themes as examples if necessary.
