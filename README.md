# About this repository
# Best practices  
## Make it readable.   
In this way your CSS will be much easier to maintain in the future, and also you´ll be able to find elements in a heartbeat.  
## Use multiple stylesheets, but be aware of them expanding beyond control.   
Depending on the complexity of the design and the size of the site, sometimes it’s easier to make smaller, multiple stylesheets instead of a giant one. If you cross the line and end up having too many stylesheets it might be hard to follow and find where some styles are.
## Test WHILE you build to avoid cross-browser issues  
One of the biggest mistake I ever made when developing html, CSS, and javascript, was not to test my pages on multiple browser while I was writing them. Instead, I used to write all my code and just view in Firefox to see how it was rendered.
In theory, this should be good. But as you know, cross-browser issues are a major problem for front-end developers, especially due to IE. If you test your documents on Firefox/IE/Chrome while your writing it, cross-browser rendering problems will be much easier to fix. I have lost hours not doing it, so I hope this final tip will help you saving your precious time. To test on multiple versions of IE, I use this very handy tool. Happy coding.  
## Commenting
Explain design or architectural decisions that cannot be conveyed in code alone by adding comments to your code.

Be sure that in conjunction with writing code that adheres to these guidelines, someone can pick up your code and immediately understand it.

Be verbose with your comments but ensure:

* Your comments add something to the code, they don't just repeat what is there

* They are kept up to date, if you change something that has been commented, ensure you up date the comment as well

* If code needs extensive commenting, can it be refactored to make it less complex / easier to understand?

* You focus on why rather than how - unless your code is too complex, it should be self documenting

Don't leave commented out chunks of code in the codebase. It makes the code look unfinished, and can be confusing for other developers.
# Image Gallery
# Async API Data
