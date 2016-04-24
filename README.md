Beautiful Tips
==============
A Simple Sass Mixin For Generating Tooltips.
--------------------------------------------

This ones simple. Just import the index file from the Beautiful Tips directory
and use the mixin: syntax is as follows:

`@include generate-tooltips(`

    selector <required>,
    
    border-color <required>,
    
    background-color <required>,
    
    text-color <required>,
    
    opacity <not required>,
    
    custom-border <not required>,
    
    custom-transition <not required>,
    
    custom-transition-time <not required>,
    
    custom-delay-time <not required>,
    
    custom-scale <not required>,
    
    custom-border-radius <not required>
    
`)`

Any of the non-required fields can be overloaded by simply
typing, for example, "$custom-transition-time : 5s".
