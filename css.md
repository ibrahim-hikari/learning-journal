# CSS

### CSS is the presentation of our website pages, making the boring HTML code look colorful, it control how elemnts show up in the page (decorate it)

- The structure of css created of selector and declaration;
  - the selector is the tag you want to decorate, there is about 8 types of selector like tag selector and id selector 
  - the declaration in the otherhand sit inside curly brackets made up of two parts: 
  1. property:the **aspect** of element you wanna change like color, font, hight, ...etc
  1. value: specify the settings you want to use for the chosen properties like blue, 20px, ...etc 

- There are two types of how you use css 
1. internal css: inside the head tag in the HTML file creating a new tag named style 
inside the style tag you can decorate whatever you want  
1. external css: outside file not in the HTML file you can start with the selector right away 

#### Example

1. Inside css

```
<head> ... </head>
<style>
p {
    color: green;
} 
</style>

```

1. outsie css

```

p {
    font-family: timesnewroman;
}

```