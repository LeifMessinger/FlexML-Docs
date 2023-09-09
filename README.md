# FlexML
Now, everything is a div, and a flexbox!

# Why?
Flexboxes suck, but I think they suck because they are underused.

In this 1.0 version, I made flexboxes in html easy using attributes and classes. The 2.0 version would happen whenever `attr` gets implemented in the major browsers. FlexML 3.0 would be some xml or xhtml to html compiler, where you don't have to say `div` anymore, it's just implied, and you can go `<bruh 1 0 10% />` and it would make a div with a `flex: 1 0 10%;` property. If `attr` never gets implemented, I might have to skip to 3.0.

# File layout
`FlexML.css` imports `reset.css`, so you'll need both unless you want to remove the import line at the top.

`test.html` Shows how you'd make a simple webpage with it.

`testLazy.html` Shows how the `grow` attribute works, which is also how the `shrink`, `nogrow` stuff works. I'd love to be able to do `grow=".2"` or something, but CSS `attr` needs to be implemented on all the browsers first.

# Todo:
Make an index.html with a bunch of example code showing how you can make rows and columns.

Do a bunch more justify and align classes (again, would be better if we had `attr`).
