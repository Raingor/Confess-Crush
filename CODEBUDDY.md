# CODEBUDDY.md
This file provides guidance to CodeBuddy Code when working with code in this repository.

## Development Overview

This is a static web application for confessing love/crush. The project consists of HTML, CSS, and JavaScript files with no build system, dependencies, linting, or testing framework.

## Common Development Commands

As this is a static site with no build system:
- **No build commands required** - Changes take effect immediately when files are saved
- **No lint commands required** - No linter is configured for this project
- **No test commands required** - No testing framework is set up for this project
- **Development workflow**: Edit files directly and commit changes to see updates

## Key Files and Structure

- `index.html`: Main page structure with buttons, audio, and animations
- `css/style.css`: Styles for the confession page
- `css/spinload.css`: Loading animation styles
- `js/main.js`: Core JavaScript logic for page interactions and animations
- `config.js`: Configuration file for text content (crush name, messages, links)
- `imagesGithub/`: Image assets used in the application
- `img/`: Additional image resources
- `sound/`: Audio files for background music
- `README.md`: User guide for editing and deploying the application

## Development Workflow

### Editing the Confession Page Content

To modify the page content:
1. Edit the `config.js` file
2. Each field controls different text:
   - `titleWeb`: Browser tab title
   - `introTitle`: The crush's name shown on the intro button
   - `introDesc`: Description text shown on intro button hover
   - `btnIntro`: Intro button text
   - `title`: Main question/title text
   - `desc`: Description paragraph text
   - `btnYes/btnNo`: Yes/No button text
   - `question`: Question shown after clicking Yes
   - `btnReply/reply`: Reply button and reply message
   - `mess/messDesc`: Final message and description
   - `btnAccept`: Accept button text
   - `messLink`: Link to personal messaging page

## Important Notes

- This is a static site with no server-side components
- All content changes are made by editing the config.js file
- Images should be placed in the appropriate directories and referenced correctly
- No build steps or package managers are required
- Changes are immediately visible after committing to GitHub
- The application is designed to work with the existing HTML structure