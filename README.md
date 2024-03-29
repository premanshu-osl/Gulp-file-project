# Gulpfile Boilerplate

## What is the Use?

This boilerplate can be used for:

1. Compiling SASS files to CSS files
2. Prefixing the compiled CSS for browser compatibility
3. Ordering and grouping CSS for similar properties
4. Splitting the CSS files for IE support
5. Combining, minifying and transpiling JS files

## How to use?

1. Clone or Download this repository
2. Open your terminal or command prompt and navigate to the directory
3. Once inside the directory for the boilerplate, type the following command:  
`npm`  
and hit return/enter
4. Some packages are going to be installed and it may take some time
5. Finally, in your terminal/command prompt type:  
`gulp`  
and hit return/enter

## Path variables?

```
const files = {
  scssPath: 'src/sass/**/*.{scss, sass}',
  jsPath: 'src/js/**/*.js'
}
```

## Prerequisites to use?

1. Node - Tested on 10.16.3 and 12.9.1
2. NPM - 6.9.0
2. Gulp 
  * CLI Version - 2.2.0
  * Version - 4.0.2

This gulpfile was created in the above environment is stable. Use the above versions to avoid any compatibility issues. More support will be added over time.