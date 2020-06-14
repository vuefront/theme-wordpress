# VueFront Wordpress Theme
This is the official VueFront Theme for Wordpress. 

## Installation
### Installation with Create-VueFront-App
1. You must first install your VueFront Web App. [yarn create vuefront-app](https://github.com/vuefront/create-vuefront-app)
2. During installation process when promited to choose a theme, pick `WordPress`

### Installation on an existing VueFront App
1. Run command `yarn add @vuefront/theme-wordpress`
2. Edit files:
add to `vuefront.config.js` new item `theme`
```
  export default {
        theme: '@vuefront/theme-wordpress',
```
3. Run command `yarn dev`

Enjoy!
