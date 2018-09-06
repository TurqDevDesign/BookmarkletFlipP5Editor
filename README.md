# BookmarkletFlipP5Editor

Bookmarklet to flip P5.js online editor.

## Instructions

Visit <a href="https://codingtrain.github.io/BookmarkletFlipP5Editor/">the bookmarklet's page</a> and drag the link to your browser toolbar.

![Animated demonstration of p5 flip bookmarklet](https://codingtrain.github.io/BookmarkletFlipP5Editor/flip_p5.gif)


## Code

```javascript
javascript:(function()%7B var style %3D document.createElement(%27style%27), styleContent %3D document.createTextNode(%27.editor-preview-container>.SplitPane>.Pane1, .editor-preview-container>.SplitPane>.Pane2>.SplitPane>.Pane1 %7B order: 2 !important%3B %7D .editor-preview-container>.SplitPane>.Resizer, .editor-preview-container>.SplitPane>.Pane2>.SplitPane>.Resizer %7B order: 1 !important%3B %7D .editor-preview-container>.SplitPane>.Pane2, .editor-preview-container>.SplitPane>.Pane2>.SplitPane>.Pane2 %7B order: 0 !important%3B %7D div.editor-preview-container>div>div.Pane.vertical.Pane2>div>div.Pane.vertical.Pane1>div>div.Pane.horizontal.Pane1>section>header>button.sidebar__expand, div.editor-preview-container>div>div.Pane.vertical.Pane2>div>div.Pane.vertical.Pane1>div>div.Pane.horizontal.Pane1>section>header>button.sidebar__contract%7B right: 0.08333rem !important%3B left: auto !important%3B transform: rotate(180deg) !important%3B %7D div.editor-preview-container>div>div.Pane.vertical.Pane2>div>div.Pane.vertical.Pane1>div>div.Pane.horizontal.Pane1>section>header>.editor__file-name %7B padding-left: 0 %7D div.editor-preview-container > div > div.Pane.vertical.Pane1 > nav > div.sidebar__root-item > ul > li button.sidebar__file-item-show-options %7B padding-right: 20px !important%3B padding-left: .5rem !important%3B %7D div.editor-preview-container > div > div.Pane.vertical.Pane1 > nav > div.sidebar__header %7B padding-right: 20px !important%3B %7D input:active, input:focus, button:active, button:focus %7B outline: none %7D%27)%3B style.appendChild(styleContent )%3B var caput %3D document.getElementsByTagName(%27head%27)%3B caput%5B0%5D.appendChild(style)%3B %7D)()%3B
```
