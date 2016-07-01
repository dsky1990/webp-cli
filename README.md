# webp-cli

This is a tool to init a web development.

# Installation

```
$ npm install webp-cli -g
```

# Init

init the project

```
$ webp init
``` 

after init, we can see the directory structure like this

```
+ build      // dev floder
  - css      // sass to css floder
  - js       // js floder
  - images   // image floder
  - icon     // icon floder
  - sass     // sass floder
+ dist       // publish floder
+ vendor     // the plugin floder
.eslintrc    // eslint file to verify js file
.stylelintrc // stylelint flie to verify sass file
gulpfile.js  // gulpfile file to run the task we need
package.json // the package we need
```

# Install package

```
webp install
```

# Run task

```
webp
```