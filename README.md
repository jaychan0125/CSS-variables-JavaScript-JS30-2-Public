
CSS variable 
:root {     <--declare on root, 
   --varName: value;     <-- use the two dashes '--' to set a variable 
}
var(--varName) <-- to use it, let CSS know it is a variable, by 'var()'.  will use the value stored in it



- nodeList is different from an array. only have a couple of methods (some people will make their nodeList into an array)

- dataset =  object that contains all the data-attributes set on an element. 


document.documentElement.style.setProperty(`--${this.name}`, this.value + suffix);
- in this entire document
- style.setProperty  --> method to set a new value for a property
- setProperty syntax  (propertyName,  value)
- in our case, the propertyName is a variable
-    - and the value is dynamically changed
-    - some values need to have a suffix of 'px' to work, so append that to the value
- because the property is a CSS variable, once the value is changed:    anytime the CSS variable is used, the value assigned to the property is also used!



