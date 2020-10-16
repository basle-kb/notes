- test of Zenith
    - zenith theme```clojure
/* IMPORT CORE THEME */
@import url('https://azlen.github.io/roam-themes/core.css');

/* GOOGLE FONTS */
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:ital,wght@0,400;0,700;1,400;1,700&display=swap');	

:root {	
    --page-width: 616px;
    --page-order: row-reverse; /* new pages show up to the right */
    /*--page-order: row; /* new pages show up to the left */
    
    --header-font: "Source Sans Pro", "Inter", sans-serif;	
    --body-font: "Source Sans Pro", "Inter", sans-serif;	
    	
    --bg-color: [EEEEEE](<../EEEEEE.md>);	
    --page-color: rgba(255, 255, 255, 0.95);	
    	
    --text-color: [000000](<../000000.md>);	
    --icon-color: [5c7080](<../5c7080.md>);
    --bullet-color: rgba(0, 0, 0, 0.2);	
    	
    --page-shadow: 0px 8px 14px rgba(0, 0, 0, 0.05);	
    	
    --color-primary: 73, 197, 91;	
    --color-primary-contrast: [FFFFFF](<../FFFFFF.md>);	
    --color-secondary: 147, 100, 235;

    --color-secondary-contrast: [FFFFFF](<../FFFFFF.md>);	
}

/* CHANGE COLOURS IN CANVAS */
canvas[data-id="layer2-node"] {	
    filter: invert(1) hue-rotate(110deg) saturate(2.5);	
}
```
        - 
