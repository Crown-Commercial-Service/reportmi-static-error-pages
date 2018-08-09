# Report management information to CCS
## Static error page generator
A simple build tool to create the static error pages for the Report management information to CCS service.

Generates:

- 404 page
- 500 page
- 422 page
- maintainence page

## Install
- Clone the repo and run `npm install` in the directory.

## Use
- Edit the src/*.md files to alter the content
- Run `npm build` to create the files and assets.
- Copy the html files and assets directory from the build directory to the Rails app public directory, the stylesheets directory is not required as css is inlined by the build step.

## Developing
- Run `npm start` to launch a small server to view the files locally e.g. http://localhost:8080/404.html
- Styles are from the GOVUK Frontend with some overrides which come from the main frontend app.
