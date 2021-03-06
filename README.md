# Single Page Site

## Installation
- ```npm install```

## Build CSS/JS
- ```npm run prod```

To recompile automatically when files are changed:
- ```npm run watch```


## Description
This repo contains some starter tooling for a simple single page site. The JS files in the JS folder will concatenate and/or Uglify (prod) automatically. The SCSS files in the SCSS folder will compile to CSS and have PostCSS applied (prod) automatically. The index.html file contains only the basic HTML to get started and pulls in the JS and CSS automatically.

## Instructions
Using the provided APIs below (or a similar comparable API), create an app that does something with the data.

### API URLs
- https://mitigation.tti.tamu.edu/wp-json/wp/v2/txdot_roadways
- https://mitigation.tti.tamu.edu/wp-json/wp/v2/txdot_projects
- https://mitigation.tti.tamu.edu/wp-json/wp/v2/regionalproject

Note: The default pagination is 10 and you can use the ?per_page= URL variable to change that from 1 to 100 (ex: ?per_page=100).

### Potential ideas for an app
- A searchable listing of roadways with categorization.
- A listing of roadways with expanding references to the related data.
- A data visualization using the metadata to illustrate the cost, time, or other data for roadways.
- A map (best you can using county or something) that allows for interactive display of the data.

### Some notes about the data in the API
- Roadways are related to txdot_projects and regionalproject
- Roadways contains a property that is an array of related object IDs for projects and regionalprojects.
- The metadata property contains related data for the object.

## Rules
- The site needs to be able to run easily on a local environment. Please include instructions on how to build/run and access the site.
- You are welcome to use any tool or framework you are comfortable with.
- Back-end scripting (node.js, php, etc) can be used, but again provide clear instructions.
- Please try limit your time to about 15 hours. There is no minimum or maximum. We do not expect this to be a fully completed app or site, just a good effort and working.
- The submitted project should contain all source code. Ideally, you should send back a link to a Github repo.
