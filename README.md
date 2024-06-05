# Eludris Client Theme Store

This repository contains custom themes for the [official eludris client](https://github.com/eludris/client).
You can create a Pull Request to this repository to have your theme displayed inside the client!

## How do I add my theme?

To add your theme, open a Pull Request that adds a new object to the array in [themes.json](https://github.com/eludris/theme-store).
A valid theme entry contains:

- `name`: The name of your theme, between 2 and 32 characters long;
- `author`: The author name you want to show in the client;
- `description`: A description that is between 16 and 128 characters long;
- `cover_url`: A url to a cover image, ideally with aspect ratio 16:9;
- EITHER
    - `repo_url`: A url to a GitHub repository that contains a `style.css` and a `README.md`, case-sensitive.
    This automatically infers the correct file urls.
  
  OR 

    - `repo_url`: A url to your theme's external repository (e.g. GitLab, Github Gist) or website;
    - `readme_url`: A url to the **raw** description markdown file;
    - `style_url`: A url to the **raw** style css file.

Please use the existing themes as examples if necessary.
