### 1. Hover
The hover effect in CSS is triggered when a user moves their cursor over an element, typically used to change the appearance of buttons, links, or images. It's often used to make websites more interactive and responsive.



Eg:
``` jsx
button:hover {
    background-color: blue;
    color: white;
}

```
### 2. Active :
The active in CSS represents an element (like a button or link) that is in the process of being clicked by the user. This effect is triggered while the user presses the mouse button down on the element and holds it. 

Eg:
``` jsx
button:active {
    background-color: red;
    transform: scale(0.95);
}

```

### 3. Opacity:
Opacity in CSS controls the transparency level of an element. It ranges from 0 (completely transparent) to 1 (fully opaque). It is commonly used to make elements see-through or to create hover effects where an element gradually becomes more or less visible. 

Eg:
``` jsx
div {
    opacity: 0.5; /* 50% transparent */
}


```

### 4. Transition:
The transition property in CSS allows you to smoothly animate changes to CSS properties over a specified duration. Instead of changing instantly, the value transitions over time. It can be applied to properties like color, background, width, height, opacity, and more. 

Eg:
``` html 
button {
    background-color: blue;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: green;
}


```