- Appleton Theme with Garamond
    - ```css
/*  Make sure you have the fonts Lato and Open Sans installed locally on your machine.
They're free to download from Google:
https://fonts.google.com/specimen/Lato
https://fonts.google.com/specimen/Open+Sans  */
body {
  font-size: 120%;
}
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: 'Whitney';
}

div,
textarea {
  font-family: 'Palatino';
}

.roam-block-container {
    max-width: 1000px;
}

.rm-query {
    border: 0.5px solid [e4e9ec](<../e4e9ec.md>);
    border-radius: 5px;
    
}

.rm-query .rm-query-title {
    background-color: [f7f8f8](<../f7f8f8.md>);
    padding: 0.8em;
    color: [d1dbe2](<../d1dbe2.md>);
    font-size: 80%;
}

.rm-reference-main.rm-query-content {
    padding: 0.8em;
}

.rm-reference-main .rm-reference-item .rm-block-text {
    font-size: 90%;
}

.rm-ref-page-view-title span {
    
}

.rm-reference-main .rm-reference-item .controls {
    margin-left: -1em;
}

.rm-ref-page-view {
    padding: 0.4em 0.2em;
}

.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper .starred-pages .page {
    padding: 6px;
}

div.flex-v-box.starred-pages-wrapper > div.flex-h-box > span {
    font-size: 14px;
    opacity: 80%;
    letter-spacing: 0.04em;
}

div.roam-sidebar-container.noselect > div > div {
    font-size: 14px;
    letter-spacing: 0.03em;
    
}

[block-input](<../block-input.md>) {
    background: white;
}

.roam-body [block-input](<../block-input.md>) > span > div {
    padding: 6px 24px;
    background: white;
}

span.bp3-icon-small.bp3-icon-star {
    display: none;
    visibility: hidden;
}

.roam-block {
    max-width: 850px;
}

[right-sidebar](<../right-sidebar.md>) > div {
    background-color: [f7f8fa](<../f7f8fa.md>);
    border-left: 1px solid [e9ebef](<../e9ebef.md>);
}
.rm-page-ref-brackets {
    display: none;
}
.controls .simple-bullet-outer .simple-bullet-inner {
    background-color: [e5e9f2](<../e5e9f2.md>);
}
.block-border-left {
    border-left: 1px solid [fff](<../fff.md>);
}
.kanban-board {
    background-color: [fff](<../fff.md>);
}
.kanban-card {
    background-color: white;
    margin: 8px;
    box-shadow: 0px 1px 2px [9EB3C0](<../9EB3C0.md>);
    padding: 10px;
    border-radius: 2px;
    line-height: 1.3em;
}
.kanban-title {
    text-align: center;
    font-weight: bold;
    padding-top: 6px;
}
.kanban-column {
    background-color: [E4EDF2](<../E4EDF2.md>);
    margin: 0px 4px 0px 4px;
    padding: 4px;
    min-width: 200px;
    border-radius: 3px;
}
.rm-block-ref::before {
    content: '';
    display: inline-block;
    width: 10px;
    border-radius: 40px;
    height: 10px;
    background: [ff913c](<../ff913c.md>);
    margin-right: 5px;
}
.rm-block-ref {
    border-bottom: none;
    font-size: 1em;
    color: [627a9d](<../627a9d.md>);
}
.rm-block-ref:hover {
    background: none;
    cursor: pointer;
}
.checkmark {
    background: [fff](<../fff.md>);
}
.check-container input:checked ~ .checkmark {
    background: [33bdea](<../33bdea.md>);
}
.check-container input:checked ~ .checkmark:after {
    border-color: [fff](<../fff.md>);
}
.rm-reference-item {
    margin-top: 8px;
    border-radius: 6px;
    border: 1px solid [e4e9ee](<../e4e9ee.md>);
    margin-right: 8px;
    flex: 1 1 100%;
    word-break: break-word;
    background-color: [f7f9fb](<../f7f9fb.md>);
    padding: 8px;
}

.rm-level2 {
    font-size: 1.5em;
}
.rm-level3 {
    color: [939aae](<../939aae.md>);
    font-weight: 400;
    font-size: 1.3em;
}
.rm-page-ref {
    color: [9aabd0](<../9aabd0.md>);
}
.rm-page-ref-link-color {
    color: [ec6f35](<../ec6f35.md>);
    font-weight: 600;
}
a {
    color: [8A3CC8](<../8A3CC8.md>);
}
.intercom-app,
.intercom-launcher-frame,
[intercom-container](<../intercom-container.md>) {
    display: none;
}
.roam-body .roam-app .roam-sidebar-container {
    background-color: white;
    border-right: 1px [eee](<../eee.md>) solid;
}
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper .starred-pages .page,
.roam-body .roam-app .roam-sidebar-container > * {
    opacity: 90%;
    box-shadow: none;
}
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper .starred-pages .page:hover,
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .log-button:hover {
    background: white;
    color: black;
    opacity: 100%;
}
[buffer](<../buffer.md>).tall {
    height: calc(100vh - 50px);
}
.check-container {
    padding-right: 4px;
}
span.rm-page-ref {
    border-radius: 2px;
    padding-left: 1px;
    padding-right: 1px;
}
.content span.rm-page-ref {
    padding: 4px 1px 1px;
    /* required for fixing azo */
}
.center-proj {
    text-align: center;
}


/* Custom data tags */
span.rm-page-ref[data-tag="TwitterPost"] {
    background: [81D5ED](<../81D5ED.md>);
    color: white;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Literature Notes"] {
    background: [9769FF](<../9769FF.md>);
    color: white;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}


span.rm-page-ref[data-tag="Evergreens"] {
    background: [0DBAC6](<../0DBAC6.md>);
    color: [fff](<../fff.md>);
    padding: 3px 8px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Seedling"] {
    color: [0dbac6](<../0dbac6.md>);
    padding: 3px 3px;
    font-weight: 600;
    line-height: 1.4em;
}

span.rm-page-ref[data-tag="Idea Bank"] {
    color: [FCB815](<../FCB815.md>);
    padding: 3px 4px;
    font-weight: 700;
    line-height: 1.4em;
}

span.rm-page-ref[data-tag="Idea Bank"]:before {
    content: '✦ '
}

span.rm-page-ref[data-tag="Illustrated Notes"] {
    color: [7172FC](<../7172FC.md>);
    padding: 3px 4px;
    font-weight: 700;
    line-height: 1.4em;
}

span.rm-page-ref[data-tag="Garden Notes"] {
    color: [9DBC13](<../9DBC13.md>);
    padding: 3px 4px;
    font-weight: 700;
    line-height: 1.4em;
}

span.rm-page-ref[data-tag="Video Tutorial"] {
    color: [db3b8d](<../db3b8d.md>);
    padding: 3px 4px;
    line-height: 1.4em;
    font-weight: 700;
}

span.rm-page-ref[data-tag="Essay"] {
    background: [ADCB2A](<../ADCB2A.md>);
    color: [fff](<../fff.md>);
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}


span.rm-page-ref[data-tag="Livestream"] {
    color: [B979CF](<../B979CF.md>);
    padding: 3px 4px;
    line-height: 1.4em;
    font-weight: 700;
}

span.rm-page-ref[data-tag="Talk"] {
    background: [7172FC](<../7172FC.md>);
    color: [fff](<../fff.md>);
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Waiting"] {
    background: [F9C866](<../F9C866.md>);
    color: [fff](<../fff.md>);
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Researching"] {
    background: [FF9D66](<../FF9D66.md>);
    color: [fff](<../fff.md>);
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Synthesising"] {
    background: [FC766F](<../FC766F.md>);
    color: [fff](<../fff.md>);
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}


span.rm-page-ref[data-tag="Alive"] {
    background: [EE5F85](<../EE5F85.md>);
    color: [fff](<../fff.md>);
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}
© 2020 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
```
    - 
- Neue Theme
    - ```html
@import url('https://neue-roam-theme.glitch.me/theme.css');```
- Neue Dark Theme
    - ```css
@import url('https://neue-roam-theme.glitch.me/dark.css');```
    - 
