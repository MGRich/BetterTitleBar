# BetterTitleBar
This version supports stable, with a small limitation.
![Preview](https://rawgit.com/MGRich/BetterTitleBar/stable/Discord_2017-10-21_23-22-34.png)
Makes the new titlebar much cleaner and customizable.
To use this, put this at the start of your custom css:
```@import url(https://rawgit.com/MGRich/BetterTitleBar/stable/code.css);```
## Variables
To use the variables, position them like this.
```
:root {
    --btb-color:#171717;
    --btb-border:#252525;
    --btb-light:1; /* 1 for light, 0 for dark, NOTE: THE BACKGROUNDS BREAK WITH THIS SET TO 0.*/
    --btb-close-hover:#E81123;
    --btb-close-active:#F1707A;
    --btb-mm-hover:#363636;
    --btb-mm-active:#505050;
    --btb-titlebar-height:32;
    --btb-button-width:48px;
}
```
`--btb-color` will change the entire titlebar color.
`--btb-light` while change the bottom border color.
`--btb-dark` will change the icon and Discord color to white or black, as as listed, 0 will break the custom background colors.
Rest of them are pretty self explainatory.
