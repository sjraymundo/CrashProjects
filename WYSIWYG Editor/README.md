# WYSIWYG Editor

Goal is to provide a markdown-type HTML formatting to content.

Currently, it relies heavily on ```document.execCommand()``` which is already obsolete.

An entry from [StackOverflow](https://stackoverflow.com/questions/60581285/execcommand-is-now-obsolete-whats-the-alternative) suggests use of the following javascript methods instead:
``` javascript
document.createRange()
window.getSelection()
appendChild
insertBefore
insertBefore + nextSibling
replaceChild
```
