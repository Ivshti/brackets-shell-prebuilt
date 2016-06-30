# brackets-shell-prebuilt
WIP

This is supposed to be a package to install Brackets Shell prebuilts, work in progress at the moment.

Brackets Shell is supported by Adobe. Unlike Electron or NW.js, uses a separate process for Node.js. 

This allows using vanilla CEF3 and Node.js, which has a few added benefits:

* Forces you to write clean architecture
* Allows your front-end to stay entirely in HTML5 and using web technologies, which allows your apps to expand to web
* Ensures there are no technical difficulties or complexities from wiring node.js directly in a web browser
