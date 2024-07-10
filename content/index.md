---
{
    .title = "Tech",
    .date = @date("2020-07-06T00:00:00"),
    .author = "Justin Braben",
    .draft = false,
    .layout = "index.html",
    .tags = [],
}  
--- 

# What is Zine?
A Zine site is a collection of markdown files, HTML templates and static assets. Zine turns your markdown content into HTML, styles it using your templates, and finally copies the result alongside your static assets into an output directory that you can then publish on static hosting services like GitHub Pages.

Zine is "low-code" by default, but once the needs of your project grow, then you will have the full power of the Zig build system at your disposal, allowing you to integrate any kind of pre-processing pipeline.