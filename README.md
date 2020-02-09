### Required:
  - NPM and NodeJS

### Install project dependencies:
  1. npm install

#### Environment Support:
localhost, staging, production

#### To compile the project:
> assemble serve --env <environment>

#### To create the distribution package:
> assemble build --env production

#### Development notes:
  - {{config.asset_url}}: for the path to the assets folder as we will have different location to store images and other files and it's not relative to the current directory. e.g: images/your_image_filename.jpg become {{config.asset_url}}/your_image_filename.jpg
  - {{config.base_url}}: for the base path to the main mccy site 
  - {{config.ga_id}}: Google analytics ID
  - {{config.ga_domain}}: Google analytics allow domain
  - Don't mention http/https protocol to the absolute path url as the production site will support both http and https.