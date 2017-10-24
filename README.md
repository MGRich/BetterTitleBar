# BetterTitleBar
![Preview](https://rawgit.com/MGRich/BetterTitleBar/master/DiscordCanary_2017-10-21_17-01-57.png)
![Preview](https://rawgit.com/MGRich/BetterTitleBar/stable/Discord_2017-10-21_23-22-34.png)
Makes the new titlebar much cleaner and customizable.
To use this, put this at the start of your custom css:
```@import url(https://rawgit.com/MGRich/BetterTitleBar/master/code.css);```
## Variables
To use the variables, position them like this.
```css
:root {
    --btb-icon-stroke:white; /* for canary */
    --btb-discord-color:white; /* for canary */
    --btb-color:#171717;
    --btb-border:#252525;
    --btb-light:1; /* 1 for dark, 0 for light, NOTE: THE BACKGROUNDS BREAK WITH THIS SET TO 0. will do nothing in canary, as replaced by icon stroke and discord color*/
    --btb-close-hover:#E81123;
    --btb-close-active:#F1707A;
    --btb-mm-hover:#363636;
    --btb-mm-active:#505050;
    --btb-titlebar-height:32;
    --btb-button-width:48px;
}
```
`--btb-color` will change the entire titlebar color.
`--btb-border` while change the bottom border color.
`--btb-icon-stroke` will change the icon color. Only for canary.
`--btb-discord-color` will change the color of the Discord icon. Only for canary.
`--btb-title-height` is the titlebar height in px. Do not add a `px` after it.
Rest of them are pretty self explainatory.
