# Page header

#### Notes for Me :)
- Built with reference to this [post](https://www.filamentgroup.com/lab/build-a-blog/)

- The section between (and including) the two `---` lines is called
    YAML Front Matter. It’s a way to write data into our template file
    that can be used by Liquid templates.

- The layout key tells Eleventy to look for files inside of the
    `_includes` folder to wrap around the content of the template.
    Specifically, we want our blog post to use the `_includes/layout.liquid` file as a wrapper layout. 

- The double curly braces in `layout.liquid` indicate a variable: 
    e.g., where the markdown content will go