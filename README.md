Super small and simple way to add the Konami Code (or a custom code) easter egg to your web page. Attach any number of easter eggs to any number of elements in your page.

Usage:

Call the eggify() function with a config object as argument.

The config object accepts 4 parameters:

'e', short for 'element', the element to attach the easter egg to. Defaults to document.body. 's', short for 'sequence', an array contining the keyCode sequence which will activate the easter egg. Defaults to the Konami Code. 'r', short for 'repeatable', specifies if the easter egg can run only once (false) or be repeated (true). Defaults to false. 'c', short for 'callback', the function to run when the easter egg has activated. Defaults to adding #HATCHED to the current URL.

Although all four parameters are optional, at least the callback parameter should be specified to make this useful.

See eggify.htm for usage examples.