# CSS pseudo class selectors / jQuery-UI

A CSS pseudo-class is a keyword added to selectors that specifies a special state of the element to be selected. 
 
Syntax example: 
```
  selector:pseudo-class {
    property: value;
  } 
  ```
  ```
  element:nth-child(an + b) {
      style properties; 
  }
  ```
  
  ```
  element:after {
    content: "";
  }


  element:before {
     content: "";
  }
  ```
  ```
  input:invalid {
     background-color: #ffdddd;
  }
  ```
  
Some of the selectors include: hover, before, after, n-child, link, visited, active. </br>
Link to all the different selectors and their description: https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes
 
jQuery UI is away to make your html elements more interactive and some examples include dragging and resizing. </br>
link to docs: https://jqueryui.com 

```
$(document).ready(function () {
  $("#datepicker").datepicker(); 
  $("#draggable").draggable();
  $("#draggable").resizable(); 
  $("#sortable").sortable();
 });
