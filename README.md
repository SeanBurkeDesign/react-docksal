# react-docksal
Set up a new Docksal instance with React, Webpack and Babel

### Dependencies
- Docksal
- NodeJS

### Installation
1. Run `fin init` from project root directory

### Commands
1. `fin exec npm run development` - runs webpack using the development config.
2. `fin exex npm run build` - runs webpack using the production config.
3. `fin exec npm` - for running npm commands

### Directory Structure
- `app/` - The entry point for webpack. All work should be done here.
- `build/` - The output directory for webpack. Deleted and rebuilt every time webpack is run. **DO NOT** work from this directory.

## To-do
- [ ] Add ESLint
- [ ] Add Stylelint
- [ ] Add SASS
- [ ] Add Autoprefixer
- [ ] Setup webpack development server
- [ ] Enable module hot reloading
- [ ] Configure webpack for handling static assets
