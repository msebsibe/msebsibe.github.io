layout: page
title: "wine"
permalink: /info/

<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>FinalProject</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>




<style type="text/css">
    pre { line-height: 125%; }
td.linenos .normal { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
span.linenos { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
td.linenos .special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
span.linenos.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
.highlight .hll { background-color: var(--jp-cell-editor-active-background) }
.highlight { background: var(--jp-cell-editor-background); color: var(--jp-mirror-editor-variable-color) }
.highlight .c { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment */
.highlight .err { color: var(--jp-mirror-editor-error-color) } /* Error */
.highlight .k { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword */
.highlight .o { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator */
.highlight .p { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation */
.highlight .ch { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Multiline */
.highlight .cp { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Preproc */
.highlight .cpf { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Single */
.highlight .cs { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Special */
.highlight .kc { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Pseudo */
.highlight .kr { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Type */
.highlight .m { color: var(--jp-mirror-editor-number-color) } /* Literal.Number */
.highlight .s { color: var(--jp-mirror-editor-string-color) } /* Literal.String */
.highlight .ow { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator.Word */
.highlight .w { color: var(--jp-mirror-editor-variable-color) } /* Text.Whitespace */
.highlight .mb { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Bin */
.highlight .mf { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Float */
.highlight .mh { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Hex */
.highlight .mi { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer */
.highlight .mo { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Oct */
.highlight .sa { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Affix */
.highlight .sb { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Backtick */
.highlight .sc { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Char */
.highlight .dl { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Delimiter */
.highlight .sd { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Doc */
.highlight .s2 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Double */
.highlight .se { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Escape */
.highlight .sh { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Heredoc */
.highlight .si { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Interpol */
.highlight .sx { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Other */
.highlight .sr { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Regex */
.highlight .s1 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Single */
.highlight .ss { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Symbol */
.highlight .il { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer.Long */
  </style>



<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
 * Mozilla scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */
[data-jp-theme-scrollbars='true'] {
  scrollbar-color: rgb(var(--jp-scrollbar-thumb-color))
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar. These selectors
 * will match lower in the tree, and so will override the above */
[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
}

/* tiny scrollbar */

.jp-scrollbar-tiny {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
  scrollbar-width: thin;
}

/*
 * Webkit scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar,
[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-corner {
  background: var(--jp-scrollbar-background-color);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-thumb {
  background: rgb(var(--jp-scrollbar-thumb-color));
  border: var(--jp-scrollbar-thumb-margin) solid transparent;
  background-clip: content-box;
  border-radius: var(--jp-scrollbar-thumb-radius);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-track:horizontal {
  border-left: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
  border-right: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-track:vertical {
  border-top: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
  border-bottom: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar */

[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar::-webkit-scrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar::-webkit-scrollbar,
[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-corner,
[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-corner {
  background-color: transparent;
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-thumb,
[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
  border: var(--jp-scrollbar-thumb-margin) solid transparent;
  background-clip: content-box;
  border-radius: var(--jp-scrollbar-thumb-radius);
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-track:horizontal {
  border-left: var(--jp-scrollbar-endpad) solid transparent;
  border-right: var(--jp-scrollbar-endpad) solid transparent;
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-track:vertical {
  border-top: var(--jp-scrollbar-endpad) solid transparent;
  border-bottom: var(--jp-scrollbar-endpad) solid transparent;
}

/* tiny scrollbar */

.jp-scrollbar-tiny::-webkit-scrollbar,
.jp-scrollbar-tiny::-webkit-scrollbar-corner {
  background-color: transparent;
  height: 4px;
  width: 4px;
}

.jp-scrollbar-tiny::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:horizontal {
  border-left: 0px solid transparent;
  border-right: 0px solid transparent;
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:vertical {
  border-top: 0px solid transparent;
  border-bottom: 0px solid transparent;
}

/*
 * Phosphor
 */

.lm-ScrollBar[data-orientation='horizontal'] {
  min-height: 16px;
  max-height: 16px;
  min-width: 45px;
  border-top: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] {
  min-width: 16px;
  max-width: 16px;
  min-height: 45px;
  border-left: 1px solid #a0a0a0;
}

.lm-ScrollBar-button {
  background-color: #f0f0f0;
  background-position: center center;
  min-height: 15px;
  max-height: 15px;
  min-width: 15px;
  max-width: 15px;
}

.lm-ScrollBar-button:hover {
  background-color: #dadada;
}

.lm-ScrollBar-button.lm-mod-active {
  background-color: #cdcdcd;
}

.lm-ScrollBar-track {
  background: #f0f0f0;
}

.lm-ScrollBar-thumb {
  background: #cdcdcd;
}

.lm-ScrollBar-thumb:hover {
  background: #bababa;
}

.lm-ScrollBar-thumb.lm-mod-active {
  background: #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal'] .lm-ScrollBar-thumb {
  height: 100%;
  min-width: 15px;
  border-left: 1px solid #a0a0a0;
  border-right: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] .lm-ScrollBar-thumb {
  width: 100%;
  min-height: 15px;
  border-top: 1px solid #a0a0a0;
  border-bottom: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-left);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-right);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-up);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-down);
  background-size: 17px;
}
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-Widget, /* </DEPRECATED> */
.lm-Widget {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  cursor: default;
}


/* <DEPRECATED> */ .p-Widget.p-mod-hidden, /* </DEPRECATED> */
.lm-Widget.lm-mod-hidden {
  display: none !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-CommandPalette, /* </DEPRECATED> */
.lm-CommandPalette {
  display: flex;
  flex-direction: column;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-CommandPalette-search, /* </DEPRECATED> */
.lm-CommandPalette-search {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-content, /* </DEPRECATED> */
.lm-CommandPalette-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  min-height: 0;
  overflow: auto;
  list-style-type: none;
}


/* <DEPRECATED> */ .p-CommandPalette-header, /* </DEPRECATED> */
.lm-CommandPalette-header {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}


/* <DEPRECATED> */ .p-CommandPalette-item, /* </DEPRECATED> */
.lm-CommandPalette-item {
  display: flex;
  flex-direction: row;
}


/* <DEPRECATED> */ .p-CommandPalette-itemIcon, /* </DEPRECATED> */
.lm-CommandPalette-itemIcon {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-itemContent, /* </DEPRECATED> */
.lm-CommandPalette-itemContent {
  flex: 1 1 auto;
  overflow: hidden;
}


/* <DEPRECATED> */ .p-CommandPalette-itemShortcut, /* </DEPRECATED> */
.lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-itemLabel, /* </DEPRECATED> */
.lm-CommandPalette-itemLabel {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.lm-close-icon {
	border:1px solid transparent;
  background-color: transparent;
  position: absolute;
	z-index:1;
	right:3%;
	top: 0;
	bottom: 0;
	margin: auto;
	padding: 7px 0;
	display: none;
	vertical-align: middle;
  outline: 0;
  cursor: pointer;
}
.lm-close-icon:after {
	content: "X";
	display: block;
	width: 15px;
	height: 15px;
	text-align: center;
	color:#000;
	font-weight: normal;
	font-size: 12px;
	cursor: pointer;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-DockPanel, /* </DEPRECATED> */
.lm-DockPanel {
  z-index: 0;
}


/* <DEPRECATED> */ .p-DockPanel-widget, /* </DEPRECATED> */
.lm-DockPanel-widget {
  z-index: 0;
}


/* <DEPRECATED> */ .p-DockPanel-tabBar, /* </DEPRECATED> */
.lm-DockPanel-tabBar {
  z-index: 1;
}


/* <DEPRECATED> */ .p-DockPanel-handle, /* </DEPRECATED> */
.lm-DockPanel-handle {
  z-index: 2;
}


/* <DEPRECATED> */ .p-DockPanel-handle.p-mod-hidden, /* </DEPRECATED> */
.lm-DockPanel-handle.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-DockPanel-handle:after, /* </DEPRECATED> */
.lm-DockPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='horizontal'],
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='horizontal'] {
  cursor: ew-resize;
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='vertical'],
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='vertical'] {
  cursor: ns-resize;
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='horizontal']:after,
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='horizontal']:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='vertical']:after,
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='vertical']:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}


/* <DEPRECATED> */ .p-DockPanel-overlay, /* </DEPRECATED> */
.lm-DockPanel-overlay {
  z-index: 3;
  box-sizing: border-box;
  pointer-events: none;
}


/* <DEPRECATED> */ .p-DockPanel-overlay.p-mod-hidden, /* </DEPRECATED> */
.lm-DockPanel-overlay.lm-mod-hidden {
  display: none !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-Menu, /* </DEPRECATED> */
.lm-Menu {
  z-index: 10000;
  position: absolute;
  white-space: nowrap;
  overflow-x: hidden;
  overflow-y: auto;
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-Menu-content, /* </DEPRECATED> */
.lm-Menu-content {
  margin: 0;
  padding: 0;
  display: table;
  list-style-type: none;
}


/* <DEPRECATED> */ .p-Menu-item, /* </DEPRECATED> */
.lm-Menu-item {
  display: table-row;
}


/* <DEPRECATED> */
.p-Menu-item.p-mod-hidden,
.p-Menu-item.p-mod-collapsed,
/* </DEPRECATED> */
.lm-Menu-item.lm-mod-hidden,
.lm-Menu-item.lm-mod-collapsed {
  display: none !important;
}


/* <DEPRECATED> */
.p-Menu-itemIcon,
.p-Menu-itemSubmenuIcon,
/* </DEPRECATED> */
.lm-Menu-itemIcon,
.lm-Menu-itemSubmenuIcon {
  display: table-cell;
  text-align: center;
}


/* <DEPRECATED> */ .p-Menu-itemLabel, /* </DEPRECATED> */
.lm-Menu-itemLabel {
  display: table-cell;
  text-align: left;
}


/* <DEPRECATED> */ .p-Menu-itemShortcut, /* </DEPRECATED> */
.lm-Menu-itemShortcut {
  display: table-cell;
  text-align: right;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-MenuBar, /* </DEPRECATED> */
.lm-MenuBar {
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-MenuBar-content, /* </DEPRECATED> */
.lm-MenuBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: row;
  list-style-type: none;
}


/* <DEPRECATED> */ .p--MenuBar-item, /* </DEPRECATED> */
.lm-MenuBar-item {
  box-sizing: border-box;
}


/* <DEPRECATED> */
.p-MenuBar-itemIcon,
.p-MenuBar-itemLabel,
/* </DEPRECATED> */
.lm-MenuBar-itemIcon,
.lm-MenuBar-itemLabel {
  display: inline-block;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-ScrollBar, /* </DEPRECATED> */
.lm-ScrollBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */
.p-ScrollBar[data-orientation='horizontal'],
/* </DEPRECATED> */
.lm-ScrollBar[data-orientation='horizontal'] {
  flex-direction: row;
}


/* <DEPRECATED> */
.p-ScrollBar[data-orientation='vertical'],
/* </DEPRECATED> */
.lm-ScrollBar[data-orientation='vertical'] {
  flex-direction: column;
}


/* <DEPRECATED> */ .p-ScrollBar-button, /* </DEPRECATED> */
.lm-ScrollBar-button {
  box-sizing: border-box;
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-ScrollBar-track, /* </DEPRECATED> */
.lm-ScrollBar-track {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  flex: 1 1 auto;
}


/* <DEPRECATED> */ .p-ScrollBar-thumb, /* </DEPRECATED> */
.lm-ScrollBar-thumb {
  box-sizing: border-box;
  position: absolute;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-SplitPanel-child, /* </DEPRECATED> */
.lm-SplitPanel-child {
  z-index: 0;
}


/* <DEPRECATED> */ .p-SplitPanel-handle, /* </DEPRECATED> */
.lm-SplitPanel-handle {
  z-index: 1;
}


/* <DEPRECATED> */ .p-SplitPanel-handle.p-mod-hidden, /* </DEPRECATED> */
.lm-SplitPanel-handle.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-SplitPanel-handle:after, /* </DEPRECATED> */
.lm-SplitPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='horizontal'] > .p-SplitPanel-handle,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle {
  cursor: ew-resize;
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='vertical'] > .p-SplitPanel-handle,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle {
  cursor: ns-resize;
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='horizontal'] > .p-SplitPanel-handle:after,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='vertical'] > .p-SplitPanel-handle:after,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-TabBar, /* </DEPRECATED> */
.lm-TabBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-TabBar[data-orientation='horizontal'], /* </DEPRECATED> */
.lm-TabBar[data-orientation='horizontal'] {
  flex-direction: row;
  align-items: flex-end;
}


/* <DEPRECATED> */ .p-TabBar[data-orientation='vertical'], /* </DEPRECATED> */
.lm-TabBar[data-orientation='vertical'] {
  flex-direction: column;
  align-items: flex-end;
}


/* <DEPRECATED> */ .p-TabBar-content, /* </DEPRECATED> */
.lm-TabBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex: 1 1 auto;
  list-style-type: none;
}


/* <DEPRECATED> */
.p-TabBar[data-orientation='horizontal'] > .p-TabBar-content,
/* </DEPRECATED> */
.lm-TabBar[data-orientation='horizontal'] > .lm-TabBar-content {
  flex-direction: row;
}


/* <DEPRECATED> */
.p-TabBar[data-orientation='vertical'] > .p-TabBar-content,
/* </DEPRECATED> */
.lm-TabBar[data-orientation='vertical'] > .lm-TabBar-content {
  flex-direction: column;
}


/* <DEPRECATED> */ .p-TabBar-tab, /* </DEPRECATED> */
.lm-TabBar-tab {
  display: flex;
  flex-direction: row;
  box-sizing: border-box;
  overflow: hidden;
}


/* <DEPRECATED> */
.p-TabBar-tabIcon,
.p-TabBar-tabCloseIcon,
/* </DEPRECATED> */
.lm-TabBar-tabIcon,
.lm-TabBar-tabCloseIcon {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-TabBar-tabLabel, /* </DEPRECATED> */
.lm-TabBar-tabLabel {
  flex: 1 1 auto;
  overflow: hidden;
  white-space: nowrap;
}


.lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing : border-box;
}


/* <DEPRECATED> */ .p-TabBar-tab.p-mod-hidden, /* </DEPRECATED> */
.lm-TabBar-tab.lm-mod-hidden {
  display: none !important;
}


.lm-TabBar-addButton.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-TabBar.p-mod-dragging .p-TabBar-tab, /* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging .lm-TabBar-tab {
  position: relative;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging[data-orientation='horizontal'] .p-TabBar-tab,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging[data-orientation='horizontal'] .lm-TabBar-tab {
  left: 0;
  transition: left 150ms ease;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging[data-orientation='vertical'] .p-TabBar-tab,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging[data-orientation='vertical'] .lm-TabBar-tab {
  top: 0;
  transition: top 150ms ease;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging .p-TabBar-tab.p-mod-dragging,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging .lm-TabBar-tab.lm-mod-dragging {
  transition: none;
}

.lm-TabBar-tabLabel .lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing : border-box;
  background: inherit;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-TabPanel-tabBar, /* </DEPRECATED> */
.lm-TabPanel-tabBar {
  z-index: 1;
}


/* <DEPRECATED> */ .p-TabPanel-stackedPanel, /* </DEPRECATED> */
.lm-TabPanel-stackedPanel {
  z-index: 0;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

@charset "UTF-8";
html{
  -webkit-box-sizing:border-box;
          box-sizing:border-box; }

*,
*::before,
*::after{
  -webkit-box-sizing:inherit;
          box-sizing:inherit; }

body{
  font-size:14px;
  font-weight:400;
  letter-spacing:0;
  line-height:1.28581;
  text-transform:none;
  color:#182026;
  font-family:-apple-system, "BlinkMacSystemFont", "Segoe UI", "Roboto", "Oxygen", "Ubuntu", "Cantarell", "Open Sans", "Helvetica Neue", "Icons16", sans-serif; }

p{
  margin-bottom:10px;
  margin-top:0; }

small{
  font-size:12px; }

strong{
  font-weight:600; }

::-moz-selection{
  background:rgba(125, 188, 255, 0.6); }

::selection{
  background:rgba(125, 188, 255, 0.6); }
.bp3-heading{
  color:#182026;
  font-weight:600;
  margin:0 0 10px;
  padding:0; }
  .bp3-dark .bp3-heading{
    color:#f5f8fa; }

h1.bp3-heading, .bp3-running-text h1{
  font-size:36px;
  line-height:40px; }

h2.bp3-heading, .bp3-running-text h2{
  font-size:28px;
  line-height:32px; }

h3.bp3-heading, .bp3-running-text h3{
  font-size:22px;
  line-height:25px; }

h4.bp3-heading, .bp3-running-text h4{
  font-size:18px;
  line-height:21px; }

h5.bp3-heading, .bp3-running-text h5{
  font-size:16px;
  line-height:19px; }

h6.bp3-heading, .bp3-running-text h6{
  font-size:14px;
  line-height:16px; }
.bp3-ui-text{
  font-size:14px;
  font-weight:400;
  letter-spacing:0;
  line-height:1.28581;
  text-transform:none; }

.bp3-monospace-text{
  font-family:monospace;
  text-transform:none; }

.bp3-text-muted{
  color:#5c7080; }
  .bp3-dark .bp3-text-muted{
    color:#a7b6c2; }

.bp3-text-disabled{
  color:rgba(92, 112, 128, 0.6); }
  .bp3-dark .bp3-text-disabled{
    color:rgba(167, 182, 194, 0.6); }

.bp3-text-overflow-ellipsis{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal; }
.bp3-running-text{
  font-size:14px;
  line-height:1.5; }
  .bp3-running-text h1{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h1{
      color:#f5f8fa; }
  .bp3-running-text h2{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h2{
      color:#f5f8fa; }
  .bp3-running-text h3{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h3{
      color:#f5f8fa; }
  .bp3-running-text h4{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h4{
      color:#f5f8fa; }
  .bp3-running-text h5{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h5{
      color:#f5f8fa; }
  .bp3-running-text h6{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h6{
      color:#f5f8fa; }
  .bp3-running-text hr{
    border:none;
    border-bottom:1px solid rgba(16, 22, 26, 0.15);
    margin:20px 0; }
    .bp3-dark .bp3-running-text hr{
      border-color:rgba(255, 255, 255, 0.15); }
  .bp3-running-text p{
    margin:0 0 10px;
    padding:0; }

.bp3-text-large{
  font-size:16px; }

.bp3-text-small{
  font-size:12px; }
a{
  color:#106ba3;
  text-decoration:none; }
  a:hover{
    color:#106ba3;
    cursor:pointer;
    text-decoration:underline; }
  a .bp3-icon, a .bp3-icon-standard, a .bp3-icon-large{
    color:inherit; }
  a code,
  .bp3-dark a code{
    color:inherit; }
  .bp3-dark a,
  .bp3-dark a:hover{
    color:#48aff0; }
    .bp3-dark a .bp3-icon, .bp3-dark a .bp3-icon-standard, .bp3-dark a .bp3-icon-large,
    .bp3-dark a:hover .bp3-icon,
    .bp3-dark a:hover .bp3-icon-standard,
    .bp3-dark a:hover .bp3-icon-large{
      color:inherit; }
.bp3-running-text code, .bp3-code{
  font-family:monospace;
  text-transform:none;
  background:rgba(255, 255, 255, 0.7);
  border-radius:3px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2);
  color:#5c7080;
  font-size:smaller;
  padding:2px 5px; }
  .bp3-dark .bp3-running-text code, .bp3-running-text .bp3-dark code, .bp3-dark .bp3-code{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#a7b6c2; }
  .bp3-running-text a > code, a > .bp3-code{
    color:#137cbd; }
    .bp3-dark .bp3-running-text a > code, .bp3-running-text .bp3-dark a > code, .bp3-dark a > .bp3-code{
      color:inherit; }

.bp3-running-text pre, .bp3-code-block{
  font-family:monospace;
  text-transform:none;
  background:rgba(255, 255, 255, 0.7);
  border-radius:3px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
  color:#182026;
  display:block;
  font-size:13px;
  line-height:1.4;
  margin:10px 0;
  padding:13px 15px 12px;
  word-break:break-all;
  word-wrap:break-word; }
  .bp3-dark .bp3-running-text pre, .bp3-running-text .bp3-dark pre, .bp3-dark .bp3-code-block{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
  .bp3-running-text pre > code, .bp3-code-block > code{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:inherit;
    font-size:inherit;
    padding:0; }

.bp3-running-text kbd, .bp3-key{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  color:#5c7080;
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  font-family:inherit;
  font-size:12px;
  height:24px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  line-height:24px;
  min-width:24px;
  padding:3px 6px;
  vertical-align:middle; }
  .bp3-running-text kbd .bp3-icon, .bp3-key .bp3-icon, .bp3-running-text kbd .bp3-icon-standard, .bp3-key .bp3-icon-standard, .bp3-running-text kbd .bp3-icon-large, .bp3-key .bp3-icon-large{
    margin-right:5px; }
  .bp3-dark .bp3-running-text kbd, .bp3-running-text .bp3-dark kbd, .bp3-dark .bp3-key{
    background:#394b59;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#a7b6c2; }
.bp3-running-text blockquote, .bp3-blockquote{
  border-left:solid 4px rgba(167, 182, 194, 0.5);
  margin:0 0 10px;
  padding:0 20px; }
  .bp3-dark .bp3-running-text blockquote, .bp3-running-text .bp3-dark blockquote, .bp3-dark .bp3-blockquote{
    border-color:rgba(115, 134, 148, 0.5); }
.bp3-running-text ul,
.bp3-running-text ol, .bp3-list{
  margin:10px 0;
  padding-left:30px; }
  .bp3-running-text ul li:not(:last-child), .bp3-running-text ol li:not(:last-child), .bp3-list li:not(:last-child){
    margin-bottom:5px; }
  .bp3-running-text ul ol, .bp3-running-text ol ol, .bp3-list ol,
  .bp3-running-text ul ul,
  .bp3-running-text ol ul,
  .bp3-list ul{
    margin-top:5px; }

.bp3-list-unstyled{
  list-style:none;
  margin:0;
  padding:0; }
  .bp3-list-unstyled li{
    padding:0; }
.bp3-rtl{
  text-align:right; }

.bp3-dark{
  color:#f5f8fa; }

:focus{
  outline:rgba(19, 124, 189, 0.6) auto 2px;
  outline-offset:2px;
  -moz-outline-radius:6px; }

.bp3-focus-disabled :focus{
  outline:none !important; }
  .bp3-focus-disabled :focus ~ .bp3-control-indicator{
    outline:none !important; }

.bp3-alert{
  max-width:400px;
  padding:20px; }

.bp3-alert-body{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }
  .bp3-alert-body .bp3-icon{
    font-size:40px;
    margin-right:20px;
    margin-top:0; }

.bp3-alert-contents{
  word-break:break-word; }

.bp3-alert-footer{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:reverse;
      -ms-flex-direction:row-reverse;
          flex-direction:row-reverse;
  margin-top:10px; }
  .bp3-alert-footer .bp3-button{
    margin-left:10px; }
.bp3-breadcrumbs{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  cursor:default;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-wrap:wrap;
      flex-wrap:wrap;
  height:30px;
  list-style:none;
  margin:0;
  padding:0; }
  .bp3-breadcrumbs > li{
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex; }
    .bp3-breadcrumbs > li::after{
      background:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M10.71 7.29l-4-4a1.003 1.003 0 00-1.42 1.42L8.59 8 5.3 11.29c-.19.18-.3.43-.3.71a1.003 1.003 0 001.71.71l4-4c.18-.18.29-.43.29-.71 0-.28-.11-.53-.29-.71z' fill='%235C7080'/%3e%3c/svg%3e");
      content:"";
      display:block;
      height:16px;
      margin:0 5px;
      width:16px; }
    .bp3-breadcrumbs > li:last-of-type::after{
      display:none; }

.bp3-breadcrumb,
.bp3-breadcrumb-current,
.bp3-breadcrumbs-collapsed{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  font-size:16px; }

.bp3-breadcrumb,
.bp3-breadcrumbs-collapsed{
  color:#5c7080; }

.bp3-breadcrumb:hover{
  text-decoration:none; }

.bp3-breadcrumb.bp3-disabled{
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-breadcrumb .bp3-icon{
  margin-right:5px; }

.bp3-breadcrumb-current{
  color:inherit;
  font-weight:600; }
  .bp3-breadcrumb-current .bp3-input{
    font-size:inherit;
    font-weight:inherit;
    vertical-align:baseline; }

.bp3-breadcrumbs-collapsed{
  background:#ced9e0;
  border:none;
  border-radius:3px;
  cursor:pointer;
  margin-right:2px;
  padding:1px 5px;
  vertical-align:text-bottom; }
  .bp3-breadcrumbs-collapsed::before{
    background:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cg fill='%235C7080'%3e%3ccircle cx='2' cy='8.03' r='2'/%3e%3ccircle cx='14' cy='8.03' r='2'/%3e%3ccircle cx='8' cy='8.03' r='2'/%3e%3c/g%3e%3c/svg%3e") center no-repeat;
    content:"";
    display:block;
    height:16px;
    width:16px; }
  .bp3-breadcrumbs-collapsed:hover{
    background:#bfccd6;
    color:#182026;
    text-decoration:none; }

.bp3-dark .bp3-breadcrumb,
.bp3-dark .bp3-breadcrumbs-collapsed{
  color:#a7b6c2; }

.bp3-dark .bp3-breadcrumbs > li::after{
  color:#a7b6c2; }

.bp3-dark .bp3-breadcrumb.bp3-disabled{
  color:rgba(167, 182, 194, 0.6); }

.bp3-dark .bp3-breadcrumb-current{
  color:#f5f8fa; }

.bp3-dark .bp3-breadcrumbs-collapsed{
  background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-breadcrumbs-collapsed:hover{
    background:rgba(16, 22, 26, 0.6);
    color:#f5f8fa; }
.bp3-button{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border:none;
  border-radius:3px;
  cursor:pointer;
  font-size:14px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  padding:5px 10px;
  text-align:left;
  vertical-align:middle;
  min-height:30px;
  min-width:30px; }
  .bp3-button > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-button > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-button::before,
  .bp3-button > *{
    margin-right:7px; }
  .bp3-button:empty::before,
  .bp3-button > :last-child{
    margin-right:0; }
  .bp3-button:empty{
    padding:0 !important; }
  .bp3-button:disabled, .bp3-button.bp3-disabled{
    cursor:not-allowed; }
  .bp3-button.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-button.bp3-align-right,
  .bp3-align-right .bp3-button{
    text-align:right; }
  .bp3-button.bp3-align-left,
  .bp3-align-left .bp3-button{
    text-align:left; }
  .bp3-button:not([class*="bp3-intent-"]){
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    color:#182026; }
    .bp3-button:not([class*="bp3-intent-"]):hover{
      background-clip:padding-box;
      background-color:#ebf1f5;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
    .bp3-button:not([class*="bp3-intent-"]):active, .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      background-color:#d8e1e8;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button:not([class*="bp3-intent-"]):disabled, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled{
      background-color:rgba(206, 217, 224, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed;
      outline:none; }
      .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active, .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active:hover, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active:hover{
        background:rgba(206, 217, 224, 0.7); }
  .bp3-button.bp3-intent-primary{
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-primary:hover, .bp3-button.bp3-intent-primary:active, .bp3-button.bp3-intent-primary.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-primary:hover{
      background-color:#106ba3;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-primary:active, .bp3-button.bp3-intent-primary.bp3-active{
      background-color:#0e5a8a;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-primary:disabled, .bp3-button.bp3-intent-primary.bp3-disabled{
      background-color:rgba(19, 124, 189, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-success{
    background-color:#0f9960;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-success:hover, .bp3-button.bp3-intent-success:active, .bp3-button.bp3-intent-success.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-success:hover{
      background-color:#0d8050;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-success:active, .bp3-button.bp3-intent-success.bp3-active{
      background-color:#0a6640;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-success:disabled, .bp3-button.bp3-intent-success.bp3-disabled{
      background-color:rgba(15, 153, 96, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-warning{
    background-color:#d9822b;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-warning:hover, .bp3-button.bp3-intent-warning:active, .bp3-button.bp3-intent-warning.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-warning:hover{
      background-color:#bf7326;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-warning:active, .bp3-button.bp3-intent-warning.bp3-active{
      background-color:#a66321;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-warning:disabled, .bp3-button.bp3-intent-warning.bp3-disabled{
      background-color:rgba(217, 130, 43, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-danger{
    background-color:#db3737;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-danger:hover, .bp3-button.bp3-intent-danger:active, .bp3-button.bp3-intent-danger.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-danger:hover{
      background-color:#c23030;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-danger:active, .bp3-button.bp3-intent-danger.bp3-active{
      background-color:#a82a2a;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-danger:disabled, .bp3-button.bp3-intent-danger.bp3-disabled{
      background-color:rgba(219, 55, 55, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button[class*="bp3-intent-"] .bp3-button-spinner .bp3-spinner-head{
    stroke:#ffffff; }
  .bp3-button.bp3-large,
  .bp3-large .bp3-button{
    min-height:40px;
    min-width:40px;
    font-size:16px;
    padding:5px 15px; }
    .bp3-button.bp3-large::before,
    .bp3-button.bp3-large > *,
    .bp3-large .bp3-button::before,
    .bp3-large .bp3-button > *{
      margin-right:10px; }
    .bp3-button.bp3-large:empty::before,
    .bp3-button.bp3-large > :last-child,
    .bp3-large .bp3-button:empty::before,
    .bp3-large .bp3-button > :last-child{
      margin-right:0; }
  .bp3-button.bp3-small,
  .bp3-small .bp3-button{
    min-height:24px;
    min-width:24px;
    padding:0 7px; }
  .bp3-button.bp3-loading{
    position:relative; }
    .bp3-button.bp3-loading[class*="bp3-icon-"]::before{
      visibility:hidden; }
    .bp3-button.bp3-loading .bp3-button-spinner{
      margin:0;
      position:absolute; }
    .bp3-button.bp3-loading > :not(.bp3-button-spinner){
      visibility:hidden; }
  .bp3-button[class*="bp3-icon-"]::before{
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-style:normal;
    font-weight:400;
    line-height:1;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    color:#5c7080; }
  .bp3-button .bp3-icon, .bp3-button .bp3-icon-standard, .bp3-button .bp3-icon-large{
    color:#5c7080; }
    .bp3-button .bp3-icon.bp3-align-right, .bp3-button .bp3-icon-standard.bp3-align-right, .bp3-button .bp3-icon-large.bp3-align-right{
      margin-left:7px; }
  .bp3-button .bp3-icon:first-child:last-child,
  .bp3-button .bp3-spinner + .bp3-icon:last-child{
    margin:0 -7px; }
  .bp3-dark .bp3-button:not([class*="bp3-intent-"]){
    background-color:#394b59;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):hover, .bp3-dark .bp3-button:not([class*="bp3-intent-"]):active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      color:#f5f8fa; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):hover{
      background-color:#30404d;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      background-color:#202b33;
      background-image:none;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):disabled, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-disabled{
      background-color:rgba(57, 75, 89, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
      .bp3-dark .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active{
        background:rgba(57, 75, 89, 0.7); }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-button-spinner .bp3-spinner-head{
      background:rgba(16, 22, 26, 0.5);
      stroke:#8a9ba8; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"])[class*="bp3-icon-"]::before{
      color:#a7b6c2; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon, .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon-standard, .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon-large{
      color:#a7b6c2; }
  .bp3-dark .bp3-button[class*="bp3-intent-"]{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:hover{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:active, .bp3-dark .bp3-button[class*="bp3-intent-"].bp3-active{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:disabled, .bp3-dark .bp3-button[class*="bp3-intent-"].bp3-disabled{
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.3); }
    .bp3-dark .bp3-button[class*="bp3-intent-"] .bp3-button-spinner .bp3-spinner-head{
      stroke:#8a9ba8; }
  .bp3-button:disabled::before,
  .bp3-button:disabled .bp3-icon, .bp3-button:disabled .bp3-icon-standard, .bp3-button:disabled .bp3-icon-large, .bp3-button.bp3-disabled::before,
  .bp3-button.bp3-disabled .bp3-icon, .bp3-button.bp3-disabled .bp3-icon-standard, .bp3-button.bp3-disabled .bp3-icon-large, .bp3-button[class*="bp3-intent-"]::before,
  .bp3-button[class*="bp3-intent-"] .bp3-icon, .bp3-button[class*="bp3-intent-"] .bp3-icon-standard, .bp3-button[class*="bp3-intent-"] .bp3-icon-large{
    color:inherit !important; }
  .bp3-button.bp3-minimal{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none; }
    .bp3-button.bp3-minimal:hover{
      background:rgba(167, 182, 194, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026;
      text-decoration:none; }
    .bp3-button.bp3-minimal:active, .bp3-button.bp3-minimal.bp3-active{
      background:rgba(115, 134, 148, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026; }
    .bp3-button.bp3-minimal:disabled, .bp3-button.bp3-minimal:disabled:hover, .bp3-button.bp3-minimal.bp3-disabled, .bp3-button.bp3-minimal.bp3-disabled:hover{
      background:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed; }
      .bp3-button.bp3-minimal:disabled.bp3-active, .bp3-button.bp3-minimal:disabled:hover.bp3-active, .bp3-button.bp3-minimal.bp3-disabled.bp3-active, .bp3-button.bp3-minimal.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button.bp3-minimal{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:inherit; }
      .bp3-dark .bp3-button.bp3-minimal:hover, .bp3-dark .bp3-button.bp3-minimal:active, .bp3-dark .bp3-button.bp3-minimal.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none; }
      .bp3-dark .bp3-button.bp3-minimal:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button.bp3-minimal:active, .bp3-dark .bp3-button.bp3-minimal.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button.bp3-minimal:disabled, .bp3-dark .bp3-button.bp3-minimal:disabled:hover, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled:hover{
        background:none;
        color:rgba(167, 182, 194, 0.6);
        cursor:not-allowed; }
        .bp3-dark .bp3-button.bp3-minimal:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal:disabled:hover.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:hover, .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:disabled, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-primary:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-success{
      color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:hover, .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:disabled, .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-success:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:hover, .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:disabled, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-warning:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-danger{
      color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:hover, .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:disabled, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-danger:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }
  .bp3-button.bp3-outlined{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    border:1px solid rgba(24, 32, 38, 0.2);
    -webkit-box-sizing:border-box;
            box-sizing:border-box; }
    .bp3-button.bp3-outlined:hover{
      background:rgba(167, 182, 194, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026;
      text-decoration:none; }
    .bp3-button.bp3-outlined:active, .bp3-button.bp3-outlined.bp3-active{
      background:rgba(115, 134, 148, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026; }
    .bp3-button.bp3-outlined:disabled, .bp3-button.bp3-outlined:disabled:hover, .bp3-button.bp3-outlined.bp3-disabled, .bp3-button.bp3-outlined.bp3-disabled:hover{
      background:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed; }
      .bp3-button.bp3-outlined:disabled.bp3-active, .bp3-button.bp3-outlined:disabled:hover.bp3-active, .bp3-button.bp3-outlined.bp3-disabled.bp3-active, .bp3-button.bp3-outlined.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button.bp3-outlined{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:inherit; }
      .bp3-dark .bp3-button.bp3-outlined:hover, .bp3-dark .bp3-button.bp3-outlined:active, .bp3-dark .bp3-button.bp3-outlined.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none; }
      .bp3-dark .bp3-button.bp3-outlined:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button.bp3-outlined:active, .bp3-dark .bp3-button.bp3-outlined.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button.bp3-outlined:disabled, .bp3-dark .bp3-button.bp3-outlined:disabled:hover, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled:hover{
        background:none;
        color:rgba(167, 182, 194, 0.6);
        cursor:not-allowed; }
        .bp3-dark .bp3-button.bp3-outlined:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined:disabled:hover.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:hover, .bp3-button.bp3-outlined.bp3-intent-primary:active, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:active, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-primary:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-success{
      color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:hover, .bp3-button.bp3-outlined.bp3-intent-success:active, .bp3-button.bp3-outlined.bp3-intent-success.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:active, .bp3-button.bp3-outlined.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-success:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:hover, .bp3-button.bp3-outlined.bp3-intent-warning:active, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:active, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-warning:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-danger{
      color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:hover, .bp3-button.bp3-outlined.bp3-intent-danger:active, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:active, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-danger:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }
    .bp3-button.bp3-outlined:disabled, .bp3-button.bp3-outlined.bp3-disabled, .bp3-button.bp3-outlined:disabled:hover, .bp3-button.bp3-outlined.bp3-disabled:hover{
      border-color:rgba(92, 112, 128, 0.1); }
    .bp3-dark .bp3-button.bp3-outlined{
      border-color:rgba(255, 255, 255, 0.4); }
      .bp3-dark .bp3-button.bp3-outlined:disabled, .bp3-dark .bp3-button.bp3-outlined:disabled:hover, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled:hover{
        border-color:rgba(255, 255, 255, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-primary{
      border-color:rgba(16, 107, 163, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
        border-color:rgba(16, 107, 163, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary{
        border-color:rgba(72, 175, 240, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
          border-color:rgba(72, 175, 240, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-success{
      border-color:rgba(13, 128, 80, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
        border-color:rgba(13, 128, 80, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success{
        border-color:rgba(61, 204, 145, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
          border-color:rgba(61, 204, 145, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-warning{
      border-color:rgba(191, 115, 38, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
        border-color:rgba(191, 115, 38, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning{
        border-color:rgba(255, 179, 102, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
          border-color:rgba(255, 179, 102, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-danger{
      border-color:rgba(194, 48, 48, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
        border-color:rgba(194, 48, 48, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger{
        border-color:rgba(255, 115, 115, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
          border-color:rgba(255, 115, 115, 0.2); }

a.bp3-button{
  text-align:center;
  text-decoration:none;
  -webkit-transition:none;
  transition:none; }
  a.bp3-button, a.bp3-button:hover, a.bp3-button:active{
    color:#182026; }
  a.bp3-button.bp3-disabled{
    color:rgba(92, 112, 128, 0.6); }

.bp3-button-text{
  -webkit-box-flex:0;
      -ms-flex:0 1 auto;
          flex:0 1 auto; }

.bp3-button.bp3-align-left .bp3-button-text, .bp3-button.bp3-align-right .bp3-button-text,
.bp3-button-group.bp3-align-left .bp3-button-text,
.bp3-button-group.bp3-align-right .bp3-button-text{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto; }
.bp3-button-group{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex; }
  .bp3-button-group .bp3-button{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    position:relative;
    z-index:4; }
    .bp3-button-group .bp3-button:focus{
      z-index:5; }
    .bp3-button-group .bp3-button:hover{
      z-index:6; }
    .bp3-button-group .bp3-button:active, .bp3-button-group .bp3-button.bp3-active{
      z-index:7; }
    .bp3-button-group .bp3-button:disabled, .bp3-button-group .bp3-button.bp3-disabled{
      z-index:3; }
    .bp3-button-group .bp3-button[class*="bp3-intent-"]{
      z-index:9; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:focus{
        z-index:10; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:hover{
        z-index:11; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:active, .bp3-button-group .bp3-button[class*="bp3-intent-"].bp3-active{
        z-index:12; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:disabled, .bp3-button-group .bp3-button[class*="bp3-intent-"].bp3-disabled{
        z-index:8; }
  .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:first-child) .bp3-button,
  .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:first-child){
    border-bottom-left-radius:0;
    border-top-left-radius:0; }
  .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:last-child){
    border-bottom-right-radius:0;
    border-top-right-radius:0;
    margin-right:-1px; }
  .bp3-button-group.bp3-minimal .bp3-button{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none; }
    .bp3-button-group.bp3-minimal .bp3-button:hover{
      background:rgba(167, 182, 194, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026;
      text-decoration:none; }
    .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
      background:rgba(115, 134, 148, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026; }
    .bp3-button-group.bp3-minimal .bp3-button:disabled, .bp3-button-group.bp3-minimal .bp3-button:disabled:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover{
      background:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed; }
      .bp3-button-group.bp3-minimal .bp3-button:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button:disabled:hover.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button-group.bp3-minimal .bp3-button{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:inherit; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:hover, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled:hover, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover{
        background:none;
        color:rgba(167, 182, 194, 0.6);
        cursor:not-allowed; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled:hover.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success{
      color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger{
      color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }
  .bp3-button-group .bp3-popover-wrapper,
  .bp3-button-group .bp3-popover-target{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-button-group.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-button-group .bp3-button.bp3-fill,
  .bp3-button-group.bp3-fill .bp3-button:not(.bp3-fixed){
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-button-group.bp3-vertical{
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column;
    vertical-align:top; }
    .bp3-button-group.bp3-vertical.bp3-fill{
      height:100%;
      width:unset; }
    .bp3-button-group.bp3-vertical .bp3-button{
      margin-right:0 !important;
      width:100%; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:first-child .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:first-child{
      border-radius:3px 3px 0 0; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:last-child .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:last-child{
      border-radius:0 0 3px 3px; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:not(:last-child){
      margin-bottom:-1px; }
  .bp3-button-group.bp3-align-left .bp3-button{
    text-align:left; }
  .bp3-dark .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-dark .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:last-child){
    margin-right:1px; }
  .bp3-dark .bp3-button-group.bp3-vertical > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-dark .bp3-button-group.bp3-vertical > .bp3-button:not(:last-child){
    margin-bottom:1px; }
.bp3-callout{
  font-size:14px;
  line-height:1.5;
  background-color:rgba(138, 155, 168, 0.15);
  border-radius:3px;
  padding:10px 12px 9px;
  position:relative;
  width:100%; }
  .bp3-callout[class*="bp3-icon-"]{
    padding-left:40px; }
    .bp3-callout[class*="bp3-icon-"]::before{
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-style:normal;
      font-weight:400;
      line-height:1;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased;
      color:#5c7080;
      left:10px;
      position:absolute;
      top:10px; }
  .bp3-callout.bp3-callout-icon{
    padding-left:40px; }
    .bp3-callout.bp3-callout-icon > .bp3-icon:first-child{
      color:#5c7080;
      left:10px;
      position:absolute;
      top:10px; }
  .bp3-callout .bp3-heading{
    line-height:20px;
    margin-bottom:5px;
    margin-top:0; }
    .bp3-callout .bp3-heading:last-child{
      margin-bottom:0; }
  .bp3-dark .bp3-callout{
    background-color:rgba(138, 155, 168, 0.2); }
    .bp3-dark .bp3-callout[class*="bp3-icon-"]::before{
      color:#a7b6c2; }
  .bp3-callout.bp3-intent-primary{
    background-color:rgba(19, 124, 189, 0.15); }
    .bp3-callout.bp3-intent-primary[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-primary > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-primary .bp3-heading{
      color:#106ba3; }
    .bp3-dark .bp3-callout.bp3-intent-primary{
      background-color:rgba(19, 124, 189, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-primary[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-primary > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-primary .bp3-heading{
        color:#48aff0; }
  .bp3-callout.bp3-intent-success{
    background-color:rgba(15, 153, 96, 0.15); }
    .bp3-callout.bp3-intent-success[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-success > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-success .bp3-heading{
      color:#0d8050; }
    .bp3-dark .bp3-callout.bp3-intent-success{
      background-color:rgba(15, 153, 96, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-success[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-success > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-success .bp3-heading{
        color:#3dcc91; }
  .bp3-callout.bp3-intent-warning{
    background-color:rgba(217, 130, 43, 0.15); }
    .bp3-callout.bp3-intent-warning[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-warning > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-warning .bp3-heading{
      color:#bf7326; }
    .bp3-dark .bp3-callout.bp3-intent-warning{
      background-color:rgba(217, 130, 43, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-warning[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-warning > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-warning .bp3-heading{
        color:#ffb366; }
  .bp3-callout.bp3-intent-danger{
    background-color:rgba(219, 55, 55, 0.15); }
    .bp3-callout.bp3-intent-danger[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-danger > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-danger .bp3-heading{
      color:#c23030; }
    .bp3-dark .bp3-callout.bp3-intent-danger{
      background-color:rgba(219, 55, 55, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-danger[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-danger > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-danger .bp3-heading{
        color:#ff7373; }
  .bp3-running-text .bp3-callout{
    margin:20px 0; }
.bp3-card{
  background-color:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
  padding:20px;
  -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-card.bp3-dark,
  .bp3-dark .bp3-card{
    background-color:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }

.bp3-elevation-0{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }
  .bp3-elevation-0.bp3-dark,
  .bp3-dark .bp3-elevation-0{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }

.bp3-elevation-1{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-1.bp3-dark,
  .bp3-dark .bp3-elevation-1{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-elevation-2{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 1px 1px rgba(16, 22, 26, 0.2), 0 2px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 1px 1px rgba(16, 22, 26, 0.2), 0 2px 6px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-2.bp3-dark,
  .bp3-dark .bp3-elevation-2{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.4), 0 2px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.4), 0 2px 6px rgba(16, 22, 26, 0.4); }

.bp3-elevation-3{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-3.bp3-dark,
  .bp3-dark .bp3-elevation-3{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }

.bp3-elevation-4{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-4.bp3-dark,
  .bp3-dark .bp3-elevation-4{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4); }

.bp3-card.bp3-interactive:hover{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  cursor:pointer; }
  .bp3-card.bp3-interactive:hover.bp3-dark,
  .bp3-dark .bp3-card.bp3-interactive:hover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }

.bp3-card.bp3-interactive:active{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  opacity:0.9;
  -webkit-transition-duration:0;
          transition-duration:0; }
  .bp3-card.bp3-interactive:active.bp3-dark,
  .bp3-dark .bp3-card.bp3-interactive:active{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-collapse{
  height:0;
  overflow-y:hidden;
  -webkit-transition:height 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:height 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-collapse .bp3-collapse-body{
    -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-collapse .bp3-collapse-body[aria-hidden="true"]{
      display:none; }

.bp3-context-menu .bp3-popover-target{
  display:block; }

.bp3-context-menu-popover-target{
  position:fixed; }

.bp3-divider{
  border-bottom:1px solid rgba(16, 22, 26, 0.15);
  border-right:1px solid rgba(16, 22, 26, 0.15);
  margin:5px; }
  .bp3-dark .bp3-divider{
    border-color:rgba(16, 22, 26, 0.4); }
.bp3-dialog-container{
  opacity:1;
  -webkit-transform:scale(1);
          transform:scale(1);
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  min-height:100%;
  pointer-events:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none;
  width:100%; }
  .bp3-dialog-container.bp3-overlay-enter > .bp3-dialog, .bp3-dialog-container.bp3-overlay-appear > .bp3-dialog{
    opacity:0;
    -webkit-transform:scale(0.5);
            transform:scale(0.5); }
  .bp3-dialog-container.bp3-overlay-enter-active > .bp3-dialog, .bp3-dialog-container.bp3-overlay-appear-active > .bp3-dialog{
    opacity:1;
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:opacity, -webkit-transform;
    transition-property:opacity, -webkit-transform;
    transition-property:opacity, transform;
    transition-property:opacity, transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-dialog-container.bp3-overlay-exit > .bp3-dialog{
    opacity:1;
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-dialog-container.bp3-overlay-exit-active > .bp3-dialog{
    opacity:0;
    -webkit-transform:scale(0.5);
            transform:scale(0.5);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:opacity, -webkit-transform;
    transition-property:opacity, -webkit-transform;
    transition-property:opacity, transform;
    transition-property:opacity, transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }

.bp3-dialog{
  background:#ebf1f5;
  border-radius:6px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:30px 0;
  padding-bottom:20px;
  pointer-events:all;
  -webkit-user-select:text;
     -moz-user-select:text;
      -ms-user-select:text;
          user-select:text;
  width:500px; }
  .bp3-dialog:focus{
    outline:0; }
  .bp3-dialog.bp3-dark,
  .bp3-dark .bp3-dialog{
    background:#293742;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }

.bp3-dialog-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background:#ffffff;
  border-radius:6px 6px 0 0;
  -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  min-height:40px;
  padding-left:20px;
  padding-right:5px;
  z-index:30; }
  .bp3-dialog-header .bp3-icon-large,
  .bp3-dialog-header .bp3-icon{
    color:#5c7080;
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    margin-right:10px; }
  .bp3-dialog-header .bp3-heading{
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    line-height:inherit;
    margin:0; }
    .bp3-dialog-header .bp3-heading:last-child{
      margin-right:20px; }
  .bp3-dark .bp3-dialog-header{
    background:#30404d;
    -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:0 1px 0 rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-dialog-header .bp3-icon-large,
    .bp3-dark .bp3-dialog-header .bp3-icon{
      color:#a7b6c2; }

.bp3-dialog-body{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  line-height:18px;
  margin:20px; }

.bp3-dialog-footer{
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  margin:0 20px; }

.bp3-dialog-footer-actions{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:end;
      -ms-flex-pack:end;
          justify-content:flex-end; }
  .bp3-dialog-footer-actions .bp3-button{
    margin-left:10px; }
.bp3-multistep-dialog-panels{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }

.bp3-multistep-dialog-left-panel{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:1;
      -ms-flex:1;
          flex:1;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column; }
  .bp3-dark .bp3-multistep-dialog-left-panel{
    background:#202b33; }

.bp3-multistep-dialog-right-panel{
  background-color:#f5f8fa;
  border-left:1px solid rgba(16, 22, 26, 0.15);
  border-radius:0 0 6px 0;
  -webkit-box-flex:3;
      -ms-flex:3;
          flex:3;
  min-width:0; }
  .bp3-dark .bp3-multistep-dialog-right-panel{
    background-color:#293742;
    border-left:1px solid rgba(16, 22, 26, 0.4); }

.bp3-multistep-dialog-footer{
  background-color:#ffffff;
  border-radius:0 0 6px 0;
  border-top:1px solid rgba(16, 22, 26, 0.15);
  padding:10px; }
  .bp3-dark .bp3-multistep-dialog-footer{
    background:#30404d;
    border-top:1px solid rgba(16, 22, 26, 0.4); }

.bp3-dialog-step-container{
  background-color:#f5f8fa;
  border-bottom:1px solid rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-dialog-step-container{
    background:#293742;
    border-bottom:1px solid rgba(16, 22, 26, 0.4); }
  .bp3-dialog-step-container.bp3-dialog-step-viewed{
    background-color:#ffffff; }
    .bp3-dark .bp3-dialog-step-container.bp3-dialog-step-viewed{
      background:#30404d; }

.bp3-dialog-step{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background-color:#f5f8fa;
  border-radius:6px;
  cursor:not-allowed;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  margin:4px;
  padding:6px 14px; }
  .bp3-dark .bp3-dialog-step{
    background:#293742; }
  .bp3-dialog-step-viewed .bp3-dialog-step{
    background-color:#ffffff;
    cursor:pointer; }
    .bp3-dark .bp3-dialog-step-viewed .bp3-dialog-step{
      background:#30404d; }
  .bp3-dialog-step:hover{
    background-color:#f5f8fa; }
    .bp3-dark .bp3-dialog-step:hover{
      background:#293742; }

.bp3-dialog-step-icon{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background-color:rgba(92, 112, 128, 0.6);
  border-radius:50%;
  color:#ffffff;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  height:25px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  width:25px; }
  .bp3-dark .bp3-dialog-step-icon{
    background-color:rgba(167, 182, 194, 0.6); }
  .bp3-active.bp3-dialog-step-viewed .bp3-dialog-step-icon{
    background-color:#2b95d6; }
  .bp3-dialog-step-viewed .bp3-dialog-step-icon{
    background-color:#8a9ba8; }

.bp3-dialog-step-title{
  color:rgba(92, 112, 128, 0.6);
  -webkit-box-flex:1;
      -ms-flex:1;
          flex:1;
  padding-left:10px; }
  .bp3-dark .bp3-dialog-step-title{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-active.bp3-dialog-step-viewed .bp3-dialog-step-title{
    color:#2b95d6; }
  .bp3-dialog-step-viewed:not(.bp3-active) .bp3-dialog-step-title{
    color:#182026; }
    .bp3-dark .bp3-dialog-step-viewed:not(.bp3-active) .bp3-dialog-step-title{
      color:#f5f8fa; }
.bp3-drawer{
  background:#ffffff;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:0;
  padding:0; }
  .bp3-drawer:focus{
    outline:0; }
  .bp3-drawer.bp3-position-top{
    height:50%;
    left:0;
    right:0;
    top:0; }
    .bp3-drawer.bp3-position-top.bp3-overlay-enter, .bp3-drawer.bp3-position-top.bp3-overlay-appear{
      -webkit-transform:translateY(-100%);
              transform:translateY(-100%); }
    .bp3-drawer.bp3-position-top.bp3-overlay-enter-active, .bp3-drawer.bp3-position-top.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-top.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer.bp3-position-top.bp3-overlay-exit-active{
      -webkit-transform:translateY(-100%);
              transform:translateY(-100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-position-bottom{
    bottom:0;
    height:50%;
    left:0;
    right:0; }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-enter, .bp3-drawer.bp3-position-bottom.bp3-overlay-appear{
      -webkit-transform:translateY(100%);
              transform:translateY(100%); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-enter-active, .bp3-drawer.bp3-position-bottom.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-exit-active{
      -webkit-transform:translateY(100%);
              transform:translateY(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-position-left{
    bottom:0;
    left:0;
    top:0;
    width:50%; }
    .bp3-drawer.bp3-position-left.bp3-overlay-enter, .bp3-drawer.bp3-position-left.bp3-overlay-appear{
      -webkit-transform:translateX(-100%);
              transform:translateX(-100%); }
    .bp3-drawer.bp3-position-left.bp3-overlay-enter-active, .bp3-drawer.bp3-position-left.bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-left.bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer.bp3-position-left.bp3-overlay-exit-active{
      -webkit-transform:translateX(-100%);
              transform:translateX(-100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-position-right{
    bottom:0;
    right:0;
    top:0;
    width:50%; }
    .bp3-drawer.bp3-position-right.bp3-overlay-enter, .bp3-drawer.bp3-position-right.bp3-overlay-appear{
      -webkit-transform:translateX(100%);
              transform:translateX(100%); }
    .bp3-drawer.bp3-position-right.bp3-overlay-enter-active, .bp3-drawer.bp3-position-right.bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-right.bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer.bp3-position-right.bp3-overlay-exit-active{
      -webkit-transform:translateX(100%);
              transform:translateX(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
  .bp3-position-right):not(.bp3-vertical){
    bottom:0;
    right:0;
    top:0;
    width:50%; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-enter, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-appear{
      -webkit-transform:translateX(100%);
              transform:translateX(100%); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-enter-active, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-exit-active{
      -webkit-transform:translateX(100%);
              transform:translateX(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
  .bp3-position-right).bp3-vertical{
    bottom:0;
    height:50%;
    left:0;
    right:0; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-enter, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-appear{
      -webkit-transform:translateY(100%);
              transform:translateY(100%); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-enter-active, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-exit-active{
      -webkit-transform:translateY(100%);
              transform:translateY(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-dark,
  .bp3-dark .bp3-drawer{
    background:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }

.bp3-drawer-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border-radius:0;
  -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  min-height:40px;
  padding:5px;
  padding-left:20px;
  position:relative; }
  .bp3-drawer-header .bp3-icon-large,
  .bp3-drawer-header .bp3-icon{
    color:#5c7080;
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    margin-right:10px; }
  .bp3-drawer-header .bp3-heading{
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    line-height:inherit;
    margin:0; }
    .bp3-drawer-header .bp3-heading:last-child{
      margin-right:20px; }
  .bp3-dark .bp3-drawer-header{
    -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:0 1px 0 rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-drawer-header .bp3-icon-large,
    .bp3-dark .bp3-drawer-header .bp3-icon{
      color:#a7b6c2; }

.bp3-drawer-body{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  line-height:18px;
  overflow:auto; }

.bp3-drawer-footer{
  -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  padding:10px 20px;
  position:relative; }
  .bp3-dark .bp3-drawer-footer{
    -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.4); }
.bp3-editable-text{
  cursor:text;
  display:inline-block;
  max-width:100%;
  position:relative;
  vertical-align:top;
  white-space:nowrap; }
  .bp3-editable-text::before{
    bottom:-3px;
    left:-3px;
    position:absolute;
    right:-3px;
    top:-3px;
    border-radius:3px;
    content:"";
    -webkit-transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-editable-text:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-editable-text.bp3-editable-text-editing::before{
    background-color:#ffffff;
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-disabled::before{
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-editable-text.bp3-intent-primary .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-primary .bp3-editable-text-content{
    color:#137cbd; }
  .bp3-editable-text.bp3-intent-primary:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(19, 124, 189, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(19, 124, 189, 0.4); }
  .bp3-editable-text.bp3-intent-primary.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-success .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-success .bp3-editable-text-content{
    color:#0f9960; }
  .bp3-editable-text.bp3-intent-success:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px rgba(15, 153, 96, 0.4);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px rgba(15, 153, 96, 0.4); }
  .bp3-editable-text.bp3-intent-success.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-warning .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-warning .bp3-editable-text-content{
    color:#d9822b; }
  .bp3-editable-text.bp3-intent-warning:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px rgba(217, 130, 43, 0.4);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px rgba(217, 130, 43, 0.4); }
  .bp3-editable-text.bp3-intent-warning.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-danger .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-danger .bp3-editable-text-content{
    color:#db3737; }
  .bp3-editable-text.bp3-intent-danger:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px rgba(219, 55, 55, 0.4);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px rgba(219, 55, 55, 0.4); }
  .bp3-editable-text.bp3-intent-danger.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-editable-text:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(255, 255, 255, 0.15); }
  .bp3-dark .bp3-editable-text.bp3-editable-text-editing::before{
    background-color:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-disabled::before{
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-dark .bp3-editable-text.bp3-intent-primary .bp3-editable-text-content{
    color:#48aff0; }
  .bp3-dark .bp3-editable-text.bp3-intent-primary:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(72, 175, 240, 0), 0 0 0 0 rgba(72, 175, 240, 0), inset 0 0 0 1px rgba(72, 175, 240, 0.4);
            box-shadow:0 0 0 0 rgba(72, 175, 240, 0), 0 0 0 0 rgba(72, 175, 240, 0), inset 0 0 0 1px rgba(72, 175, 240, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-primary.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #48aff0, 0 0 0 3px rgba(72, 175, 240, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #48aff0, 0 0 0 3px rgba(72, 175, 240, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-success .bp3-editable-text-content{
    color:#3dcc91; }
  .bp3-dark .bp3-editable-text.bp3-intent-success:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(61, 204, 145, 0), 0 0 0 0 rgba(61, 204, 145, 0), inset 0 0 0 1px rgba(61, 204, 145, 0.4);
            box-shadow:0 0 0 0 rgba(61, 204, 145, 0), 0 0 0 0 rgba(61, 204, 145, 0), inset 0 0 0 1px rgba(61, 204, 145, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-success.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #3dcc91, 0 0 0 3px rgba(61, 204, 145, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #3dcc91, 0 0 0 3px rgba(61, 204, 145, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-warning .bp3-editable-text-content{
    color:#ffb366; }
  .bp3-dark .bp3-editable-text.bp3-intent-warning:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(255, 179, 102, 0), 0 0 0 0 rgba(255, 179, 102, 0), inset 0 0 0 1px rgba(255, 179, 102, 0.4);
            box-shadow:0 0 0 0 rgba(255, 179, 102, 0), 0 0 0 0 rgba(255, 179, 102, 0), inset 0 0 0 1px rgba(255, 179, 102, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-warning.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #ffb366, 0 0 0 3px rgba(255, 179, 102, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #ffb366, 0 0 0 3px rgba(255, 179, 102, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-danger .bp3-editable-text-content{
    color:#ff7373; }
  .bp3-dark .bp3-editable-text.bp3-intent-danger:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(255, 115, 115, 0), 0 0 0 0 rgba(255, 115, 115, 0), inset 0 0 0 1px rgba(255, 115, 115, 0.4);
            box-shadow:0 0 0 0 rgba(255, 115, 115, 0), 0 0 0 0 rgba(255, 115, 115, 0), inset 0 0 0 1px rgba(255, 115, 115, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-danger.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #ff7373, 0 0 0 3px rgba(255, 115, 115, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #ff7373, 0 0 0 3px rgba(255, 115, 115, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-editable-text-input,
.bp3-editable-text-content{
  color:inherit;
  display:inherit;
  font:inherit;
  letter-spacing:inherit;
  max-width:inherit;
  min-width:inherit;
  position:relative;
  resize:none;
  text-transform:inherit;
  vertical-align:top; }

.bp3-editable-text-input{
  background:none;
  border:none;
  -webkit-box-shadow:none;
          box-shadow:none;
  padding:0;
  white-space:pre-wrap;
  width:100%; }
  .bp3-editable-text-input::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input:focus{
    outline:none; }
  .bp3-editable-text-input::-ms-clear{
    display:none; }

.bp3-editable-text-content{
  overflow:hidden;
  padding-right:2px;
  text-overflow:ellipsis;
  white-space:pre; }
  .bp3-editable-text-editing > .bp3-editable-text-content{
    left:0;
    position:absolute;
    visibility:hidden; }
  .bp3-editable-text-placeholder > .bp3-editable-text-content{
    color:rgba(92, 112, 128, 0.6); }
    .bp3-dark .bp3-editable-text-placeholder > .bp3-editable-text-content{
      color:rgba(167, 182, 194, 0.6); }

.bp3-editable-text.bp3-multiline{
  display:block; }
  .bp3-editable-text.bp3-multiline .bp3-editable-text-content{
    overflow:auto;
    white-space:pre-wrap;
    word-wrap:break-word; }
.bp3-divider{
  border-bottom:1px solid rgba(16, 22, 26, 0.15);
  border-right:1px solid rgba(16, 22, 26, 0.15);
  margin:5px; }
  .bp3-dark .bp3-divider{
    border-color:rgba(16, 22, 26, 0.4); }
.bp3-control-group{
  -webkit-transform:translateZ(0);
          transform:translateZ(0);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:stretch;
      -ms-flex-align:stretch;
          align-items:stretch; }
  .bp3-control-group > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-control-group > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-control-group .bp3-button,
  .bp3-control-group .bp3-html-select,
  .bp3-control-group .bp3-input,
  .bp3-control-group .bp3-select{
    position:relative; }
  .bp3-control-group .bp3-input{
    border-radius:inherit;
    z-index:2; }
    .bp3-control-group .bp3-input:focus{
      border-radius:3px;
      z-index:14; }
    .bp3-control-group .bp3-input[class*="bp3-intent"]{
      z-index:13; }
      .bp3-control-group .bp3-input[class*="bp3-intent"]:focus{
        z-index:15; }
    .bp3-control-group .bp3-input[readonly], .bp3-control-group .bp3-input:disabled, .bp3-control-group .bp3-input.bp3-disabled{
      z-index:1; }
  .bp3-control-group .bp3-input-group[class*="bp3-intent"] .bp3-input{
    z-index:13; }
    .bp3-control-group .bp3-input-group[class*="bp3-intent"] .bp3-input:focus{
      z-index:15; }
  .bp3-control-group .bp3-button,
  .bp3-control-group .bp3-html-select select,
  .bp3-control-group .bp3-select select{
    -webkit-transform:translateZ(0);
            transform:translateZ(0);
    border-radius:inherit;
    z-index:4; }
    .bp3-control-group .bp3-button:focus,
    .bp3-control-group .bp3-html-select select:focus,
    .bp3-control-group .bp3-select select:focus{
      z-index:5; }
    .bp3-control-group .bp3-button:hover,
    .bp3-control-group .bp3-html-select select:hover,
    .bp3-control-group .bp3-select select:hover{
      z-index:6; }
    .bp3-control-group .bp3-button:active,
    .bp3-control-group .bp3-html-select select:active,
    .bp3-control-group .bp3-select select:active{
      z-index:7; }
    .bp3-control-group .bp3-button[readonly], .bp3-control-group .bp3-button:disabled, .bp3-control-group .bp3-button.bp3-disabled,
    .bp3-control-group .bp3-html-select select[readonly],
    .bp3-control-group .bp3-html-select select:disabled,
    .bp3-control-group .bp3-html-select select.bp3-disabled,
    .bp3-control-group .bp3-select select[readonly],
    .bp3-control-group .bp3-select select:disabled,
    .bp3-control-group .bp3-select select.bp3-disabled{
      z-index:3; }
    .bp3-control-group .bp3-button[class*="bp3-intent"],
    .bp3-control-group .bp3-html-select select[class*="bp3-intent"],
    .bp3-control-group .bp3-select select[class*="bp3-intent"]{
      z-index:9; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:focus,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:focus,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:focus{
        z-index:10; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:hover,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:hover,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:hover{
        z-index:11; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:active,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:active,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:active{
        z-index:12; }
      .bp3-control-group .bp3-button[class*="bp3-intent"][readonly], .bp3-control-group .bp3-button[class*="bp3-intent"]:disabled, .bp3-control-group .bp3-button[class*="bp3-intent"].bp3-disabled,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"][readonly],
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:disabled,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"].bp3-disabled,
      .bp3-control-group .bp3-select select[class*="bp3-intent"][readonly],
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:disabled,
      .bp3-control-group .bp3-select select[class*="bp3-intent"].bp3-disabled{
        z-index:8; }
  .bp3-control-group .bp3-input-group > .bp3-icon,
  .bp3-control-group .bp3-input-group > .bp3-button,
  .bp3-control-group .bp3-input-group > .bp3-input-left-container,
  .bp3-control-group .bp3-input-group > .bp3-input-action{
    z-index:16; }
  .bp3-control-group .bp3-select::after,
  .bp3-control-group .bp3-html-select::after,
  .bp3-control-group .bp3-select > .bp3-icon,
  .bp3-control-group .bp3-html-select > .bp3-icon{
    z-index:17; }
  .bp3-control-group .bp3-select:focus-within{
    z-index:5; }
  .bp3-control-group:not(.bp3-vertical) > *:not(.bp3-divider){
    margin-right:-1px; }
  .bp3-control-group:not(.bp3-vertical) > .bp3-divider:not(:first-child){
    margin-left:6px; }
  .bp3-dark .bp3-control-group:not(.bp3-vertical) > *:not(.bp3-divider){
    margin-right:0; }
  .bp3-dark .bp3-control-group:not(.bp3-vertical) > .bp3-button + .bp3-button{
    margin-left:1px; }
  .bp3-control-group .bp3-popover-wrapper,
  .bp3-control-group .bp3-popover-target{
    border-radius:inherit; }
  .bp3-control-group > :first-child{
    border-radius:3px 0 0 3px; }
  .bp3-control-group > :last-child{
    border-radius:0 3px 3px 0;
    margin-right:0; }
  .bp3-control-group > :only-child{
    border-radius:3px;
    margin-right:0; }
  .bp3-control-group .bp3-input-group .bp3-button{
    border-radius:3px; }
  .bp3-control-group .bp3-numeric-input:not(:first-child) .bp3-input-group{
    border-bottom-left-radius:0;
    border-top-left-radius:0; }
  .bp3-control-group.bp3-fill{
    width:100%; }
  .bp3-control-group > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-control-group.bp3-fill > *:not(.bp3-fixed){
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-control-group.bp3-vertical{
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column; }
    .bp3-control-group.bp3-vertical > *{
      margin-top:-1px; }
    .bp3-control-group.bp3-vertical > :first-child{
      border-radius:3px 3px 0 0;
      margin-top:0; }
    .bp3-control-group.bp3-vertical > :last-child{
      border-radius:0 0 3px 3px; }
.bp3-control{
  cursor:pointer;
  display:block;
  margin-bottom:10px;
  position:relative;
  text-transform:none; }
  .bp3-control input:checked ~ .bp3-control-indicator{
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
  .bp3-control:hover input:checked ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
  .bp3-control input:not(:disabled):active:checked ~ .bp3-control-indicator{
    background:#0e5a8a;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-control input:disabled:checked ~ .bp3-control-indicator{
    background:rgba(19, 124, 189, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-dark .bp3-control input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control:hover input:checked ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control input:not(:disabled):active:checked ~ .bp3-control-indicator{
    background-color:#0e5a8a;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-control input:disabled:checked ~ .bp3-control-indicator{
    background:rgba(14, 90, 138, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-control:not(.bp3-align-right){
    padding-left:26px; }
    .bp3-control:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-26px; }
  .bp3-control.bp3-align-right{
    padding-right:26px; }
    .bp3-control.bp3-align-right .bp3-control-indicator{
      margin-right:-26px; }
  .bp3-control.bp3-disabled{
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
  .bp3-control.bp3-inline{
    display:inline-block;
    margin-right:20px; }
  .bp3-control input{
    left:0;
    opacity:0;
    position:absolute;
    top:0;
    z-index:-1; }
  .bp3-control .bp3-control-indicator{
    background-clip:padding-box;
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    border:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    cursor:pointer;
    display:inline-block;
    font-size:16px;
    height:1em;
    margin-right:10px;
    margin-top:-3px;
    position:relative;
    -webkit-user-select:none;
       -moz-user-select:none;
        -ms-user-select:none;
            user-select:none;
    vertical-align:middle;
    width:1em; }
    .bp3-control .bp3-control-indicator::before{
      content:"";
      display:block;
      height:1em;
      width:1em; }
  .bp3-control:hover .bp3-control-indicator{
    background-color:#ebf1f5; }
  .bp3-control input:not(:disabled):active ~ .bp3-control-indicator{
    background:#d8e1e8;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-control input:disabled ~ .bp3-control-indicator{
    background:rgba(206, 217, 224, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none;
    cursor:not-allowed; }
  .bp3-control input:focus ~ .bp3-control-indicator{
    outline:rgba(19, 124, 189, 0.6) auto 2px;
    outline-offset:2px;
    -moz-outline-radius:6px; }
  .bp3-control.bp3-align-right .bp3-control-indicator{
    float:right;
    margin-left:10px;
    margin-top:1px; }
  .bp3-control.bp3-large{
    font-size:16px; }
    .bp3-control.bp3-large:not(.bp3-align-right){
      padding-left:30px; }
      .bp3-control.bp3-large:not(.bp3-align-right) .bp3-control-indicator{
        margin-left:-30px; }
    .bp3-control.bp3-large.bp3-align-right{
      padding-right:30px; }
      .bp3-control.bp3-large.bp3-align-right .bp3-control-indicator{
        margin-right:-30px; }
    .bp3-control.bp3-large .bp3-control-indicator{
      font-size:20px; }
    .bp3-control.bp3-large.bp3-align-right .bp3-control-indicator{
      margin-top:0; }
  .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator{
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
  .bp3-control.bp3-checkbox:hover input:indeterminate ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
  .bp3-control.bp3-checkbox input:not(:disabled):active:indeterminate ~ .bp3-control-indicator{
    background:#0e5a8a;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
    background:rgba(19, 124, 189, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-dark .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-checkbox:hover input:indeterminate ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-checkbox input:not(:disabled):active:indeterminate ~ .bp3-control-indicator{
    background-color:#0e5a8a;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
    background:rgba(14, 90, 138, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-control.bp3-checkbox .bp3-control-indicator{
    border-radius:3px; }
  .bp3-control.bp3-checkbox input:checked ~ .bp3-control-indicator::before{
    background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M12 5c-.28 0-.53.11-.71.29L7 9.59l-2.29-2.3a1.003 1.003 0 00-1.42 1.42l3 3c.18.18.43.29.71.29s.53-.11.71-.29l5-5A1.003 1.003 0 0012 5z' fill='white'/%3e%3c/svg%3e"); }
  .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator::before{
    background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M11 7H5c-.55 0-1 .45-1 1s.45 1 1 1h6c.55 0 1-.45 1-1s-.45-1-1-1z' fill='white'/%3e%3c/svg%3e"); }
  .bp3-control.bp3-radio .bp3-control-indicator{
    border-radius:50%; }
  .bp3-control.bp3-radio input:checked ~ .bp3-control-indicator::before{
    background-image:radial-gradient(#ffffff, #ffffff 28%, transparent 32%); }
  .bp3-control.bp3-radio input:checked:disabled ~ .bp3-control-indicator::before{
    opacity:0.5; }
  .bp3-control.bp3-radio input:focus ~ .bp3-control-indicator{
    -moz-outline-radius:16px; }
  .bp3-control.bp3-switch input ~ .bp3-control-indicator{
    background:rgba(167, 182, 194, 0.5); }
  .bp3-control.bp3-switch:hover input ~ .bp3-control-indicator{
    background:rgba(115, 134, 148, 0.5); }
  .bp3-control.bp3-switch input:not(:disabled):active ~ .bp3-control-indicator{
    background:rgba(92, 112, 128, 0.5); }
  .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator{
    background:rgba(206, 217, 224, 0.5); }
    .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator::before{
      background:rgba(255, 255, 255, 0.8); }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator{
    background:#137cbd; }
  .bp3-control.bp3-switch:hover input:checked ~ .bp3-control-indicator{
    background:#106ba3; }
  .bp3-control.bp3-switch input:checked:not(:disabled):active ~ .bp3-control-indicator{
    background:#0e5a8a; }
  .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator{
    background:rgba(19, 124, 189, 0.5); }
    .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator::before{
      background:rgba(255, 255, 255, 0.8); }
  .bp3-control.bp3-switch:not(.bp3-align-right){
    padding-left:38px; }
    .bp3-control.bp3-switch:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-38px; }
  .bp3-control.bp3-switch.bp3-align-right{
    padding-right:38px; }
    .bp3-control.bp3-switch.bp3-align-right .bp3-control-indicator{
      margin-right:-38px; }
  .bp3-control.bp3-switch .bp3-control-indicator{
    border:none;
    border-radius:1.75em;
    -webkit-box-shadow:none !important;
            box-shadow:none !important;
    min-width:1.75em;
    -webkit-transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    width:auto; }
    .bp3-control.bp3-switch .bp3-control-indicator::before{
      background:#ffffff;
      border-radius:50%;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
      height:calc(1em - 4px);
      left:0;
      margin:2px;
      position:absolute;
      -webkit-transition:left 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
      transition:left 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
      width:calc(1em - 4px); }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator::before{
    left:calc(100% - 1em); }
  .bp3-control.bp3-switch.bp3-large:not(.bp3-align-right){
    padding-left:45px; }
    .bp3-control.bp3-switch.bp3-large:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-45px; }
  .bp3-control.bp3-switch.bp3-large.bp3-align-right{
    padding-right:45px; }
    .bp3-control.bp3-switch.bp3-large.bp3-align-right .bp3-control-indicator{
      margin-right:-45px; }
  .bp3-dark .bp3-control.bp3-switch input ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.5); }
  .bp3-dark .bp3-control.bp3-switch:hover input ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.7); }
  .bp3-dark .bp3-control.bp3-switch input:not(:disabled):active ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.9); }
  .bp3-dark .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator{
    background:rgba(57, 75, 89, 0.5); }
    .bp3-dark .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator::before{
      background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator{
    background:#137cbd; }
  .bp3-dark .bp3-control.bp3-switch:hover input:checked ~ .bp3-control-indicator{
    background:#106ba3; }
  .bp3-dark .bp3-control.bp3-switch input:checked:not(:disabled):active ~ .bp3-control-indicator{
    background:#0e5a8a; }
  .bp3-dark .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator{
    background:rgba(14, 90, 138, 0.5); }
    .bp3-dark .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator::before{
      background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch .bp3-control-indicator::before{
    background:#394b59;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator::before{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-control.bp3-switch .bp3-switch-inner-text{
    font-size:0.7em;
    text-align:center; }
  .bp3-control.bp3-switch .bp3-control-indicator-child:first-child{
    line-height:0;
    margin-left:0.5em;
    margin-right:1.2em;
    visibility:hidden; }
  .bp3-control.bp3-switch .bp3-control-indicator-child:last-child{
    line-height:1em;
    margin-left:1.2em;
    margin-right:0.5em;
    visibility:visible; }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator .bp3-control-indicator-child:first-child{
    line-height:1em;
    visibility:visible; }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator .bp3-control-indicator-child:last-child{
    line-height:0;
    visibility:hidden; }
  .bp3-dark .bp3-control{
    color:#f5f8fa; }
    .bp3-dark .bp3-control.bp3-disabled{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-control .bp3-control-indicator{
      background-color:#394b59;
      background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
      background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-control:hover .bp3-control-indicator{
      background-color:#30404d; }
    .bp3-dark .bp3-control input:not(:disabled):active ~ .bp3-control-indicator{
      background:#202b33;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-control input:disabled ~ .bp3-control-indicator{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      cursor:not-allowed; }
    .bp3-dark .bp3-control.bp3-checkbox input:disabled:checked ~ .bp3-control-indicator, .bp3-dark .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
      color:rgba(167, 182, 194, 0.6); }
.bp3-file-input{
  cursor:pointer;
  display:inline-block;
  height:30px;
  position:relative; }
  .bp3-file-input input{
    margin:0;
    min-width:200px;
    opacity:0; }
    .bp3-file-input input:disabled + .bp3-file-upload-input,
    .bp3-file-input input.bp3-disabled + .bp3-file-upload-input{
      background:rgba(206, 217, 224, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed;
      resize:none; }
      .bp3-file-input input:disabled + .bp3-file-upload-input::after,
      .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after{
        background-color:rgba(206, 217, 224, 0.5);
        background-image:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:rgba(92, 112, 128, 0.6);
        cursor:not-allowed;
        outline:none; }
        .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active, .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active:hover,
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active,
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active:hover{
          background:rgba(206, 217, 224, 0.7); }
      .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input, .bp3-dark
      .bp3-file-input input.bp3-disabled + .bp3-file-upload-input{
        background:rgba(57, 75, 89, 0.5);
        -webkit-box-shadow:none;
                box-shadow:none;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input::after, .bp3-dark
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after{
          background-color:rgba(57, 75, 89, 0.5);
          background-image:none;
          -webkit-box-shadow:none;
                  box-shadow:none;
          color:rgba(167, 182, 194, 0.6); }
          .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active, .bp3-dark
          .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active{
            background:rgba(57, 75, 89, 0.7); }
  .bp3-file-input.bp3-file-input-has-selection .bp3-file-upload-input{
    color:#182026; }
  .bp3-dark .bp3-file-input.bp3-file-input-has-selection .bp3-file-upload-input{
    color:#f5f8fa; }
  .bp3-file-input.bp3-fill{
    width:100%; }
  .bp3-file-input.bp3-large,
  .bp3-large .bp3-file-input{
    height:40px; }
  .bp3-file-input .bp3-file-upload-input-custom-text::after{
    content:attr(bp3-button-text); }

.bp3-file-upload-input{
  -webkit-appearance:none;
     -moz-appearance:none;
          appearance:none;
  background:#ffffff;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
  color:#182026;
  font-size:14px;
  font-weight:400;
  height:30px;
  line-height:30px;
  outline:none;
  padding:0 10px;
  -webkit-transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  vertical-align:middle;
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  color:rgba(92, 112, 128, 0.6);
  left:0;
  padding-right:80px;
  position:absolute;
  right:0;
  top:0;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-file-upload-input::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input:focus, .bp3-file-upload-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-file-upload-input[type="search"], .bp3-file-upload-input.bp3-round{
    border-radius:30px;
    -webkit-box-sizing:border-box;
            box-sizing:border-box;
    padding-left:10px; }
  .bp3-file-upload-input[readonly]{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-file-upload-input:disabled, .bp3-file-upload-input.bp3-disabled{
    background:rgba(206, 217, 224, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    resize:none; }
  .bp3-file-upload-input::after{
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    color:#182026;
    min-height:24px;
    min-width:24px;
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    border-radius:3px;
    content:"Browse";
    line-height:24px;
    margin:3px;
    position:absolute;
    right:0;
    text-align:center;
    top:0;
    width:70px; }
    .bp3-file-upload-input::after:hover{
      background-clip:padding-box;
      background-color:#ebf1f5;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
    .bp3-file-upload-input::after:active, .bp3-file-upload-input::after.bp3-active{
      background-color:#d8e1e8;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-file-upload-input::after:disabled, .bp3-file-upload-input::after.bp3-disabled{
      background-color:rgba(206, 217, 224, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed;
      outline:none; }
      .bp3-file-upload-input::after:disabled.bp3-active, .bp3-file-upload-input::after:disabled.bp3-active:hover, .bp3-file-upload-input::after.bp3-disabled.bp3-active, .bp3-file-upload-input::after.bp3-disabled.bp3-active:hover{
        background:rgba(206, 217, 224, 0.7); }
  .bp3-file-upload-input:hover::after{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
  .bp3-file-upload-input:active::after{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-large .bp3-file-upload-input{
    font-size:16px;
    height:40px;
    line-height:40px;
    padding-right:95px; }
    .bp3-large .bp3-file-upload-input[type="search"], .bp3-large .bp3-file-upload-input.bp3-round{
      padding:0 15px; }
    .bp3-large .bp3-file-upload-input::after{
      min-height:30px;
      min-width:30px;
      line-height:30px;
      margin:5px;
      width:85px; }
  .bp3-dark .bp3-file-upload-input{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa;
    color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input:disabled, .bp3-dark .bp3-file-upload-input.bp3-disabled{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::after{
      background-color:#394b59;
      background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
      background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      color:#f5f8fa; }
      .bp3-dark .bp3-file-upload-input::after:hover, .bp3-dark .bp3-file-upload-input::after:active, .bp3-dark .bp3-file-upload-input::after.bp3-active{
        color:#f5f8fa; }
      .bp3-dark .bp3-file-upload-input::after:hover{
        background-color:#30404d;
        -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-file-upload-input::after:active, .bp3-dark .bp3-file-upload-input::after.bp3-active{
        background-color:#202b33;
        background-image:none;
        -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
                box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
      .bp3-dark .bp3-file-upload-input::after:disabled, .bp3-dark .bp3-file-upload-input::after.bp3-disabled{
        background-color:rgba(57, 75, 89, 0.5);
        background-image:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-file-upload-input::after:disabled.bp3-active, .bp3-dark .bp3-file-upload-input::after.bp3-disabled.bp3-active{
          background:rgba(57, 75, 89, 0.7); }
      .bp3-dark .bp3-file-upload-input::after .bp3-button-spinner .bp3-spinner-head{
        background:rgba(16, 22, 26, 0.5);
        stroke:#8a9ba8; }
    .bp3-dark .bp3-file-upload-input:hover::after{
      background-color:#30404d;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input:active::after{
      background-color:#202b33;
      background-image:none;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
.bp3-file-upload-input::after{
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
.bp3-form-group{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:0 0 15px; }
  .bp3-form-group label.bp3-label{
    margin-bottom:5px; }
  .bp3-form-group .bp3-control{
    margin-top:7px; }
  .bp3-form-group .bp3-form-helper-text{
    color:#5c7080;
    font-size:12px;
    margin-top:5px; }
  .bp3-form-group.bp3-intent-primary .bp3-form-helper-text{
    color:#106ba3; }
  .bp3-form-group.bp3-intent-success .bp3-form-helper-text{
    color:#0d8050; }
  .bp3-form-group.bp3-intent-warning .bp3-form-helper-text{
    color:#bf7326; }
  .bp3-form-group.bp3-intent-danger .bp3-form-helper-text{
    color:#c23030; }
  .bp3-form-group.bp3-inline{
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start;
    -webkit-box-orient:horizontal;
    -webkit-box-direction:normal;
        -ms-flex-direction:row;
            flex-direction:row; }
    .bp3-form-group.bp3-inline.bp3-large label.bp3-label{
      line-height:40px;
      margin:0 10px 0 0; }
    .bp3-form-group.bp3-inline label.bp3-label{
      line-height:30px;
      margin:0 10px 0 0; }
  .bp3-form-group.bp3-disabled .bp3-label,
  .bp3-form-group.bp3-disabled .bp3-text-muted,
  .bp3-form-group.bp3-disabled .bp3-form-helper-text{
    color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-dark .bp3-form-group.bp3-intent-primary .bp3-form-helper-text{
    color:#48aff0; }
  .bp3-dark .bp3-form-group.bp3-intent-success .bp3-form-helper-text{
    color:#3dcc91; }
  .bp3-dark .bp3-form-group.bp3-intent-warning .bp3-form-helper-text{
    color:#ffb366; }
  .bp3-dark .bp3-form-group.bp3-intent-danger .bp3-form-helper-text{
    color:#ff7373; }
  .bp3-dark .bp3-form-group .bp3-form-helper-text{
    color:#a7b6c2; }
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-label,
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-text-muted,
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-form-helper-text{
    color:rgba(167, 182, 194, 0.6) !important; }
.bp3-input-group{
  display:block;
  position:relative; }
  .bp3-input-group .bp3-input{
    position:relative;
    width:100%; }
    .bp3-input-group .bp3-input:not(:first-child){
      padding-left:30px; }
    .bp3-input-group .bp3-input:not(:last-child){
      padding-right:30px; }
  .bp3-input-group .bp3-input-action,
  .bp3-input-group > .bp3-input-left-container,
  .bp3-input-group > .bp3-button,
  .bp3-input-group > .bp3-icon{
    position:absolute;
    top:0; }
    .bp3-input-group .bp3-input-action:first-child,
    .bp3-input-group > .bp3-input-left-container:first-child,
    .bp3-input-group > .bp3-button:first-child,
    .bp3-input-group > .bp3-icon:first-child{
      left:0; }
    .bp3-input-group .bp3-input-action:last-child,
    .bp3-input-group > .bp3-input-left-container:last-child,
    .bp3-input-group > .bp3-button:last-child,
    .bp3-input-group > .bp3-icon:last-child{
      right:0; }
  .bp3-input-group .bp3-button{
    min-height:24px;
    min-width:24px;
    margin:3px;
    padding:0 7px; }
    .bp3-input-group .bp3-button:empty{
      padding:0; }
  .bp3-input-group > .bp3-input-left-container,
  .bp3-input-group > .bp3-icon{
    z-index:1; }
  .bp3-input-group > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group > .bp3-icon{
    color:#5c7080; }
    .bp3-input-group > .bp3-input-left-container > .bp3-icon:empty,
    .bp3-input-group > .bp3-icon:empty{
      font-family:"Icons16", sans-serif;
      font-size:16px;
      font-style:normal;
      font-weight:400;
      line-height:1;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased; }
  .bp3-input-group > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group > .bp3-icon,
  .bp3-input-group .bp3-input-action > .bp3-spinner{
    margin:7px; }
  .bp3-input-group .bp3-tag{
    margin:5px; }
  .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus),
  .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus){
    color:#5c7080; }
    .bp3-dark .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus), .bp3-dark
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus){
      color:#a7b6c2; }
    .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-standard, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-large,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-standard,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-large{
      color:#5c7080; }
  .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled,
  .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled{
    color:rgba(92, 112, 128, 0.6) !important; }
    .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon-standard, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon-large,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon-standard,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon-large{
      color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-input-group.bp3-disabled{
    cursor:not-allowed; }
    .bp3-input-group.bp3-disabled .bp3-icon{
      color:rgba(92, 112, 128, 0.6); }
  .bp3-input-group.bp3-large .bp3-button{
    min-height:30px;
    min-width:30px;
    margin:5px; }
  .bp3-input-group.bp3-large > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group.bp3-large > .bp3-icon,
  .bp3-input-group.bp3-large .bp3-input-action > .bp3-spinner{
    margin:12px; }
  .bp3-input-group.bp3-large .bp3-input{
    font-size:16px;
    height:40px;
    line-height:40px; }
    .bp3-input-group.bp3-large .bp3-input[type="search"], .bp3-input-group.bp3-large .bp3-input.bp3-round{
      padding:0 15px; }
    .bp3-input-group.bp3-large .bp3-input:not(:first-child){
      padding-left:40px; }
    .bp3-input-group.bp3-large .bp3-input:not(:last-child){
      padding-right:40px; }
  .bp3-input-group.bp3-small .bp3-button{
    min-height:20px;
    min-width:20px;
    margin:2px; }
  .bp3-input-group.bp3-small .bp3-tag{
    min-height:20px;
    min-width:20px;
    margin:2px; }
  .bp3-input-group.bp3-small > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group.bp3-small > .bp3-icon,
  .bp3-input-group.bp3-small .bp3-input-action > .bp3-spinner{
    margin:4px; }
  .bp3-input-group.bp3-small .bp3-input{
    font-size:12px;
    height:24px;
    line-height:24px;
    padding-left:8px;
    padding-right:8px; }
    .bp3-input-group.bp3-small .bp3-input[type="search"], .bp3-input-group.bp3-small .bp3-input.bp3-round{
      padding:0 12px; }
    .bp3-input-group.bp3-small .bp3-input:not(:first-child){
      padding-left:24px; }
    .bp3-input-group.bp3-small .bp3-input:not(:last-child){
      padding-right:24px; }
  .bp3-input-group.bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:100%; }
  .bp3-input-group.bp3-round .bp3-button,
  .bp3-input-group.bp3-round .bp3-input,
  .bp3-input-group.bp3-round .bp3-tag{
    border-radius:30px; }
  .bp3-dark .bp3-input-group .bp3-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-input-group.bp3-disabled .bp3-icon{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-input-group.bp3-intent-primary .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-primary .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-primary .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #137cbd;
              box-shadow:inset 0 0 0 1px #137cbd; }
    .bp3-input-group.bp3-intent-primary .bp3-input:disabled, .bp3-input-group.bp3-intent-primary .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-primary > .bp3-icon{
    color:#106ba3; }
    .bp3-dark .bp3-input-group.bp3-intent-primary > .bp3-icon{
      color:#48aff0; }
  .bp3-input-group.bp3-intent-success .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-success .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-success .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #0f9960;
              box-shadow:inset 0 0 0 1px #0f9960; }
    .bp3-input-group.bp3-intent-success .bp3-input:disabled, .bp3-input-group.bp3-intent-success .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-success > .bp3-icon{
    color:#0d8050; }
    .bp3-dark .bp3-input-group.bp3-intent-success > .bp3-icon{
      color:#3dcc91; }
  .bp3-input-group.bp3-intent-warning .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-warning .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-warning .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #d9822b;
              box-shadow:inset 0 0 0 1px #d9822b; }
    .bp3-input-group.bp3-intent-warning .bp3-input:disabled, .bp3-input-group.bp3-intent-warning .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-warning > .bp3-icon{
    color:#bf7326; }
    .bp3-dark .bp3-input-group.bp3-intent-warning > .bp3-icon{
      color:#ffb366; }
  .bp3-input-group.bp3-intent-danger .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-danger .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-danger .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #db3737;
              box-shadow:inset 0 0 0 1px #db3737; }
    .bp3-input-group.bp3-intent-danger .bp3-input:disabled, .bp3-input-group.bp3-intent-danger .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-danger > .bp3-icon{
    color:#c23030; }
    .bp3-dark .bp3-input-group.bp3-intent-danger > .bp3-icon{
      color:#ff7373; }
.bp3-input{
  -webkit-appearance:none;
     -moz-appearance:none;
          appearance:none;
  background:#ffffff;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
  color:#182026;
  font-size:14px;
  font-weight:400;
  height:30px;
  line-height:30px;
  outline:none;
  padding:0 10px;
  -webkit-transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  vertical-align:middle; }
  .bp3-input::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input:focus, .bp3-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-input[type="search"], .bp3-input.bp3-round{
    border-radius:30px;
    -webkit-box-sizing:border-box;
            box-sizing:border-box;
    padding-left:10px; }
  .bp3-input[readonly]{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-input:disabled, .bp3-input.bp3-disabled{
    background:rgba(206, 217, 224, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    resize:none; }
  .bp3-input.bp3-large{
    font-size:16px;
    height:40px;
    line-height:40px; }
    .bp3-input.bp3-large[type="search"], .bp3-input.bp3-large.bp3-round{
      padding:0 15px; }
  .bp3-input.bp3-small{
    font-size:12px;
    height:24px;
    line-height:24px;
    padding-left:8px;
    padding-right:8px; }
    .bp3-input.bp3-small[type="search"], .bp3-input.bp3-small.bp3-round{
      padding:0 12px; }
  .bp3-input.bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:100%; }
  .bp3-dark .bp3-input{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark .bp3-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-input:disabled, .bp3-dark .bp3-input.bp3-disabled{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
  .bp3-input.bp3-intent-primary{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-primary:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-primary[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #137cbd;
              box-shadow:inset 0 0 0 1px #137cbd; }
    .bp3-input.bp3-intent-primary:disabled, .bp3-input.bp3-intent-primary.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-primary:focus{
        -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-primary[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #137cbd;
                box-shadow:inset 0 0 0 1px #137cbd; }
      .bp3-dark .bp3-input.bp3-intent-primary:disabled, .bp3-dark .bp3-input.bp3-intent-primary.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-success{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-success:focus{
      -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-success[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #0f9960;
              box-shadow:inset 0 0 0 1px #0f9960; }
    .bp3-input.bp3-intent-success:disabled, .bp3-input.bp3-intent-success.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-success{
      -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-success:focus{
        -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #0f9960, 0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-success[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #0f9960;
                box-shadow:inset 0 0 0 1px #0f9960; }
      .bp3-dark .bp3-input.bp3-intent-success:disabled, .bp3-dark .bp3-input.bp3-intent-success.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-warning{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-warning:focus{
      -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-warning[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #d9822b;
              box-shadow:inset 0 0 0 1px #d9822b; }
    .bp3-input.bp3-intent-warning:disabled, .bp3-input.bp3-intent-warning.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-warning:focus{
        -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #d9822b, 0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-warning[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #d9822b;
                box-shadow:inset 0 0 0 1px #d9822b; }
      .bp3-dark .bp3-input.bp3-intent-warning:disabled, .bp3-dark .bp3-input.bp3-intent-warning.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-danger{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-danger:focus{
      -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-danger[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #db3737;
              box-shadow:inset 0 0 0 1px #db3737; }
    .bp3-input.bp3-intent-danger:disabled, .bp3-input.bp3-intent-danger.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-danger:focus{
        -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #db3737, 0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-danger[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #db3737;
                box-shadow:inset 0 0 0 1px #db3737; }
      .bp3-dark .bp3-input.bp3-intent-danger:disabled, .bp3-dark .bp3-input.bp3-intent-danger.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input::-ms-clear{
    display:none; }
textarea.bp3-input{
  max-width:100%;
  padding:10px; }
  textarea.bp3-input, textarea.bp3-input.bp3-large, textarea.bp3-input.bp3-small{
    height:auto;
    line-height:inherit; }
  textarea.bp3-input.bp3-small{
    padding:8px; }
  .bp3-dark textarea.bp3-input{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark textarea.bp3-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark textarea.bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark textarea.bp3-input:disabled, .bp3-dark textarea.bp3-input.bp3-disabled{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
label.bp3-label{
  display:block;
  margin-bottom:15px;
  margin-top:0; }
  label.bp3-label .bp3-html-select,
  label.bp3-label .bp3-input,
  label.bp3-label .bp3-select,
  label.bp3-label .bp3-slider,
  label.bp3-label .bp3-popover-wrapper{
    display:block;
    margin-top:5px;
    text-transform:none; }
  label.bp3-label .bp3-button-group{
    margin-top:5px; }
  label.bp3-label .bp3-select select,
  label.bp3-label .bp3-html-select select{
    font-weight:400;
    vertical-align:top;
    width:100%; }
  label.bp3-label.bp3-disabled,
  label.bp3-label.bp3-disabled .bp3-text-muted{
    color:rgba(92, 112, 128, 0.6); }
  label.bp3-label.bp3-inline{
    line-height:30px; }
    label.bp3-label.bp3-inline .bp3-html-select,
    label.bp3-label.bp3-inline .bp3-input,
    label.bp3-label.bp3-inline .bp3-input-group,
    label.bp3-label.bp3-inline .bp3-select,
    label.bp3-label.bp3-inline .bp3-popover-wrapper{
      display:inline-block;
      margin:0 0 0 5px;
      vertical-align:top; }
    label.bp3-label.bp3-inline .bp3-button-group{
      margin:0 0 0 5px; }
    label.bp3-label.bp3-inline .bp3-input-group .bp3-input{
      margin-left:0; }
    label.bp3-label.bp3-inline.bp3-large{
      line-height:40px; }
  label.bp3-label:not(.bp3-inline) .bp3-popover-target{
    display:block; }
  .bp3-dark label.bp3-label{
    color:#f5f8fa; }
    .bp3-dark label.bp3-label.bp3-disabled,
    .bp3-dark label.bp3-label.bp3-disabled .bp3-text-muted{
      color:rgba(167, 182, 194, 0.6); }
.bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button{
  -webkit-box-flex:1;
      -ms-flex:1 1 14px;
          flex:1 1 14px;
  min-height:0;
  padding:0;
  width:30px; }
  .bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button:first-child{
    border-radius:0 3px 0 0; }
  .bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button:last-child{
    border-radius:0 0 3px 0; }

.bp3-numeric-input .bp3-button-group.bp3-vertical:first-child > .bp3-button:first-child{
  border-radius:3px 0 0 0; }

.bp3-numeric-input .bp3-button-group.bp3-vertical:first-child > .bp3-button:last-child{
  border-radius:0 0 0 3px; }

.bp3-numeric-input.bp3-large .bp3-button-group.bp3-vertical > .bp3-button{
  width:40px; }

form{
  display:block; }
.bp3-html-select select,
.bp3-select select{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border:none;
  border-radius:3px;
  cursor:pointer;
  font-size:14px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  padding:5px 10px;
  text-align:left;
  vertical-align:middle;
  background-color:#f5f8fa;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
  color:#182026;
  -moz-appearance:none;
  -webkit-appearance:none;
  border-radius:3px;
  height:30px;
  padding:0 25px 0 10px;
  width:100%; }
  .bp3-html-select select > *, .bp3-select select > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-html-select select > .bp3-fill, .bp3-select select > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-html-select select::before,
  .bp3-select select::before, .bp3-html-select select > *, .bp3-select select > *{
    margin-right:7px; }
  .bp3-html-select select:empty::before,
  .bp3-select select:empty::before,
  .bp3-html-select select > :last-child,
  .bp3-select select > :last-child{
    margin-right:0; }
  .bp3-html-select select:hover,
  .bp3-select select:hover{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
  .bp3-html-select select:active,
  .bp3-select select:active, .bp3-html-select select.bp3-active,
  .bp3-select select.bp3-active{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-html-select select:disabled,
  .bp3-select select:disabled, .bp3-html-select select.bp3-disabled,
  .bp3-select select.bp3-disabled{
    background-color:rgba(206, 217, 224, 0.5);
    background-image:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    outline:none; }
    .bp3-html-select select:disabled.bp3-active,
    .bp3-select select:disabled.bp3-active, .bp3-html-select select:disabled.bp3-active:hover,
    .bp3-select select:disabled.bp3-active:hover, .bp3-html-select select.bp3-disabled.bp3-active,
    .bp3-select select.bp3-disabled.bp3-active, .bp3-html-select select.bp3-disabled.bp3-active:hover,
    .bp3-select select.bp3-disabled.bp3-active:hover{
      background:rgba(206, 217, 224, 0.7); }

.bp3-html-select.bp3-minimal select,
.bp3-select.bp3-minimal select{
  background:none;
  -webkit-box-shadow:none;
          box-shadow:none; }
  .bp3-html-select.bp3-minimal select:hover,
  .bp3-select.bp3-minimal select:hover{
    background:rgba(167, 182, 194, 0.3);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:#182026;
    text-decoration:none; }
  .bp3-html-select.bp3-minimal select:active,
  .bp3-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal select.bp3-active,
  .bp3-select.bp3-minimal select.bp3-active{
    background:rgba(115, 134, 148, 0.3);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:#182026; }
  .bp3-html-select.bp3-minimal select:disabled,
  .bp3-select.bp3-minimal select:disabled, .bp3-html-select.bp3-minimal select:disabled:hover,
  .bp3-select.bp3-minimal select:disabled:hover, .bp3-html-select.bp3-minimal select.bp3-disabled,
  .bp3-select.bp3-minimal select.bp3-disabled, .bp3-html-select.bp3-minimal select.bp3-disabled:hover,
  .bp3-select.bp3-minimal select.bp3-disabled:hover{
    background:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
    .bp3-html-select.bp3-minimal select:disabled.bp3-active,
    .bp3-select.bp3-minimal select:disabled.bp3-active, .bp3-html-select.bp3-minimal select:disabled:hover.bp3-active,
    .bp3-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-html-select.bp3-minimal select.bp3-disabled.bp3-active,
    .bp3-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-disabled:hover.bp3-active,
    .bp3-select.bp3-minimal select.bp3-disabled:hover.bp3-active{
      background:rgba(115, 134, 148, 0.3); }
  .bp3-dark .bp3-html-select.bp3-minimal select, .bp3-html-select.bp3-minimal .bp3-dark select,
  .bp3-dark .bp3-select.bp3-minimal select, .bp3-select.bp3-minimal .bp3-dark select{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:inherit; }
    .bp3-dark .bp3-html-select.bp3-minimal select:hover, .bp3-html-select.bp3-minimal .bp3-dark select:hover,
    .bp3-dark .bp3-select.bp3-minimal select:hover, .bp3-select.bp3-minimal .bp3-dark select:hover, .bp3-dark .bp3-html-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal .bp3-dark select:active,
    .bp3-dark .bp3-select.bp3-minimal select:active, .bp3-select.bp3-minimal .bp3-dark select:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-active,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-html-select.bp3-minimal select:hover, .bp3-html-select.bp3-minimal .bp3-dark select:hover,
    .bp3-dark .bp3-select.bp3-minimal select:hover, .bp3-select.bp3-minimal .bp3-dark select:hover{
      background:rgba(138, 155, 168, 0.15); }
    .bp3-dark .bp3-html-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal .bp3-dark select:active,
    .bp3-dark .bp3-select.bp3-minimal select:active, .bp3-select.bp3-minimal .bp3-dark select:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-active,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-active{
      background:rgba(138, 155, 168, 0.3);
      color:#f5f8fa; }
    .bp3-dark .bp3-html-select.bp3-minimal select:disabled, .bp3-html-select.bp3-minimal .bp3-dark select:disabled,
    .bp3-dark .bp3-select.bp3-minimal select:disabled, .bp3-select.bp3-minimal .bp3-dark select:disabled, .bp3-dark .bp3-html-select.bp3-minimal select:disabled:hover, .bp3-html-select.bp3-minimal .bp3-dark select:disabled:hover,
    .bp3-dark .bp3-select.bp3-minimal select:disabled:hover, .bp3-select.bp3-minimal .bp3-dark select:disabled:hover, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled:hover,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled:hover{
      background:none;
      color:rgba(167, 182, 194, 0.6);
      cursor:not-allowed; }
      .bp3-dark .bp3-html-select.bp3-minimal select:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select:disabled.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select:disabled:hover.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-select.bp3-minimal .bp3-dark select:disabled:hover.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled:hover.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled:hover.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled:hover.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled:hover.bp3-active{
        background:rgba(138, 155, 168, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-primary,
  .bp3-select.bp3-minimal select.bp3-intent-primary{
    color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover,
    .bp3-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-html-select.bp3-minimal select.bp3-intent-primary:active,
    .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover,
    .bp3-select.bp3-minimal select.bp3-intent-primary:hover{
      background:rgba(19, 124, 189, 0.15);
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:active,
    .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active{
      background:rgba(19, 124, 189, 0.3);
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled{
      background:none;
      color:rgba(16, 107, 163, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active{
        background:rgba(19, 124, 189, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
      stroke:#106ba3; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary{
      color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.2);
        color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(72, 175, 240, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-success,
  .bp3-select.bp3-minimal select.bp3-intent-success{
    color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:hover,
    .bp3-select.bp3-minimal select.bp3-intent-success:hover, .bp3-html-select.bp3-minimal select.bp3-intent-success:active,
    .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:hover,
    .bp3-select.bp3-minimal select.bp3-intent-success:hover{
      background:rgba(15, 153, 96, 0.15);
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:active,
    .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active{
      background:rgba(15, 153, 96, 0.3);
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled{
      background:none;
      color:rgba(13, 128, 80, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active{
        background:rgba(15, 153, 96, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-success .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
      stroke:#0d8050; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success{
      color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.2);
        color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(61, 204, 145, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-warning,
  .bp3-select.bp3-minimal select.bp3-intent-warning{
    color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover,
    .bp3-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-html-select.bp3-minimal select.bp3-intent-warning:active,
    .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover,
    .bp3-select.bp3-minimal select.bp3-intent-warning:hover{
      background:rgba(217, 130, 43, 0.15);
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:active,
    .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active{
      background:rgba(217, 130, 43, 0.3);
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled{
      background:none;
      color:rgba(191, 115, 38, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active{
        background:rgba(217, 130, 43, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
      stroke:#bf7326; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning{
      color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.2);
        color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(255, 179, 102, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-danger,
  .bp3-select.bp3-minimal select.bp3-intent-danger{
    color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover,
    .bp3-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-html-select.bp3-minimal select.bp3-intent-danger:active,
    .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover,
    .bp3-select.bp3-minimal select.bp3-intent-danger:hover{
      background:rgba(219, 55, 55, 0.15);
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:active,
    .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active{
      background:rgba(219, 55, 55, 0.3);
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled{
      background:none;
      color:rgba(194, 48, 48, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active{
        background:rgba(219, 55, 55, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
      stroke:#c23030; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger{
      color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.2);
        color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(255, 115, 115, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }

.bp3-html-select.bp3-large select,
.bp3-select.bp3-large select{
  font-size:16px;
  height:40px;
  padding-right:35px; }

.bp3-dark .bp3-html-select select, .bp3-dark .bp3-select select{
  background-color:#394b59;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
  color:#f5f8fa; }
  .bp3-dark .bp3-html-select select:hover, .bp3-dark .bp3-select select:hover, .bp3-dark .bp3-html-select select:active, .bp3-dark .bp3-select select:active, .bp3-dark .bp3-html-select select.bp3-active, .bp3-dark .bp3-select select.bp3-active{
    color:#f5f8fa; }
  .bp3-dark .bp3-html-select select:hover, .bp3-dark .bp3-select select:hover{
    background-color:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-html-select select:active, .bp3-dark .bp3-select select:active, .bp3-dark .bp3-html-select select.bp3-active, .bp3-dark .bp3-select select.bp3-active{
    background-color:#202b33;
    background-image:none;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-html-select select:disabled, .bp3-dark .bp3-select select:disabled, .bp3-dark .bp3-html-select select.bp3-disabled, .bp3-dark .bp3-select select.bp3-disabled{
    background-color:rgba(57, 75, 89, 0.5);
    background-image:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-html-select select:disabled.bp3-active, .bp3-dark .bp3-select select:disabled.bp3-active, .bp3-dark .bp3-html-select select.bp3-disabled.bp3-active, .bp3-dark .bp3-select select.bp3-disabled.bp3-active{
      background:rgba(57, 75, 89, 0.7); }
  .bp3-dark .bp3-html-select select .bp3-button-spinner .bp3-spinner-head, .bp3-dark .bp3-select select .bp3-button-spinner .bp3-spinner-head{
    background:rgba(16, 22, 26, 0.5);
    stroke:#8a9ba8; }

.bp3-html-select select:disabled,
.bp3-select select:disabled{
  background-color:rgba(206, 217, 224, 0.5);
  -webkit-box-shadow:none;
          box-shadow:none;
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-html-select .bp3-icon,
.bp3-select .bp3-icon, .bp3-select::after{
  color:#5c7080;
  pointer-events:none;
  position:absolute;
  right:7px;
  top:7px; }
  .bp3-html-select .bp3-disabled.bp3-icon,
  .bp3-select .bp3-disabled.bp3-icon, .bp3-disabled.bp3-select::after{
    color:rgba(92, 112, 128, 0.6); }
.bp3-html-select,
.bp3-select{
  display:inline-block;
  letter-spacing:normal;
  position:relative;
  vertical-align:middle; }
  .bp3-html-select select::-ms-expand,
  .bp3-select select::-ms-expand{
    display:none; }
  .bp3-html-select .bp3-icon,
  .bp3-select .bp3-icon{
    color:#5c7080; }
    .bp3-html-select .bp3-icon:hover,
    .bp3-select .bp3-icon:hover{
      color:#182026; }
    .bp3-dark .bp3-html-select .bp3-icon, .bp3-dark
    .bp3-select .bp3-icon{
      color:#a7b6c2; }
      .bp3-dark .bp3-html-select .bp3-icon:hover, .bp3-dark
      .bp3-select .bp3-icon:hover{
        color:#f5f8fa; }
  .bp3-html-select.bp3-large::after,
  .bp3-html-select.bp3-large .bp3-icon,
  .bp3-select.bp3-large::after,
  .bp3-select.bp3-large .bp3-icon{
    right:12px;
    top:12px; }
  .bp3-html-select.bp3-fill,
  .bp3-html-select.bp3-fill select,
  .bp3-select.bp3-fill,
  .bp3-select.bp3-fill select{
    width:100%; }
  .bp3-dark .bp3-html-select option, .bp3-dark
  .bp3-select option{
    background-color:#30404d;
    color:#f5f8fa; }
  .bp3-dark .bp3-html-select option:disabled, .bp3-dark
  .bp3-select option:disabled{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-html-select::after, .bp3-dark
  .bp3-select::after{
    color:#a7b6c2; }

.bp3-select::after{
  font-family:"Icons16", sans-serif;
  font-size:16px;
  font-style:normal;
  font-weight:400;
  line-height:1;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  content:"???"; }
.bp3-running-text table, table.bp3-html-table{
  border-spacing:0;
  font-size:14px; }
  .bp3-running-text table th, table.bp3-html-table th,
  .bp3-running-text table td,
  table.bp3-html-table td{
    padding:11px;
    text-align:left;
    vertical-align:top; }
  .bp3-running-text table th, table.bp3-html-table th{
    color:#182026;
    font-weight:600; }
  
  .bp3-running-text table td,
  table.bp3-html-table td{
    color:#182026; }
  .bp3-running-text table tbody tr:first-child th, table.bp3-html-table tbody tr:first-child th,
  .bp3-running-text table tbody tr:first-child td,
  table.bp3-html-table tbody tr:first-child td,
  .bp3-running-text table tfoot tr:first-child th,
  table.bp3-html-table tfoot tr:first-child th,
  .bp3-running-text table tfoot tr:first-child td,
  table.bp3-html-table tfoot tr:first-child td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-running-text table th, .bp3-running-text .bp3-dark table th, .bp3-dark table.bp3-html-table th{
    color:#f5f8fa; }
  .bp3-dark .bp3-running-text table td, .bp3-running-text .bp3-dark table td, .bp3-dark table.bp3-html-table td{
    color:#f5f8fa; }
  .bp3-dark .bp3-running-text table tbody tr:first-child th, .bp3-running-text .bp3-dark table tbody tr:first-child th, .bp3-dark table.bp3-html-table tbody tr:first-child th,
  .bp3-dark .bp3-running-text table tbody tr:first-child td,
  .bp3-running-text .bp3-dark table tbody tr:first-child td,
  .bp3-dark table.bp3-html-table tbody tr:first-child td,
  .bp3-dark .bp3-running-text table tfoot tr:first-child th,
  .bp3-running-text .bp3-dark table tfoot tr:first-child th,
  .bp3-dark table.bp3-html-table tfoot tr:first-child th,
  .bp3-dark .bp3-running-text table tfoot tr:first-child td,
  .bp3-running-text .bp3-dark table tfoot tr:first-child td,
  .bp3-dark table.bp3-html-table tfoot tr:first-child td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15); }

table.bp3-html-table.bp3-html-table-condensed th,
table.bp3-html-table.bp3-html-table-condensed td, table.bp3-html-table.bp3-small th,
table.bp3-html-table.bp3-small td{
  padding-bottom:6px;
  padding-top:6px; }

table.bp3-html-table.bp3-html-table-striped tbody tr:nth-child(odd) td{
  background:rgba(191, 204, 214, 0.15); }

table.bp3-html-table.bp3-html-table-bordered th:not(:first-child){
  -webkit-box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-html-table-bordered tbody tr td,
table.bp3-html-table.bp3-html-table-bordered tfoot tr td{
  -webkit-box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15); }
  table.bp3-html-table.bp3-html-table-bordered tbody tr td:not(:first-child),
  table.bp3-html-table.bp3-html-table-bordered tfoot tr td:not(:first-child){
    -webkit-box-shadow:inset 1px 1px 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 1px 1px 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td{
  -webkit-box-shadow:none;
          box-shadow:none; }
  table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td:not(:first-child){
    -webkit-box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-interactive tbody tr:hover td{
  background-color:rgba(191, 204, 214, 0.3);
  cursor:pointer; }

table.bp3-html-table.bp3-interactive tbody tr:active td{
  background-color:rgba(191, 204, 214, 0.4); }

.bp3-dark table.bp3-html-table{ }
  .bp3-dark table.bp3-html-table.bp3-html-table-striped tbody tr:nth-child(odd) td{
    background:rgba(92, 112, 128, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered th:not(:first-child){
    -webkit-box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered tbody tr td,
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered tfoot tr td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15); }
    .bp3-dark table.bp3-html-table.bp3-html-table-bordered tbody tr td:not(:first-child),
    .bp3-dark table.bp3-html-table.bp3-html-table-bordered tfoot tr td:not(:first-child){
      -webkit-box-shadow:inset 1px 1px 0 0 rgba(255, 255, 255, 0.15);
              box-shadow:inset 1px 1px 0 0 rgba(255, 255, 255, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td{
    -webkit-box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15); }
    .bp3-dark table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td:first-child{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-dark table.bp3-html-table.bp3-interactive tbody tr:hover td{
    background-color:rgba(92, 112, 128, 0.3);
    cursor:pointer; }
  .bp3-dark table.bp3-html-table.bp3-interactive tbody tr:active td{
    background-color:rgba(92, 112, 128, 0.4); }

.bp3-key-combo{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center; }
  .bp3-key-combo > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-key-combo > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-key-combo::before,
  .bp3-key-combo > *{
    margin-right:5px; }
  .bp3-key-combo:empty::before,
  .bp3-key-combo > :last-child{
    margin-right:0; }

.bp3-hotkey-dialog{
  padding-bottom:0;
  top:40px; }
  .bp3-hotkey-dialog .bp3-dialog-body{
    margin:0;
    padding:0; }
  .bp3-hotkey-dialog .bp3-hotkey-label{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1; }

.bp3-hotkey-column{
  margin:auto;
  max-height:80vh;
  overflow-y:auto;
  padding:30px; }
  .bp3-hotkey-column .bp3-heading{
    margin-bottom:20px; }
    .bp3-hotkey-column .bp3-heading:not(:first-child){
      margin-top:40px; }

.bp3-hotkey{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:justify;
      -ms-flex-pack:justify;
          justify-content:space-between;
  margin-left:0;
  margin-right:0; }
  .bp3-hotkey:not(:last-child){
    margin-bottom:10px; }
.bp3-icon{
  display:inline-block;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  vertical-align:text-bottom; }
  .bp3-icon:not(:empty)::before{
    content:"" !important;
    content:unset !important; }
  .bp3-icon > svg{
    display:block; }
    .bp3-icon > svg:not([fill]){
      fill:currentColor; }

.bp3-icon.bp3-intent-primary, .bp3-icon-standard.bp3-intent-primary, .bp3-icon-large.bp3-intent-primary{
  color:#106ba3; }
  .bp3-dark .bp3-icon.bp3-intent-primary, .bp3-dark .bp3-icon-standard.bp3-intent-primary, .bp3-dark .bp3-icon-large.bp3-intent-primary{
    color:#48aff0; }

.bp3-icon.bp3-intent-success, .bp3-icon-standard.bp3-intent-success, .bp3-icon-large.bp3-intent-success{
  color:#0d8050; }
  .bp3-dark .bp3-icon.bp3-intent-success, .bp3-dark .bp3-icon-standard.bp3-intent-success, .bp3-dark .bp3-icon-large.bp3-intent-success{
    color:#3dcc91; }

.bp3-icon.bp3-intent-warning, .bp3-icon-standard.bp3-intent-warning, .bp3-icon-large.bp3-intent-warning{
  color:#bf7326; }
  .bp3-dark .bp3-icon.bp3-intent-warning, .bp3-dark .bp3-icon-standard.bp3-intent-warning, .bp3-dark .bp3-icon-large.bp3-intent-warning{
    color:#ffb366; }

.bp3-icon.bp3-intent-danger, .bp3-icon-standard.bp3-intent-danger, .bp3-icon-large.bp3-intent-danger{
  color:#c23030; }
  .bp3-dark .bp3-icon.bp3-intent-danger, .bp3-dark .bp3-icon-standard.bp3-intent-danger, .bp3-dark .bp3-icon-large.bp3-intent-danger{
    color:#ff7373; }

span.bp3-icon-standard{
  font-family:"Icons16", sans-serif;
  font-size:16px;
  font-style:normal;
  font-weight:400;
  line-height:1;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  display:inline-block; }

span.bp3-icon-large{
  font-family:"Icons20", sans-serif;
  font-size:20px;
  font-style:normal;
  font-weight:400;
  line-height:1;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  display:inline-block; }

span.bp3-icon:empty{
  font-family:"Icons20";
  font-size:inherit;
  font-style:normal;
  font-weight:400;
  line-height:1; }
  span.bp3-icon:empty::before{
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased; }

.bp3-icon-add::before{
  content:"???"; }

.bp3-icon-add-column-left::before{
  content:"???"; }

.bp3-icon-add-column-right::before{
  content:"???"; }

.bp3-icon-add-row-bottom::before{
  content:"???"; }

.bp3-icon-add-row-top::before{
  content:"???"; }

.bp3-icon-add-to-artifact::before{
  content:"???"; }

.bp3-icon-add-to-folder::before{
  content:"???"; }

.bp3-icon-airplane::before{
  content:"???"; }

.bp3-icon-align-center::before{
  content:"???"; }

.bp3-icon-align-justify::before{
  content:"???"; }

.bp3-icon-align-left::before{
  content:"???"; }

.bp3-icon-align-right::before{
  content:"???"; }

.bp3-icon-alignment-bottom::before{
  content:"???"; }

.bp3-icon-alignment-horizontal-center::before{
  content:"???"; }

.bp3-icon-alignment-left::before{
  content:"???"; }

.bp3-icon-alignment-right::before{
  content:"???"; }

.bp3-icon-alignment-top::before{
  content:"???"; }

.bp3-icon-alignment-vertical-center::before{
  content:"???"; }

.bp3-icon-annotation::before{
  content:"???"; }

.bp3-icon-application::before{
  content:"???"; }

.bp3-icon-applications::before{
  content:"???"; }

.bp3-icon-archive::before{
  content:"???"; }

.bp3-icon-arrow-bottom-left::before{
  content:"???"; }

.bp3-icon-arrow-bottom-right::before{
  content:"???"; }

.bp3-icon-arrow-down::before{
  content:"???"; }

.bp3-icon-arrow-left::before{
  content:"???"; }

.bp3-icon-arrow-right::before{
  content:"???"; }

.bp3-icon-arrow-top-left::before{
  content:"???"; }

.bp3-icon-arrow-top-right::before{
  content:"???"; }

.bp3-icon-arrow-up::before{
  content:"???"; }

.bp3-icon-arrows-horizontal::before{
  content:"???"; }

.bp3-icon-arrows-vertical::before{
  content:"???"; }

.bp3-icon-asterisk::before{
  content:"*"; }

.bp3-icon-automatic-updates::before{
  content:"???"; }

.bp3-icon-badge::before{
  content:"???"; }

.bp3-icon-ban-circle::before{
  content:"???"; }

.bp3-icon-bank-account::before{
  content:"???"; }

.bp3-icon-barcode::before{
  content:"???"; }

.bp3-icon-blank::before{
  content:"???"; }

.bp3-icon-blocked-person::before{
  content:"???"; }

.bp3-icon-bold::before{
  content:"???"; }

.bp3-icon-book::before{
  content:"???"; }

.bp3-icon-bookmark::before{
  content:"???"; }

.bp3-icon-box::before{
  content:"???"; }

.bp3-icon-briefcase::before{
  content:"???"; }

.bp3-icon-bring-data::before{
  content:"???"; }

.bp3-icon-build::before{
  content:"???"; }

.bp3-icon-calculator::before{
  content:"???"; }

.bp3-icon-calendar::before{
  content:"???"; }

.bp3-icon-camera::before{
  content:"???"; }

.bp3-icon-caret-down::before{
  content:"???"; }

.bp3-icon-caret-left::before{
  content:"???"; }

.bp3-icon-caret-right::before{
  content:"???"; }

.bp3-icon-caret-up::before{
  content:"???"; }

.bp3-icon-cell-tower::before{
  content:"???"; }

.bp3-icon-changes::before{
  content:"???"; }

.bp3-icon-chart::before{
  content:"???"; }

.bp3-icon-chat::before{
  content:"???"; }

.bp3-icon-chevron-backward::before{
  content:"???"; }

.bp3-icon-chevron-down::before{
  content:"???"; }

.bp3-icon-chevron-forward::before{
  content:"???"; }

.bp3-icon-chevron-left::before{
  content:"???"; }

.bp3-icon-chevron-right::before{
  content:"???"; }

.bp3-icon-chevron-up::before{
  content:"???"; }

.bp3-icon-circle::before{
  content:"???"; }

.bp3-icon-circle-arrow-down::before{
  content:"???"; }

.bp3-icon-circle-arrow-left::before{
  content:"???"; }

.bp3-icon-circle-arrow-right::before{
  content:"???"; }

.bp3-icon-circle-arrow-up::before{
  content:"???"; }

.bp3-icon-citation::before{
  content:"???"; }

.bp3-icon-clean::before{
  content:"???"; }

.bp3-icon-clipboard::before{
  content:"???"; }

.bp3-icon-cloud::before{
  content:"???"; }

.bp3-icon-cloud-download::before{
  content:"???"; }

.bp3-icon-cloud-upload::before{
  content:"???"; }

.bp3-icon-code::before{
  content:"???"; }

.bp3-icon-code-block::before{
  content:"???"; }

.bp3-icon-cog::before{
  content:"???"; }

.bp3-icon-collapse-all::before{
  content:"???"; }

.bp3-icon-column-layout::before{
  content:"???"; }

.bp3-icon-comment::before{
  content:"???"; }

.bp3-icon-comparison::before{
  content:"???"; }

.bp3-icon-compass::before{
  content:"???"; }

.bp3-icon-compressed::before{
  content:"???"; }

.bp3-icon-confirm::before{
  content:"???"; }

.bp3-icon-console::before{
  content:"???"; }

.bp3-icon-contrast::before{
  content:"???"; }

.bp3-icon-control::before{
  content:"???"; }

.bp3-icon-credit-card::before{
  content:"???"; }

.bp3-icon-cross::before{
  content:"???"; }

.bp3-icon-crown::before{
  content:"???"; }

.bp3-icon-cube::before{
  content:"???"; }

.bp3-icon-cube-add::before{
  content:"???"; }

.bp3-icon-cube-remove::before{
  content:"???"; }

.bp3-icon-curved-range-chart::before{
  content:"???"; }

.bp3-icon-cut::before{
  content:"???"; }

.bp3-icon-dashboard::before{
  content:"???"; }

.bp3-icon-data-lineage::before{
  content:"???"; }

.bp3-icon-database::before{
  content:"???"; }

.bp3-icon-delete::before{
  content:"???"; }

.bp3-icon-delta::before{
  content:"??"; }

.bp3-icon-derive-column::before{
  content:"???"; }

.bp3-icon-desktop::before{
  content:"???"; }

.bp3-icon-diagnosis::before{
  content:"???"; }

.bp3-icon-diagram-tree::before{
  content:"???"; }

.bp3-icon-direction-left::before{
  content:"???"; }

.bp3-icon-direction-right::before{
  content:"???"; }

.bp3-icon-disable::before{
  content:"???"; }

.bp3-icon-document::before{
  content:"???"; }

.bp3-icon-document-open::before{
  content:"???"; }

.bp3-icon-document-share::before{
  content:"???"; }

.bp3-icon-dollar::before{
  content:"$"; }

.bp3-icon-dot::before{
  content:"???"; }

.bp3-icon-double-caret-horizontal::before{
  content:"???"; }

.bp3-icon-double-caret-vertical::before{
  content:"???"; }

.bp3-icon-double-chevron-down::before{
  content:"???"; }

.bp3-icon-double-chevron-left::before{
  content:"???"; }

.bp3-icon-double-chevron-right::before{
  content:"???"; }

.bp3-icon-double-chevron-up::before{
  content:"???"; }

.bp3-icon-doughnut-chart::before{
  content:"???"; }

.bp3-icon-download::before{
  content:"???"; }

.bp3-icon-drag-handle-horizontal::before{
  content:"???"; }

.bp3-icon-drag-handle-vertical::before{
  content:"???"; }

.bp3-icon-draw::before{
  content:"???"; }

.bp3-icon-drive-time::before{
  content:"???"; }

.bp3-icon-duplicate::before{
  content:"???"; }

.bp3-icon-edit::before{
  content:"???"; }

.bp3-icon-eject::before{
  content:"???"; }

.bp3-icon-endorsed::before{
  content:"???"; }

.bp3-icon-envelope::before{
  content:"???"; }

.bp3-icon-equals::before{
  content:"???"; }

.bp3-icon-eraser::before{
  content:"???"; }

.bp3-icon-error::before{
  content:"???"; }

.bp3-icon-euro::before{
  content:"???"; }

.bp3-icon-exchange::before{
  content:"???"; }

.bp3-icon-exclude-row::before{
  content:"???"; }

.bp3-icon-expand-all::before{
  content:"???"; }

.bp3-icon-export::before{
  content:"???"; }

.bp3-icon-eye-off::before{
  content:"???"; }

.bp3-icon-eye-on::before{
  content:"???"; }

.bp3-icon-eye-open::before{
  content:"???"; }

.bp3-icon-fast-backward::before{
  content:"???"; }

.bp3-icon-fast-forward::before{
  content:"???"; }

.bp3-icon-feed::before{
  content:"???"; }

.bp3-icon-feed-subscribed::before{
  content:"???"; }

.bp3-icon-film::before{
  content:"???"; }

.bp3-icon-filter::before{
  content:"???"; }

.bp3-icon-filter-keep::before{
  content:"???"; }

.bp3-icon-filter-list::before{
  content:"???"; }

.bp3-icon-filter-open::before{
  content:"???"; }

.bp3-icon-filter-remove::before{
  content:"???"; }

.bp3-icon-flag::before{
  content:"???"; }

.bp3-icon-flame::before{
  content:"???"; }

.bp3-icon-flash::before{
  content:"???"; }

.bp3-icon-floppy-disk::before{
  content:"???"; }

.bp3-icon-flow-branch::before{
  content:"???"; }

.bp3-icon-flow-end::before{
  content:"???"; }

.bp3-icon-flow-linear::before{
  content:"???"; }

.bp3-icon-flow-review::before{
  content:"???"; }

.bp3-icon-flow-review-branch::before{
  content:"???"; }

.bp3-icon-flows::before{
  content:"???"; }

.bp3-icon-folder-close::before{
  content:"???"; }

.bp3-icon-folder-new::before{
  content:"???"; }

.bp3-icon-folder-open::before{
  content:"???"; }

.bp3-icon-folder-shared::before{
  content:"???"; }

.bp3-icon-folder-shared-open::before{
  content:"???"; }

.bp3-icon-follower::before{
  content:"???"; }

.bp3-icon-following::before{
  content:"???"; }

.bp3-icon-font::before{
  content:"???"; }

.bp3-icon-fork::before{
  content:"???"; }

.bp3-icon-form::before{
  content:"???"; }

.bp3-icon-full-circle::before{
  content:"???"; }

.bp3-icon-full-stacked-chart::before{
  content:"???"; }

.bp3-icon-fullscreen::before{
  content:"???"; }

.bp3-icon-function::before{
  content:"???"; }

.bp3-icon-gantt-chart::before{
  content:"???"; }

.bp3-icon-geolocation::before{
  content:"???"; }

.bp3-icon-geosearch::before{
  content:"???"; }

.bp3-icon-git-branch::before{
  content:"???"; }

.bp3-icon-git-commit::before{
  content:"???"; }

.bp3-icon-git-merge::before{
  content:"???"; }

.bp3-icon-git-new-branch::before{
  content:"???"; }

.bp3-icon-git-pull::before{
  content:"???"; }

.bp3-icon-git-push::before{
  content:"???"; }

.bp3-icon-git-repo::before{
  content:"???"; }

.bp3-icon-glass::before{
  content:"???"; }

.bp3-icon-globe::before{
  content:"???"; }

.bp3-icon-globe-network::before{
  content:"???"; }

.bp3-icon-graph::before{
  content:"???"; }

.bp3-icon-graph-remove::before{
  content:"???"; }

.bp3-icon-greater-than::before{
  content:"???"; }

.bp3-icon-greater-than-or-equal-to::before{
  content:"???"; }

.bp3-icon-grid::before{
  content:"???"; }

.bp3-icon-grid-view::before{
  content:"???"; }

.bp3-icon-group-objects::before{
  content:"???"; }

.bp3-icon-grouped-bar-chart::before{
  content:"???"; }

.bp3-icon-hand::before{
  content:"???"; }

.bp3-icon-hand-down::before{
  content:"???"; }

.bp3-icon-hand-left::before{
  content:"???"; }

.bp3-icon-hand-right::before{
  content:"???"; }

.bp3-icon-hand-up::before{
  content:"???"; }

.bp3-icon-header::before{
  content:"???"; }

.bp3-icon-header-one::before{
  content:"???"; }

.bp3-icon-header-two::before{
  content:"???"; }

.bp3-icon-headset::before{
  content:"???"; }

.bp3-icon-heart::before{
  content:"???"; }

.bp3-icon-heart-broken::before{
  content:"???"; }

.bp3-icon-heat-grid::before{
  content:"???"; }

.bp3-icon-heatmap::before{
  content:"???"; }

.bp3-icon-help::before{
  content:"?"; }

.bp3-icon-helper-management::before{
  content:"???"; }

.bp3-icon-highlight::before{
  content:"???"; }

.bp3-icon-history::before{
  content:"???"; }

.bp3-icon-home::before{
  content:"???"; }

.bp3-icon-horizontal-bar-chart::before{
  content:"???"; }

.bp3-icon-horizontal-bar-chart-asc::before{
  content:"???"; }

.bp3-icon-horizontal-bar-chart-desc::before{
  content:"???"; }

.bp3-icon-horizontal-distribution::before{
  content:"???"; }

.bp3-icon-id-number::before{
  content:"???"; }

.bp3-icon-image-rotate-left::before{
  content:"???"; }

.bp3-icon-image-rotate-right::before{
  content:"???"; }

.bp3-icon-import::before{
  content:"???"; }

.bp3-icon-inbox::before{
  content:"???"; }

.bp3-icon-inbox-filtered::before{
  content:"???"; }

.bp3-icon-inbox-geo::before{
  content:"???"; }

.bp3-icon-inbox-search::before{
  content:"???"; }

.bp3-icon-inbox-update::before{
  content:"???"; }

.bp3-icon-info-sign::before{
  content:"???"; }

.bp3-icon-inheritance::before{
  content:"???"; }

.bp3-icon-inner-join::before{
  content:"???"; }

.bp3-icon-insert::before{
  content:"???"; }

.bp3-icon-intersection::before{
  content:"???"; }

.bp3-icon-ip-address::before{
  content:"???"; }

.bp3-icon-issue::before{
  content:"???"; }

.bp3-icon-issue-closed::before{
  content:"???"; }

.bp3-icon-issue-new::before{
  content:"???"; }

.bp3-icon-italic::before{
  content:"???"; }

.bp3-icon-join-table::before{
  content:"???"; }

.bp3-icon-key::before{
  content:"???"; }

.bp3-icon-key-backspace::before{
  content:"???"; }

.bp3-icon-key-command::before{
  content:"???"; }

.bp3-icon-key-control::before{
  content:"???"; }

.bp3-icon-key-delete::before{
  content:"???"; }

.bp3-icon-key-enter::before{
  content:"???"; }

.bp3-icon-key-escape::before{
  content:"???"; }

.bp3-icon-key-option::before{
  content:"???"; }

.bp3-icon-key-shift::before{
  content:"???"; }

.bp3-icon-key-tab::before{
  content:"???"; }

.bp3-icon-known-vehicle::before{
  content:"???"; }

.bp3-icon-lab-test::before{
  content:"???"; }

.bp3-icon-label::before{
  content:"???"; }

.bp3-icon-layer::before{
  content:"???"; }

.bp3-icon-layers::before{
  content:"???"; }

.bp3-icon-layout::before{
  content:"???"; }

.bp3-icon-layout-auto::before{
  content:"???"; }

.bp3-icon-layout-balloon::before{
  content:"???"; }

.bp3-icon-layout-circle::before{
  content:"???"; }

.bp3-icon-layout-grid::before{
  content:"???"; }

.bp3-icon-layout-group-by::before{
  content:"???"; }

.bp3-icon-layout-hierarchy::before{
  content:"???"; }

.bp3-icon-layout-linear::before{
  content:"???"; }

.bp3-icon-layout-skew-grid::before{
  content:"???"; }

.bp3-icon-layout-sorted-clusters::before{
  content:"???"; }

.bp3-icon-learning::before{
  content:"???"; }

.bp3-icon-left-join::before{
  content:"???"; }

.bp3-icon-less-than::before{
  content:"???"; }

.bp3-icon-less-than-or-equal-to::before{
  content:"???"; }

.bp3-icon-lifesaver::before{
  content:"???"; }

.bp3-icon-lightbulb::before{
  content:"???"; }

.bp3-icon-link::before{
  content:"???"; }

.bp3-icon-list::before{
  content:"???"; }

.bp3-icon-list-columns::before{
  content:"???"; }

.bp3-icon-list-detail-view::before{
  content:"???"; }

.bp3-icon-locate::before{
  content:"???"; }

.bp3-icon-lock::before{
  content:"???"; }

.bp3-icon-log-in::before{
  content:"???"; }

.bp3-icon-log-out::before{
  content:"???"; }

.bp3-icon-manual::before{
  content:"???"; }

.bp3-icon-manually-entered-data::before{
  content:"???"; }

.bp3-icon-map::before{
  content:"???"; }

.bp3-icon-map-create::before{
  content:"???"; }

.bp3-icon-map-marker::before{
  content:"???"; }

.bp3-icon-maximize::before{
  content:"???"; }

.bp3-icon-media::before{
  content:"???"; }

.bp3-icon-menu::before{
  content:"???"; }

.bp3-icon-menu-closed::before{
  content:"???"; }

.bp3-icon-menu-open::before{
  content:"???"; }

.bp3-icon-merge-columns::before{
  content:"???"; }

.bp3-icon-merge-links::before{
  content:"???"; }

.bp3-icon-minimize::before{
  content:"???"; }

.bp3-icon-minus::before{
  content:"???"; }

.bp3-icon-mobile-phone::before{
  content:"???"; }

.bp3-icon-mobile-video::before{
  content:"???"; }

.bp3-icon-moon::before{
  content:"???"; }

.bp3-icon-more::before{
  content:"???"; }

.bp3-icon-mountain::before{
  content:"???"; }

.bp3-icon-move::before{
  content:"???"; }

.bp3-icon-mugshot::before{
  content:"???"; }

.bp3-icon-multi-select::before{
  content:"???"; }

.bp3-icon-music::before{
  content:"???"; }

.bp3-icon-new-drawing::before{
  content:"???"; }

.bp3-icon-new-grid-item::before{
  content:"???"; }

.bp3-icon-new-layer::before{
  content:"???"; }

.bp3-icon-new-layers::before{
  content:"???"; }

.bp3-icon-new-link::before{
  content:"???"; }

.bp3-icon-new-object::before{
  content:"???"; }

.bp3-icon-new-person::before{
  content:"???"; }

.bp3-icon-new-prescription::before{
  content:"???"; }

.bp3-icon-new-text-box::before{
  content:"???"; }

.bp3-icon-ninja::before{
  content:"???"; }

.bp3-icon-not-equal-to::before{
  content:"???"; }

.bp3-icon-notifications::before{
  content:"???"; }

.bp3-icon-notifications-updated::before{
  content:"???"; }

.bp3-icon-numbered-list::before{
  content:"???"; }

.bp3-icon-numerical::before{
  content:"???"; }

.bp3-icon-office::before{
  content:"???"; }

.bp3-icon-offline::before{
  content:"???"; }

.bp3-icon-oil-field::before{
  content:"???"; }

.bp3-icon-one-column::before{
  content:"???"; }

.bp3-icon-outdated::before{
  content:"???"; }

.bp3-icon-page-layout::before{
  content:"???"; }

.bp3-icon-panel-stats::before{
  content:"???"; }

.bp3-icon-panel-table::before{
  content:"???"; }

.bp3-icon-paperclip::before{
  content:"???"; }

.bp3-icon-paragraph::before{
  content:"???"; }

.bp3-icon-path::before{
  content:"???"; }

.bp3-icon-path-search::before{
  content:"???"; }

.bp3-icon-pause::before{
  content:"???"; }

.bp3-icon-people::before{
  content:"???"; }

.bp3-icon-percentage::before{
  content:"???"; }

.bp3-icon-person::before{
  content:"???"; }

.bp3-icon-phone::before{
  content:"???"; }

.bp3-icon-pie-chart::before{
  content:"???"; }

.bp3-icon-pin::before{
  content:"???"; }

.bp3-icon-pivot::before{
  content:"???"; }

.bp3-icon-pivot-table::before{
  content:"???"; }

.bp3-icon-play::before{
  content:"???"; }

.bp3-icon-plus::before{
  content:"+"; }

.bp3-icon-polygon-filter::before{
  content:"???"; }

.bp3-icon-power::before{
  content:"???"; }

.bp3-icon-predictive-analysis::before{
  content:"???"; }

.bp3-icon-prescription::before{
  content:"???"; }

.bp3-icon-presentation::before{
  content:"???"; }

.bp3-icon-print::before{
  content:"???"; }

.bp3-icon-projects::before{
  content:"???"; }

.bp3-icon-properties::before{
  content:"???"; }

.bp3-icon-property::before{
  content:"???"; }

.bp3-icon-publish-function::before{
  content:"???"; }

.bp3-icon-pulse::before{
  content:"???"; }

.bp3-icon-random::before{
  content:"???"; }

.bp3-icon-record::before{
  content:"???"; }

.bp3-icon-redo::before{
  content:"???"; }

.bp3-icon-refresh::before{
  content:"???"; }

.bp3-icon-regression-chart::before{
  content:"???"; }

.bp3-icon-remove::before{
  content:"???"; }

.bp3-icon-remove-column::before{
  content:"???"; }

.bp3-icon-remove-column-left::before{
  content:"???"; }

.bp3-icon-remove-column-right::before{
  content:"???"; }

.bp3-icon-remove-row-bottom::before{
  content:"???"; }

.bp3-icon-remove-row-top::before{
  content:"???"; }

.bp3-icon-repeat::before{
  content:"???"; }

.bp3-icon-reset::before{
  content:"???"; }

.bp3-icon-resolve::before{
  content:"???"; }

.bp3-icon-rig::before{
  content:"???"; }

.bp3-icon-right-join::before{
  content:"???"; }

.bp3-icon-ring::before{
  content:"???"; }

.bp3-icon-rotate-document::before{
  content:"???"; }

.bp3-icon-rotate-page::before{
  content:"???"; }

.bp3-icon-satellite::before{
  content:"???"; }

.bp3-icon-saved::before{
  content:"???"; }

.bp3-icon-scatter-plot::before{
  content:"???"; }

.bp3-icon-search::before{
  content:"???"; }

.bp3-icon-search-around::before{
  content:"???"; }

.bp3-icon-search-template::before{
  content:"???"; }

.bp3-icon-search-text::before{
  content:"???"; }

.bp3-icon-segmented-control::before{
  content:"???"; }

.bp3-icon-select::before{
  content:"???"; }

.bp3-icon-selection::before{
  content:"???"; }

.bp3-icon-send-to::before{
  content:"???"; }

.bp3-icon-send-to-graph::before{
  content:"???"; }

.bp3-icon-send-to-map::before{
  content:"???"; }

.bp3-icon-series-add::before{
  content:"???"; }

.bp3-icon-series-configuration::before{
  content:"???"; }

.bp3-icon-series-derived::before{
  content:"???"; }

.bp3-icon-series-filtered::before{
  content:"???"; }

.bp3-icon-series-search::before{
  content:"???"; }

.bp3-icon-settings::before{
  content:"???"; }

.bp3-icon-share::before{
  content:"???"; }

.bp3-icon-shield::before{
  content:"???"; }

.bp3-icon-shop::before{
  content:"???"; }

.bp3-icon-shopping-cart::before{
  content:"???"; }

.bp3-icon-signal-search::before{
  content:"???"; }

.bp3-icon-sim-card::before{
  content:"???"; }

.bp3-icon-slash::before{
  content:"???"; }

.bp3-icon-small-cross::before{
  content:"???"; }

.bp3-icon-small-minus::before{
  content:"???"; }

.bp3-icon-small-plus::before{
  content:"???"; }

.bp3-icon-small-tick::before{
  content:"???"; }

.bp3-icon-snowflake::before{
  content:"???"; }

.bp3-icon-social-media::before{
  content:"???"; }

.bp3-icon-sort::before{
  content:"???"; }

.bp3-icon-sort-alphabetical::before{
  content:"???"; }

.bp3-icon-sort-alphabetical-desc::before{
  content:"???"; }

.bp3-icon-sort-asc::before{
  content:"???"; }

.bp3-icon-sort-desc::before{
  content:"???"; }

.bp3-icon-sort-numerical::before{
  content:"???"; }

.bp3-icon-sort-numerical-desc::before{
  content:"???"; }

.bp3-icon-split-columns::before{
  content:"???"; }

.bp3-icon-square::before{
  content:"???"; }

.bp3-icon-stacked-chart::before{
  content:"???"; }

.bp3-icon-star::before{
  content:"???"; }

.bp3-icon-star-empty::before{
  content:"???"; }

.bp3-icon-step-backward::before{
  content:"???"; }

.bp3-icon-step-chart::before{
  content:"???"; }

.bp3-icon-step-forward::before{
  content:"???"; }

.bp3-icon-stop::before{
  content:"???"; }

.bp3-icon-stopwatch::before{
  content:"???"; }

.bp3-icon-strikethrough::before{
  content:"???"; }

.bp3-icon-style::before{
  content:"???"; }

.bp3-icon-swap-horizontal::before{
  content:"???"; }

.bp3-icon-swap-vertical::before{
  content:"???"; }

.bp3-icon-symbol-circle::before{
  content:"???"; }

.bp3-icon-symbol-cross::before{
  content:"???"; }

.bp3-icon-symbol-diamond::before{
  content:"???"; }

.bp3-icon-symbol-square::before{
  content:"???"; }

.bp3-icon-symbol-triangle-down::before{
  content:"???"; }

.bp3-icon-symbol-triangle-up::before{
  content:"???"; }

.bp3-icon-tag::before{
  content:"???"; }

.bp3-icon-take-action::before{
  content:"???"; }

.bp3-icon-taxi::before{
  content:"???"; }

.bp3-icon-text-highlight::before{
  content:"???"; }

.bp3-icon-th::before{
  content:"???"; }

.bp3-icon-th-derived::before{
  content:"???"; }

.bp3-icon-th-disconnect::before{
  content:"???"; }

.bp3-icon-th-filtered::before{
  content:"???"; }

.bp3-icon-th-list::before{
  content:"???"; }

.bp3-icon-thumbs-down::before{
  content:"???"; }

.bp3-icon-thumbs-up::before{
  content:"???"; }

.bp3-icon-tick::before{
  content:"???"; }

.bp3-icon-tick-circle::before{
  content:"???"; }

.bp3-icon-time::before{
  content:"???"; }

.bp3-icon-timeline-area-chart::before{
  content:"???"; }

.bp3-icon-timeline-bar-chart::before{
  content:"???"; }

.bp3-icon-timeline-events::before{
  content:"???"; }

.bp3-icon-timeline-line-chart::before{
  content:"???"; }

.bp3-icon-tint::before{
  content:"???"; }

.bp3-icon-torch::before{
  content:"???"; }

.bp3-icon-tractor::before{
  content:"???"; }

.bp3-icon-train::before{
  content:"???"; }

.bp3-icon-translate::before{
  content:"???"; }

.bp3-icon-trash::before{
  content:"???"; }

.bp3-icon-tree::before{
  content:"???"; }

.bp3-icon-trending-down::before{
  content:"???"; }

.bp3-icon-trending-up::before{
  content:"???"; }

.bp3-icon-truck::before{
  content:"???"; }

.bp3-icon-two-columns::before{
  content:"???"; }

.bp3-icon-unarchive::before{
  content:"???"; }

.bp3-icon-underline::before{
  content:"???"; }

.bp3-icon-undo::before{
  content:"???"; }

.bp3-icon-ungroup-objects::before{
  content:"???"; }

.bp3-icon-unknown-vehicle::before{
  content:"???"; }

.bp3-icon-unlock::before{
  content:"???"; }

.bp3-icon-unpin::before{
  content:"???"; }

.bp3-icon-unresolve::before{
  content:"???"; }

.bp3-icon-updated::before{
  content:"???"; }

.bp3-icon-upload::before{
  content:"???"; }

.bp3-icon-user::before{
  content:"???"; }

.bp3-icon-variable::before{
  content:"???"; }

.bp3-icon-vertical-bar-chart-asc::before{
  content:"???"; }

.bp3-icon-vertical-bar-chart-desc::before{
  content:"???"; }

.bp3-icon-vertical-distribution::before{
  content:"???"; }

.bp3-icon-video::before{
  content:"???"; }

.bp3-icon-volume-down::before{
  content:"???"; }

.bp3-icon-volume-off::before{
  content:"???"; }

.bp3-icon-volume-up::before{
  content:"???"; }

.bp3-icon-walk::before{
  content:"???"; }

.bp3-icon-warning-sign::before{
  content:"???"; }

.bp3-icon-waterfall-chart::before{
  content:"???"; }

.bp3-icon-widget::before{
  content:"???"; }

.bp3-icon-widget-button::before{
  content:"???"; }

.bp3-icon-widget-footer::before{
  content:"???"; }

.bp3-icon-widget-header::before{
  content:"???"; }

.bp3-icon-wrench::before{
  content:"???"; }

.bp3-icon-zoom-in::before{
  content:"???"; }

.bp3-icon-zoom-out::before{
  content:"???"; }

.bp3-icon-zoom-to-fit::before{
  content:"???"; }
.bp3-submenu > .bp3-popover-wrapper{
  display:block; }

.bp3-submenu .bp3-popover-target{
  display:block; }
  .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{ }

.bp3-submenu.bp3-popover{
  -webkit-box-shadow:none;
          box-shadow:none;
  padding:0 5px; }
  .bp3-submenu.bp3-popover > .bp3-popover-content{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-submenu.bp3-popover, .bp3-submenu.bp3-popover.bp3-dark{
    -webkit-box-shadow:none;
            box-shadow:none; }
    .bp3-dark .bp3-submenu.bp3-popover > .bp3-popover-content, .bp3-submenu.bp3-popover.bp3-dark > .bp3-popover-content{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
.bp3-menu{
  background:#ffffff;
  border-radius:3px;
  color:#182026;
  list-style:none;
  margin:0;
  min-width:180px;
  padding:5px;
  text-align:left; }

.bp3-menu-divider{
  border-top:1px solid rgba(16, 22, 26, 0.15);
  display:block;
  margin:5px; }
  .bp3-dark .bp3-menu-divider{
    border-top-color:rgba(255, 255, 255, 0.15); }

.bp3-menu-item{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  border-radius:2px;
  color:inherit;
  line-height:20px;
  padding:5px 7px;
  text-decoration:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-menu-item > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-menu-item > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-menu-item::before,
  .bp3-menu-item > *{
    margin-right:7px; }
  .bp3-menu-item:empty::before,
  .bp3-menu-item > :last-child{
    margin-right:0; }
  .bp3-menu-item > .bp3-fill{
    word-break:break-word; }
  .bp3-menu-item:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
    background-color:rgba(167, 182, 194, 0.3);
    cursor:pointer;
    text-decoration:none; }
  .bp3-menu-item.bp3-disabled{
    background-color:inherit;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
  .bp3-dark .bp3-menu-item{
    color:inherit; }
    .bp3-dark .bp3-menu-item:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
      background-color:rgba(138, 155, 168, 0.15);
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-disabled{
      background-color:inherit;
      color:rgba(167, 182, 194, 0.6); }
  .bp3-menu-item.bp3-intent-primary{
    color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-primary::before, .bp3-menu-item.bp3-intent-primary::after,
    .bp3-menu-item.bp3-intent-primary .bp3-menu-item-label{
      color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-menu-item.bp3-intent-primary.bp3-active{
      background-color:#137cbd; }
    .bp3-menu-item.bp3-intent-primary:active{
      background-color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-menu-item.bp3-intent-primary:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-menu-item.bp3-intent-primary:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-primary:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-primary:active, .bp3-menu-item.bp3-intent-primary:active::before, .bp3-menu-item.bp3-intent-primary:active::after,
    .bp3-menu-item.bp3-intent-primary:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-primary.bp3-active, .bp3-menu-item.bp3-intent-primary.bp3-active::before, .bp3-menu-item.bp3-intent-primary.bp3-active::after,
    .bp3-menu-item.bp3-intent-primary.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-success{
    color:#0d8050; }
    .bp3-menu-item.bp3-intent-success .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-success::before, .bp3-menu-item.bp3-intent-success::after,
    .bp3-menu-item.bp3-intent-success .bp3-menu-item-label{
      color:#0d8050; }
    .bp3-menu-item.bp3-intent-success:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-menu-item.bp3-intent-success.bp3-active{
      background-color:#0f9960; }
    .bp3-menu-item.bp3-intent-success:active{
      background-color:#0d8050; }
    .bp3-menu-item.bp3-intent-success:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-menu-item.bp3-intent-success:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-menu-item.bp3-intent-success:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-success:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-success:active, .bp3-menu-item.bp3-intent-success:active::before, .bp3-menu-item.bp3-intent-success:active::after,
    .bp3-menu-item.bp3-intent-success:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-success.bp3-active, .bp3-menu-item.bp3-intent-success.bp3-active::before, .bp3-menu-item.bp3-intent-success.bp3-active::after,
    .bp3-menu-item.bp3-intent-success.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-warning{
    color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-warning::before, .bp3-menu-item.bp3-intent-warning::after,
    .bp3-menu-item.bp3-intent-warning .bp3-menu-item-label{
      color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-menu-item.bp3-intent-warning.bp3-active{
      background-color:#d9822b; }
    .bp3-menu-item.bp3-intent-warning:active{
      background-color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-menu-item.bp3-intent-warning:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-menu-item.bp3-intent-warning:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-warning:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-warning:active, .bp3-menu-item.bp3-intent-warning:active::before, .bp3-menu-item.bp3-intent-warning:active::after,
    .bp3-menu-item.bp3-intent-warning:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-warning.bp3-active, .bp3-menu-item.bp3-intent-warning.bp3-active::before, .bp3-menu-item.bp3-intent-warning.bp3-active::after,
    .bp3-menu-item.bp3-intent-warning.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-danger{
    color:#c23030; }
    .bp3-menu-item.bp3-intent-danger .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-danger::before, .bp3-menu-item.bp3-intent-danger::after,
    .bp3-menu-item.bp3-intent-danger .bp3-menu-item-label{
      color:#c23030; }
    .bp3-menu-item.bp3-intent-danger:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-menu-item.bp3-intent-danger.bp3-active{
      background-color:#db3737; }
    .bp3-menu-item.bp3-intent-danger:active{
      background-color:#c23030; }
    .bp3-menu-item.bp3-intent-danger:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-menu-item.bp3-intent-danger:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-menu-item.bp3-intent-danger:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-danger:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-danger:active, .bp3-menu-item.bp3-intent-danger:active::before, .bp3-menu-item.bp3-intent-danger:active::after,
    .bp3-menu-item.bp3-intent-danger:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-danger.bp3-active, .bp3-menu-item.bp3-intent-danger.bp3-active::before, .bp3-menu-item.bp3-intent-danger.bp3-active::after,
    .bp3-menu-item.bp3-intent-danger.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item::before{
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-style:normal;
    font-weight:400;
    line-height:1;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    margin-right:7px; }
  .bp3-menu-item::before,
  .bp3-menu-item > .bp3-icon{
    color:#5c7080;
    margin-top:2px; }
  .bp3-menu-item .bp3-menu-item-label{
    color:#5c7080; }
  .bp3-menu-item:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
    color:inherit; }
  .bp3-menu-item.bp3-active, .bp3-menu-item:active{
    background-color:rgba(115, 134, 148, 0.3); }
  .bp3-menu-item.bp3-disabled{
    background-color:inherit !important;
    color:rgba(92, 112, 128, 0.6) !important;
    cursor:not-allowed !important;
    outline:none !important; }
    .bp3-menu-item.bp3-disabled::before,
    .bp3-menu-item.bp3-disabled > .bp3-icon,
    .bp3-menu-item.bp3-disabled .bp3-menu-item-label{
      color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-large .bp3-menu-item{
    font-size:16px;
    line-height:22px;
    padding:9px 7px; }
    .bp3-large .bp3-menu-item .bp3-icon{
      margin-top:3px; }
    .bp3-large .bp3-menu-item::before{
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-style:normal;
      font-weight:400;
      line-height:1;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased;
      margin-right:10px;
      margin-top:1px; }

button.bp3-menu-item{
  background:none;
  border:none;
  text-align:left;
  width:100%; }
.bp3-menu-header{
  border-top:1px solid rgba(16, 22, 26, 0.15);
  display:block;
  margin:5px;
  cursor:default;
  padding-left:2px; }
  .bp3-dark .bp3-menu-header{
    border-top-color:rgba(255, 255, 255, 0.15); }
  .bp3-menu-header:first-of-type{
    border-top:none; }
  .bp3-menu-header > h6{
    color:#182026;
    font-weight:600;
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    line-height:17px;
    margin:0;
    padding:10px 7px 0 1px; }
    .bp3-dark .bp3-menu-header > h6{
      color:#f5f8fa; }
  .bp3-menu-header:first-of-type > h6{
    padding-top:0; }
  .bp3-large .bp3-menu-header > h6{
    font-size:18px;
    padding-bottom:5px;
    padding-top:15px; }
  .bp3-large .bp3-menu-header:first-of-type > h6{
    padding-top:0; }

.bp3-dark .bp3-menu{
  background:#30404d;
  color:#f5f8fa; }

.bp3-dark .bp3-menu-item{ }
  .bp3-dark .bp3-menu-item.bp3-intent-primary{
    color:#48aff0; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary::before, .bp3-dark .bp3-menu-item.bp3-intent-primary::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary .bp3-menu-item-label{
      color:#48aff0; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active{
      background-color:#137cbd; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary:active{
      background-color:#106ba3; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-primary:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-primary:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-primary:active, .bp3-dark .bp3-menu-item.bp3-intent-primary:active::before, .bp3-dark .bp3-menu-item.bp3-intent-primary:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item.bp3-intent-success{
    color:#3dcc91; }
    .bp3-dark .bp3-menu-item.bp3-intent-success .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-success::before, .bp3-dark .bp3-menu-item.bp3-intent-success::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success .bp3-menu-item-label{
      color:#3dcc91; }
    .bp3-dark .bp3-menu-item.bp3-intent-success:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active{
      background-color:#0f9960; }
    .bp3-dark .bp3-menu-item.bp3-intent-success:active{
      background-color:#0d8050; }
    .bp3-dark .bp3-menu-item.bp3-intent-success:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-success:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-success:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-success:active, .bp3-dark .bp3-menu-item.bp3-intent-success:active::before, .bp3-dark .bp3-menu-item.bp3-intent-success:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item.bp3-intent-warning{
    color:#ffb366; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning::before, .bp3-dark .bp3-menu-item.bp3-intent-warning::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning .bp3-menu-item-label{
      color:#ffb366; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active{
      background-color:#d9822b; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning:active{
      background-color:#bf7326; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-warning:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-warning:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-warning:active, .bp3-dark .bp3-menu-item.bp3-intent-warning:active::before, .bp3-dark .bp3-menu-item.bp3-intent-warning:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item.bp3-intent-danger{
    color:#ff7373; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger::before, .bp3-dark .bp3-menu-item.bp3-intent-danger::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger .bp3-menu-item-label{
      color:#ff7373; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active{
      background-color:#db3737; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger:active{
      background-color:#c23030; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-danger:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-danger:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-danger:active, .bp3-dark .bp3-menu-item.bp3-intent-danger:active::before, .bp3-dark .bp3-menu-item.bp3-intent-danger:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item::before,
  .bp3-dark .bp3-menu-item > .bp3-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-menu-item .bp3-menu-item-label{
    color:#a7b6c2; }
  .bp3-dark .bp3-menu-item.bp3-active, .bp3-dark .bp3-menu-item:active{
    background-color:rgba(138, 155, 168, 0.3); }
  .bp3-dark .bp3-menu-item.bp3-disabled{
    color:rgba(167, 182, 194, 0.6) !important; }
    .bp3-dark .bp3-menu-item.bp3-disabled::before,
    .bp3-dark .bp3-menu-item.bp3-disabled > .bp3-icon,
    .bp3-dark .bp3-menu-item.bp3-disabled .bp3-menu-item-label{
      color:rgba(167, 182, 194, 0.6) !important; }

.bp3-dark .bp3-menu-divider,
.bp3-dark .bp3-menu-header{
  border-color:rgba(255, 255, 255, 0.15); }

.bp3-dark .bp3-menu-header > h6{
  color:#f5f8fa; }

.bp3-label .bp3-menu{
  margin-top:5px; }
.bp3-navbar{
  background-color:#ffffff;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  height:50px;
  padding:0 15px;
  position:relative;
  width:100%;
  z-index:10; }
  .bp3-navbar.bp3-dark,
  .bp3-dark .bp3-navbar{
    background-color:#394b59; }
  .bp3-navbar.bp3-dark{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-navbar{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-navbar.bp3-fixed-top{
    left:0;
    position:fixed;
    right:0;
    top:0; }

.bp3-navbar-heading{
  font-size:16px;
  margin-right:15px; }

.bp3-navbar-group{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  height:50px; }
  .bp3-navbar-group.bp3-align-left{
    float:left; }
  .bp3-navbar-group.bp3-align-right{
    float:right; }

.bp3-navbar-divider{
  border-left:1px solid rgba(16, 22, 26, 0.15);
  height:20px;
  margin:0 10px; }
  .bp3-dark .bp3-navbar-divider{
    border-left-color:rgba(255, 255, 255, 0.15); }
.bp3-non-ideal-state{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  height:100%;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  text-align:center;
  width:100%; }
  .bp3-non-ideal-state > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-non-ideal-state > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-non-ideal-state::before,
  .bp3-non-ideal-state > *{
    margin-bottom:20px; }
  .bp3-non-ideal-state:empty::before,
  .bp3-non-ideal-state > :last-child{
    margin-bottom:0; }
  .bp3-non-ideal-state > *{
    max-width:400px; }

.bp3-non-ideal-state-visual{
  color:rgba(92, 112, 128, 0.6);
  font-size:60px; }
  .bp3-dark .bp3-non-ideal-state-visual{
    color:rgba(167, 182, 194, 0.6); }

.bp3-overflow-list{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-wrap:nowrap;
      flex-wrap:nowrap;
  min-width:0; }

.bp3-overflow-list-spacer{
  -ms-flex-negative:1;
      flex-shrink:1;
  width:1px; }

body.bp3-overlay-open{
  overflow:hidden; }

.bp3-overlay{
  bottom:0;
  left:0;
  position:static;
  right:0;
  top:0;
  z-index:20; }
  .bp3-overlay:not(.bp3-overlay-open){
    pointer-events:none; }
  .bp3-overlay.bp3-overlay-container{
    overflow:hidden;
    position:fixed; }
    .bp3-overlay.bp3-overlay-container.bp3-overlay-inline{
      position:absolute; }
  .bp3-overlay.bp3-overlay-scroll-container{
    overflow:auto;
    position:fixed; }
    .bp3-overlay.bp3-overlay-scroll-container.bp3-overlay-inline{
      position:absolute; }
  .bp3-overlay.bp3-overlay-inline{
    display:inline;
    overflow:visible; }

.bp3-overlay-content{
  position:fixed;
  z-index:20; }
  .bp3-overlay-inline .bp3-overlay-content,
  .bp3-overlay-scroll-container .bp3-overlay-content{
    position:absolute; }

.bp3-overlay-backdrop{
  bottom:0;
  left:0;
  position:fixed;
  right:0;
  top:0;
  opacity:1;
  background-color:rgba(16, 22, 26, 0.7);
  overflow:auto;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none;
  z-index:20; }
  .bp3-overlay-backdrop.bp3-overlay-enter, .bp3-overlay-backdrop.bp3-overlay-appear{
    opacity:0; }
  .bp3-overlay-backdrop.bp3-overlay-enter-active, .bp3-overlay-backdrop.bp3-overlay-appear-active{
    opacity:1;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-overlay-backdrop.bp3-overlay-exit{
    opacity:1; }
  .bp3-overlay-backdrop.bp3-overlay-exit-active{
    opacity:0;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-overlay-backdrop:focus{
    outline:none; }
  .bp3-overlay-inline .bp3-overlay-backdrop{
    position:absolute; }
.bp3-panel-stack{
  overflow:hidden;
  position:relative; }

.bp3-panel-stack-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-shadow:0 1px rgba(16, 22, 26, 0.15);
          box-shadow:0 1px rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-negative:0;
      flex-shrink:0;
  height:30px;
  z-index:1; }
  .bp3-dark .bp3-panel-stack-header{
    -webkit-box-shadow:0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 1px rgba(255, 255, 255, 0.15); }
  .bp3-panel-stack-header > span{
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1;
            flex:1; }
  .bp3-panel-stack-header .bp3-heading{
    margin:0 5px; }

.bp3-button.bp3-panel-stack-header-back{
  margin-left:5px;
  padding-left:0;
  white-space:nowrap; }
  .bp3-button.bp3-panel-stack-header-back .bp3-icon{
    margin:0 2px; }

.bp3-panel-stack-view{
  bottom:0;
  left:0;
  position:absolute;
  right:0;
  top:0;
  background-color:#ffffff;
  border-right:1px solid rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin-right:-1px;
  overflow-y:auto;
  z-index:1; }
  .bp3-dark .bp3-panel-stack-view{
    background-color:#30404d; }
  .bp3-panel-stack-view:nth-last-child(n + 4){
    display:none; }

.bp3-panel-stack-push .bp3-panel-stack-enter, .bp3-panel-stack-push .bp3-panel-stack-appear{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0; }

.bp3-panel-stack-push .bp3-panel-stack-enter-active, .bp3-panel-stack-push .bp3-panel-stack-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack-push .bp3-panel-stack-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack-push .bp3-panel-stack-exit-active{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack-pop .bp3-panel-stack-enter, .bp3-panel-stack-pop .bp3-panel-stack-appear{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0; }

.bp3-panel-stack-pop .bp3-panel-stack-enter-active, .bp3-panel-stack-pop .bp3-panel-stack-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack-pop .bp3-panel-stack-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack-pop .bp3-panel-stack-exit-active{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }
.bp3-panel-stack2{
  overflow:hidden;
  position:relative; }

.bp3-panel-stack2-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-shadow:0 1px rgba(16, 22, 26, 0.15);
          box-shadow:0 1px rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-negative:0;
      flex-shrink:0;
  height:30px;
  z-index:1; }
  .bp3-dark .bp3-panel-stack2-header{
    -webkit-box-shadow:0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 1px rgba(255, 255, 255, 0.15); }
  .bp3-panel-stack2-header > span{
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1;
            flex:1; }
  .bp3-panel-stack2-header .bp3-heading{
    margin:0 5px; }

.bp3-button.bp3-panel-stack2-header-back{
  margin-left:5px;
  padding-left:0;
  white-space:nowrap; }
  .bp3-button.bp3-panel-stack2-header-back .bp3-icon{
    margin:0 2px; }

.bp3-panel-stack2-view{
  bottom:0;
  left:0;
  position:absolute;
  right:0;
  top:0;
  background-color:#ffffff;
  border-right:1px solid rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin-right:-1px;
  overflow-y:auto;
  z-index:1; }
  .bp3-dark .bp3-panel-stack2-view{
    background-color:#30404d; }
  .bp3-panel-stack2-view:nth-last-child(n + 4){
    display:none; }

.bp3-panel-stack2-push .bp3-panel-stack2-enter, .bp3-panel-stack2-push .bp3-panel-stack2-appear{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0; }

.bp3-panel-stack2-push .bp3-panel-stack2-enter-active, .bp3-panel-stack2-push .bp3-panel-stack2-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack2-push .bp3-panel-stack2-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack2-push .bp3-panel-stack2-exit-active{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack2-pop .bp3-panel-stack2-enter, .bp3-panel-stack2-pop .bp3-panel-stack2-appear{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0; }

.bp3-panel-stack2-pop .bp3-panel-stack2-enter-active, .bp3-panel-stack2-pop .bp3-panel-stack2-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack2-pop .bp3-panel-stack2-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack2-pop .bp3-panel-stack2-exit-active{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }
.bp3-popover{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  -webkit-transform:scale(1);
          transform:scale(1);
  border-radius:3px;
  display:inline-block;
  z-index:20; }
  .bp3-popover .bp3-popover-arrow{
    height:30px;
    position:absolute;
    width:30px; }
    .bp3-popover .bp3-popover-arrow::before{
      height:20px;
      margin:5px;
      width:20px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover{
    margin-bottom:17px;
    margin-top:-17px; }
    .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow{
      bottom:-11px; }
      .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(-90deg);
                transform:rotate(-90deg); }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover{
    margin-left:17px; }
    .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow{
      left:-11px; }
      .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(0);
                transform:rotate(0); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover{
    margin-top:17px; }
    .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow{
      top:-11px; }
      .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(90deg);
                transform:rotate(90deg); }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover{
    margin-left:-17px;
    margin-right:17px; }
    .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow{
      right:-11px; }
      .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(180deg);
                transform:rotate(180deg); }
  .bp3-tether-element-attached-middle > .bp3-popover > .bp3-popover-arrow{
    top:50%;
    -webkit-transform:translateY(-50%);
            transform:translateY(-50%); }
  .bp3-tether-element-attached-center > .bp3-popover > .bp3-popover-arrow{
    right:50%;
    -webkit-transform:translateX(50%);
            transform:translateX(50%); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow{
    top:-0.3934px; }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow{
    right:-0.3934px; }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow{
    left:-0.3934px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow{
    bottom:-0.3934px; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:top left;
            transform-origin:top left; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:top center;
            transform-origin:top center; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:top right;
            transform-origin:top right; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:center left;
            transform-origin:center left; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:center center;
            transform-origin:center center; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:center right;
            transform-origin:center right; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:bottom left;
            transform-origin:bottom left; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:bottom center;
            transform-origin:bottom center; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:bottom right;
            transform-origin:bottom right; }
  .bp3-popover .bp3-popover-content{
    background:#ffffff;
    color:inherit; }
  .bp3-popover .bp3-popover-arrow::before{
    -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2);
            box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2); }
  .bp3-popover .bp3-popover-arrow-border{
    fill:#10161a;
    fill-opacity:0.1; }
  .bp3-popover .bp3-popover-arrow-fill{
    fill:#ffffff; }
  .bp3-popover-enter > .bp3-popover, .bp3-popover-appear > .bp3-popover{
    -webkit-transform:scale(0.3);
            transform:scale(0.3); }
  .bp3-popover-enter-active > .bp3-popover, .bp3-popover-appear-active > .bp3-popover{
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-popover-exit > .bp3-popover{
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-popover-exit-active > .bp3-popover{
    -webkit-transform:scale(0.3);
            transform:scale(0.3);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-popover .bp3-popover-content{
    border-radius:3px;
    position:relative; }
  .bp3-popover.bp3-popover-content-sizing .bp3-popover-content{
    max-width:350px;
    padding:20px; }
  .bp3-popover-target + .bp3-overlay .bp3-popover.bp3-popover-content-sizing{
    width:350px; }
  .bp3-popover.bp3-minimal{
    margin:0 !important; }
    .bp3-popover.bp3-minimal .bp3-popover-arrow{
      display:none; }
    .bp3-popover.bp3-minimal.bp3-popover{
      -webkit-transform:scale(1);
              transform:scale(1); }
      .bp3-popover-enter > .bp3-popover.bp3-minimal.bp3-popover, .bp3-popover-appear > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1); }
      .bp3-popover-enter-active > .bp3-popover.bp3-minimal.bp3-popover, .bp3-popover-appear-active > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1);
        -webkit-transition-delay:0;
                transition-delay:0;
        -webkit-transition-duration:100ms;
                transition-duration:100ms;
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform, -webkit-transform;
        -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
                transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
      .bp3-popover-exit > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1); }
      .bp3-popover-exit-active > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1);
        -webkit-transition-delay:0;
                transition-delay:0;
        -webkit-transition-duration:100ms;
                transition-duration:100ms;
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform, -webkit-transform;
        -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
                transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-popover.bp3-dark,
  .bp3-dark .bp3-popover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-popover.bp3-dark .bp3-popover-content,
    .bp3-dark .bp3-popover .bp3-popover-content{
      background:#30404d;
      color:inherit; }
    .bp3-popover.bp3-dark .bp3-popover-arrow::before,
    .bp3-dark .bp3-popover .bp3-popover-arrow::before{
      -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4);
              box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4); }
    .bp3-popover.bp3-dark .bp3-popover-arrow-border,
    .bp3-dark .bp3-popover .bp3-popover-arrow-border{
      fill:#10161a;
      fill-opacity:0.2; }
    .bp3-popover.bp3-dark .bp3-popover-arrow-fill,
    .bp3-dark .bp3-popover .bp3-popover-arrow-fill{
      fill:#30404d; }

.bp3-popover-arrow::before{
  border-radius:2px;
  content:"";
  display:block;
  position:absolute;
  -webkit-transform:rotate(45deg);
          transform:rotate(45deg); }

.bp3-tether-pinned .bp3-popover-arrow{
  display:none; }

.bp3-popover-backdrop{
  background:rgba(255, 255, 255, 0); }

.bp3-transition-container{
  opacity:1;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  z-index:20; }
  .bp3-transition-container.bp3-popover-enter, .bp3-transition-container.bp3-popover-appear{
    opacity:0; }
  .bp3-transition-container.bp3-popover-enter-active, .bp3-transition-container.bp3-popover-appear-active{
    opacity:1;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-transition-container.bp3-popover-exit{
    opacity:1; }
  .bp3-transition-container.bp3-popover-exit-active{
    opacity:0;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-transition-container:focus{
    outline:none; }
  .bp3-transition-container.bp3-popover-leave .bp3-popover-content{
    pointer-events:none; }
  .bp3-transition-container[data-x-out-of-boundaries]{
    display:none; }

span.bp3-popover-target{
  display:inline-block; }

.bp3-popover-wrapper.bp3-fill{
  width:100%; }

.bp3-portal{
  left:0;
  position:absolute;
  right:0;
  top:0; }
@-webkit-keyframes linear-progress-bar-stripes{
  from{
    background-position:0 0; }
  to{
    background-position:30px 0; } }
@keyframes linear-progress-bar-stripes{
  from{
    background-position:0 0; }
  to{
    background-position:30px 0; } }

.bp3-progress-bar{
  background:rgba(92, 112, 128, 0.2);
  border-radius:40px;
  display:block;
  height:8px;
  overflow:hidden;
  position:relative;
  width:100%; }
  .bp3-progress-bar .bp3-progress-meter{
    background:linear-gradient(-45deg, rgba(255, 255, 255, 0.2) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.2) 50%, rgba(255, 255, 255, 0.2) 75%, transparent 75%);
    background-color:rgba(92, 112, 128, 0.8);
    background-size:30px 30px;
    border-radius:40px;
    height:100%;
    position:absolute;
    -webkit-transition:width 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:width 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    width:100%; }
  .bp3-progress-bar:not(.bp3-no-animation):not(.bp3-no-stripes) .bp3-progress-meter{
    animation:linear-progress-bar-stripes 300ms linear infinite reverse; }
  .bp3-progress-bar.bp3-no-stripes .bp3-progress-meter{
    background-image:none; }

.bp3-dark .bp3-progress-bar{
  background:rgba(16, 22, 26, 0.5); }
  .bp3-dark .bp3-progress-bar .bp3-progress-meter{
    background-color:#8a9ba8; }

.bp3-progress-bar.bp3-intent-primary .bp3-progress-meter{
  background-color:#137cbd; }

.bp3-progress-bar.bp3-intent-success .bp3-progress-meter{
  background-color:#0f9960; }

.bp3-progress-bar.bp3-intent-warning .bp3-progress-meter{
  background-color:#d9822b; }

.bp3-progress-bar.bp3-intent-danger .bp3-progress-meter{
  background-color:#db3737; }
@-webkit-keyframes skeleton-glow{
  from{
    background:rgba(206, 217, 224, 0.2);
    border-color:rgba(206, 217, 224, 0.2); }
  to{
    background:rgba(92, 112, 128, 0.2);
    border-color:rgba(92, 112, 128, 0.2); } }
@keyframes skeleton-glow{
  from{
    background:rgba(206, 217, 224, 0.2);
    border-color:rgba(206, 217, 224, 0.2); }
  to{
    background:rgba(92, 112, 128, 0.2);
    border-color:rgba(92, 112, 128, 0.2); } }
.bp3-skeleton{
  -webkit-animation:1000ms linear infinite alternate skeleton-glow;
          animation:1000ms linear infinite alternate skeleton-glow;
  background:rgba(206, 217, 224, 0.2);
  background-clip:padding-box !important;
  border-color:rgba(206, 217, 224, 0.2) !important;
  border-radius:2px;
  -webkit-box-shadow:none !important;
          box-shadow:none !important;
  color:transparent !important;
  cursor:default;
  pointer-events:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-skeleton::before, .bp3-skeleton::after,
  .bp3-skeleton *{
    visibility:hidden !important; }
.bp3-slider{
  height:40px;
  min-width:150px;
  width:100%;
  cursor:default;
  outline:none;
  position:relative;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-slider:hover{
    cursor:pointer; }
  .bp3-slider:active{
    cursor:-webkit-grabbing;
    cursor:grabbing; }
  .bp3-slider.bp3-disabled{
    cursor:not-allowed;
    opacity:0.5; }
  .bp3-slider.bp3-slider-unlabeled{
    height:16px; }

.bp3-slider-track,
.bp3-slider-progress{
  height:6px;
  left:0;
  right:0;
  top:5px;
  position:absolute; }

.bp3-slider-track{
  border-radius:3px;
  overflow:hidden; }

.bp3-slider-progress{
  background:rgba(92, 112, 128, 0.2); }
  .bp3-dark .bp3-slider-progress{
    background:rgba(16, 22, 26, 0.5); }
  .bp3-slider-progress.bp3-intent-primary{
    background-color:#137cbd; }
  .bp3-slider-progress.bp3-intent-success{
    background-color:#0f9960; }
  .bp3-slider-progress.bp3-intent-warning{
    background-color:#d9822b; }
  .bp3-slider-progress.bp3-intent-danger{
    background-color:#db3737; }

.bp3-slider-handle{
  background-color:#f5f8fa;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
  color:#182026;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
  cursor:pointer;
  height:16px;
  left:0;
  position:absolute;
  top:0;
  width:16px; }
  .bp3-slider-handle:hover{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
  .bp3-slider-handle:active, .bp3-slider-handle.bp3-active{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-slider-handle:disabled, .bp3-slider-handle.bp3-disabled{
    background-color:rgba(206, 217, 224, 0.5);
    background-image:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    outline:none; }
    .bp3-slider-handle:disabled.bp3-active, .bp3-slider-handle:disabled.bp3-active:hover, .bp3-slider-handle.bp3-disabled.bp3-active, .bp3-slider-handle.bp3-disabled.bp3-active:hover{
      background:rgba(206, 217, 224, 0.7); }
  .bp3-slider-handle:focus{
    z-index:1; }
  .bp3-slider-handle:hover{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
    cursor:-webkit-grab;
    cursor:grab;
    z-index:2; }
  .bp3-slider-handle.bp3-active{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 1px rgba(16, 22, 26, 0.1);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 1px rgba(16, 22, 26, 0.1);
    cursor:-webkit-grabbing;
    cursor:grabbing; }
  .bp3-disabled .bp3-slider-handle{
    background:#bfccd6;
    -webkit-box-shadow:none;
            box-shadow:none;
    pointer-events:none; }
  .bp3-dark .bp3-slider-handle{
    background-color:#394b59;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle:hover, .bp3-dark .bp3-slider-handle:active, .bp3-dark .bp3-slider-handle.bp3-active{
      color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle:hover{
      background-color:#30404d;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-slider-handle:active, .bp3-dark .bp3-slider-handle.bp3-active{
      background-color:#202b33;
      background-image:none;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-slider-handle:disabled, .bp3-dark .bp3-slider-handle.bp3-disabled{
      background-color:rgba(57, 75, 89, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
      .bp3-dark .bp3-slider-handle:disabled.bp3-active, .bp3-dark .bp3-slider-handle.bp3-disabled.bp3-active{
        background:rgba(57, 75, 89, 0.7); }
    .bp3-dark .bp3-slider-handle .bp3-button-spinner .bp3-spinner-head{
      background:rgba(16, 22, 26, 0.5);
      stroke:#8a9ba8; }
    .bp3-dark .bp3-slider-handle, .bp3-dark .bp3-slider-handle:hover{
      background-color:#394b59; }
    .bp3-dark .bp3-slider-handle.bp3-active{
      background-color:#293742; }
  .bp3-dark .bp3-disabled .bp3-slider-handle{
    background:#5c7080;
    border-color:#5c7080;
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-slider-handle .bp3-slider-label{
    background:#394b59;
    border-radius:3px;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
    color:#f5f8fa;
    margin-left:8px; }
    .bp3-dark .bp3-slider-handle .bp3-slider-label{
      background:#e1e8ed;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
      color:#394b59; }
    .bp3-disabled .bp3-slider-handle .bp3-slider-label{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-slider-handle.bp3-start, .bp3-slider-handle.bp3-end{
    width:8px; }
  .bp3-slider-handle.bp3-start{
    border-bottom-right-radius:0;
    border-top-right-radius:0; }
  .bp3-slider-handle.bp3-end{
    border-bottom-left-radius:0;
    border-top-left-radius:0;
    margin-left:8px; }
    .bp3-slider-handle.bp3-end .bp3-slider-label{
      margin-left:0; }

.bp3-slider-label{
  -webkit-transform:translate(-50%, 20px);
          transform:translate(-50%, 20px);
  display:inline-block;
  font-size:12px;
  line-height:1;
  padding:2px 5px;
  position:absolute;
  vertical-align:top; }

.bp3-slider.bp3-vertical{
  height:150px;
  min-width:40px;
  width:40px; }
  .bp3-slider.bp3-vertical .bp3-slider-track,
  .bp3-slider.bp3-vertical .bp3-slider-progress{
    bottom:0;
    height:auto;
    left:5px;
    top:0;
    width:6px; }
  .bp3-slider.bp3-vertical .bp3-slider-progress{
    top:auto; }
  .bp3-slider.bp3-vertical .bp3-slider-label{
    -webkit-transform:translate(20px, 50%);
            transform:translate(20px, 50%); }
  .bp3-slider.bp3-vertical .bp3-slider-handle{
    top:auto; }
    .bp3-slider.bp3-vertical .bp3-slider-handle .bp3-slider-label{
      margin-left:0;
      margin-top:-8px; }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-end, .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start{
      height:8px;
      margin-left:0;
      width:16px; }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start{
      border-bottom-right-radius:3px;
      border-top-left-radius:0; }
      .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start .bp3-slider-label{
        -webkit-transform:translate(20px);
                transform:translate(20px); }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-end{
      border-bottom-left-radius:0;
      border-bottom-right-radius:0;
      border-top-left-radius:3px;
      margin-bottom:8px; }

@-webkit-keyframes pt-spinner-animation{
  from{
    -webkit-transform:rotate(0deg);
            transform:rotate(0deg); }
  to{
    -webkit-transform:rotate(360deg);
            transform:rotate(360deg); } }

@keyframes pt-spinner-animation{
  from{
    -webkit-transform:rotate(0deg);
            transform:rotate(0deg); }
  to{
    -webkit-transform:rotate(360deg);
            transform:rotate(360deg); } }

.bp3-spinner{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  overflow:visible;
  vertical-align:middle; }
  .bp3-spinner svg{
    display:block; }
  .bp3-spinner path{
    fill-opacity:0; }
  .bp3-spinner .bp3-spinner-head{
    stroke:rgba(92, 112, 128, 0.8);
    stroke-linecap:round;
    -webkit-transform-origin:center;
            transform-origin:center;
    -webkit-transition:stroke-dashoffset 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:stroke-dashoffset 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-spinner .bp3-spinner-track{
    stroke:rgba(92, 112, 128, 0.2); }

.bp3-spinner-animation{
  -webkit-animation:pt-spinner-animation 500ms linear infinite;
          animation:pt-spinner-animation 500ms linear infinite; }
  .bp3-no-spin > .bp3-spinner-animation{
    -webkit-animation:none;
            animation:none; }

.bp3-dark .bp3-spinner .bp3-spinner-head{
  stroke:#8a9ba8; }

.bp3-dark .bp3-spinner .bp3-spinner-track{
  stroke:rgba(16, 22, 26, 0.5); }

.bp3-spinner.bp3-intent-primary .bp3-spinner-head{
  stroke:#137cbd; }

.bp3-spinner.bp3-intent-success .bp3-spinner-head{
  stroke:#0f9960; }

.bp3-spinner.bp3-intent-warning .bp3-spinner-head{
  stroke:#d9822b; }

.bp3-spinner.bp3-intent-danger .bp3-spinner-head{
  stroke:#db3737; }
.bp3-tabs.bp3-vertical{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }
  .bp3-tabs.bp3-vertical > .bp3-tab-list{
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start;
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column; }
    .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab{
      border-radius:3px;
      padding:0 10px;
      width:100%; }
      .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab[aria-selected="true"]{
        background-color:rgba(19, 124, 189, 0.2);
        -webkit-box-shadow:none;
                box-shadow:none; }
    .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab-indicator-wrapper .bp3-tab-indicator{
      background-color:rgba(19, 124, 189, 0.2);
      border-radius:3px;
      bottom:0;
      height:auto;
      left:0;
      right:0;
      top:0; }
  .bp3-tabs.bp3-vertical > .bp3-tab-panel{
    margin-top:0;
    padding-left:20px; }

.bp3-tab-list{
  -webkit-box-align:end;
      -ms-flex-align:end;
          align-items:flex-end;
  border:none;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  list-style:none;
  margin:0;
  padding:0;
  position:relative; }
  .bp3-tab-list > *:not(:last-child){
    margin-right:20px; }

.bp3-tab{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  color:#182026;
  cursor:pointer;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  font-size:14px;
  line-height:30px;
  max-width:100%;
  position:relative;
  vertical-align:top; }
  .bp3-tab a{
    color:inherit;
    display:block;
    text-decoration:none; }
  .bp3-tab-indicator-wrapper ~ .bp3-tab{
    background-color:transparent !important;
    -webkit-box-shadow:none !important;
            box-shadow:none !important; }
  .bp3-tab[aria-disabled="true"]{
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
  .bp3-tab[aria-selected="true"]{
    border-radius:0;
    -webkit-box-shadow:inset 0 -3px 0 #106ba3;
            box-shadow:inset 0 -3px 0 #106ba3; }
  .bp3-tab[aria-selected="true"], .bp3-tab:not([aria-disabled="true"]):hover{
    color:#106ba3; }
  .bp3-tab:focus{
    -moz-outline-radius:0; }
  .bp3-large > .bp3-tab{
    font-size:16px;
    line-height:40px; }

.bp3-tab-panel{
  margin-top:20px; }
  .bp3-tab-panel[aria-hidden="true"]{
    display:none; }

.bp3-tab-indicator-wrapper{
  left:0;
  pointer-events:none;
  position:absolute;
  top:0;
  -webkit-transform:translateX(0), translateY(0);
          transform:translateX(0), translateY(0);
  -webkit-transition:height, width, -webkit-transform;
  transition:height, width, -webkit-transform;
  transition:height, transform, width;
  transition:height, transform, width, -webkit-transform;
  -webkit-transition-duration:200ms;
          transition-duration:200ms;
  -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
          transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-tab-indicator-wrapper .bp3-tab-indicator{
    background-color:#106ba3;
    bottom:0;
    height:3px;
    left:0;
    position:absolute;
    right:0; }
  .bp3-tab-indicator-wrapper.bp3-no-animation{
    -webkit-transition:none;
    transition:none; }

.bp3-dark .bp3-tab{
  color:#f5f8fa; }
  .bp3-dark .bp3-tab[aria-disabled="true"]{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-tab[aria-selected="true"]{
    -webkit-box-shadow:inset 0 -3px 0 #48aff0;
            box-shadow:inset 0 -3px 0 #48aff0; }
  .bp3-dark .bp3-tab[aria-selected="true"], .bp3-dark .bp3-tab:not([aria-disabled="true"]):hover{
    color:#48aff0; }

.bp3-dark .bp3-tab-indicator{
  background-color:#48aff0; }

.bp3-flex-expander{
  -webkit-box-flex:1;
      -ms-flex:1 1;
          flex:1 1; }
.bp3-tag{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background-color:#5c7080;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:none;
          box-shadow:none;
  color:#f5f8fa;
  font-size:12px;
  line-height:16px;
  max-width:100%;
  min-height:20px;
  min-width:20px;
  padding:2px 6px;
  position:relative; }
  .bp3-tag.bp3-interactive{
    cursor:pointer; }
    .bp3-tag.bp3-interactive:hover{
      background-color:rgba(92, 112, 128, 0.85); }
    .bp3-tag.bp3-interactive.bp3-active, .bp3-tag.bp3-interactive:active{
      background-color:rgba(92, 112, 128, 0.7); }
  .bp3-tag > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-tag > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-tag::before,
  .bp3-tag > *{
    margin-right:4px; }
  .bp3-tag:empty::before,
  .bp3-tag > :last-child{
    margin-right:0; }
  .bp3-tag:focus{
    outline:rgba(19, 124, 189, 0.6) auto 2px;
    outline-offset:0;
    -moz-outline-radius:6px; }
  .bp3-tag.bp3-round{
    border-radius:30px;
    padding-left:8px;
    padding-right:8px; }
  .bp3-dark .bp3-tag{
    background-color:#bfccd6;
    color:#182026; }
    .bp3-dark .bp3-tag.bp3-interactive{
      cursor:pointer; }
      .bp3-dark .bp3-tag.bp3-interactive:hover{
        background-color:rgba(191, 204, 214, 0.85); }
      .bp3-dark .bp3-tag.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-interactive:active{
        background-color:rgba(191, 204, 214, 0.7); }
    .bp3-dark .bp3-tag > .bp3-icon, .bp3-dark .bp3-tag .bp3-icon-standard, .bp3-dark .bp3-tag .bp3-icon-large{
      fill:currentColor; }
  .bp3-tag > .bp3-icon, .bp3-tag .bp3-icon-standard, .bp3-tag .bp3-icon-large{
    fill:#ffffff; }
  .bp3-tag.bp3-large,
  .bp3-large .bp3-tag{
    font-size:14px;
    line-height:20px;
    min-height:30px;
    min-width:30px;
    padding:5px 10px; }
    .bp3-tag.bp3-large::before,
    .bp3-tag.bp3-large > *,
    .bp3-large .bp3-tag::before,
    .bp3-large .bp3-tag > *{
      margin-right:7px; }
    .bp3-tag.bp3-large:empty::before,
    .bp3-tag.bp3-large > :last-child,
    .bp3-large .bp3-tag:empty::before,
    .bp3-large .bp3-tag > :last-child{
      margin-right:0; }
    .bp3-tag.bp3-large.bp3-round,
    .bp3-large .bp3-tag.bp3-round{
      padding-left:12px;
      padding-right:12px; }
  .bp3-tag.bp3-intent-primary{
    background:#137cbd;
    color:#ffffff; }
    .bp3-tag.bp3-intent-primary.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-primary.bp3-interactive:hover{
        background-color:rgba(19, 124, 189, 0.85); }
      .bp3-tag.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-primary.bp3-interactive:active{
        background-color:rgba(19, 124, 189, 0.7); }
  .bp3-tag.bp3-intent-success{
    background:#0f9960;
    color:#ffffff; }
    .bp3-tag.bp3-intent-success.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-success.bp3-interactive:hover{
        background-color:rgba(15, 153, 96, 0.85); }
      .bp3-tag.bp3-intent-success.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-success.bp3-interactive:active{
        background-color:rgba(15, 153, 96, 0.7); }
  .bp3-tag.bp3-intent-warning{
    background:#d9822b;
    color:#ffffff; }
    .bp3-tag.bp3-intent-warning.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-warning.bp3-interactive:hover{
        background-color:rgba(217, 130, 43, 0.85); }
      .bp3-tag.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-warning.bp3-interactive:active{
        background-color:rgba(217, 130, 43, 0.7); }
  .bp3-tag.bp3-intent-danger{
    background:#db3737;
    color:#ffffff; }
    .bp3-tag.bp3-intent-danger.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-danger.bp3-interactive:hover{
        background-color:rgba(219, 55, 55, 0.85); }
      .bp3-tag.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-danger.bp3-interactive:active{
        background-color:rgba(219, 55, 55, 0.7); }
  .bp3-tag.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-tag.bp3-minimal > .bp3-icon, .bp3-tag.bp3-minimal .bp3-icon-standard, .bp3-tag.bp3-minimal .bp3-icon-large{
    fill:#5c7080; }
  .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]){
    background-color:rgba(138, 155, 168, 0.2);
    color:#182026; }
    .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:hover{
        background-color:rgba(92, 112, 128, 0.3); }
      .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive.bp3-active, .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:active{
        background-color:rgba(92, 112, 128, 0.4); }
    .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]){
      color:#f5f8fa; }
      .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:hover{
          background-color:rgba(191, 204, 214, 0.3); }
        .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:active{
          background-color:rgba(191, 204, 214, 0.4); }
      .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) > .bp3-icon, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) .bp3-icon-standard, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) .bp3-icon-large{
        fill:#a7b6c2; }
  .bp3-tag.bp3-minimal.bp3-intent-primary{
    background-color:rgba(19, 124, 189, 0.15);
    color:#106ba3; }
    .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:hover{
        background-color:rgba(19, 124, 189, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:active{
        background-color:rgba(19, 124, 189, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-primary > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-primary .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-primary .bp3-icon-large{
      fill:#137cbd; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary{
      background-color:rgba(19, 124, 189, 0.25);
      color:#48aff0; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:hover{
          background-color:rgba(19, 124, 189, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:active{
          background-color:rgba(19, 124, 189, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-success{
    background-color:rgba(15, 153, 96, 0.15);
    color:#0d8050; }
    .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:hover{
        background-color:rgba(15, 153, 96, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:active{
        background-color:rgba(15, 153, 96, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-success > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-success .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-success .bp3-icon-large{
      fill:#0f9960; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success{
      background-color:rgba(15, 153, 96, 0.25);
      color:#3dcc91; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:hover{
          background-color:rgba(15, 153, 96, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:active{
          background-color:rgba(15, 153, 96, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-warning{
    background-color:rgba(217, 130, 43, 0.15);
    color:#bf7326; }
    .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:hover{
        background-color:rgba(217, 130, 43, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:active{
        background-color:rgba(217, 130, 43, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-warning > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-warning .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-warning .bp3-icon-large{
      fill:#d9822b; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning{
      background-color:rgba(217, 130, 43, 0.25);
      color:#ffb366; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:hover{
          background-color:rgba(217, 130, 43, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:active{
          background-color:rgba(217, 130, 43, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-danger{
    background-color:rgba(219, 55, 55, 0.15);
    color:#c23030; }
    .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:hover{
        background-color:rgba(219, 55, 55, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:active{
        background-color:rgba(219, 55, 55, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-danger > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-danger .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-danger .bp3-icon-large{
      fill:#db3737; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger{
      background-color:rgba(219, 55, 55, 0.25);
      color:#ff7373; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:hover{
          background-color:rgba(219, 55, 55, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:active{
          background-color:rgba(219, 55, 55, 0.45); }

.bp3-tag-remove{
  background:none;
  border:none;
  color:inherit;
  cursor:pointer;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  margin-bottom:-2px;
  margin-right:-6px !important;
  margin-top:-2px;
  opacity:0.5;
  padding:2px;
  padding-left:0; }
  .bp3-tag-remove:hover{
    background:none;
    opacity:0.8;
    text-decoration:none; }
  .bp3-tag-remove:active{
    opacity:1; }
  .bp3-tag-remove:empty::before{
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-style:normal;
    font-weight:400;
    line-height:1;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    content:"???"; }
  .bp3-large .bp3-tag-remove{
    margin-right:-10px !important;
    padding:0 5px 0 0; }
    .bp3-large .bp3-tag-remove:empty::before{
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-style:normal;
      font-weight:400;
      line-height:1; }
.bp3-tag-input{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  cursor:text;
  height:auto;
  line-height:inherit;
  min-height:30px;
  padding-left:5px;
  padding-right:0; }
  .bp3-tag-input > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-tag-input > .bp3-tag-input-values{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-tag-input .bp3-tag-input-icon{
    color:#5c7080;
    margin-left:2px;
    margin-right:7px;
    margin-top:7px; }
  .bp3-tag-input .bp3-tag-input-values{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-orient:horizontal;
    -webkit-box-direction:normal;
        -ms-flex-direction:row;
            flex-direction:row;
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    -ms-flex-item-align:stretch;
        align-self:stretch;
    -ms-flex-wrap:wrap;
        flex-wrap:wrap;
    margin-right:7px;
    margin-top:5px;
    min-width:0; }
    .bp3-tag-input .bp3-tag-input-values > *{
      -webkit-box-flex:0;
          -ms-flex-positive:0;
              flex-grow:0;
      -ms-flex-negative:0;
          flex-shrink:0; }
    .bp3-tag-input .bp3-tag-input-values > .bp3-fill{
      -webkit-box-flex:1;
          -ms-flex-positive:1;
              flex-grow:1;
      -ms-flex-negative:1;
          flex-shrink:1; }
    .bp3-tag-input .bp3-tag-input-values::before,
    .bp3-tag-input .bp3-tag-input-values > *{
      margin-right:5px; }
    .bp3-tag-input .bp3-tag-input-values:empty::before,
    .bp3-tag-input .bp3-tag-input-values > :last-child{
      margin-right:0; }
    .bp3-tag-input .bp3-tag-input-values:first-child .bp3-input-ghost:first-child{
      padding-left:5px; }
    .bp3-tag-input .bp3-tag-input-values > *{
      margin-bottom:5px; }
  .bp3-tag-input .bp3-tag{
    overflow-wrap:break-word; }
    .bp3-tag-input .bp3-tag.bp3-active{
      outline:rgba(19, 124, 189, 0.6) auto 2px;
      outline-offset:0;
      -moz-outline-radius:6px; }
  .bp3-tag-input .bp3-input-ghost{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    line-height:20px;
    width:80px; }
    .bp3-tag-input .bp3-input-ghost:disabled, .bp3-tag-input .bp3-input-ghost.bp3-disabled{
      cursor:not-allowed; }
  .bp3-tag-input .bp3-button,
  .bp3-tag-input .bp3-spinner{
    margin:3px;
    margin-left:0; }
  .bp3-tag-input .bp3-button{
    min-height:24px;
    min-width:24px;
    padding:0 7px; }
  .bp3-tag-input.bp3-large{
    height:auto;
    min-height:40px; }
    .bp3-tag-input.bp3-large::before,
    .bp3-tag-input.bp3-large > *{
      margin-right:10px; }
    .bp3-tag-input.bp3-large:empty::before,
    .bp3-tag-input.bp3-large > :last-child{
      margin-right:0; }
    .bp3-tag-input.bp3-large .bp3-tag-input-icon{
      margin-left:5px;
      margin-top:10px; }
    .bp3-tag-input.bp3-large .bp3-input-ghost{
      line-height:30px; }
    .bp3-tag-input.bp3-large .bp3-button{
      min-height:30px;
      min-width:30px;
      padding:5px 10px;
      margin:5px;
      margin-left:0; }
    .bp3-tag-input.bp3-large .bp3-spinner{
      margin:8px;
      margin-left:0; }
  .bp3-tag-input.bp3-active{
    background-color:#ffffff;
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-success{
      -webkit-box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-tag-input .bp3-tag-input-icon, .bp3-tag-input.bp3-dark .bp3-tag-input-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-tag-input .bp3-input-ghost, .bp3-tag-input.bp3-dark .bp3-input-ghost{
    color:#f5f8fa; }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-webkit-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-moz-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost:-ms-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-ms-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::placeholder{
      color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-tag-input.bp3-active, .bp3-tag-input.bp3-dark.bp3-active{
    background-color:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-primary, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-success, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-success{
      -webkit-box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-warning, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-danger, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-input-ghost{
  background:none;
  border:none;
  -webkit-box-shadow:none;
          box-shadow:none;
  padding:0; }
  .bp3-input-ghost::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost:focus{
    outline:none !important; }
.bp3-toast{
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  background-color:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  margin:20px 0 0;
  max-width:500px;
  min-width:300px;
  pointer-events:all;
  position:relative !important; }
  .bp3-toast.bp3-toast-enter, .bp3-toast.bp3-toast-appear{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px); }
  .bp3-toast.bp3-toast-enter-active, .bp3-toast.bp3-toast-appear-active{
    -webkit-transform:translateY(0);
            transform:translateY(0);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-toast.bp3-toast-enter ~ .bp3-toast, .bp3-toast.bp3-toast-appear ~ .bp3-toast{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px); }
  .bp3-toast.bp3-toast-enter-active ~ .bp3-toast, .bp3-toast.bp3-toast-appear-active ~ .bp3-toast{
    -webkit-transform:translateY(0);
            transform:translateY(0);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-toast.bp3-toast-exit{
    opacity:1;
    -webkit-filter:blur(0);
            filter:blur(0); }
  .bp3-toast.bp3-toast-exit-active{
    opacity:0;
    -webkit-filter:blur(10px);
            filter:blur(10px);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:opacity, filter;
    transition-property:opacity, filter, -webkit-filter;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-toast.bp3-toast-exit ~ .bp3-toast{
    -webkit-transform:translateY(0);
            transform:translateY(0); }
  .bp3-toast.bp3-toast-exit-active ~ .bp3-toast{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px);
    -webkit-transition-delay:50ms;
            transition-delay:50ms;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-toast .bp3-button-group{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    padding:5px;
    padding-left:0; }
  .bp3-toast > .bp3-icon{
    color:#5c7080;
    margin:12px;
    margin-right:0; }
  .bp3-toast.bp3-dark,
  .bp3-dark .bp3-toast{
    background-color:#394b59;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-toast.bp3-dark > .bp3-icon,
    .bp3-dark .bp3-toast > .bp3-icon{
      color:#a7b6c2; }
  .bp3-toast[class*="bp3-intent-"] a{
    color:rgba(255, 255, 255, 0.7); }
    .bp3-toast[class*="bp3-intent-"] a:hover{
      color:#ffffff; }
  .bp3-toast[class*="bp3-intent-"] > .bp3-icon{
    color:#ffffff; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button, .bp3-toast[class*="bp3-intent-"] .bp3-button::before,
  .bp3-toast[class*="bp3-intent-"] .bp3-button .bp3-icon, .bp3-toast[class*="bp3-intent-"] .bp3-button:active{
    color:rgba(255, 255, 255, 0.7) !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:focus{
    outline-color:rgba(255, 255, 255, 0.5); }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:hover{
    background-color:rgba(255, 255, 255, 0.15) !important;
    color:#ffffff !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:active{
    background-color:rgba(255, 255, 255, 0.3) !important;
    color:#ffffff !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button::after{
    background:rgba(255, 255, 255, 0.3) !important; }
  .bp3-toast.bp3-intent-primary{
    background-color:#137cbd;
    color:#ffffff; }
  .bp3-toast.bp3-intent-success{
    background-color:#0f9960;
    color:#ffffff; }
  .bp3-toast.bp3-intent-warning{
    background-color:#d9822b;
    color:#ffffff; }
  .bp3-toast.bp3-intent-danger{
    background-color:#db3737;
    color:#ffffff; }

.bp3-toast-message{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  padding:11px;
  word-break:break-word; }

.bp3-toast-container{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box !important;
  display:-ms-flexbox !important;
  display:flex !important;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  left:0;
  overflow:hidden;
  padding:0 20px 20px;
  pointer-events:none;
  right:0;
  z-index:40; }
  .bp3-toast-container.bp3-toast-container-in-portal{
    position:fixed; }
  .bp3-toast-container.bp3-toast-container-inline{
    position:absolute; }
  .bp3-toast-container.bp3-toast-container-top{
    top:0; }
  .bp3-toast-container.bp3-toast-container-bottom{
    bottom:0;
    -webkit-box-orient:vertical;
    -webkit-box-direction:reverse;
        -ms-flex-direction:column-reverse;
            flex-direction:column-reverse;
    top:auto; }
  .bp3-toast-container.bp3-toast-container-left{
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start; }
  .bp3-toast-container.bp3-toast-container-right{
    -webkit-box-align:end;
        -ms-flex-align:end;
            align-items:flex-end; }

.bp3-toast-container-bottom .bp3-toast.bp3-toast-enter:not(.bp3-toast-enter-active),
.bp3-toast-container-bottom .bp3-toast.bp3-toast-enter:not(.bp3-toast-enter-active) ~ .bp3-toast, .bp3-toast-container-bottom .bp3-toast.bp3-toast-appear:not(.bp3-toast-appear-active),
.bp3-toast-container-bottom .bp3-toast.bp3-toast-appear:not(.bp3-toast-appear-active) ~ .bp3-toast,
.bp3-toast-container-bottom .bp3-toast.bp3-toast-exit-active ~ .bp3-toast,
.bp3-toast-container-bottom .bp3-toast.bp3-toast-leave-active ~ .bp3-toast{
  -webkit-transform:translateY(60px);
          transform:translateY(60px); }
.bp3-tooltip{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  -webkit-transform:scale(1);
          transform:scale(1); }
  .bp3-tooltip .bp3-popover-arrow{
    height:22px;
    position:absolute;
    width:22px; }
    .bp3-tooltip .bp3-popover-arrow::before{
      height:14px;
      margin:4px;
      width:14px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip{
    margin-bottom:11px;
    margin-top:-11px; }
    .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow{
      bottom:-8px; }
      .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(-90deg);
                transform:rotate(-90deg); }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip{
    margin-left:11px; }
    .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow{
      left:-8px; }
      .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(0);
                transform:rotate(0); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip{
    margin-top:11px; }
    .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow{
      top:-8px; }
      .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(90deg);
                transform:rotate(90deg); }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip{
    margin-left:-11px;
    margin-right:11px; }
    .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow{
      right:-8px; }
      .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(180deg);
                transform:rotate(180deg); }
  .bp3-tether-element-attached-middle > .bp3-tooltip > .bp3-popover-arrow{
    top:50%;
    -webkit-transform:translateY(-50%);
            transform:translateY(-50%); }
  .bp3-tether-element-attached-center > .bp3-tooltip > .bp3-popover-arrow{
    right:50%;
    -webkit-transform:translateX(50%);
            transform:translateX(50%); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow{
    top:-0.22183px; }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow{
    right:-0.22183px; }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow{
    left:-0.22183px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow{
    bottom:-0.22183px; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:top left;
            transform-origin:top left; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:top center;
            transform-origin:top center; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:top right;
            transform-origin:top right; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:center left;
            transform-origin:center left; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:center center;
            transform-origin:center center; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:center right;
            transform-origin:center right; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:bottom left;
            transform-origin:bottom left; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:bottom center;
            transform-origin:bottom center; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:bottom right;
            transform-origin:bottom right; }
  .bp3-tooltip .bp3-popover-content{
    background:#394b59;
    color:#f5f8fa; }
  .bp3-tooltip .bp3-popover-arrow::before{
    -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2);
            box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2); }
  .bp3-tooltip .bp3-popover-arrow-border{
    fill:#10161a;
    fill-opacity:0.1; }
  .bp3-tooltip .bp3-popover-arrow-fill{
    fill:#394b59; }
  .bp3-popover-enter > .bp3-tooltip, .bp3-popover-appear > .bp3-tooltip{
    -webkit-transform:scale(0.8);
            transform:scale(0.8); }
  .bp3-popover-enter-active > .bp3-tooltip, .bp3-popover-appear-active > .bp3-tooltip{
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-popover-exit > .bp3-tooltip{
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-popover-exit-active > .bp3-tooltip{
    -webkit-transform:scale(0.8);
            transform:scale(0.8);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-tooltip .bp3-popover-content{
    padding:10px 12px; }
  .bp3-tooltip.bp3-dark,
  .bp3-dark .bp3-tooltip{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-tooltip.bp3-dark .bp3-popover-content,
    .bp3-dark .bp3-tooltip .bp3-popover-content{
      background:#e1e8ed;
      color:#394b59; }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow::before,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow::before{
      -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4);
              box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4); }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow-border,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow-border{
      fill:#10161a;
      fill-opacity:0.2; }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow-fill,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow-fill{
      fill:#e1e8ed; }
  .bp3-tooltip.bp3-intent-primary .bp3-popover-content{
    background:#137cbd;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-primary .bp3-popover-arrow-fill{
    fill:#137cbd; }
  .bp3-tooltip.bp3-intent-success .bp3-popover-content{
    background:#0f9960;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-success .bp3-popover-arrow-fill{
    fill:#0f9960; }
  .bp3-tooltip.bp3-intent-warning .bp3-popover-content{
    background:#d9822b;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-warning .bp3-popover-arrow-fill{
    fill:#d9822b; }
  .bp3-tooltip.bp3-intent-danger .bp3-popover-content{
    background:#db3737;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-danger .bp3-popover-arrow-fill{
    fill:#db3737; }

.bp3-tooltip-indicator{
  border-bottom:dotted 1px;
  cursor:help; }
.bp3-tree .bp3-icon, .bp3-tree .bp3-icon-standard, .bp3-tree .bp3-icon-large{
  color:#5c7080; }
  .bp3-tree .bp3-icon.bp3-intent-primary, .bp3-tree .bp3-icon-standard.bp3-intent-primary, .bp3-tree .bp3-icon-large.bp3-intent-primary{
    color:#137cbd; }
  .bp3-tree .bp3-icon.bp3-intent-success, .bp3-tree .bp3-icon-standard.bp3-intent-success, .bp3-tree .bp3-icon-large.bp3-intent-success{
    color:#0f9960; }
  .bp3-tree .bp3-icon.bp3-intent-warning, .bp3-tree .bp3-icon-standard.bp3-intent-warning, .bp3-tree .bp3-icon-large.bp3-intent-warning{
    color:#d9822b; }
  .bp3-tree .bp3-icon.bp3-intent-danger, .bp3-tree .bp3-icon-standard.bp3-intent-danger, .bp3-tree .bp3-icon-large.bp3-intent-danger{
    color:#db3737; }

.bp3-tree-node-list{
  list-style:none;
  margin:0;
  padding-left:0; }

.bp3-tree-root{
  background-color:transparent;
  cursor:default;
  padding-left:0;
  position:relative; }

.bp3-tree-node-content-0{
  padding-left:0px; }

.bp3-tree-node-content-1{
  padding-left:23px; }

.bp3-tree-node-content-2{
  padding-left:46px; }

.bp3-tree-node-content-3{
  padding-left:69px; }

.bp3-tree-node-content-4{
  padding-left:92px; }

.bp3-tree-node-content-5{
  padding-left:115px; }

.bp3-tree-node-content-6{
  padding-left:138px; }

.bp3-tree-node-content-7{
  padding-left:161px; }

.bp3-tree-node-content-8{
  padding-left:184px; }

.bp3-tree-node-content-9{
  padding-left:207px; }

.bp3-tree-node-content-10{
  padding-left:230px; }

.bp3-tree-node-content-11{
  padding-left:253px; }

.bp3-tree-node-content-12{
  padding-left:276px; }

.bp3-tree-node-content-13{
  padding-left:299px; }

.bp3-tree-node-content-14{
  padding-left:322px; }

.bp3-tree-node-content-15{
  padding-left:345px; }

.bp3-tree-node-content-16{
  padding-left:368px; }

.bp3-tree-node-content-17{
  padding-left:391px; }

.bp3-tree-node-content-18{
  padding-left:414px; }

.bp3-tree-node-content-19{
  padding-left:437px; }

.bp3-tree-node-content-20{
  padding-left:460px; }

.bp3-tree-node-content{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  height:30px;
  padding-right:5px;
  width:100%; }
  .bp3-tree-node-content:hover{
    background-color:rgba(191, 204, 214, 0.4); }

.bp3-tree-node-caret,
.bp3-tree-node-caret-none{
  min-width:30px; }

.bp3-tree-node-caret{
  color:#5c7080;
  cursor:pointer;
  padding:7px;
  -webkit-transform:rotate(0deg);
          transform:rotate(0deg);
  -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-tree-node-caret:hover{
    color:#182026; }
  .bp3-dark .bp3-tree-node-caret{
    color:#a7b6c2; }
    .bp3-dark .bp3-tree-node-caret:hover{
      color:#f5f8fa; }
  .bp3-tree-node-caret.bp3-tree-node-caret-open{
    -webkit-transform:rotate(90deg);
            transform:rotate(90deg); }
  .bp3-tree-node-caret.bp3-icon-standard::before{
    content:"???"; }

.bp3-tree-node-icon{
  margin-right:7px;
  position:relative; }

.bp3-tree-node-label{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  position:relative;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-tree-node-label span{
    display:inline; }

.bp3-tree-node-secondary-label{
  padding:0 5px;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-tree-node-secondary-label .bp3-popover-wrapper,
  .bp3-tree-node-secondary-label .bp3-popover-target{
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex; }

.bp3-tree-node.bp3-disabled .bp3-tree-node-content{
  background-color:inherit;
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-tree-node.bp3-disabled .bp3-tree-node-caret,
.bp3-tree-node.bp3-disabled .bp3-tree-node-icon{
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content{
  background-color:#137cbd; }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content,
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon, .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon-standard, .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon-large{
    color:#ffffff; }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-tree-node-caret::before{
    color:rgba(255, 255, 255, 0.7); }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-tree-node-caret:hover::before{
    color:#ffffff; }

.bp3-dark .bp3-tree-node-content:hover{
  background-color:rgba(92, 112, 128, 0.3); }

.bp3-dark .bp3-tree .bp3-icon, .bp3-dark .bp3-tree .bp3-icon-standard, .bp3-dark .bp3-tree .bp3-icon-large{
  color:#a7b6c2; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-primary, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-primary, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-primary{
    color:#137cbd; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-success, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-success, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-success{
    color:#0f9960; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-warning, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-warning, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-warning{
    color:#d9822b; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-danger, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-danger, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-danger{
    color:#db3737; }

.bp3-dark .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content{
  background-color:#137cbd; }
.bp3-omnibar{
  -webkit-filter:blur(0);
          filter:blur(0);
  opacity:1;
  background-color:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  left:calc(50% - 250px);
  top:20vh;
  width:500px;
  z-index:21; }
  .bp3-omnibar.bp3-overlay-enter, .bp3-omnibar.bp3-overlay-appear{
    -webkit-filter:blur(20px);
            filter:blur(20px);
    opacity:0.2; }
  .bp3-omnibar.bp3-overlay-enter-active, .bp3-omnibar.bp3-overlay-appear-active{
    -webkit-filter:blur(0);
            filter:blur(0);
    opacity:1;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:filter, opacity;
    transition-property:filter, opacity, -webkit-filter;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-omnibar.bp3-overlay-exit{
    -webkit-filter:blur(0);
            filter:blur(0);
    opacity:1; }
  .bp3-omnibar.bp3-overlay-exit-active{
    -webkit-filter:blur(20px);
            filter:blur(20px);
    opacity:0.2;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:filter, opacity;
    transition-property:filter, opacity, -webkit-filter;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-omnibar .bp3-input{
    background-color:transparent;
    border-radius:0; }
    .bp3-omnibar .bp3-input, .bp3-omnibar .bp3-input:focus{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-omnibar .bp3-menu{
    background-color:transparent;
    border-radius:0;
    -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
    max-height:calc(60vh - 40px);
    overflow:auto; }
    .bp3-omnibar .bp3-menu:empty{
      display:none; }
  .bp3-dark .bp3-omnibar, .bp3-omnibar.bp3-dark{
    background-color:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4); }

.bp3-omnibar-overlay .bp3-overlay-backdrop{
  background-color:rgba(16, 22, 26, 0.2); }

.bp3-select-popover .bp3-popover-content{
  padding:5px; }

.bp3-select-popover .bp3-input-group{
  margin-bottom:0; }

.bp3-select-popover .bp3-menu{
  max-height:300px;
  max-width:400px;
  overflow:auto;
  padding:0; }
  .bp3-select-popover .bp3-menu:not(:first-child){
    padding-top:5px; }

.bp3-multi-select{
  min-width:150px; }

.bp3-multi-select-popover .bp3-menu{
  max-height:300px;
  max-width:400px;
  overflow:auto; }

.bp3-select-popover .bp3-popover-content{
  padding:5px; }

.bp3-select-popover .bp3-input-group{
  margin-bottom:0; }

.bp3-select-popover .bp3-menu{
  max-height:300px;
  max-width:400px;
  overflow:auto;
  padding:0; }
  .bp3-select-popover .bp3-menu:not(:first-child){
    padding-top:5px; }
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensureUiComponents() in @jupyterlab/buildutils */

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

/* Icons urls */

:root {
  --jp-icon-add: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDEzaC02djZoLTJ2LTZINXYtMmg2VjVoMnY2aDZ2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bug: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0yMCA4aC0yLjgxYy0uNDUtLjc4LTEuMDctMS40NS0xLjgyLTEuOTZMMTcgNC40MSAxNS41OSAzbC0yLjE3IDIuMTdDMTIuOTYgNS4wNiAxMi40OSA1IDEyIDVjLS40OSAwLS45Ni4wNi0xLjQxLjE3TDguNDEgMyA3IDQuNDFsMS42MiAxLjYzQzcuODggNi41NSA3LjI2IDcuMjIgNi44MSA4SDR2MmgyLjA5Yy0uMDUuMzMtLjA5LjY2LS4wOSAxdjFINHYyaDJ2MWMwIC4zNC4wNC42Ny4wOSAxSDR2MmgyLjgxYzEuMDQgMS43OSAyLjk3IDMgNS4xOSAzczQuMTUtMS4yMSA1LjE5LTNIMjB2LTJoLTIuMDljLjA1LS4zMy4wOS0uNjYuMDktMXYtMWgydi0yaC0ydi0xYzAtLjM0LS4wNC0uNjctLjA5LTFIMjBWOHptLTYgOGgtNHYtMmg0djJ6bTAtNGgtNHYtMmg0djJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-build: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE0LjkgMTcuNDVDMTYuMjUgMTcuNDUgMTcuMzUgMTYuMzUgMTcuMzUgMTVDMTcuMzUgMTMuNjUgMTYuMjUgMTIuNTUgMTQuOSAxMi41NUMxMy41NCAxMi41NSAxMi40NSAxMy42NSAxMi40NSAxNUMxMi40NSAxNi4zNSAxMy41NCAxNy40NSAxNC45IDE3LjQ1Wk0yMC4xIDE1LjY4TDIxLjU4IDE2Ljg0QzIxLjcxIDE2Ljk1IDIxLjc1IDE3LjEzIDIxLjY2IDE3LjI5TDIwLjI2IDE5LjcxQzIwLjE3IDE5Ljg2IDIwIDE5LjkyIDE5LjgzIDE5Ljg2TDE4LjA5IDE5LjE2QzE3LjczIDE5LjQ0IDE3LjMzIDE5LjY3IDE2LjkxIDE5Ljg1TDE2LjY0IDIxLjdDMTYuNjIgMjEuODcgMTYuNDcgMjIgMTYuMyAyMkgxMy41QzEzLjMyIDIyIDEzLjE4IDIxLjg3IDEzLjE1IDIxLjdMMTIuODkgMTkuODVDMTIuNDYgMTkuNjcgMTIuMDcgMTkuNDQgMTEuNzEgMTkuMTZMOS45NjAwMiAxOS44NkM5LjgxMDAyIDE5LjkyIDkuNjIwMDIgMTkuODYgOS41NDAwMiAxOS43MUw4LjE0MDAyIDE3LjI5QzguMDUwMDIgMTcuMTMgOC4wOTAwMiAxNi45NSA4LjIyMDAyIDE2Ljg0TDkuNzAwMDIgMTUuNjhMOS42NTAwMSAxNUw5LjcwMDAyIDE0LjMxTDguMjIwMDIgMTMuMTZDOC4wOTAwMiAxMy4wNSA4LjA1MDAyIDEyLjg2IDguMTQwMDIgMTIuNzFMOS41NDAwMiAxMC4yOUM5LjYyMDAyIDEwLjEzIDkuODEwMDIgMTAuMDcgOS45NjAwMiAxMC4xM0wxMS43MSAxMC44NEMxMi4wNyAxMC41NiAxMi40NiAxMC4zMiAxMi44OSAxMC4xNUwxMy4xNSA4LjI4OTk4QzEzLjE4IDguMTI5OTggMTMuMzIgNy45OTk5OCAxMy41IDcuOTk5OThIMTYuM0MxNi40NyA3Ljk5OTk4IDE2LjYyIDguMTI5OTggMTYuNjQgOC4yODk5OEwxNi45MSAxMC4xNUMxNy4zMyAxMC4zMiAxNy43MyAxMC41NiAxOC4wOSAxMC44NEwxOS44MyAxMC4xM0MyMCAxMC4wNyAyMC4xNyAxMC4xMyAyMC4yNiAxMC4yOUwyMS42NiAxMi43MUMyMS43NSAxMi44NiAyMS43MSAxMy4wNSAyMS41OCAxMy4xNkwyMC4xIDE0LjMxTDIwLjE1IDE1TDIwLjEgMTUuNjhaIi8+CiAgICA8cGF0aCBkPSJNNy4zMjk2NiA3LjQ0NDU0QzguMDgzMSA3LjAwOTU0IDguMzM5MzIgNi4wNTMzMiA3LjkwNDMyIDUuMjk5ODhDNy40NjkzMiA0LjU0NjQzIDYuNTA4MSA0LjI4MTU2IDUuNzU0NjYgNC43MTY1NkM1LjM5MTc2IDQuOTI2MDggNS4xMjY5NSA1LjI3MTE4IDUuMDE4NDkgNS42NzU5NEM0LjkxMDA0IDYuMDgwNzEgNC45NjY4MiA2LjUxMTk4IDUuMTc2MzQgNi44NzQ4OEM1LjYxMTM0IDcuNjI4MzIgNi41NzYyMiA3Ljg3OTU0IDcuMzI5NjYgNy40NDQ1NFpNOS42NTcxOCA0Ljc5NTkzTDEwLjg2NzIgNC45NTE3OUMxMC45NjI4IDQuOTc3NDEgMTEuMDQwMiA1LjA3MTMzIDExLjAzODIgNS4xODc5M0wxMS4wMzg4IDYuOTg4OTNDMTEuMDQ1NSA3LjEwMDU0IDEwLjk2MTYgNy4xOTUxOCAxMC44NTUgNy4yMTA1NEw5LjY2MDAxIDcuMzgwODNMOS4yMzkxNSA4LjEzMTg4TDkuNjY5NjEgOS4yNTc0NUM5LjcwNzI5IDkuMzYyNzEgOS42NjkzNCA5LjQ3Njk5IDkuNTc0MDggOS41MzE5OUw4LjAxNTIzIDEwLjQzMkM3LjkxMTMxIDEwLjQ5MiA3Ljc5MzM3IDEwLjQ2NzcgNy43MjEwNSAxMC4zODI0TDYuOTg3NDggOS40MzE4OEw2LjEwOTMxIDkuNDMwODNMNS4zNDcwNCAxMC4zOTA1QzUuMjg5MDkgMTAuNDcwMiA1LjE3MzgzIDEwLjQ5MDUgNS4wNzE4NyAxMC40MzM5TDMuNTEyNDUgOS41MzI5M0MzLjQxMDQ5IDkuNDc2MzMgMy4zNzY0NyA5LjM1NzQxIDMuNDEwNzUgOS4yNTY3OUwzLjg2MzQ3IDguMTQwOTNMMy42MTc0OSA3Ljc3NDg4TDMuNDIzNDcgNy4zNzg4M0wyLjIzMDc1IDcuMjEyOTdDMi4xMjY0NyA3LjE5MjM1IDIuMDQwNDkgNy4xMDM0MiAyLjA0MjQ1IDYuOTg2ODJMMi4wNDE4NyA1LjE4NTgyQzIuMDQzODMgNS4wNjkyMiAyLjExOTA5IDQuOTc5NTggMi4yMTcwNCA0Ljk2OTIyTDMuNDIwNjUgNC43OTM5M0wzLjg2NzQ5IDQuMDI3ODhMMy40MTEwNSAyLjkxNzMxQzMuMzczMzcgMi44MTIwNCAzLjQxMTMxIDIuNjk3NzYgMy41MTUyMyAyLjYzNzc2TDUuMDc0MDggMS43Mzc3NkM1LjE2OTM0IDEuNjgyNzYgNS4yODcyOSAxLjcwNzA0IDUuMzU5NjEgMS43OTIzMUw2LjExOTE1IDIuNzI3ODhMNi45ODAwMSAyLjczODkzTDcuNzI0OTYgMS43ODkyMkM3Ljc5MTU2IDEuNzA0NTggNy45MTU0OCAxLjY3OTIyIDguMDA4NzkgMS43NDA4Mkw5LjU2ODIxIDIuNjQxODJDOS42NzAxNyAyLjY5ODQyIDkuNzEyODUgMi44MTIzNCA5LjY4NzIzIDIuOTA3OTdMOS4yMTcxOCA0LjAzMzgzTDkuNDYzMTYgNC4zOTk4OEw5LjY1NzE4IDQuNzk1OTNaIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iOS45LDEzLjYgMy42LDcuNCA0LjQsNi42IDkuOSwxMi4yIDE1LjQsNi43IDE2LjEsNy40ICIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNS45TDksOS43bDMuOC0zLjhsMS4yLDEuMmwtNC45LDVsLTQuOS01TDUuMiw1Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNy41TDksMTEuMmwzLjgtMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-left: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik0xMC44LDEyLjhMNy4xLDlsMy44LTMuOGwwLDcuNkgxMC44eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-right: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik03LjIsNS4yTDEwLjksOWwtMy44LDMuOFY1LjJINy4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-up-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iMTUuNCwxMy4zIDkuOSw3LjcgNC40LDEzLjIgMy42LDEyLjUgOS45LDYuMyAxNi4xLDEyLjYgIi8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-up: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik01LjIsMTAuNUw5LDYuOGwzLjgsMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-case-sensitive: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWFjY2VudDIiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTcuNiw4aDAuOWwzLjUsOGgtMS4xTDEwLDE0SDZsLTAuOSwySDRMNy42LDh6IE04LDkuMUw2LjQsMTNoMy4yTDgsOS4xeiIvPgogICAgPHBhdGggZD0iTTE2LjYsOS44Yy0wLjIsMC4xLTAuNCwwLjEtMC43LDAuMWMtMC4yLDAtMC40LTAuMS0wLjYtMC4yYy0wLjEtMC4xLTAuMi0wLjQtMC4yLTAuNyBjLTAuMywwLjMtMC42LDAuNS0wLjksMC43Yy0wLjMsMC4xLTAuNywwLjItMS4xLDAuMmMtMC4zLDAtMC41LDAtMC43LTAuMWMtMC4yLTAuMS0wLjQtMC4yLTAuNi0wLjNjLTAuMi0wLjEtMC4zLTAuMy0wLjQtMC41IGMtMC4xLTAuMi0wLjEtMC40LTAuMS0wLjdjMC0wLjMsMC4xLTAuNiwwLjItMC44YzAuMS0wLjIsMC4zLTAuNCwwLjQtMC41QzEyLDcsMTIuMiw2LjksMTIuNSw2LjhjMC4yLTAuMSwwLjUtMC4xLDAuNy0wLjIgYzAuMy0wLjEsMC41LTAuMSwwLjctMC4xYzAuMiwwLDAuNC0wLjEsMC42LTAuMWMwLjIsMCwwLjMtMC4xLDAuNC0wLjJjMC4xLTAuMSwwLjItMC4yLDAuMi0wLjRjMC0xLTEuMS0xLTEuMy0xIGMtMC40LDAtMS40LDAtMS40LDEuMmgtMC45YzAtMC40LDAuMS0wLjcsMC4yLTFjMC4xLTAuMiwwLjMtMC40LDAuNS0wLjZjMC4yLTAuMiwwLjUtMC4zLDAuOC0wLjNDMTMuMyw0LDEzLjYsNCwxMy45LDQgYzAuMywwLDAuNSwwLDAuOCwwLjFjMC4zLDAsMC41LDAuMSwwLjcsMC4yYzAuMiwwLjEsMC40LDAuMywwLjUsMC41QzE2LDUsMTYsNS4yLDE2LDUuNnYyLjljMCwwLjIsMCwwLjQsMCwwLjUgYzAsMC4xLDAuMSwwLjIsMC4zLDAuMmMwLjEsMCwwLjIsMCwwLjMsMFY5Ljh6IE0xNS4yLDYuOWMtMS4yLDAuNi0zLjEsMC4yLTMuMSwxLjRjMCwxLjQsMy4xLDEsMy4xLTAuNVY2Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik05IDE2LjE3TDQuODMgMTJsLTEuNDIgMS40MUw5IDE5IDIxIDdsLTEuNDEtMS40MXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-circle-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDJDNi40NyAyIDIgNi40NyAyIDEyczQuNDcgMTAgMTAgMTAgMTAtNC40NyAxMC0xMFMxNy41MyAyIDEyIDJ6bTAgMThjLTQuNDEgMC04LTMuNTktOC04czMuNTktOCA4LTggOCAzLjU5IDggOC0zLjU5IDgtOCA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iOSIgY3k9IjkiIHI9IjgiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-clear: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8bWFzayBpZD0iZG9udXRIb2xlIj4KICAgIDxyZWN0IHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgZmlsbD0id2hpdGUiIC8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI4IiBmaWxsPSJibGFjayIvPgogIDwvbWFzaz4KCiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxyZWN0IGhlaWdodD0iMTgiIHdpZHRoPSIyIiB4PSIxMSIgeT0iMyIgdHJhbnNmb3JtPSJyb3RhdGUoMzE1LCAxMiwgMTIpIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxMCIgbWFzaz0idXJsKCNkb251dEhvbGUpIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-close: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1ub25lIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIGpwLWljb24zLWhvdmVyIiBmaWxsPSJub25lIj4KICAgIDxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjExIi8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIGpwLWljb24tYWNjZW50Mi1ob3ZlciIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMTkgNi40MUwxNy41OSA1IDEyIDEwLjU5IDYuNDEgNSA1IDYuNDEgMTAuNTkgMTIgNSAxNy41OSA2LjQxIDE5IDEyIDEzLjQxIDE3LjU5IDE5IDE5IDE3LjU5IDEzLjQxIDEyeiIvPgogIDwvZz4KCiAgPGcgY2xhc3M9ImpwLWljb24tbm9uZSBqcC1pY29uLWJ1c3kiIGZpbGw9Im5vbmUiPgogICAgPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-code: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTExLjQgMTguNkw2LjggMTRMMTEuNCA5LjRMMTAgOEw0IDE0TDEwIDIwTDExLjQgMTguNlpNMTYuNiAxOC42TDIxLjIgMTRMMTYuNiA5LjRMMTggOEwyNCAxNEwxOCAyMEwxNi42IDE4LjZWMTguNloiLz4KCTwvZz4KPC9zdmc+Cg==);
  --jp-icon-console: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwMCAyMDAiPgogIDxnIGNsYXNzPSJqcC1pY29uLWJyYW5kMSBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMjg4RDEiPgogICAgPHBhdGggZD0iTTIwIDE5LjhoMTYwdjE1OS45SDIweiIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNmZmYiPgogICAgPHBhdGggZD0iTTEwNSAxMjcuM2g0MHYxMi44aC00MHpNNTEuMSA3N0w3NCA5OS45bC0yMy4zIDIzLjMgMTAuNSAxMC41IDIzLjMtMjMuM0w5NSA5OS45IDg0LjUgODkuNCA2MS42IDY2LjV6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-copy: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTExLjksMUgzLjJDMi40LDEsMS43LDEuNywxLjcsMi41djEwLjJoMS41VjIuNWg4LjdWMXogTTE0LjEsMy45aC04Yy0wLjgsMC0xLjUsMC43LTEuNSwxLjV2MTAuMmMwLDAuOCwwLjcsMS41LDEuNSwxLjVoOCBjMC44LDAsMS41LTAuNywxLjUtMS41VjUuNEMxNS41LDQuNiwxNC45LDMuOSwxNC4xLDMuOXogTTE0LjEsMTUuNWgtOFY1LjRoOFYxNS41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-copyright: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDI0IDI0IiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCI+CiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0xMS44OCw5LjE0YzEuMjgsMC4wNiwxLjYxLDEuMTUsMS42MywxLjY2aDEuNzljLTAuMDgtMS45OC0xLjQ5LTMuMTktMy40NS0zLjE5QzkuNjQsNy42MSw4LDksOCwxMi4xNCBjMCwxLjk0LDAuOTMsNC4yNCwzLjg0LDQuMjRjMi4yMiwwLDMuNDEtMS42NSwzLjQ0LTIuOTVoLTEuNzljLTAuMDMsMC41OS0wLjQ1LDEuMzgtMS42MywxLjQ0QzEwLjU1LDE0LjgzLDEwLDEzLjgxLDEwLDEyLjE0IEMxMCw5LjI1LDExLjI4LDkuMTYsMTEuODgsOS4xNHogTTEyLDJDNi40OCwyLDIsNi40OCwyLDEyczQuNDgsMTAsMTAsMTBzMTAtNC40OCwxMC0xMFMxNy41MiwyLDEyLDJ6IE0xMiwyMGMtNC40MSwwLTgtMy41OS04LTggczMuNTktOCw4LThzOCwzLjU5LDgsOFMxNi40MSwyMCwxMiwyMHoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-cut: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkuNjQgNy42NGMuMjMtLjUuMzYtMS4wNS4zNi0xLjY0IDAtMi4yMS0xLjc5LTQtNC00UzIgMy43OSAyIDZzMS43OSA0IDQgNGMuNTkgMCAxLjE0LS4xMyAxLjY0LS4zNkwxMCAxMmwtMi4zNiAyLjM2QzcuMTQgMTQuMTMgNi41OSAxNCA2IDE0Yy0yLjIxIDAtNCAxLjc5LTQgNHMxLjc5IDQgNCA0IDQtMS43OSA0LTRjMC0uNTktLjEzLTEuMTQtLjM2LTEuNjRMMTIgMTRsNyA3aDN2LTFMOS42NCA3LjY0ek02IDhjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTAgMTJjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTYtNy41Yy0uMjggMC0uNS0uMjItLjUtLjVzLjIyLS41LjUtLjUuNS4yMi41LjUtLjIyLjUtLjUuNXpNMTkgM2wtNiA2IDIgMiA3LTdWM3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-download: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDloLTRWM0g5djZINWw3IDcgNy03ek01IDE4djJoMTR2LTJINXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-edit: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMgMTcuMjVWMjFoMy43NUwxNy44MSA5Ljk0bC0zLjc1LTMuNzVMMyAxNy4yNXpNMjAuNzEgNy4wNGMuMzktLjM5LjM5LTEuMDIgMC0xLjQxbC0yLjM0LTIuMzRjLS4zOS0uMzktMS4wMi0uMzktMS40MSAwbC0xLjgzIDEuODMgMy43NSAzLjc1IDEuODMtMS44M3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-ellipses: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iNSIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxOSIgY3k9IjEyIiByPSIyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-extension: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwLjUgMTFIMTlWN2MwLTEuMS0uOS0yLTItMmgtNFYzLjVDMTMgMi4xMiAxMS44OCAxIDEwLjUgMVM4IDIuMTIgOCAzLjVWNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAydjMuOEgzLjVjMS40OSAwIDIuNyAxLjIxIDIuNyAyLjdzLTEuMjEgMi43LTIuNyAyLjdIMlYyMGMwIDEuMS45IDIgMiAyaDMuOHYtMS41YzAtMS40OSAxLjIxLTIuNyAyLjctMi43IDEuNDkgMCAyLjcgMS4yMSAyLjcgMi43VjIySDE3YzEuMSAwIDItLjkgMi0ydi00aDEuNWMxLjM4IDAgMi41LTEuMTIgMi41LTIuNVMyMS44OCAxMSAyMC41IDExeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-fast-forward: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTQgMThsOC41LTZMNCA2djEyem05LTEydjEybDguNS02TDEzIDZ6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-file-upload: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkgMTZoNnYtNmg0bC03LTctNyA3aDR6bS00IDJoMTR2Mkg1eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-file: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuMyA4LjJsLTUuNS01LjVjLS4zLS4zLS43LS41LTEuMi0uNUgzLjljLS44LjEtMS42LjktMS42IDEuOHYxNC4xYzAgLjkuNyAxLjYgMS42IDEuNmgxNC4yYy45IDAgMS42LS43IDEuNi0xLjZWOS40Yy4xLS41LS4xLS45LS40LTEuMnptLTUuOC0zLjNsMy40IDMuNmgtMy40VjQuOXptMy45IDEyLjdINC43Yy0uMSAwLS4yIDAtLjItLjJWNC43YzAtLjIuMS0uMy4yLS4zaDcuMnY0LjRzMCAuOC4zIDEuMWMuMy4zIDEuMS4zIDEuMS4zaDQuM3Y3LjJzLS4xLjItLjIuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-filter-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEwIDE4aDR2LTJoLTR2MnpNMyA2djJoMThWNkgzem0zIDdoMTJ2LTJINnYyeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY4YzAtMS4xLS45LTItMi0yaC04bC0yLTJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-html5: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMDAiIGQ9Ik0xMDguNCAwaDIzdjIyLjhoMjEuMlYwaDIzdjY5aC0yM1Y0NmgtMjF2MjNoLTIzLjJNMjA2IDIzaC0yMC4zVjBoNjMuN3YyM0gyMjl2NDZoLTIzbTUzLjUtNjloMjQuMWwxNC44IDI0LjNMMzEzLjIgMGgyNC4xdjY5aC0yM1YzNC44bC0xNi4xIDI0LjgtMTYuMS0yNC44VjY5aC0yMi42bTg5LjItNjloMjN2NDYuMmgzMi42VjY5aC01NS42Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2U0NGQyNiIgZD0iTTEwNy42IDQ3MWwtMzMtMzcwLjRoMzYyLjhsLTMzIDM3MC4yTDI1NS43IDUxMiIvPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNmMTY1MjkiIGQ9Ik0yNTYgNDgwLjVWMTMxaDE0OC4zTDM3NiA0NDciLz4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNlYmViZWIiIGQ9Ik0xNDIgMTc2LjNoMTE0djQ1LjRoLTY0LjJsNC4yIDQ2LjVoNjB2NDUuM0gxNTQuNG0yIDIyLjhIMjAybDMuMiAzNi4zIDUwLjggMTMuNnY0Ny40bC05My4yLTI2Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIiBkPSJNMzY5LjYgMTc2LjNIMjU1Ljh2NDUuNGgxMDkuNm0tNC4xIDQ2LjVIMjU1Ljh2NDUuNGg1NmwtNS4zIDU5LTUwLjcgMTMuNnY0Ny4ybDkzLTI1LjgiLz4KPC9zdmc+Cg==);
  --jp-icon-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1icmFuZDQganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNGRkYiIGQ9Ik0yLjIgMi4yaDE3LjV2MTcuNUgyLjJ6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzNGNTFCNSIgZD0iTTIuMiAyLjJ2MTcuNWgxNy41bC4xLTE3LjVIMi4yem0xMi4xIDIuMmMxLjIgMCAyLjIgMSAyLjIgMi4ycy0xIDIuMi0yLjIgMi4yLTIuMi0xLTIuMi0yLjIgMS0yLjIgMi4yLTIuMnpNNC40IDE3LjZsMy4zLTguOCAzLjMgNi42IDIuMi0zLjIgNC40IDUuNEg0LjR6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-inspector: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY2YzAtMS4xLS45LTItMi0yem0tNSAxNEg0di00aDExdjR6bTAtNUg0VjloMTF2NHptNSA1aC00VjloNHY5eiIvPgo8L3N2Zz4K);
  --jp-icon-json: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMSBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNGOUE4MjUiPgogICAgPHBhdGggZD0iTTIwLjIgMTEuOGMtMS42IDAtMS43LjUtMS43IDEgMCAuNC4xLjkuMSAxLjMuMS41LjEuOS4xIDEuMyAwIDEuNy0xLjQgMi4zLTMuNSAyLjNoLS45di0xLjloLjVjMS4xIDAgMS40IDAgMS40LS44IDAtLjMgMC0uNi0uMS0xIDAtLjQtLjEtLjgtLjEtMS4yIDAtMS4zIDAtMS44IDEuMy0yLTEuMy0uMi0xLjMtLjctMS4zLTIgMC0uNC4xLS44LjEtMS4yLjEtLjQuMS0uNy4xLTEgMC0uOC0uNC0uNy0xLjQtLjhoLS41VjQuMWguOWMyLjIgMCAzLjUuNyAzLjUgMi4zIDAgLjQtLjEuOS0uMSAxLjMtLjEuNS0uMS45LS4xIDEuMyAwIC41LjIgMSAxLjcgMXYxLjh6TTEuOCAxMC4xYzEuNiAwIDEuNy0uNSAxLjctMSAwLS40LS4xLS45LS4xLTEuMy0uMS0uNS0uMS0uOS0uMS0xLjMgMC0xLjYgMS40LTIuMyAzLjUtMi4zaC45djEuOWgtLjVjLTEgMC0xLjQgMC0xLjQuOCAwIC4zIDAgLjYuMSAxIDAgLjIuMS42LjEgMSAwIDEuMyAwIDEuOC0xLjMgMkM2IDExLjIgNiAxMS43IDYgMTNjMCAuNC0uMS44LS4xIDEuMi0uMS4zLS4xLjctLjEgMSAwIC44LjMuOCAxLjQuOGguNXYxLjloLS45Yy0yLjEgMC0zLjUtLjYtMy41LTIuMyAwLS40LjEtLjkuMS0xLjMuMS0uNS4xLS45LjEtMS4zIDAtLjUtLjItMS0xLjctMXYtMS45eiIvPgogICAgPGNpcmNsZSBjeD0iMTEiIGN5PSIxMy44IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY3g9IjExIiBjeT0iOC4yIiByPSIyLjEiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-julia: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDMyNSAzMDAiPgogIDxnIGNsYXNzPSJqcC1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjY2IzYzMzIj4KICAgIDxwYXRoIGQ9Ik0gMTUwLjg5ODQzOCAyMjUgQyAxNTAuODk4NDM4IDI2Ni40MjE4NzUgMTE3LjMyMDMxMiAzMDAgNzUuODk4NDM4IDMwMCBDIDM0LjQ3NjU2MiAzMDAgMC44OTg0MzggMjY2LjQyMTg3NSAwLjg5ODQzOCAyMjUgQyAwLjg5ODQzOCAxODMuNTc4MTI1IDM0LjQ3NjU2MiAxNTAgNzUuODk4NDM4IDE1MCBDIDExNy4zMjAzMTIgMTUwIDE1MC44OTg0MzggMTgzLjU3ODEyNSAxNTAuODk4NDM4IDIyNSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzM4OTgyNiI+CiAgICA8cGF0aCBkPSJNIDIzNy41IDc1IEMgMjM3LjUgMTE2LjQyMTg3NSAyMDMuOTIxODc1IDE1MCAxNjIuNSAxNTAgQyAxMjEuMDc4MTI1IDE1MCA4Ny41IDExNi40MjE4NzUgODcuNSA3NSBDIDg3LjUgMzMuNTc4MTI1IDEyMS4wNzgxMjUgMCAxNjIuNSAwIEMgMjAzLjkyMTg3NSAwIDIzNy41IDMzLjU3ODEyNSAyMzcuNSA3NSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzk1NThiMiI+CiAgICA8cGF0aCBkPSJNIDMyNC4xMDE1NjIgMjI1IEMgMzI0LjEwMTU2MiAyNjYuNDIxODc1IDI5MC41MjM0MzggMzAwIDI0OS4xMDE1NjIgMzAwIEMgMjA3LjY3OTY4OCAzMDAgMTc0LjEwMTU2MiAyNjYuNDIxODc1IDE3NC4xMDE1NjIgMjI1IEMgMTc0LjEwMTU2MiAxODMuNTc4MTI1IDIwNy42Nzk2ODggMTUwIDI0OS4xMDE1NjIgMTUwIEMgMjkwLjUyMzQzOCAxNTAgMzI0LjEwMTU2MiAxODMuNTc4MTI1IDMyNC4xMDE1NjIgMjI1Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-jupyter-favicon: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTUyIiBoZWlnaHQ9IjE2NSIgdmlld0JveD0iMCAwIDE1MiAxNjUiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA3ODk0NywgMTEwLjU4MjkyNykiIGQ9Ik03NS45NDIyODQyLDI5LjU4MDQ1NjEgQzQzLjMwMjM5NDcsMjkuNTgwNDU2MSAxNC43OTY3ODMyLDE3LjY1MzQ2MzQgMCwwIEM1LjUxMDgzMjExLDE1Ljg0MDY4MjkgMTUuNzgxNTM4OSwyOS41NjY3NzMyIDI5LjM5MDQ5NDcsMzkuMjc4NDE3MSBDNDIuOTk5Nyw0OC45ODk4NTM3IDU5LjI3MzcsNTQuMjA2NzgwNSA3NS45NjA1Nzg5LDU0LjIwNjc4MDUgQzkyLjY0NzQ1NzksNTQuMjA2NzgwNSAxMDguOTIxNDU4LDQ4Ljk4OTg1MzcgMTIyLjUzMDY2MywzOS4yNzg0MTcxIEMxMzYuMTM5NDUzLDI5LjU2Njc3MzIgMTQ2LjQxMDI4NCwxNS44NDA2ODI5IDE1MS45MjExNTgsMCBDMTM3LjA4Nzg2OCwxNy42NTM0NjM0IDEwOC41ODI1ODksMjkuNTgwNDU2MSA3NS45NDIyODQyLDI5LjU4MDQ1NjEgTDc1Ljk0MjI4NDIsMjkuNTgwNDU2MSBaIiAvPgogICAgPHBhdGggdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMzczNjgsIDAuNzA0ODc4KSIgZD0iTTc1Ljk3ODQ1NzksMjQuNjI2NDA3MyBDMTA4LjYxODc2MywyNC42MjY0MDczIDEzNy4xMjQ0NTgsMzYuNTUzNDQxNSAxNTEuOTIxMTU4LDU0LjIwNjc4MDUgQzE0Ni40MTAyODQsMzguMzY2MjIyIDEzNi4xMzk0NTMsMjQuNjQwMTMxNyAxMjIuNTMwNjYzLDE0LjkyODQ4NzggQzEwOC45MjE0NTgsNS4yMTY4NDM5IDkyLjY0NzQ1NzksMCA3NS45NjA1Nzg5LDAgQzU5LjI3MzcsMCA0Mi45OTk3LDUuMjE2ODQzOSAyOS4zOTA0OTQ3LDE0LjkyODQ4NzggQzE1Ljc4MTUzODksMjQuNjQwMTMxNyA1LjUxMDgzMjExLDM4LjM2NjIyMiAwLDU0LjIwNjc4MDUgQzE0LjgzMzA4MTYsMzYuNTg5OTI5MyA0My4zMzg1Njg0LDI0LjYyNjQwNzMgNzUuOTc4NDU3OSwyNC42MjY0MDczIEw3NS45Nzg0NTc5LDI0LjYyNjQwNzMgWiIgLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-jupyter: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzkiIGhlaWdodD0iNTEiIHZpZXdCb3g9IjAgMCAzOSA1MSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMTYzOCAtMjI4MSkiPgogICAgPGcgY2xhc3M9ImpwLWljb24td2FybjAiIGZpbGw9IiNGMzc3MjYiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5Ljc0IDIzMTEuOTgpIiBkPSJNIDE4LjI2NDYgNy4xMzQxMUMgMTAuNDE0NSA3LjEzNDExIDMuNTU4NzIgNC4yNTc2IDAgMEMgMS4zMjUzOSAzLjgyMDQgMy43OTU1NiA3LjEzMDgxIDcuMDY4NiA5LjQ3MzAzQyAxMC4zNDE3IDExLjgxNTIgMTQuMjU1NyAxMy4wNzM0IDE4LjI2OSAxMy4wNzM0QyAyMi4yODIzIDEzLjA3MzQgMjYuMTk2MyAxMS44MTUyIDI5LjQ2OTQgOS40NzMwM0MgMzIuNzQyNCA3LjEzMDgxIDM1LjIxMjYgMy44MjA0IDM2LjUzOCAwQyAzMi45NzA1IDQuMjU3NiAyNi4xMTQ4IDcuMTM0MTEgMTguMjY0NiA3LjEzNDExWiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5LjczIDIyODUuNDgpIiBkPSJNIDE4LjI3MzMgNS45MzkzMUMgMjYuMTIzNSA1LjkzOTMxIDMyLjk3OTMgOC44MTU4MyAzNi41MzggMTMuMDczNEMgMzUuMjEyNiA5LjI1MzAzIDMyLjc0MjQgNS45NDI2MiAyOS40Njk0IDMuNjAwNEMgMjYuMTk2MyAxLjI1ODE4IDIyLjI4MjMgMCAxOC4yNjkgMEMgMTQuMjU1NyAwIDEwLjM0MTcgMS4yNTgxOCA3LjA2ODYgMy42MDA0QyAzLjc5NTU2IDUuOTQyNjIgMS4zMjUzOSA5LjI1MzAzIDAgMTMuMDczNEMgMy41Njc0NSA4LjgyNDYzIDEwLjQyMzIgNS45MzkzMSAxOC4yNzMzIDUuOTM5MzFaIi8+CiAgICA8L2c+CiAgICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjY5LjMgMjI4MS4zMSkiIGQ9Ik0gNS44OTM1MyAyLjg0NEMgNS45MTg4OSAzLjQzMTY1IDUuNzcwODUgNC4wMTM2NyA1LjQ2ODE1IDQuNTE2NDVDIDUuMTY1NDUgNS4wMTkyMiA0LjcyMTY4IDUuNDIwMTUgNC4xOTI5OSA1LjY2ODUxQyAzLjY2NDMgNS45MTY4OCAzLjA3NDQ0IDYuMDAxNTEgMi40OTgwNSA1LjkxMTcxQyAxLjkyMTY2IDUuODIxOSAxLjM4NDYzIDUuNTYxNyAwLjk1NDg5OCA1LjE2NDAxQyAwLjUyNTE3IDQuNzY2MzMgMC4yMjIwNTYgNC4yNDkwMyAwLjA4MzkwMzcgMy42Nzc1N0MgLTAuMDU0MjQ4MyAzLjEwNjExIC0wLjAyMTIzIDIuNTA2MTcgMC4xNzg3ODEgMS45NTM2NEMgMC4zNzg3OTMgMS40MDExIDAuNzM2ODA5IDAuOTIwODE3IDEuMjA3NTQgMC41NzM1MzhDIDEuNjc4MjYgMC4yMjYyNTkgMi4yNDA1NSAwLjAyNzU5MTkgMi44MjMyNiAwLjAwMjY3MjI5QyAzLjYwMzg5IC0wLjAzMDcxMTUgNC4zNjU3MyAwLjI0OTc4OSA0Ljk0MTQyIDAuNzgyNTUxQyA1LjUxNzExIDEuMzE1MzEgNS44NTk1NiAyLjA1Njc2IDUuODkzNTMgMi44NDRaIi8+CiAgICAgIDxwYXRoIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE2MzkuOCAyMzIzLjgxKSIgZD0iTSA3LjQyNzg5IDMuNTgzMzhDIDcuNDYwMDggNC4zMjQzIDcuMjczNTUgNS4wNTgxOSA2Ljg5MTkzIDUuNjkyMTNDIDYuNTEwMzEgNi4zMjYwNyA1Ljk1MDc1IDYuODMxNTYgNS4yODQxMSA3LjE0NDZDIDQuNjE3NDcgNy40NTc2MyAzLjg3MzcxIDcuNTY0MTQgMy4xNDcwMiA3LjQ1MDYzQyAyLjQyMDMyIDcuMzM3MTIgMS43NDMzNiA3LjAwODcgMS4yMDE4NCA2LjUwNjk1QyAwLjY2MDMyOCA2LjAwNTIgMC4yNzg2MSA1LjM1MjY4IDAuMTA1MDE3IDQuNjMyMDJDIC0wLjA2ODU3NTcgMy45MTEzNSAtMC4wMjYyMzYxIDMuMTU0OTQgMC4yMjY2NzUgMi40NTg1NkMgMC40Nzk1ODcgMS43NjIxNyAwLjkzMTY5NyAxLjE1NzEzIDEuNTI1NzYgMC43MjAwMzNDIDIuMTE5ODMgMC4yODI5MzUgMi44MjkxNCAwLjAzMzQzOTUgMy41NjM4OSAwLjAwMzEzMzQ0QyA0LjU0NjY3IC0wLjAzNzQwMzMgNS41MDUyOSAwLjMxNjcwNiA2LjIyOTYxIDAuOTg3ODM1QyA2Ljk1MzkzIDEuNjU4OTYgNy4zODQ4NCAyLjU5MjM1IDcuNDI3ODkgMy41ODMzOEwgNy40Mjc4OSAzLjU4MzM4WiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM4LjM2IDIyODYuMDYpIiBkPSJNIDIuMjc0NzEgNC4zOTYyOUMgMS44NDM2MyA0LjQxNTA4IDEuNDE2NzEgNC4zMDQ0NSAxLjA0Nzk5IDQuMDc4NDNDIDAuNjc5MjY4IDMuODUyNCAwLjM4NTMyOCAzLjUyMTE0IDAuMjAzMzcxIDMuMTI2NTZDIDAuMDIxNDEzNiAyLjczMTk4IC0wLjA0MDM3OTggMi4yOTE4MyAwLjAyNTgxMTYgMS44NjE4MUMgMC4wOTIwMDMxIDEuNDMxOCAwLjI4MzIwNCAxLjAzMTI2IDAuNTc1MjEzIDAuNzEwODgzQyAwLjg2NzIyMiAwLjM5MDUxIDEuMjQ2OTEgMC4xNjQ3MDggMS42NjYyMiAwLjA2MjA1OTJDIDIuMDg1NTMgLTAuMDQwNTg5NyAyLjUyNTYxIC0wLjAxNTQ3MTQgMi45MzA3NiAwLjEzNDIzNUMgMy4zMzU5MSAwLjI4Mzk0MSAzLjY4NzkyIDAuNTUxNTA1IDMuOTQyMjIgMC45MDMwNkMgNC4xOTY1MiAxLjI1NDYyIDQuMzQxNjkgMS42NzQzNiA0LjM1OTM1IDIuMTA5MTZDIDQuMzgyOTkgMi42OTEwNyA0LjE3Njc4IDMuMjU4NjkgMy43ODU5NyAzLjY4NzQ2QyAzLjM5NTE2IDQuMTE2MjQgMi44NTE2NiA0LjM3MTE2IDIuMjc0NzEgNC4zOTYyOUwgMi4yNzQ3MSA0LjM5NjI5WiIvPgogICAgPC9nPgogIDwvZz4+Cjwvc3ZnPgo=);
  --jp-icon-jupyterlab-wordmark: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIHZpZXdCb3g9IjAgMCAxODYwLjggNDc1Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0RTRFNEUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDQ4MC4xMzY0MDEsIDY0LjI3MTQ5MykiPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMDAwMDAsIDU4Ljg3NTU2NikiPgogICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA4NzYwMywgMC4xNDAyOTQpIj4KICAgICAgICA8cGF0aCBkPSJNLTQyNi45LDE2OS44YzAsNDguNy0zLjcsNjQuNy0xMy42LDc2LjRjLTEwLjgsMTAtMjUsMTUuNS0zOS43LDE1LjVsMy43LDI5IGMyMi44LDAuMyw0NC44LTcuOSw2MS45LTIzLjFjMTcuOC0xOC41LDI0LTQ0LjEsMjQtODMuM1YwSC00Mjd2MTcwLjFMLTQyNi45LDE2OS44TC00MjYuOSwxNjkuOHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTU1LjA0NTI5NiwgNTYuODM3MTA0KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuNTYyNDUzLCAxLjc5OTg0MikiPgogICAgICAgIDxwYXRoIGQ9Ik0tMzEyLDE0OGMwLDIxLDAsMzkuNSwxLjcsNTUuNGgtMzEuOGwtMi4xLTMzLjNoLTAuOGMtNi43LDExLjYtMTYuNCwyMS4zLTI4LDI3LjkgYy0xMS42LDYuNi0yNC44LDEwLTM4LjIsOS44Yy0zMS40LDAtNjktMTcuNy02OS04OVYwaDM2LjR2MTEyLjdjMCwzOC43LDExLjYsNjQuNyw0NC42LDY0LjdjMTAuMy0wLjIsMjAuNC0zLjUsMjguOS05LjQgYzguNS01LjksMTUuMS0xNC4zLDE4LjktMjMuOWMyLjItNi4xLDMuMy0xMi41LDMuMy0xOC45VjAuMmgzNi40VjE0OEgtMzEyTC0zMTIsMTQ4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzOTAuMDEzMzIyLCA1My40Nzk2MzgpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS43MDY0NTgsIDAuMjMxNDI1KSI+CiAgICAgICAgPHBhdGggZD0iTS00NzguNiw3MS40YzAtMjYtMC44LTQ3LTEuNy02Ni43aDMyLjdsMS43LDM0LjhoMC44YzcuMS0xMi41LDE3LjUtMjIuOCwzMC4xLTI5LjcgYzEyLjUtNywyNi43LTEwLjMsNDEtOS44YzQ4LjMsMCw4NC43LDQxLjcsODQuNywxMDMuM2MwLDczLjEtNDMuNywxMDkuMi05MSwxMDkuMmMtMTIuMSwwLjUtMjQuMi0yLjItMzUtNy44IGMtMTAuOC01LjYtMTkuOS0xMy45LTI2LjYtMjQuMmgtMC44VjI5MWgtMzZ2LTIyMEwtNDc4LjYsNzEuNEwtNDc4LjYsNzEuNHogTS00NDIuNiwxMjUuNmMwLjEsNS4xLDAuNiwxMC4xLDEuNywxNS4xIGMzLDEyLjMsOS45LDIzLjMsMTkuOCwzMS4xYzkuOSw3LjgsMjIuMSwxMi4xLDM0LjcsMTIuMWMzOC41LDAsNjAuNy0zMS45LDYwLjctNzguNWMwLTQwLjctMjEuMS03NS42LTU5LjUtNzUuNiBjLTEyLjksMC40LTI1LjMsNS4xLTM1LjMsMTMuNGMtOS45LDguMy0xNi45LDE5LjctMTkuNiwzMi40Yy0xLjUsNC45LTIuMywxMC0yLjUsMTUuMVYxMjUuNkwtNDQyLjYsMTI1LjZMLTQ0Mi42LDEyNS42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg2MDYuNzQwNzI2LCA1Ni44MzcxMDQpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC43NTEyMjYsIDEuOTg5Mjk5KSI+CiAgICAgICAgPHBhdGggZD0iTS00NDAuOCwwbDQzLjcsMTIwLjFjNC41LDEzLjQsOS41LDI5LjQsMTIuOCw0MS43aDAuOGMzLjctMTIuMiw3LjktMjcuNywxMi44LTQyLjQgbDM5LjctMTE5LjJoMzguNUwtMzQ2LjksMTQ1Yy0yNiw2OS43LTQzLjcsMTA1LjQtNjguNiwxMjcuMmMtMTIuNSwxMS43LTI3LjksMjAtNDQuNiwyMy45bC05LjEtMzEuMSBjMTEuNy0zLjksMjIuNS0xMC4xLDMxLjgtMTguMWMxMy4yLTExLjEsMjMuNy0yNS4yLDMwLjYtNDEuMmMxLjUtMi44LDIuNS01LjcsMi45LTguOGMtMC4zLTMuMy0xLjItNi42LTIuNS05LjdMLTQ4MC4yLDAuMSBoMzkuN0wtNDQwLjgsMEwtNDQwLjgsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoODIyLjc0ODEwNCwgMC4wMDAwMDApIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS40NjQwNTAsIDAuMzc4OTE0KSI+CiAgICAgICAgPHBhdGggZD0iTS00MTMuNywwdjU4LjNoNTJ2MjguMmgtNTJWMTk2YzAsMjUsNywzOS41LDI3LjMsMzkuNWM3LjEsMC4xLDE0LjItMC43LDIxLjEtMi41IGwxLjcsMjcuN2MtMTAuMywzLjctMjEuMyw1LjQtMzIuMiw1Yy03LjMsMC40LTE0LjYtMC43LTIxLjMtMy40Yy02LjgtMi43LTEyLjktNi44LTE3LjktMTIuMWMtMTAuMy0xMC45LTE0LjEtMjktMTQuMS01Mi45IFY4Ni41aC0zMVY1OC4zaDMxVjkuNkwtNDEzLjcsMEwtNDEzLjcsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTc0LjQzMzI4NiwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAuOTkwMDM0LCAwLjYxMDMzOSkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDQ1LjgsMTEzYzAuOCw1MCwzMi4yLDcwLjYsNjguNiw3MC42YzE5LDAuNiwzNy45LTMsNTUuMy0xMC41bDYuMiwyNi40IGMtMjAuOSw4LjktNDMuNSwxMy4xLTY2LjIsMTIuNmMtNjEuNSwwLTk4LjMtNDEuMi05OC4zLTEwMi41Qy00ODAuMiw0OC4yLTQ0NC43LDAtMzg2LjUsMGM2NS4yLDAsODIuNyw1OC4zLDgyLjcsOTUuNyBjLTAuMSw1LjgtMC41LDExLjUtMS4yLDE3LjJoLTE0MC42SC00NDUuOEwtNDQ1LjgsMTEzeiBNLTMzOS4yLDg2LjZjMC40LTIzLjUtOS41LTYwLjEtNTAuNC02MC4xIGMtMzYuOCwwLTUyLjgsMzQuNC01NS43LDYwLjFILTMzOS4yTC0zMzkuMiw4Ni42TC0zMzkuMiw4Ni42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMjAxLjk2MTA1OCwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuMTc5NjQwLCAwLjcwNTA2OCkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDc4LjYsNjhjMC0yMy45LTAuNC00NC41LTEuNy02My40aDMxLjhsMS4yLDM5LjloMS43YzkuMS0yNy4zLDMxLTQ0LjUsNTUuMy00NC41IGMzLjUtMC4xLDcsMC40LDEwLjMsMS4ydjM0LjhjLTQuMS0wLjktOC4yLTEuMy0xMi40LTEuMmMtMjUuNiwwLTQzLjcsMTkuNy00OC43LDQ3LjRjLTEsNS43LTEuNiwxMS41LTEuNywxNy4ydjEwOC4zaC0zNlY2OCBMLTQ3OC42LDY4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCBkPSJNMTM1Mi4zLDMyNi4yaDM3VjI4aC0zN1YzMjYuMnogTTE2MDQuOCwzMjYuMmMtMi41LTEzLjktMy40LTMxLjEtMy40LTQ4Ljd2LTc2IGMwLTQwLjctMTUuMS04My4xLTc3LjMtODMuMWMtMjUuNiwwLTUwLDcuMS02Ni44LDE4LjFsOC40LDI0LjRjMTQuMy05LjIsMzQtMTUuMSw1My0xNS4xYzQxLjYsMCw0Ni4yLDMwLjIsNDYuMiw0N3Y0LjIgYy03OC42LTAuNC0xMjIuMywyNi41LTEyMi4zLDc1LjZjMCwyOS40LDIxLDU4LjQsNjIuMiw1OC40YzI5LDAsNTAuOS0xNC4zLDYyLjItMzAuMmgxLjNsMi45LDI1LjZIMTYwNC44eiBNMTU2NS43LDI1Ny43IGMwLDMuOC0wLjgsOC0yLjEsMTEuOGMtNS45LDE3LjItMjIuNywzNC00OS4yLDM0Yy0xOC45LDAtMzQuOS0xMS4zLTM0LjktMzUuM2MwLTM5LjUsNDUuOC00Ni42LDg2LjItNDUuOFYyNTcuN3ogTTE2OTguNSwzMjYuMiBsMS43LTMzLjZoMS4zYzE1LjEsMjYuOSwzOC43LDM4LjIsNjguMSwzOC4yYzQ1LjQsMCw5MS4yLTM2LjEsOTEuMi0xMDguOGMwLjQtNjEuNy0zNS4zLTEwMy43LTg1LjctMTAzLjcgYy0zMi44LDAtNTYuMywxNC43LTY5LjMsMzcuNGgtMC44VjI4aC0zNi42djI0NS43YzAsMTguMS0wLjgsMzguNi0xLjcsNTIuNUgxNjk4LjV6IE0xNzA0LjgsMjA4LjJjMC01LjksMS4zLTEwLjksMi4xLTE1LjEgYzcuNi0yOC4xLDMxLjEtNDUuNCw1Ni4zLTQ1LjRjMzkuNSwwLDYwLjUsMzQuOSw2MC41LDc1LjZjMCw0Ni42LTIzLjEsNzguMS02MS44LDc4LjFjLTI2LjksMC00OC4zLTE3LjYtNTUuNS00My4zIGMtMC44LTQuMi0xLjctOC44LTEuNy0xMy40VjIwOC4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzYxNjE2MSIgZD0iTTE1IDlIOXY2aDZWOXptLTIgNGgtMnYtMmgydjJ6bTgtMlY5aC0yVjdjMC0xLjEtLjktMi0yLTJoLTJWM2gtMnYyaC0yVjNIOXYySDdjLTEuMSAwLTIgLjktMiAydjJIM3YyaDJ2MkgzdjJoMnYyYzAgMS4xLjkgMiAyIDJoMnYyaDJ2LTJoMnYyaDJ2LTJoMmMxLjEgMCAyLS45IDItMnYtMmgydi0yaC0ydi0yaDJ6bS00IDZIN1Y3aDEwdjEweiIvPgo8L3N2Zz4K);
  --jp-icon-keyboard: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMTdjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY3YzAtMS4xLS45LTItMi0yem0tOSAzaDJ2MmgtMlY4em0wIDNoMnYyaC0ydi0yek04IDhoMnYySDhWOHptMCAzaDJ2Mkg4di0yem0tMSAySDV2LTJoMnYyem0wLTNINVY4aDJ2MnptOSA3SDh2LTJoOHYyem0wLTRoLTJ2LTJoMnYyem0wLTNoLTJWOGgydjJ6bTMgM2gtMnYtMmgydjJ6bTAtM2gtMlY4aDJ2MnoiLz4KPC9zdmc+Cg==);
  --jp-icon-launcher: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkgMTlINVY1aDdWM0g1YTIgMiAwIDAwLTIgMnYxNGEyIDIgMCAwMDIgMmgxNGMxLjEgMCAyLS45IDItMnYtN2gtMnY3ek0xNCAzdjJoMy41OWwtOS44MyA5LjgzIDEuNDEgMS40MUwxOSA2LjQxVjEwaDJWM2gtN3oiLz4KPC9zdmc+Cg==);
  --jp-icon-line-form: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNS44OCA0LjEyTDEzLjc2IDEybC03Ljg4IDcuODhMOCAyMmwxMC0xMEw4IDJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-link: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMuOSAxMmMwLTEuNzEgMS4zOS0zLjEgMy4xLTMuMWg0VjdIN2MtMi43NiAwLTUgMi4yNC01IDVzMi4yNCA1IDUgNWg0di0xLjlIN2MtMS43MSAwLTMuMS0xLjM5LTMuMS0zLjF6TTggMTNoOHYtMkg4djJ6bTktNmgtNHYxLjloNGMxLjcxIDAgMy4xIDEuMzkgMy4xIDMuMXMtMS4zOSAzLjEtMy4xIDMuMWgtNFYxN2g0YzIuNzYgMCA1LTIuMjQgNS01cy0yLjI0LTUtNS01eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xOSA1djE0SDVWNWgxNG0xLjEtMkgzLjljLS41IDAtLjkuNC0uOS45djE2LjJjMCAuNC40LjkuOS45aDE2LjJjLjQgMCAuOS0uNS45LS45VjMuOWMwLS41LS41LS45LS45LS45ek0xMSA3aDZ2MmgtNlY3em0wIDRoNnYyaC02di0yem0wIDRoNnYyaC02ek03IDdoMnYySDd6bTAgNGgydjJIN3ptMCA0aDJ2Mkg3eiIvPgo8L3N2Zz4=);
  --jp-icon-listings-info: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1MC45NzggNTAuOTc4IiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1MC45NzggNTAuOTc4OyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+Cgk8Zz4KCQk8cGF0aCBzdHlsZT0iZmlsbDojMDEwMDAyOyIgZD0iTTQzLjUyLDcuNDU4QzM4LjcxMSwyLjY0OCwzMi4zMDcsMCwyNS40ODksMEMxOC42NywwLDEyLjI2NiwyLjY0OCw3LjQ1OCw3LjQ1OAoJCQljLTkuOTQzLDkuOTQxLTkuOTQzLDI2LjExOSwwLDM2LjA2MmM0LjgwOSw0LjgwOSwxMS4yMTIsNy40NTYsMTguMDMxLDcuNDU4YzAsMCwwLjAwMSwwLDAuMDAyLDAKCQkJYzYuODE2LDAsMTMuMjIxLTIuNjQ4LDE4LjAyOS03LjQ1OGM0LjgwOS00LjgwOSw3LjQ1Ny0xMS4yMTIsNy40NTctMTguMDNDNTAuOTc3LDE4LjY3LDQ4LjMyOCwxMi4yNjYsNDMuNTIsNy40NTh6CgkJCSBNNDIuMTA2LDQyLjEwNWMtNC40MzIsNC40MzEtMTAuMzMyLDYuODcyLTE2LjYxNSw2Ljg3MmgtMC4wMDJjLTYuMjg1LTAuMDAxLTEyLjE4Ny0yLjQ0MS0xNi42MTctNi44NzIKCQkJYy05LjE2Mi05LjE2My05LjE2Mi0yNC4wNzEsMC0zMy4yMzNDMTMuMzAzLDQuNDQsMTkuMjA0LDIsMjUuNDg5LDJjNi4yODQsMCwxMi4xODYsMi40NCwxNi42MTcsNi44NzIKCQkJYzQuNDMxLDQuNDMxLDYuODcxLDEwLjMzMiw2Ljg3MSwxNi42MTdDNDguOTc3LDMxLjc3Miw0Ni41MzYsMzcuNjc1LDQyLjEwNiw0Mi4xMDV6Ii8+CgkJPHBhdGggc3R5bGU9ImZpbGw6IzAxMDAwMjsiIGQ9Ik0yMy41NzgsMzIuMjE4Yy0wLjAyMy0xLjczNCwwLjE0My0zLjA1OSwwLjQ5Ni0zLjk3MmMwLjM1My0wLjkxMywxLjExLTEuOTk3LDIuMjcyLTMuMjUzCgkJCWMwLjQ2OC0wLjUzNiwwLjkyMy0xLjA2MiwxLjM2Ny0xLjU3NWMwLjYyNi0wLjc1MywxLjEwNC0xLjQ3OCwxLjQzNi0yLjE3NWMwLjMzMS0wLjcwNywwLjQ5NS0xLjU0MSwwLjQ5NS0yLjUKCQkJYzAtMS4wOTYtMC4yNi0yLjA4OC0wLjc3OS0yLjk3OWMtMC41NjUtMC44NzktMS41MDEtMS4zMzYtMi44MDYtMS4zNjljLTEuODAyLDAuMDU3LTIuOTg1LDAuNjY3LTMuNTUsMS44MzIKCQkJYy0wLjMwMSwwLjUzNS0wLjUwMywxLjE0MS0wLjYwNywxLjgxNGMtMC4xMzksMC43MDctMC4yMDcsMS40MzItMC4yMDcsMi4xNzRoLTIuOTM3Yy0wLjA5MS0yLjIwOCwwLjQwNy00LjExNCwxLjQ5My01LjcxOQoJCQljMS4wNjItMS42NCwyLjg1NS0yLjQ4MSw1LjM3OC0yLjUyN2MyLjE2LDAuMDIzLDMuODc0LDAuNjA4LDUuMTQxLDEuNzU4YzEuMjc4LDEuMTYsMS45MjksMi43NjQsMS45NSw0LjgxMQoJCQljMCwxLjE0Mi0wLjEzNywyLjExMS0wLjQxLDIuOTExYy0wLjMwOSwwLjg0NS0wLjczMSwxLjU5My0xLjI2OCwyLjI0M2MtMC40OTIsMC42NS0xLjA2OCwxLjMxOC0xLjczLDIuMDAyCgkJCWMtMC42NSwwLjY5Ny0xLjMxMywxLjQ3OS0xLjk4NywyLjM0NmMtMC4yMzksMC4zNzctMC40MjksMC43NzctMC41NjUsMS4xOTljLTAuMTYsMC45NTktMC4yMTcsMS45NTEtMC4xNzEsMi45NzkKCQkJQzI2LjU4OSwzMi4yMTgsMjMuNTc4LDMyLjIxOCwyMy41NzgsMzIuMjE4eiBNMjMuNTc4LDM4LjIydi0zLjQ4NGgzLjA3NnYzLjQ4NEgyMy41Nzh6Ii8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-markdown: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjN0IxRkEyIiBkPSJNNSAxNC45aDEybC02LjEgNnptOS40LTYuOGMwLTEuMy0uMS0yLjktLjEtNC41LS40IDEuNC0uOSAyLjktMS4zIDQuM2wtMS4zIDQuM2gtMkw4LjUgNy45Yy0uNC0xLjMtLjctMi45LTEtNC4zLS4xIDEuNi0uMSAzLjItLjIgNC42TDcgMTIuNEg0LjhsLjctMTFoMy4zTDEwIDVjLjQgMS4yLjcgMi43IDEgMy45LjMtMS4yLjctMi42IDEtMy45bDEuMi0zLjdoMy4zbC42IDExaC0yLjRsLS4zLTQuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-new-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDZoLThsLTItMkg0Yy0xLjExIDAtMS45OS44OS0xLjk5IDJMMiAxOGMwIDEuMTEuODkgMiAyIDJoMTZjMS4xMSAwIDItLjg5IDItMlY4YzAtMS4xMS0uODktMi0yLTJ6bS0xIDhoLTN2M2gtMnYtM2gtM3YtMmgzVjloMnYzaDN2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-not-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI1IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMTkgMTcuMTg0NCAyLjk2OTY4IDE0LjMwMzIgMS44NjA5NCAxMS40NDA5WiIvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24yIiBzdHJva2U9IiMzMzMzMzMiIHN0cm9rZS13aWR0aD0iMiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOS4zMTU5MiA5LjMyMDMxKSIgZD0iTTcuMzY4NDIgMEwwIDcuMzY0NzkiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDkuMzE1OTIgMTYuNjgzNikgc2NhbGUoMSAtMSkiIGQ9Ik03LjM2ODQyIDBMMCA3LjM2NDc5Ii8+Cjwvc3ZnPgo=);
  --jp-icon-notebook: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNFRjZDMDAiPgogICAgPHBhdGggZD0iTTE4LjcgMy4zdjE1LjRIMy4zVjMuM2gxNS40bTEuNS0xLjVIMS44djE4LjNoMTguM2wuMS0xOC4zeiIvPgogICAgPHBhdGggZD0iTTE2LjUgMTYuNWwtNS40LTQuMy01LjYgNC4zdi0xMWgxMXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-numbering: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTQgMTlINlYxOS41SDVWMjAuNUg2VjIxSDRWMjJIN1YxOEg0VjE5Wk01IDEwSDZWNkg0VjdINVYxMFpNNCAxM0g1LjhMNCAxNS4xVjE2SDdWMTVINS4yTDcgMTIuOVYxMkg0VjEzWk05IDdWOUgyM1Y3SDlaTTkgMjFIMjNWMTlIOVYyMVpNOSAxNUgyM1YxM0g5VjE1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-offline-bolt: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDIuMDJjLTUuNTEgMC05Ljk4IDQuNDctOS45OCA5Ljk4czQuNDcgOS45OCA5Ljk4IDkuOTggOS45OC00LjQ3IDkuOTgtOS45OFMxNy41MSAyLjAyIDEyIDIuMDJ6TTExLjQ4IDIwdi02LjI2SDhMMTMgNHY2LjI2aDMuMzVMMTEuNDggMjB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-palette: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE4IDEzVjIwSDRWNkg5LjAyQzkuMDcgNS4yOSA5LjI0IDQuNjIgOS41IDRINEMyLjkgNCAyIDQuOSAyIDZWMjBDMiAyMS4xIDIuOSAyMiA0IDIySDE4QzE5LjEgMjIgMjAgMjEuMSAyMCAyMFYxNUwxOCAxM1pNMTkuMyA4Ljg5QzE5Ljc0IDguMTkgMjAgNy4zOCAyMCA2LjVDMjAgNC4wMSAxNy45OSAyIDE1LjUgMkMxMy4wMSAyIDExIDQuMDEgMTEgNi41QzExIDguOTkgMTMuMDEgMTEgMTUuNDkgMTFDMTYuMzcgMTEgMTcuMTkgMTAuNzQgMTcuODggMTAuM0wyMSAxMy40MkwyMi40MiAxMkwxOS4zIDguODlaTTE1LjUgOUMxNC4xMiA5IDEzIDcuODggMTMgNi41QzEzIDUuMTIgMTQuMTIgNCAxNS41IDRDMTYuODggNCAxOCA1LjEyIDE4IDYuNUMxOCA3Ljg4IDE2Ljg4IDkgMTUuNSA5WiIvPgogICAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik00IDZIOS4wMTg5NEM5LjAwNjM5IDYuMTY1MDIgOSA2LjMzMTc2IDkgNi41QzkgOC44MTU3NyAxMC4yMTEgMTAuODQ4NyAxMi4wMzQzIDEySDlWMTRIMTZWMTIuOTgxMUMxNi41NzAzIDEyLjkzNzcgMTcuMTIgMTIuODIwNyAxNy42Mzk2IDEyLjYzOTZMMTggMTNWMjBINFY2Wk04IDhINlYxMEg4VjhaTTYgMTJIOFYxNEg2VjEyWk04IDE2SDZWMThIOFYxNlpNOSAxNkgxNlYxOEg5VjE2WiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-paste: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE5IDJoLTQuMThDMTQuNC44NCAxMy4zIDAgMTIgMGMtMS4zIDAtMi40Ljg0LTIuODIgMkg1Yy0xLjEgMC0yIC45LTIgMnYxNmMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjRjMC0xLjEtLjktMi0yLTJ6bS03IDBjLjU1IDAgMSAuNDUgMSAxcy0uNDUgMS0xIDEtMS0uNDUtMS0xIC40NS0xIDEtMXptNyAxOEg1VjRoMnYzaDEwVjRoMnYxNnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-pdf: url(data:image/svg+xml;base64,PHN2ZwogICB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyMiAyMiIgd2lkdGg9IjE2Ij4KICAgIDxwYXRoIHRyYW5zZm9ybT0icm90YXRlKDQ1KSIgY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI0ZGMkEyQSIKICAgICAgIGQ9Im0gMjIuMzQ0MzY5LC0zLjAxNjM2NDIgaCA1LjYzODYwNCB2IDEuNTc5MjQzMyBoIC0zLjU0OTIyNyB2IDEuNTA4NjkyOTkgaCAzLjMzNzU3NiBWIDEuNjUwODE1NCBoIC0zLjMzNzU3NiB2IDMuNDM1MjYxMyBoIC0yLjA4OTM3NyB6IG0gLTcuMTM2NDQ0LDEuNTc5MjQzMyB2IDQuOTQzOTU0MyBoIDAuNzQ4OTIgcSAxLjI4MDc2MSwwIDEuOTUzNzAzLC0wLjYzNDk1MzUgMC42NzgzNjksLTAuNjM0OTUzNSAwLjY3ODM2OSwtMS44NDUxNjQxIDAsLTEuMjA0NzgzNTUgLTAuNjcyOTQyLC0xLjgzNDMxMDExIC0wLjY3Mjk0MiwtMC42Mjk1MjY1OSAtMS45NTkxMywtMC42Mjk1MjY1OSB6IG0gLTIuMDg5Mzc3LC0xLjU3OTI0MzMgaCAyLjIwMzM0MyBxIDEuODQ1MTY0LDAgMi43NDYwMzksMC4yNjU5MjA3IDAuOTA2MzAxLDAuMjYwNDkzNyAxLjU1MjEwOCwwLjg5MDAyMDMgMC41Njk4MywwLjU0ODEyMjMgMC44NDY2MDUsMS4yNjQ0ODAwNiAwLjI3Njc3NCwwLjcxNjM1NzgxIDAuMjc2Nzc0LDEuNjIyNjU4OTQgMCwwLjkxNzE1NTEgLTAuMjc2Nzc0LDEuNjM4OTM5OSAtMC4yNzY3NzUsMC43MTYzNTc4IC0wLjg0NjYwNSwxLjI2NDQ4IC0wLjY1MTIzNCwwLjYyOTUyNjYgLTEuNTYyOTYyLDAuODk1NDQ3MyAtMC45MTE3MjgsMC4yNjA0OTM3IC0yLjczNTE4NSwwLjI2MDQ5MzcgaCAtMi4yMDMzNDMgeiBtIC04LjE0NTg1NjUsMCBoIDMuNDY3ODIzIHEgMS41NDY2ODE2LDAgMi4zNzE1Nzg1LDAuNjg5MjIzIDAuODMwMzI0LDAuNjgzNzk2MSAwLjgzMDMyNCwxLjk1MzcwMzE0IDAsMS4yNzUzMzM5NyAtMC44MzAzMjQsMS45NjQ1NTcwNiBRIDkuOTg3MTk2MSwyLjI3NDkxNSA4LjQ0MDUxNDUsMi4yNzQ5MTUgSCA3LjA2MjA2ODQgViA1LjA4NjA3NjcgSCA0Ljk3MjY5MTUgWiBtIDIuMDg5Mzc2OSwxLjUxNDExOTkgdiAyLjI2MzAzOTQzIGggMS4xNTU5NDEgcSAwLjYwNzgxODgsMCAwLjkzODg2MjksLTAuMjkzMDU1NDcgMC4zMzEwNDQxLC0wLjI5ODQ4MjQxIDAuMzMxMDQ0MSwtMC44NDExNzc3MiAwLC0wLjU0MjY5NTMxIC0wLjMzMTA0NDEsLTAuODM1NzUwNzQgLTAuMzMxMDQ0MSwtMC4yOTMwNTU1IC0wLjkzODg2MjksLTAuMjkzMDU1NSB6IgovPgo8L3N2Zz4K);
  --jp-icon-python: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMEQ0N0ExIj4KICAgIDxwYXRoIGQ9Ik0xMS4xIDYuOVY1LjhINi45YzAtLjUgMC0xLjMuMi0xLjYuNC0uNy44LTEuMSAxLjctMS40IDEuNy0uMyAyLjUtLjMgMy45LS4xIDEgLjEgMS45LjkgMS45IDEuOXY0LjJjMCAuNS0uOSAxLjYtMiAxLjZIOC44Yy0xLjUgMC0yLjQgMS40LTIuNCAyLjh2Mi4ySDQuN0MzLjUgMTUuMSAzIDE0IDMgMTMuMVY5Yy0uMS0xIC42LTIgMS44LTIgMS41LS4xIDYuMy0uMSA2LjMtLjF6Ii8+CiAgICA8cGF0aCBkPSJNMTAuOSAxNS4xdjEuMWg0LjJjMCAuNSAwIDEuMy0uMiAxLjYtLjQuNy0uOCAxLjEtMS43IDEuNC0xLjcuMy0yLjUuMy0zLjkuMS0xLS4xLTEuOS0uOS0xLjktMS45di00LjJjMC0uNS45LTEuNiAyLTEuNmgzLjhjMS41IDAgMi40LTEuNCAyLjQtMi44VjYuNmgxLjdDMTguNSA2LjkgMTkgOCAxOSA4LjlWMTNjMCAxLS43IDIuMS0xLjkgMi4xaC02LjJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-r-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjE5NkYzIiBkPSJNNC40IDIuNWMxLjItLjEgMi45LS4zIDQuOS0uMyAyLjUgMCA0LjEuNCA1LjIgMS4zIDEgLjcgMS41IDEuOSAxLjUgMy41IDAgMi0xLjQgMy41LTIuOSA0LjEgMS4yLjQgMS43IDEuNiAyLjIgMyAuNiAxLjkgMSAzLjkgMS4zIDQuNmgtMy44Yy0uMy0uNC0uOC0xLjctMS4yLTMuN3MtMS4yLTIuNi0yLjYtMi42aC0uOXY2LjRINC40VjIuNXptMy43IDYuOWgxLjRjMS45IDAgMi45LS45IDIuOS0yLjNzLTEtMi4zLTIuOC0yLjNjLS43IDAtMS4zIDAtMS42LjJ2NC41aC4xdi0uMXoiLz4KPC9zdmc+Cg==);
  --jp-icon-react: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMTUwIDE1MCA1NDEuOSAyOTUuMyI+CiAgPGcgY2xhc3M9ImpwLWljb24tYnJhbmQyIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxREFGQiI+CiAgICA8cGF0aCBkPSJNNjY2LjMgMjk2LjVjMC0zMi41LTQwLjctNjMuMy0xMDMuMS04Mi40IDE0LjQtNjMuNiA4LTExNC4yLTIwLjItMTMwLjQtNi41LTMuOC0xNC4xLTUuNi0yMi40LTUuNnYyMi4zYzQuNiAwIDguMy45IDExLjQgMi42IDEzLjYgNy44IDE5LjUgMzcuNSAxNC45IDc1LjctMS4xIDkuNC0yLjkgMTkuMy01LjEgMjkuNC0xOS42LTQuOC00MS04LjUtNjMuNS0xMC45LTEzLjUtMTguNS0yNy41LTM1LjMtNDEuNi01MCAzMi42LTMwLjMgNjMuMi00Ni45IDg0LTQ2LjlWNzhjLTI3LjUgMC02My41IDE5LjYtOTkuOSA1My42LTM2LjQtMzMuOC03Mi40LTUzLjItOTkuOS01My4ydjIyLjNjMjAuNyAwIDUxLjQgMTYuNSA4NCA0Ni42LTE0IDE0LjctMjggMzEuNC00MS4zIDQ5LjktMjIuNiAyLjQtNDQgNi4xLTYzLjYgMTEtMi4zLTEwLTQtMTkuNy01LjItMjktNC43LTM4LjIgMS4xLTY3LjkgMTQuNi03NS44IDMtMS44IDYuOS0yLjYgMTEuNS0yLjZWNzguNWMtOC40IDAtMTYgMS44LTIyLjYgNS42LTI4LjEgMTYuMi0zNC40IDY2LjctMTkuOSAxMzAuMS02Mi4yIDE5LjItMTAyLjcgNDkuOS0xMDIuNyA4Mi4zIDAgMzIuNSA0MC43IDYzLjMgMTAzLjEgODIuNC0xNC40IDYzLjYtOCAxMTQuMiAyMC4yIDEzMC40IDYuNSAzLjggMTQuMSA1LjYgMjIuNSA1LjYgMjcuNSAwIDYzLjUtMTkuNiA5OS45LTUzLjYgMzYuNCAzMy44IDcyLjQgNTMuMiA5OS45IDUzLjIgOC40IDAgMTYtMS44IDIyLjYtNS42IDI4LjEtMTYuMiAzNC40LTY2LjcgMTkuOS0xMzAuMSA2Mi0xOS4xIDEwMi41LTQ5LjkgMTAyLjUtODIuM3ptLTEzMC4yLTY2LjdjLTMuNyAxMi45LTguMyAyNi4yLTEzLjUgMzkuNS00LjEtOC04LjQtMTYtMTMuMS0yNC00LjYtOC05LjUtMTUuOC0xNC40LTIzLjQgMTQuMiAyLjEgMjcuOSA0LjcgNDEgNy45em0tNDUuOCAxMDYuNWMtNy44IDEzLjUtMTUuOCAyNi4zLTI0LjEgMzguMi0xNC45IDEuMy0zMCAyLTQ1LjIgMi0xNS4xIDAtMzAuMi0uNy00NS0xLjktOC4zLTExLjktMTYuNC0yNC42LTI0LjItMzgtNy42LTEzLjEtMTQuNS0yNi40LTIwLjgtMzkuOCA2LjItMTMuNCAxMy4yLTI2LjggMjAuNy0zOS45IDcuOC0xMy41IDE1LjgtMjYuMyAyNC4xLTM4LjIgMTQuOS0xLjMgMzAtMiA0NS4yLTIgMTUuMSAwIDMwLjIuNyA0NSAxLjkgOC4zIDExLjkgMTYuNCAyNC42IDI0LjIgMzggNy42IDEzLjEgMTQuNSAyNi40IDIwLjggMzkuOC02LjMgMTMuNC0xMy4yIDI2LjgtMjAuNyAzOS45em0zMi4zLTEzYzUuNCAxMy40IDEwIDI2LjggMTMuOCAzOS44LTEzLjEgMy4yLTI2LjkgNS45LTQxLjIgOCA0LjktNy43IDkuOC0xNS42IDE0LjQtMjMuNyA0LjYtOCA4LjktMTYuMSAxMy0yNC4xek00MjEuMiA0MzBjLTkuMy05LjYtMTguNi0yMC4zLTI3LjgtMzIgOSAuNCAxOC4yLjcgMjcuNS43IDkuNCAwIDE4LjctLjIgMjcuOC0uNy05IDExLjctMTguMyAyMi40LTI3LjUgMzJ6bS03NC40LTU4LjljLTE0LjItMi4xLTI3LjktNC43LTQxLTcuOSAzLjctMTIuOSA4LjMtMjYuMiAxMy41LTM5LjUgNC4xIDggOC40IDE2IDEzLjEgMjQgNC43IDggOS41IDE1LjggMTQuNCAyMy40ek00MjAuNyAxNjNjOS4zIDkuNiAxOC42IDIwLjMgMjcuOCAzMi05LS40LTE4LjItLjctMjcuNS0uNy05LjQgMC0xOC43LjItMjcuOC43IDktMTEuNyAxOC4zLTIyLjQgMjcuNS0zMnptLTc0IDU4LjljLTQuOSA3LjctOS44IDE1LjYtMTQuNCAyMy43LTQuNiA4LTguOSAxNi0xMyAyNC01LjQtMTMuNC0xMC0yNi44LTEzLjgtMzkuOCAxMy4xLTMuMSAyNi45LTUuOCA0MS4yLTcuOXptLTkwLjUgMTI1LjJjLTM1LjQtMTUuMS01OC4zLTM0LjktNTguMy01MC42IDAtMTUuNyAyMi45LTM1LjYgNTguMy01MC42IDguNi0zLjcgMTgtNyAyNy43LTEwLjEgNS43IDE5LjYgMTMuMiA0MCAyMi41IDYwLjktOS4yIDIwLjgtMTYuNiA0MS4xLTIyLjIgNjAuNi05LjktMy4xLTE5LjMtNi41LTI4LTEwLjJ6TTMxMCA0OTBjLTEzLjYtNy44LTE5LjUtMzcuNS0xNC45LTc1LjcgMS4xLTkuNCAyLjktMTkuMyA1LjEtMjkuNCAxOS42IDQuOCA0MSA4LjUgNjMuNSAxMC45IDEzLjUgMTguNSAyNy41IDM1LjMgNDEuNiA1MC0zMi42IDMwLjMtNjMuMiA0Ni45LTg0IDQ2LjktNC41LS4xLTguMy0xLTExLjMtMi43em0yMzcuMi03Ni4yYzQuNyAzOC4yLTEuMSA2Ny45LTE0LjYgNzUuOC0zIDEuOC02LjkgMi42LTExLjUgMi42LTIwLjcgMC01MS40LTE2LjUtODQtNDYuNiAxNC0xNC43IDI4LTMxLjQgNDEuMy00OS45IDIyLjYtMi40IDQ0LTYuMSA2My42LTExIDIuMyAxMC4xIDQuMSAxOS44IDUuMiAyOS4xem0zOC41LTY2LjdjLTguNiAzLjctMTggNy0yNy43IDEwLjEtNS43LTE5LjYtMTMuMi00MC0yMi41LTYwLjkgOS4yLTIwLjggMTYuNi00MS4xIDIyLjItNjAuNiA5LjkgMy4xIDE5LjMgNi41IDI4LjEgMTAuMiAzNS40IDE1LjEgNTguMyAzNC45IDU4LjMgNTAuNi0uMSAxNS43LTIzIDM1LjYtNTguNCA1MC42ek0zMjAuOCA3OC40eiIvPgogICAgPGNpcmNsZSBjeD0iNDIwLjkiIGN5PSIyOTYuNSIgcj0iNDUuNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-redo: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTE4LjQgMTAuNkMxNi41NSA4Ljk5IDE0LjE1IDggMTEuNSA4Yy00LjY1IDAtOC41OCAzLjAzLTkuOTYgNy4yMkwzLjkgMTZjMS4wNS0zLjE5IDQuMDUtNS41IDcuNi01LjUgMS45NSAwIDMuNzMuNzIgNS4xMiAxLjg4TDEzIDE2aDlWN2wtMy42IDMuNnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-refresh: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTkgMTMuNWMtMi40OSAwLTQuNS0yLjAxLTQuNS00LjVTNi41MSA0LjUgOSA0LjVjMS4yNCAwIDIuMzYuNTIgMy4xNyAxLjMzTDEwIDhoNVYzbC0xLjc2IDEuNzZDMTIuMTUgMy42OCAxMC42NiAzIDkgMyA1LjY5IDMgMy4wMSA1LjY5IDMuMDEgOVM1LjY5IDE1IDkgMTVjMi45NyAwIDUuNDMtMi4xNiA1LjktNWgtMS41MmMtLjQ2IDItMi4yNCAzLjUtNC4zOCAzLjV6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-regex: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiBmaWxsPSIjRkZGIj4KICAgIDxjaXJjbGUgY2xhc3M9InN0MiIgY3g9IjUuNSIgY3k9IjE0LjUiIHI9IjEuNSIvPgogICAgPHJlY3QgeD0iMTIiIHk9IjQiIGNsYXNzPSJzdDIiIHdpZHRoPSIxIiBoZWlnaHQ9IjgiLz4KICAgIDxyZWN0IHg9IjguNSIgeT0iNy41IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjg2NiAtMC41IDAuNSAwLjg2NiAtMi4zMjU1IDcuMzIxOSkiIGNsYXNzPSJzdDIiIHdpZHRoPSI4IiBoZWlnaHQ9IjEiLz4KICAgIDxyZWN0IHg9IjEyIiB5PSI0IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjUgLTAuODY2IDAuODY2IDAuNSAtMC42Nzc5IDE0LjgyNTIpIiBjbGFzcz0ic3QyIiB3aWR0aD0iMSIgaGVpZ2h0PSI4Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-run: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTggNXYxNGwxMS03eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-running: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMjU2IDhDMTE5IDggOCAxMTkgOCAyNTZzMTExIDI0OCAyNDggMjQ4IDI0OC0xMTEgMjQ4LTI0OFMzOTMgOCAyNTYgOHptOTYgMzI4YzAgOC44LTcuMiAxNi0xNiAxNkgxNzZjLTguOCAwLTE2LTcuMi0xNi0xNlYxNzZjMC04LjggNy4yLTE2IDE2LTE2aDE2MGM4LjggMCAxNiA3LjIgMTYgMTZ2MTYweiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-save: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE3IDNINWMtMS4xMSAwLTIgLjktMiAydjE0YzAgMS4xLjg5IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjdsLTQtNHptLTUgMTZjLTEuNjYgMC0zLTEuMzQtMy0zczEuMzQtMyAzLTMgMyAxLjM0IDMgMy0xLjM0IDMtMyAzem0zLTEwSDVWNWgxMHY0eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-search: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjEsMTAuOWgtMC43bC0wLjItMC4yYzAuOC0wLjksMS4zLTIuMiwxLjMtMy41YzAtMy0yLjQtNS40LTUuNC01LjRTMS44LDQuMiwxLjgsNy4xczIuNCw1LjQsNS40LDUuNCBjMS4zLDAsMi41LTAuNSwzLjUtMS4zbDAuMiwwLjJ2MC43bDQuMSw0LjFsMS4yLTEuMkwxMi4xLDEwLjl6IE03LjEsMTAuOWMtMi4xLDAtMy43LTEuNy0zLjctMy43czEuNy0zLjcsMy43LTMuN3MzLjcsMS43LDMuNywzLjcgUzkuMiwxMC45LDcuMSwxMC45eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-settings: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuNDMgMTIuOThjLjA0LS4zMi4wNy0uNjQuMDctLjk4cy0uMDMtLjY2LS4wNy0uOThsMi4xMS0xLjY1Yy4xOS0uMTUuMjQtLjQyLjEyLS42NGwtMi0zLjQ2Yy0uMTItLjIyLS4zOS0uMy0uNjEtLjIybC0yLjQ5IDFjLS41Mi0uNC0xLjA4LS43My0xLjY5LS45OGwtLjM4LTIuNjVBLjQ4OC40ODggMCAwMDE0IDJoLTRjLS4yNSAwLS40Ni4xOC0uNDkuNDJsLS4zOCAyLjY1Yy0uNjEuMjUtMS4xNy41OS0xLjY5Ljk4bC0yLjQ5LTFjLS4yMy0uMDktLjQ5IDAtLjYxLjIybC0yIDMuNDZjLS4xMy4yMi0uMDcuNDkuMTIuNjRsMi4xMSAxLjY1Yy0uMDQuMzItLjA3LjY1LS4wNy45OHMuMDMuNjYuMDcuOThsLTIuMTEgMS42NWMtLjE5LjE1LS4yNC40Mi0uMTIuNjRsMiAzLjQ2Yy4xMi4yMi4zOS4zLjYxLjIybDIuNDktMWMuNTIuNCAxLjA4LjczIDEuNjkuOThsLjM4IDIuNjVjLjAzLjI0LjI0LjQyLjQ5LjQyaDRjLjI1IDAgLjQ2LS4xOC40OS0uNDJsLjM4LTIuNjVjLjYxLS4yNSAxLjE3LS41OSAxLjY5LS45OGwyLjQ5IDFjLjIzLjA5LjQ5IDAgLjYxLS4yMmwyLTMuNDZjLjEyLS4yMi4wNy0uNDktLjEyLS42NGwtMi4xMS0xLjY1ek0xMiAxNS41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiLz4KPC9zdmc+Cg==);
  --jp-icon-spreadsheet: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNENBRjUwIiBkPSJNMi4yIDIuMnYxNy42aDE3LjZWMi4ySDIuMnptMTUuNCA3LjdoLTUuNVY0LjRoNS41djUuNXpNOS45IDQuNHY1LjVINC40VjQuNGg1LjV6bS01LjUgNy43aDUuNXY1LjVINC40di01LjV6bTcuNyA1LjV2LTUuNWg1LjV2NS41aC01LjV6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-stop: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik02IDZoMTJ2MTJINnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tab: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIxIDNIM2MtMS4xIDAtMiAuOS0yIDJ2MTRjMCAxLjEuOSAyIDIgMmgxOGMxLjEgMCAyLS45IDItMlY1YzAtMS4xLS45LTItMi0yem0wIDE2SDNWNWgxMHY0aDh2MTB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-table-rows: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMSw4SDNWNGgxOFY4eiBNMjEsMTBIM3Y0aDE4VjEweiBNMjEsMTZIM3Y0aDE4VjE2eiIvPgogICAgPC9nPgo8L3N2Zz4=);
  --jp-icon-tag: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjgiIGhlaWdodD0iMjgiIHZpZXdCb3g9IjAgMCA0MyAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTI4LjgzMzIgMTIuMzM0TDMyLjk5OTggMTYuNTAwN0wzNy4xNjY1IDEyLjMzNEgyOC44MzMyWiIvPgoJCTxwYXRoIGQ9Ik0xNi4yMDk1IDIxLjYxMDRDMTUuNjg3MyAyMi4xMjk5IDE0Ljg0NDMgMjIuMTI5OSAxNC4zMjQ4IDIxLjYxMDRMNi45ODI5IDE0LjcyNDVDNi41NzI0IDE0LjMzOTQgNi4wODMxMyAxMy42MDk4IDYuMDQ3ODYgMTMuMDQ4MkM1Ljk1MzQ3IDExLjUyODggNi4wMjAwMiA4LjYxOTQ0IDYuMDY2MjEgNy4wNzY5NUM2LjA4MjgxIDYuNTE0NzcgNi41NTU0OCA2LjA0MzQ3IDcuMTE4MDQgNi4wMzA1NUM5LjA4ODYzIDUuOTg0NzMgMTMuMjYzOCA1LjkzNTc5IDEzLjY1MTggNi4zMjQyNUwyMS43MzY5IDEzLjYzOUMyMi4yNTYgMTQuMTU4NSAyMS43ODUxIDE1LjQ3MjQgMjEuMjYyIDE1Ljk5NDZMMTYuMjA5NSAyMS42MTA0Wk05Ljc3NTg1IDguMjY1QzkuMzM1NTEgNy44MjU2NiA4LjYyMzUxIDcuODI1NjYgOC4xODI4IDguMjY1QzcuNzQzNDYgOC43MDU3MSA3Ljc0MzQ2IDkuNDE3MzMgOC4xODI4IDkuODU2NjdDOC42MjM4MiAxMC4yOTY0IDkuMzM1ODIgMTAuMjk2NCA5Ljc3NTg1IDkuODU2NjdDMTAuMjE1NiA5LjQxNzMzIDEwLjIxNTYgOC43MDUzMyA5Ljc3NTg1IDguMjY1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-terminal: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0IiA+CiAgICA8cmVjdCBjbGFzcz0ianAtaWNvbjIganAtaWNvbi1zZWxlY3RhYmxlIiB3aWR0aD0iMjAiIGhlaWdodD0iMjAiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMikiIGZpbGw9IiMzMzMzMzMiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uLWFjY2VudDIganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGQ9Ik01LjA1NjY0IDguNzYxNzJDNS4wNTY2NCA4LjU5NzY2IDUuMDMxMjUgOC40NTMxMiA0Ljk4MDQ3IDguMzI4MTJDNC45MzM1OSA4LjE5OTIyIDQuODU1NDcgOC4wODIwMyA0Ljc0NjA5IDcuOTc2NTZDNC42NDA2MiA3Ljg3MTA5IDQuNSA3Ljc3NTM5IDQuMzI0MjIgNy42ODk0NUM0LjE1MjM0IDcuNTk5NjEgMy45NDMzNiA3LjUxMTcyIDMuNjk3MjcgNy40MjU3OEMzLjMwMjczIDcuMjg1MTYgMi45NDMzNiA3LjEzNjcyIDIuNjE5MTQgNi45ODA0N0MyLjI5NDkyIDYuODI0MjIgMi4wMTc1OCA2LjY0MjU4IDEuNzg3MTEgNi40MzU1NUMxLjU2MDU1IDYuMjI4NTIgMS4zODQ3NyA1Ljk4ODI4IDEuMjU5NzcgNS43MTQ4NEMxLjEzNDc3IDUuNDM3NSAxLjA3MjI3IDUuMTA5MzggMS4wNzIyNyA0LjczMDQ3QzEuMDcyMjcgNC4zOTg0NCAxLjEyODkxIDQuMDk1NyAxLjI0MjE5IDMuODIyMjdDMS4zNTU0NyAzLjU0NDkyIDEuNTE1NjIgMy4zMDQ2OSAxLjcyMjY2IDMuMTAxNTZDMS45Mjk2OSAyLjg5ODQ0IDIuMTc5NjkgMi43MzQzNyAyLjQ3MjY2IDIuNjA5MzhDMi43NjU2MiAyLjQ4NDM4IDMuMDkxOCAyLjQwNDMgMy40NTExNyAyLjM2OTE0VjEuMTA5MzhINC4zODg2N1YyLjM4MDg2QzQuNzQwMjMgMi40Mjc3MyA1LjA1NjY0IDIuNTIzNDQgNS4zMzc4OSAyLjY2Nzk3QzUuNjE5MTQgMi44MTI1IDUuODU3NDIgMy4wMDE5NSA2LjA1MjczIDMuMjM2MzNDNi4yNTE5NSAzLjQ2NjggNi40MDQzIDMuNzQwMjMgNi41MDk3NyA0LjA1NjY0QzYuNjE5MTQgNC4zNjkxNCA2LjY3MzgzIDQuNzIwNyA2LjY3MzgzIDUuMTExMzNINS4wNDQ5MkM1LjA0NDkyIDQuNjM4NjcgNC45Mzc1IDQuMjgxMjUgNC43MjI2NiA0LjAzOTA2QzQuNTA3ODEgMy43OTI5NyA0LjIxNjggMy42Njk5MiAzLjg0OTYxIDMuNjY5OTJDMy42NTAzOSAzLjY2OTkyIDMuNDc2NTYgMy42OTcyNyAzLjMyODEyIDMuNzUxOTVDMy4xODM1OSAzLjgwMjczIDMuMDY0NDUgMy44NzY5NSAyLjk3MDcgMy45NzQ2MUMyLjg3Njk1IDQuMDY4MzYgMi44MDY2NCA0LjE3OTY5IDIuNzU5NzcgNC4zMDg1OUMyLjcxNjggNC40Mzc1IDIuNjk1MzEgNC41NzgxMiAyLjY5NTMxIDQuNzMwNDdDMi42OTUzMSA0Ljg4MjgxIDIuNzE2OCA1LjAxOTUzIDIuNzU5NzcgNS4xNDA2MkMyLjgwNjY0IDUuMjU3ODEgMi44ODI4MSA1LjM2NzE5IDIuOTg4MjggNS40Njg3NUMzLjA5NzY2IDUuNTcwMzEgMy4yNDAyMyA1LjY2Nzk3IDMuNDE2MDIgNS43NjE3MkMzLjU5MTggNS44NTE1NiAzLjgxMDU1IDUuOTQzMzYgNC4wNzIyNyA2LjAzNzExQzQuNDY2OCA2LjE4NTU1IDQuODI0MjIgNi4zMzk4NCA1LjE0NDUzIDYuNUM1LjQ2NDg0IDYuNjU2MjUgNS43MzgyOCA2LjgzOTg0IDUuOTY0ODQgNy4wNTA3OEM2LjE5NTMxIDcuMjU3ODEgNi4zNzEwOSA3LjUgNi40OTIxOSA3Ljc3NzM0QzYuNjE3MTkgOC4wNTA3OCA2LjY3OTY5IDguMzc1IDYuNjc5NjkgOC43NUM2LjY3OTY5IDkuMDkzNzUgNi42MjMwNSA5LjQwNDMgNi41MDk3NyA5LjY4MTY0QzYuMzk2NDggOS45NTUwOCA2LjIzNDM4IDEwLjE5MTQgNi4wMjM0NCAxMC4zOTA2QzUuODEyNSAxMC41ODk4IDUuNTU4NTkgMTAuNzUgNS4yNjE3MiAxMC44NzExQzQuOTY0ODQgMTAuOTg4MyA0LjYzMjgxIDExLjA2NDUgNC4yNjU2MiAxMS4wOTk2VjEyLjI0OEgzLjMzMzk4VjExLjA5OTZDMy4wMDE5NSAxMS4wNjg0IDIuNjc5NjkgMTAuOTk2MSAyLjM2NzE5IDEwLjg4MjhDMi4wNTQ2OSAxMC43NjU2IDEuNzc3MzQgMTAuNTk3NyAxLjUzNTE2IDEwLjM3ODlDMS4yOTY4OCAxMC4xNjAyIDEuMTA1NDcgOS44ODQ3NyAwLjk2MDkzOCA5LjU1MjczQzAuODE2NDA2IDkuMjE2OCAwLjc0NDE0MSA4LjgxNDQ1IDAuNzQ0MTQxIDguMzQ1N0gyLjM3ODkxQzIuMzc4OTEgOC42MjY5NSAyLjQxOTkyIDguODYzMjggMi41MDE5NSA5LjA1NDY5QzIuNTgzOTggOS4yNDIxOSAyLjY4OTQ1IDkuMzkyNTggMi44MTgzNiA5LjUwNTg2QzIuOTUxMTcgOS42MTUyMyAzLjEwMTU2IDkuNjkzMzYgMy4yNjk1MyA5Ljc0MDIzQzMuNDM3NSA5Ljc4NzExIDMuNjA5MzggOS44MTA1NSAzLjc4NTE2IDkuODEwNTVDNC4yMDMxMiA5LjgxMDU1IDQuNTE5NTMgOS43MTI4OSA0LjczNDM4IDkuNTE3NThDNC45NDkyMiA5LjMyMjI3IDUuMDU2NjQgOS4wNzAzMSA1LjA1NjY0IDguNzYxNzJaTTEzLjQxOCAxMi4yNzE1SDguMDc0MjJWMTFIMTMuNDE4VjEyLjI3MTVaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzLjk1MjY0IDYpIiBmaWxsPSJ3aGl0ZSIvPgo8L3N2Zz4K);
  --jp-icon-text-editor: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTUgMTVIM3YyaDEydi0yem0wLThIM3YyaDEyVjd6TTMgMTNoMTh2LTJIM3Yyem0wIDhoMTh2LTJIM3Yyek0zIDN2MmgxOFYzSDN6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-toc: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik03LDVIMjFWN0g3VjVNNywxM1YxMUgyMVYxM0g3TTQsNC41QTEuNSwxLjUgMCAwLDEgNS41LDZBMS41LDEuNSAwIDAsMSA0LDcuNUExLjUsMS41IDAgMCwxIDIuNSw2QTEuNSwxLjUgMCAwLDEgNCw0LjVNNCwxMC41QTEuNSwxLjUgMCAwLDEgNS41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMy41QTEuNSwxLjUgMCAwLDEgMi41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMC41TTcsMTlWMTdIMjFWMTlIN000LDE2LjVBMS41LDEuNSAwIDAsMSA1LjUsMThBMS41LDEuNSAwIDAsMSA0LDE5LjVBMS41LDEuNSAwIDAsMSAyLjUsMThBMS41LDEuNSAwIDAsMSA0LDE2LjVaIiAvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tree-view: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMiAxMVYzaC03djNIOVYzSDJ2OGg3VjhoMnYxMGg0djNoN3YtOGgtN3YzaC0yVjhoMnYzeiIvPgogICAgPC9nPgo8L3N2Zz4=);
  --jp-icon-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMiAxNy4xODQ0IDIuOTY5NjggMTQuMzAzMiAxLjg2MDk0IDExLjQ0MDlaIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiMzMzMzMzMiIHN0cm9rZT0iIzMzMzMzMyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOCA5Ljg2NzE5KSIgZD0iTTIuODYwMTUgNC44NjUzNUwwLjcyNjU0OSAyLjk5OTU5TDAgMy42MzA0NUwyLjg2MDE1IDYuMTMxNTdMOCAwLjYzMDg3Mkw3LjI3ODU3IDBMMi44NjAxNSA0Ljg2NTM1WiIvPgo8L3N2Zz4K);
  --jp-icon-undo: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjUgOGMtMi42NSAwLTUuMDUuOTktNi45IDIuNkwyIDd2OWg5bC0zLjYyLTMuNjJjMS4zOS0xLjE2IDMuMTYtMS44OCA1LjEyLTEuODggMy41NCAwIDYuNTUgMi4zMSA3LjYgNS41bDIuMzctLjc4QzIxLjA4IDExLjAzIDE3LjE1IDggMTIuNSA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-vega: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbjEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjEyMTIxIj4KICAgIDxwYXRoIGQ9Ik0xMC42IDUuNGwyLjItMy4ySDIuMnY3LjNsNC02LjZ6Ii8+CiAgICA8cGF0aCBkPSJNMTUuOCAyLjJsLTQuNCA2LjZMNyA2LjNsLTQuOCA4djUuNWgxNy42VjIuMmgtNHptLTcgMTUuNEg1LjV2LTQuNGgzLjN2NC40em00LjQgMEg5LjhWOS44aDMuNHY3Ljh6bTQuNCAwaC0zLjRWNi41aDMuNHYxMS4xeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-yaml: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1jb250cmFzdDIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjRDgxQjYwIj4KICAgIDxwYXRoIGQ9Ik03LjIgMTguNnYtNS40TDMgNS42aDMuM2wxLjQgMy4xYy4zLjkuNiAxLjYgMSAyLjUuMy0uOC42LTEuNiAxLTIuNWwxLjQtMy4xaDMuNGwtNC40IDcuNnY1LjVsLTIuOS0uMXoiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxNi41IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxMSIgcj0iMi4xIi8+CiAgPC9nPgo8L3N2Zz4K);
}

/* Icon CSS class declarations */

.jp-AddIcon {
  background-image: var(--jp-icon-add);
}
.jp-BugIcon {
  background-image: var(--jp-icon-bug);
}
.jp-BuildIcon {
  background-image: var(--jp-icon-build);
}
.jp-CaretDownEmptyIcon {
  background-image: var(--jp-icon-caret-down-empty);
}
.jp-CaretDownEmptyThinIcon {
  background-image: var(--jp-icon-caret-down-empty-thin);
}
.jp-CaretDownIcon {
  background-image: var(--jp-icon-caret-down);
}
.jp-CaretLeftIcon {
  background-image: var(--jp-icon-caret-left);
}
.jp-CaretRightIcon {
  background-image: var(--jp-icon-caret-right);
}
.jp-CaretUpEmptyThinIcon {
  background-image: var(--jp-icon-caret-up-empty-thin);
}
.jp-CaretUpIcon {
  background-image: var(--jp-icon-caret-up);
}
.jp-CaseSensitiveIcon {
  background-image: var(--jp-icon-case-sensitive);
}
.jp-CheckIcon {
  background-image: var(--jp-icon-check);
}
.jp-CircleEmptyIcon {
  background-image: var(--jp-icon-circle-empty);
}
.jp-CircleIcon {
  background-image: var(--jp-icon-circle);
}
.jp-ClearIcon {
  background-image: var(--jp-icon-clear);
}
.jp-CloseIcon {
  background-image: var(--jp-icon-close);
}
.jp-CodeIcon {
  background-image: var(--jp-icon-code);
}
.jp-ConsoleIcon {
  background-image: var(--jp-icon-console);
}
.jp-CopyIcon {
  background-image: var(--jp-icon-copy);
}
.jp-CopyrightIcon {
  background-image: var(--jp-icon-copyright);
}
.jp-CutIcon {
  background-image: var(--jp-icon-cut);
}
.jp-DownloadIcon {
  background-image: var(--jp-icon-download);
}
.jp-EditIcon {
  background-image: var(--jp-icon-edit);
}
.jp-EllipsesIcon {
  background-image: var(--jp-icon-ellipses);
}
.jp-ExtensionIcon {
  background-image: var(--jp-icon-extension);
}
.jp-FastForwardIcon {
  background-image: var(--jp-icon-fast-forward);
}
.jp-FileIcon {
  background-image: var(--jp-icon-file);
}
.jp-FileUploadIcon {
  background-image: var(--jp-icon-file-upload);
}
.jp-FilterListIcon {
  background-image: var(--jp-icon-filter-list);
}
.jp-FolderIcon {
  background-image: var(--jp-icon-folder);
}
.jp-Html5Icon {
  background-image: var(--jp-icon-html5);
}
.jp-ImageIcon {
  background-image: var(--jp-icon-image);
}
.jp-InspectorIcon {
  background-image: var(--jp-icon-inspector);
}
.jp-JsonIcon {
  background-image: var(--jp-icon-json);
}
.jp-JuliaIcon {
  background-image: var(--jp-icon-julia);
}
.jp-JupyterFaviconIcon {
  background-image: var(--jp-icon-jupyter-favicon);
}
.jp-JupyterIcon {
  background-image: var(--jp-icon-jupyter);
}
.jp-JupyterlabWordmarkIcon {
  background-image: var(--jp-icon-jupyterlab-wordmark);
}
.jp-KernelIcon {
  background-image: var(--jp-icon-kernel);
}
.jp-KeyboardIcon {
  background-image: var(--jp-icon-keyboard);
}
.jp-LauncherIcon {
  background-image: var(--jp-icon-launcher);
}
.jp-LineFormIcon {
  background-image: var(--jp-icon-line-form);
}
.jp-LinkIcon {
  background-image: var(--jp-icon-link);
}
.jp-ListIcon {
  background-image: var(--jp-icon-list);
}
.jp-ListingsInfoIcon {
  background-image: var(--jp-icon-listings-info);
}
.jp-MarkdownIcon {
  background-image: var(--jp-icon-markdown);
}
.jp-NewFolderIcon {
  background-image: var(--jp-icon-new-folder);
}
.jp-NotTrustedIcon {
  background-image: var(--jp-icon-not-trusted);
}
.jp-NotebookIcon {
  background-image: var(--jp-icon-notebook);
}
.jp-NumberingIcon {
  background-image: var(--jp-icon-numbering);
}
.jp-OfflineBoltIcon {
  background-image: var(--jp-icon-offline-bolt);
}
.jp-PaletteIcon {
  background-image: var(--jp-icon-palette);
}
.jp-PasteIcon {
  background-image: var(--jp-icon-paste);
}
.jp-PdfIcon {
  background-image: var(--jp-icon-pdf);
}
.jp-PythonIcon {
  background-image: var(--jp-icon-python);
}
.jp-RKernelIcon {
  background-image: var(--jp-icon-r-kernel);
}
.jp-ReactIcon {
  background-image: var(--jp-icon-react);
}
.jp-RedoIcon {
  background-image: var(--jp-icon-redo);
}
.jp-RefreshIcon {
  background-image: var(--jp-icon-refresh);
}
.jp-RegexIcon {
  background-image: var(--jp-icon-regex);
}
.jp-RunIcon {
  background-image: var(--jp-icon-run);
}
.jp-RunningIcon {
  background-image: var(--jp-icon-running);
}
.jp-SaveIcon {
  background-image: var(--jp-icon-save);
}
.jp-SearchIcon {
  background-image: var(--jp-icon-search);
}
.jp-SettingsIcon {
  background-image: var(--jp-icon-settings);
}
.jp-SpreadsheetIcon {
  background-image: var(--jp-icon-spreadsheet);
}
.jp-StopIcon {
  background-image: var(--jp-icon-stop);
}
.jp-TabIcon {
  background-image: var(--jp-icon-tab);
}
.jp-TableRowsIcon {
  background-image: var(--jp-icon-table-rows);
}
.jp-TagIcon {
  background-image: var(--jp-icon-tag);
}
.jp-TerminalIcon {
  background-image: var(--jp-icon-terminal);
}
.jp-TextEditorIcon {
  background-image: var(--jp-icon-text-editor);
}
.jp-TocIcon {
  background-image: var(--jp-icon-toc);
}
.jp-TreeViewIcon {
  background-image: var(--jp-icon-tree-view);
}
.jp-TrustedIcon {
  background-image: var(--jp-icon-trusted);
}
.jp-UndoIcon {
  background-image: var(--jp-icon-undo);
}
.jp-VegaIcon {
  background-image: var(--jp-icon-vega);
}
.jp-YamlIcon {
  background-image: var(--jp-icon-yaml);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

.jp-Icon,
.jp-MaterialIcon {
  background-position: center;
  background-repeat: no-repeat;
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-cover {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/**
 * (DEPRECATED) Support for specific CSS icon sizes
 */

.jp-Icon-16 {
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-18 {
  background-size: 18px;
  min-width: 18px;
  min-height: 18px;
}

.jp-Icon-20 {
  background-size: 20px;
  min-width: 20px;
  min-height: 20px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for icons as inline SVG HTMLElements
 */

/* recolor the primary elements of an icon */
.jp-icon0[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon1[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon2[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon3[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}
/* recolor the accent elements of an icon */
.jp-icon-accent0[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-accent1[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-accent2[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-accent3[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-accent4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-accent0[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-accent1[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-accent2[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-accent3[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-accent4[stroke] {
  stroke: var(--jp-layout-color4);
}
/* set the color of an icon to transparent */
.jp-icon-none[fill] {
  fill: none;
}

.jp-icon-none[stroke] {
  stroke: none;
}
/* brand icon colors. Same for light and dark */
.jp-icon-brand0[fill] {
  fill: var(--jp-brand-color0);
}
.jp-icon-brand1[fill] {
  fill: var(--jp-brand-color1);
}
.jp-icon-brand2[fill] {
  fill: var(--jp-brand-color2);
}
.jp-icon-brand3[fill] {
  fill: var(--jp-brand-color3);
}
.jp-icon-brand4[fill] {
  fill: var(--jp-brand-color4);
}

.jp-icon-brand0[stroke] {
  stroke: var(--jp-brand-color0);
}
.jp-icon-brand1[stroke] {
  stroke: var(--jp-brand-color1);
}
.jp-icon-brand2[stroke] {
  stroke: var(--jp-brand-color2);
}
.jp-icon-brand3[stroke] {
  stroke: var(--jp-brand-color3);
}
.jp-icon-brand4[stroke] {
  stroke: var(--jp-brand-color4);
}
/* warn icon colors. Same for light and dark */
.jp-icon-warn0[fill] {
  fill: var(--jp-warn-color0);
}
.jp-icon-warn1[fill] {
  fill: var(--jp-warn-color1);
}
.jp-icon-warn2[fill] {
  fill: var(--jp-warn-color2);
}
.jp-icon-warn3[fill] {
  fill: var(--jp-warn-color3);
}

.jp-icon-warn0[stroke] {
  stroke: var(--jp-warn-color0);
}
.jp-icon-warn1[stroke] {
  stroke: var(--jp-warn-color1);
}
.jp-icon-warn2[stroke] {
  stroke: var(--jp-warn-color2);
}
.jp-icon-warn3[stroke] {
  stroke: var(--jp-warn-color3);
}
/* icon colors that contrast well with each other and most backgrounds */
.jp-icon-contrast0[fill] {
  fill: var(--jp-icon-contrast-color0);
}
.jp-icon-contrast1[fill] {
  fill: var(--jp-icon-contrast-color1);
}
.jp-icon-contrast2[fill] {
  fill: var(--jp-icon-contrast-color2);
}
.jp-icon-contrast3[fill] {
  fill: var(--jp-icon-contrast-color3);
}

.jp-icon-contrast0[stroke] {
  stroke: var(--jp-icon-contrast-color0);
}
.jp-icon-contrast1[stroke] {
  stroke: var(--jp-icon-contrast-color1);
}
.jp-icon-contrast2[stroke] {
  stroke: var(--jp-icon-contrast-color2);
}
.jp-icon-contrast3[stroke] {
  stroke: var(--jp-icon-contrast-color3);
}

/* CSS for icons in selected items in the settings editor */
#setting-editor .jp-PluginList .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}
#setting-editor
  .jp-PluginList
  .jp-mod-selected
  .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* CSS for icons in selected filebrowser listing items */
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* CSS for icons in selected tabs in the sidebar tab manager */
#tab-manager .lm-TabBar-tab.jp-mod-active .jp-icon-selectable[fill] {
  fill: #fff;
}

#tab-manager .lm-TabBar-tab.jp-mod-active .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}
#tab-manager
  .lm-TabBar-tab.jp-mod-active
  .jp-icon-hover
  :hover
  .jp-icon-selectable[fill] {
  fill: var(--jp-brand-color1);
}

#tab-manager
  .lm-TabBar-tab.jp-mod-active
  .jp-icon-hover
  :hover
  .jp-icon-selectable-inverse[fill] {
  fill: #fff;
}

/**
 * TODO: come up with non css-hack solution for showing the busy icon on top
 *  of the close icon
 * CSS for complex behavior of close icon of tabs in the sidebar tab manager
 */
#tab-manager
  .lm-TabBar-tab.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}
#tab-manager
  .lm-TabBar-tab.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

#tab-manager
  .lm-TabBar-tab.jp-mod-dirty.jp-mod-active
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: #fff;
}

/**
* TODO: come up with non css-hack solution for showing the busy icon on top
*  of the close icon
* CSS for complex behavior of close icon of tabs in the main area tabbar
*/
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

/* CSS for icons in status bar */
#jp-main-statusbar .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

#jp-main-statusbar .jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}
/* special handling for splash icon CSS. While the theme CSS reloads during
   splash, the splash icon can loose theming. To prevent that, we set a
   default for its color variable */
:root {
  --jp-warn-color0: var(--md-orange-700);
}

/* not sure what to do with this one, used in filebrowser listing */
.jp-DragIcon {
  margin-right: 4px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for alt colors for icons as inline SVG HTMLElements
 */

/* alt recolor the primary elements of an icon */
.jp-icon-alt .jp-icon0[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-alt .jp-icon1[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-alt .jp-icon2[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-alt .jp-icon3[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-alt .jp-icon4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-alt .jp-icon0[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-alt .jp-icon1[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-alt .jp-icon2[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-alt .jp-icon3[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-alt .jp-icon4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* alt recolor the accent elements of an icon */
.jp-icon-alt .jp-icon-accent0[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-alt .jp-icon-accent1[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-alt .jp-icon-accent2[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-alt .jp-icon-accent3[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-alt .jp-icon-accent4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-alt .jp-icon-accent0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-alt .jp-icon-accent1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-alt .jp-icon-accent2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-alt .jp-icon-accent3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-alt .jp-icon-accent4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-icon-hoverShow:not(:hover) svg {
  display: none !important;
}

/**
 * Support for hover colors for icons as inline SVG HTMLElements
 */

/**
 * regular colors
 */

/* recolor the primary elements of an icon */
.jp-icon-hover :hover .jp-icon0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-hover :hover .jp-icon1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-hover :hover .jp-icon2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-hover :hover .jp-icon3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-hover :hover .jp-icon4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-hover :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-hover :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-hover :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-hover :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-hover :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-hover :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-hover :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-hover :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-hover :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-hover :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-hover :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-hover :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-hover :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-hover :hover .jp-icon-none-hover[fill] {
  fill: none;
}

.jp-icon-hover :hover .jp-icon-none-hover[stroke] {
  stroke: none;
}

/**
 * inverse colors
 */

/* inverse recolor the primary elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* inverse recolor the accent elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-switch {
  display: flex;
  align-items: center;
  padding-left: 4px;
  padding-right: 4px;
  font-size: var(--jp-ui-font-size1);
  background-color: transparent;
  color: var(--jp-ui-font-color1);
  border: none;
  height: 20px;
}

.jp-switch:hover {
  background-color: var(--jp-layout-color2);
}

.jp-switch-label {
  margin-right: 5px;
}

.jp-switch-track {
  cursor: pointer;
  background-color: var(--jp-border-color1);
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 34px;
  height: 16px;
  width: 35px;
  position: relative;
}

.jp-switch-track::before {
  content: '';
  position: absolute;
  height: 10px;
  width: 10px;
  margin: 3px;
  left: 0px;
  background-color: var(--jp-ui-inverse-font-color1);
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 50%;
}

.jp-switch[aria-checked='true'] .jp-switch-track {
  background-color: var(--jp-warn-color0);
}

.jp-switch[aria-checked='true'] .jp-switch-track::before {
  /* track width (35) - margins (3 + 3) - thumb width (10) */
  left: 19px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* Sibling imports */

/* Override Blueprint's _reset.scss styles */
html {
  box-sizing: unset;
}

*,
*::before,
*::after {
  box-sizing: unset;
}

body {
  color: unset;
  font-family: var(--jp-ui-font-family);
}

p {
  margin-top: unset;
  margin-bottom: unset;
}

small {
  font-size: unset;
}

strong {
  font-weight: unset;
}

/* Override Blueprint's _typography.scss styles */
a {
  text-decoration: unset;
  color: unset;
}
a:hover {
  text-decoration: unset;
  color: unset;
}

/* Override Blueprint's _accessibility.scss styles */
:focus {
  outline: unset;
  outline-offset: unset;
  -moz-outline-radius: unset;
}

/* Styles for ui-components */
.jp-Button {
  border-radius: var(--jp-border-radius);
  padding: 0px 12px;
  font-size: var(--jp-ui-font-size1);
}

/* Use our own theme for hover styles */
button.jp-Button.bp3-button.bp3-minimal:hover {
  background-color: var(--jp-layout-color2);
}
.jp-Button.minimal {
  color: unset !important;
}

.jp-Button.jp-ToolbarButtonComponent {
  text-transform: none;
}

.jp-InputGroup input {
  box-sizing: border-box;
  border-radius: 0;
  background-color: transparent;
  color: var(--jp-ui-font-color0);
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.jp-InputGroup input:focus {
  box-shadow: inset 0 0 0 var(--jp-border-width)
      var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-InputGroup input::placeholder,
input::placeholder {
  color: var(--jp-ui-font-color3);
}

.jp-BPIcon {
  display: inline-block;
  vertical-align: middle;
  margin: auto;
}

/* Stop blueprint futzing with our icon fills */
.bp3-icon.jp-BPIcon > svg:not([fill]) {
  fill: var(--jp-inverse-layout-color3);
}

.jp-InputGroupAction {
  padding: 6px;
}

.jp-HTMLSelect.jp-DefaultStyle select {
  background-color: initial;
  border: none;
  border-radius: 0;
  box-shadow: none;
  color: var(--jp-ui-font-color0);
  display: block;
  font-size: var(--jp-ui-font-size1);
  height: 24px;
  line-height: 14px;
  padding: 0 25px 0 10px;
  text-align: left;
  -moz-appearance: none;
  -webkit-appearance: none;
}

/* Use our own theme for hover and option styles */
.jp-HTMLSelect.jp-DefaultStyle select:hover,
.jp-HTMLSelect.jp-DefaultStyle select > option {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color0);
}
select {
  box-sizing: border-box;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapse {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-top: 1px solid var(--jp-border-color2);
  border-bottom: 1px solid var(--jp-border-color2);
}

.jp-Collapse-header {
  padding: 1px 12px;
  color: var(--jp-ui-font-color1);
  background-color: var(--jp-layout-color1);
  font-size: var(--jp-ui-font-size2);
}

.jp-Collapse-header:hover {
  background-color: var(--jp-layout-color2);
}

.jp-Collapse-contents {
  padding: 0px 12px 0px 12px;
  background-color: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-commandpalette-search-height: 28px;
}

/*-----------------------------------------------------------------------------
| Overall styles
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  padding-bottom: 0px;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Modal variant
|----------------------------------------------------------------------------*/

.jp-ModalCommandPalette {
  position: absolute;
  z-index: 10000;
  top: 38px;
  left: 30%;
  margin: 0;
  padding: 4px;
  width: 40%;
  box-shadow: var(--jp-elevation-z4);
  border-radius: 4px;
  background: var(--jp-layout-color0);
}

.jp-ModalCommandPalette .lm-CommandPalette {
  max-height: 40vh;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-close-icon::after {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-header {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-item {
  margin-left: 4px;
  margin-right: 4px;
}

.jp-ModalCommandPalette
  .lm-CommandPalette
  .lm-CommandPalette-item.lm-mod-disabled {
  display: none;
}

/*-----------------------------------------------------------------------------
| Search
|----------------------------------------------------------------------------*/

.lm-CommandPalette-search {
  padding: 4px;
  background-color: var(--jp-layout-color1);
  z-index: 2;
}

.lm-CommandPalette-wrapper {
  overflow: overlay;
  padding: 0px 9px;
  background-color: var(--jp-input-active-background);
  height: 30px;
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.lm-CommandPalette.lm-mod-focused .lm-CommandPalette-wrapper {
  box-shadow: inset 0 0 0 1px var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-SearchIconGroup {
  color: white;
  background-color: var(--jp-brand-color1);
  position: absolute;
  top: 4px;
  right: 4px;
  padding: 5px 5px 1px 5px;
}

.jp-SearchIconGroup svg {
  height: 20px;
  width: 20px;
}

.jp-SearchIconGroup .jp-icon3[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-input {
  background: transparent;
  width: calc(100% - 18px);
  float: left;
  border: none;
  outline: none;
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  line-height: var(--jp-private-commandpalette-search-height);
}

.lm-CommandPalette-input::-webkit-input-placeholder,
.lm-CommandPalette-input::-moz-placeholder,
.lm-CommandPalette-input:-ms-input-placeholder {
  color: var(--jp-ui-font-color2);
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Results
|----------------------------------------------------------------------------*/

.lm-CommandPalette-header:first-child {
  margin-top: 0px;
}

.lm-CommandPalette-header {
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin-top: 8px;
  padding: 8px 0 8px 12px;
  text-transform: uppercase;
}

.lm-CommandPalette-header.lm-mod-active {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-header > mark {
  background-color: transparent;
  font-weight: bold;
  color: var(--jp-ui-font-color1);
}

.lm-CommandPalette-item {
  padding: 4px 12px 4px 4px;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  font-weight: 400;
  display: flex;
}

.lm-CommandPalette-item.lm-mod-disabled {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item.lm-mod-active {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item.lm-mod-active .lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-inverse-font-color0);
}

.lm-CommandPalette-item.lm-mod-active .jp-icon-selectable[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-item.lm-mod-active .lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-inverse-font-color0);
}

.lm-CommandPalette-item.lm-mod-active:hover:not(.lm-mod-disabled) {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item:hover:not(.lm-mod-active):not(.lm-mod-disabled) {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-itemContent {
  overflow: hidden;
}

.lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.lm-CommandPalette-item.lm-mod-disabled mark {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item .lm-CommandPalette-itemIcon {
  margin: 0 4px 0 0;
  position: relative;
  width: 16px;
  top: 2px;
  flex: 0 0 auto;
}

.lm-CommandPalette-item.lm-mod-disabled .lm-CommandPalette-itemIcon {
  opacity: 0.6;
}

.lm-CommandPalette-item .lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemCaption {
  display: none;
}

.lm-CommandPalette-content {
  background-color: var(--jp-layout-color1);
}

.lm-CommandPalette-content:empty:after {
  content: 'No results';
  margin: auto;
  margin-top: 20px;
  width: 100px;
  display: block;
  font-size: var(--jp-ui-font-size2);
  font-family: var(--jp-ui-font-family);
  font-weight: lighter;
}

.lm-CommandPalette-emptyMessage {
  text-align: center;
  margin-top: 24px;
  line-height: 1.32;
  padding: 0px 8px;
  color: var(--jp-content-font-color3);
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Dialog {
  position: absolute;
  z-index: 10000;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  top: 0px;
  left: 0px;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-dialog-background);
}

.jp-Dialog-content {
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  background: var(--jp-layout-color1);
  padding: 24px;
  padding-bottom: 12px;
  min-width: 300px;
  min-height: 150px;
  max-width: 1000px;
  max-height: 500px;
  box-sizing: border-box;
  box-shadow: var(--jp-elevation-z20);
  word-wrap: break-word;
  border-radius: var(--jp-border-radius);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color1);
  resize: both;
}

.jp-Dialog-button {
  overflow: visible;
}

button.jp-Dialog-button:focus {
  outline: 1px solid var(--jp-brand-color1);
  outline-offset: 4px;
  -moz-outline-radius: 0px;
}

button.jp-Dialog-button:focus::-moz-focus-inner {
  border: 0;
}

button.jp-Dialog-close-button {
  padding: 0;
  height: 100%;
  min-width: unset;
  min-height: unset;
}

.jp-Dialog-header {
  display: flex;
  justify-content: space-between;
  flex: 0 0 auto;
  padding-bottom: 12px;
  font-size: var(--jp-ui-font-size3);
  font-weight: 400;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-body {
  display: flex;
  flex-direction: column;
  flex: 1 1 auto;
  font-size: var(--jp-ui-font-size1);
  background: var(--jp-layout-color1);
  overflow: auto;
}

.jp-Dialog-footer {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  flex: 0 0 auto;
  margin-left: -12px;
  margin-right: -12px;
  padding: 12px;
}

.jp-Dialog-title {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.jp-Dialog-body > .jp-select-wrapper {
  width: 100%;
}

.jp-Dialog-body > button {
  padding: 0px 16px;
}

.jp-Dialog-body > label {
  line-height: 1.4;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-button.jp-mod-styled:not(:last-child) {
  margin-right: 12px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-HoverBox {
  position: fixed;
}

.jp-HoverBox.jp-mod-outofview {
  display: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-IFrame {
  width: 100%;
  height: 100%;
}

.jp-IFrame > iframe {
  border: none;
}

/*
When drag events occur, `p-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-IFrame {
  position: relative;
}

body.lm-mod-override-cursor .jp-IFrame:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

.jp-Input-Boolean-Dialog {
  flex-direction: row-reverse;
  align-items: end;
  width: 100%;
}

.jp-Input-Boolean-Dialog > label {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MainAreaWidget > :focus {
  outline: none;
}

/**
 * google-material-color v1.2.6
 * https://github.com/danlevan/google-material-color
 */
:root {
  --md-red-50: #ffebee;
  --md-red-100: #ffcdd2;
  --md-red-200: #ef9a9a;
  --md-red-300: #e57373;
  --md-red-400: #ef5350;
  --md-red-500: #f44336;
  --md-red-600: #e53935;
  --md-red-700: #d32f2f;
  --md-red-800: #c62828;
  --md-red-900: #b71c1c;
  --md-red-A100: #ff8a80;
  --md-red-A200: #ff5252;
  --md-red-A400: #ff1744;
  --md-red-A700: #d50000;

  --md-pink-50: #fce4ec;
  --md-pink-100: #f8bbd0;
  --md-pink-200: #f48fb1;
  --md-pink-300: #f06292;
  --md-pink-400: #ec407a;
  --md-pink-500: #e91e63;
  --md-pink-600: #d81b60;
  --md-pink-700: #c2185b;
  --md-pink-800: #ad1457;
  --md-pink-900: #880e4f;
  --md-pink-A100: #ff80ab;
  --md-pink-A200: #ff4081;
  --md-pink-A400: #f50057;
  --md-pink-A700: #c51162;

  --md-purple-50: #f3e5f5;
  --md-purple-100: #e1bee7;
  --md-purple-200: #ce93d8;
  --md-purple-300: #ba68c8;
  --md-purple-400: #ab47bc;
  --md-purple-500: #9c27b0;
  --md-purple-600: #8e24aa;
  --md-purple-700: #7b1fa2;
  --md-purple-800: #6a1b9a;
  --md-purple-900: #4a148c;
  --md-purple-A100: #ea80fc;
  --md-purple-A200: #e040fb;
  --md-purple-A400: #d500f9;
  --md-purple-A700: #aa00ff;

  --md-deep-purple-50: #ede7f6;
  --md-deep-purple-100: #d1c4e9;
  --md-deep-purple-200: #b39ddb;
  --md-deep-purple-300: #9575cd;
  --md-deep-purple-400: #7e57c2;
  --md-deep-purple-500: #673ab7;
  --md-deep-purple-600: #5e35b1;
  --md-deep-purple-700: #512da8;
  --md-deep-purple-800: #4527a0;
  --md-deep-purple-900: #311b92;
  --md-deep-purple-A100: #b388ff;
  --md-deep-purple-A200: #7c4dff;
  --md-deep-purple-A400: #651fff;
  --md-deep-purple-A700: #6200ea;

  --md-indigo-50: #e8eaf6;
  --md-indigo-100: #c5cae9;
  --md-indigo-200: #9fa8da;
  --md-indigo-300: #7986cb;
  --md-indigo-400: #5c6bc0;
  --md-indigo-500: #3f51b5;
  --md-indigo-600: #3949ab;
  --md-indigo-700: #303f9f;
  --md-indigo-800: #283593;
  --md-indigo-900: #1a237e;
  --md-indigo-A100: #8c9eff;
  --md-indigo-A200: #536dfe;
  --md-indigo-A400: #3d5afe;
  --md-indigo-A700: #304ffe;

  --md-blue-50: #e3f2fd;
  --md-blue-100: #bbdefb;
  --md-blue-200: #90caf9;
  --md-blue-300: #64b5f6;
  --md-blue-400: #42a5f5;
  --md-blue-500: #2196f3;
  --md-blue-600: #1e88e5;
  --md-blue-700: #1976d2;
  --md-blue-800: #1565c0;
  --md-blue-900: #0d47a1;
  --md-blue-A100: #82b1ff;
  --md-blue-A200: #448aff;
  --md-blue-A400: #2979ff;
  --md-blue-A700: #2962ff;

  --md-light-blue-50: #e1f5fe;
  --md-light-blue-100: #b3e5fc;
  --md-light-blue-200: #81d4fa;
  --md-light-blue-300: #4fc3f7;
  --md-light-blue-400: #29b6f6;
  --md-light-blue-500: #03a9f4;
  --md-light-blue-600: #039be5;
  --md-light-blue-700: #0288d1;
  --md-light-blue-800: #0277bd;
  --md-light-blue-900: #01579b;
  --md-light-blue-A100: #80d8ff;
  --md-light-blue-A200: #40c4ff;
  --md-light-blue-A400: #00b0ff;
  --md-light-blue-A700: #0091ea;

  --md-cyan-50: #e0f7fa;
  --md-cyan-100: #b2ebf2;
  --md-cyan-200: #80deea;
  --md-cyan-300: #4dd0e1;
  --md-cyan-400: #26c6da;
  --md-cyan-500: #00bcd4;
  --md-cyan-600: #00acc1;
  --md-cyan-700: #0097a7;
  --md-cyan-800: #00838f;
  --md-cyan-900: #006064;
  --md-cyan-A100: #84ffff;
  --md-cyan-A200: #18ffff;
  --md-cyan-A400: #00e5ff;
  --md-cyan-A700: #00b8d4;

  --md-teal-50: #e0f2f1;
  --md-teal-100: #b2dfdb;
  --md-teal-200: #80cbc4;
  --md-teal-300: #4db6ac;
  --md-teal-400: #26a69a;
  --md-teal-500: #009688;
  --md-teal-600: #00897b;
  --md-teal-700: #00796b;
  --md-teal-800: #00695c;
  --md-teal-900: #004d40;
  --md-teal-A100: #a7ffeb;
  --md-teal-A200: #64ffda;
  --md-teal-A400: #1de9b6;
  --md-teal-A700: #00bfa5;

  --md-green-50: #e8f5e9;
  --md-green-100: #c8e6c9;
  --md-green-200: #a5d6a7;
  --md-green-300: #81c784;
  --md-green-400: #66bb6a;
  --md-green-500: #4caf50;
  --md-green-600: #43a047;
  --md-green-700: #388e3c;
  --md-green-800: #2e7d32;
  --md-green-900: #1b5e20;
  --md-green-A100: #b9f6ca;
  --md-green-A200: #69f0ae;
  --md-green-A400: #00e676;
  --md-green-A700: #00c853;

  --md-light-green-50: #f1f8e9;
  --md-light-green-100: #dcedc8;
  --md-light-green-200: #c5e1a5;
  --md-light-green-300: #aed581;
  --md-light-green-400: #9ccc65;
  --md-light-green-500: #8bc34a;
  --md-light-green-600: #7cb342;
  --md-light-green-700: #689f38;
  --md-light-green-800: #558b2f;
  --md-light-green-900: #33691e;
  --md-light-green-A100: #ccff90;
  --md-light-green-A200: #b2ff59;
  --md-light-green-A400: #76ff03;
  --md-light-green-A700: #64dd17;

  --md-lime-50: #f9fbe7;
  --md-lime-100: #f0f4c3;
  --md-lime-200: #e6ee9c;
  --md-lime-300: #dce775;
  --md-lime-400: #d4e157;
  --md-lime-500: #cddc39;
  --md-lime-600: #c0ca33;
  --md-lime-700: #afb42b;
  --md-lime-800: #9e9d24;
  --md-lime-900: #827717;
  --md-lime-A100: #f4ff81;
  --md-lime-A200: #eeff41;
  --md-lime-A400: #c6ff00;
  --md-lime-A700: #aeea00;

  --md-yellow-50: #fffde7;
  --md-yellow-100: #fff9c4;
  --md-yellow-200: #fff59d;
  --md-yellow-300: #fff176;
  --md-yellow-400: #ffee58;
  --md-yellow-500: #ffeb3b;
  --md-yellow-600: #fdd835;
  --md-yellow-700: #fbc02d;
  --md-yellow-800: #f9a825;
  --md-yellow-900: #f57f17;
  --md-yellow-A100: #ffff8d;
  --md-yellow-A200: #ffff00;
  --md-yellow-A400: #ffea00;
  --md-yellow-A700: #ffd600;

  --md-amber-50: #fff8e1;
  --md-amber-100: #ffecb3;
  --md-amber-200: #ffe082;
  --md-amber-300: #ffd54f;
  --md-amber-400: #ffca28;
  --md-amber-500: #ffc107;
  --md-amber-600: #ffb300;
  --md-amber-700: #ffa000;
  --md-amber-800: #ff8f00;
  --md-amber-900: #ff6f00;
  --md-amber-A100: #ffe57f;
  --md-amber-A200: #ffd740;
  --md-amber-A400: #ffc400;
  --md-amber-A700: #ffab00;

  --md-orange-50: #fff3e0;
  --md-orange-100: #ffe0b2;
  --md-orange-200: #ffcc80;
  --md-orange-300: #ffb74d;
  --md-orange-400: #ffa726;
  --md-orange-500: #ff9800;
  --md-orange-600: #fb8c00;
  --md-orange-700: #f57c00;
  --md-orange-800: #ef6c00;
  --md-orange-900: #e65100;
  --md-orange-A100: #ffd180;
  --md-orange-A200: #ffab40;
  --md-orange-A400: #ff9100;
  --md-orange-A700: #ff6d00;

  --md-deep-orange-50: #fbe9e7;
  --md-deep-orange-100: #ffccbc;
  --md-deep-orange-200: #ffab91;
  --md-deep-orange-300: #ff8a65;
  --md-deep-orange-400: #ff7043;
  --md-deep-orange-500: #ff5722;
  --md-deep-orange-600: #f4511e;
  --md-deep-orange-700: #e64a19;
  --md-deep-orange-800: #d84315;
  --md-deep-orange-900: #bf360c;
  --md-deep-orange-A100: #ff9e80;
  --md-deep-orange-A200: #ff6e40;
  --md-deep-orange-A400: #ff3d00;
  --md-deep-orange-A700: #dd2c00;

  --md-brown-50: #efebe9;
  --md-brown-100: #d7ccc8;
  --md-brown-200: #bcaaa4;
  --md-brown-300: #a1887f;
  --md-brown-400: #8d6e63;
  --md-brown-500: #795548;
  --md-brown-600: #6d4c41;
  --md-brown-700: #5d4037;
  --md-brown-800: #4e342e;
  --md-brown-900: #3e2723;

  --md-grey-50: #fafafa;
  --md-grey-100: #f5f5f5;
  --md-grey-200: #eeeeee;
  --md-grey-300: #e0e0e0;
  --md-grey-400: #bdbdbd;
  --md-grey-500: #9e9e9e;
  --md-grey-600: #757575;
  --md-grey-700: #616161;
  --md-grey-800: #424242;
  --md-grey-900: #212121;

  --md-blue-grey-50: #eceff1;
  --md-blue-grey-100: #cfd8dc;
  --md-blue-grey-200: #b0bec5;
  --md-blue-grey-300: #90a4ae;
  --md-blue-grey-400: #78909c;
  --md-blue-grey-500: #607d8b;
  --md-blue-grey-600: #546e7a;
  --md-blue-grey-700: #455a64;
  --md-blue-grey-800: #37474f;
  --md-blue-grey-900: #263238;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Spinner {
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 10;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-layout-color0);
  outline: none;
}

.jp-SpinnerContent {
  font-size: 10px;
  margin: 50px auto;
  text-indent: -9999em;
  width: 3em;
  height: 3em;
  border-radius: 50%;
  background: var(--jp-brand-color3);
  background: linear-gradient(
    to right,
    #f37626 10%,
    rgba(255, 255, 255, 0) 42%
  );
  position: relative;
  animation: load3 1s infinite linear, fadeIn 1s;
}

.jp-SpinnerContent:before {
  width: 50%;
  height: 50%;
  background: #f37626;
  border-radius: 100% 0 0 0;
  position: absolute;
  top: 0;
  left: 0;
  content: '';
}

.jp-SpinnerContent:after {
  background: var(--jp-layout-color0);
  width: 75%;
  height: 75%;
  border-radius: 50%;
  content: '';
  margin: auto;
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

@keyframes load3 {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

button.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: none;
  box-sizing: border-box;
  text-align: center;
  line-height: 32px;
  height: 32px;
  padding: 0px 12px;
  letter-spacing: 0.8px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input.jp-mod-styled {
  background: var(--jp-input-background);
  height: 28px;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color1);
  padding-left: 7px;
  padding-right: 7px;
  font-size: var(--jp-ui-font-size2);
  color: var(--jp-ui-font-color0);
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input[type='checkbox'].jp-mod-styled {
  appearance: checkbox;
  -webkit-appearance: checkbox;
  -moz-appearance: checkbox;
  height: auto;
}

input.jp-mod-styled:focus {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-FileDialog-Checkbox {
  margin-top: 35px;
  display: flex;
  flex-direction: row;
  align-items: end;
  width: 100%;
}

.jp-FileDialog-Checkbox > label {
  flex: 1 1 auto;
}

.jp-select-wrapper {
  display: flex;
  position: relative;
  flex-direction: column;
  padding: 1px;
  background-color: var(--jp-layout-color1);
  height: 28px;
  box-sizing: border-box;
  margin-bottom: 12px;
}

.jp-select-wrapper.jp-mod-focused select.jp-mod-styled {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-input-active-background);
}

select.jp-mod-styled:hover {
  background-color: var(--jp-layout-color1);
  cursor: pointer;
  color: var(--jp-ui-font-color0);
  background-color: var(--jp-input-hover-background);
  box-shadow: inset 0 0px 1px rgba(0, 0, 0, 0.5);
}

select.jp-mod-styled {
  flex: 1 1 auto;
  height: 32px;
  width: 100%;
  font-size: var(--jp-ui-font-size2);
  background: var(--jp-input-background);
  color: var(--jp-ui-font-color0);
  padding: 0 25px 0 8px;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toolbar-height: calc(
    28px + var(--jp-border-width)
  ); /* leave 28px for content */
}

.jp-Toolbar {
  color: var(--jp-ui-font-color1);
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: 2px;
  z-index: 1;
  overflow-x: auto;
}

/* Toolbar items */

.jp-Toolbar > .jp-Toolbar-item.jp-Toolbar-spacer {
  flex-grow: 1;
  flex-shrink: 1;
}

.jp-Toolbar-item.jp-Toolbar-kernelStatus {
  display: inline-block;
  width: 32px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: 16px;
}

.jp-Toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  display: flex;
  padding-left: 1px;
  padding-right: 1px;
  font-size: var(--jp-ui-font-size1);
  line-height: var(--jp-private-toolbar-height);
  height: 100%;
}

/* Toolbar buttons */

/* This is the div we use to wrap the react component into a Widget */
div.jp-ToolbarButton {
  color: transparent;
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0px;
  margin: 0px;
}

button.jp-ToolbarButtonComponent {
  background: var(--jp-layout-color1);
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0px 6px;
  margin: 0px;
  height: 24px;
  border-radius: var(--jp-border-radius);
  display: flex;
  align-items: center;
  text-align: center;
  font-size: 14px;
  min-width: unset;
  min-height: unset;
}

button.jp-ToolbarButtonComponent:disabled {
  opacity: 0.4;
}

button.jp-ToolbarButtonComponent span {
  padding: 0px;
  flex: 0 0 auto;
}

button.jp-ToolbarButtonComponent .jp-ToolbarButtonComponent-label {
  font-size: var(--jp-ui-font-size1);
  line-height: 100%;
  padding-left: 2px;
  color: var(--jp-ui-font-color1);
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar.jp-Toolbar-micro {
  padding: 0;
  min-height: 0;
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar {
  border: none;
  box-shadow: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ body.p-mod-override-cursor *, /* </DEPRECATED> */
body.lm-mod-override-cursor * {
  cursor: inherit !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-JSONEditor {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.jp-JSONEditor-host {
  flex: 1 1 auto;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0px;
  background: var(--jp-layout-color0);
  min-height: 50px;
  padding: 1px;
}

.jp-JSONEditor.jp-mod-error .jp-JSONEditor-host {
  border-color: red;
  outline-color: red;
}

.jp-JSONEditor-header {
  display: flex;
  flex: 1 0 auto;
  padding: 0 0 0 12px;
}

.jp-JSONEditor-header label {
  flex: 0 0 auto;
}

.jp-JSONEditor-commitButton {
  height: 16px;
  width: 16px;
  background-size: 18px;
  background-repeat: no-repeat;
  background-position: center;
}

.jp-JSONEditor-host.jp-mod-focused {
  background-color: var(--jp-input-active-background);
  border: 1px solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

.jp-Editor.jp-mod-dropTarget {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

/* BASICS */

.CodeMirror {
  /* Set height, width, borders, and global font properties here */
  font-family: monospace;
  height: 300px;
  color: black;
  direction: ltr;
}

/* PADDING */

.CodeMirror-lines {
  padding: 4px 0; /* Vertical padding around content */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  padding: 0 4px; /* Horizontal padding of content */
}

.CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  background-color: white; /* The little square between H and V scrollbars */
}

/* GUTTER */

.CodeMirror-gutters {
  border-right: 1px solid #ddd;
  background-color: #f7f7f7;
  white-space: nowrap;
}
.CodeMirror-linenumbers {}
.CodeMirror-linenumber {
  padding: 0 3px 0 5px;
  min-width: 20px;
  text-align: right;
  color: #999;
  white-space: nowrap;
}

.CodeMirror-guttermarker { color: black; }
.CodeMirror-guttermarker-subtle { color: #999; }

/* CURSOR */

.CodeMirror-cursor {
  border-left: 1px solid black;
  border-right: none;
  width: 0;
}
/* Shown when moving in bi-directional text */
.CodeMirror div.CodeMirror-secondarycursor {
  border-left: 1px solid silver;
}
.cm-fat-cursor .CodeMirror-cursor {
  width: auto;
  border: 0 !important;
  background: #7e7;
}
.cm-fat-cursor div.CodeMirror-cursors {
  z-index: 1;
}
.cm-fat-cursor-mark {
  background-color: rgba(20, 255, 20, 0.5);
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
}
.cm-animate-fat-cursor {
  width: auto;
  border: 0;
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
  background-color: #7e7;
}
@-moz-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@-webkit-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}

/* Can style cursor different in overwrite (non-insert) mode */
.CodeMirror-overwrite .CodeMirror-cursor {}

.cm-tab { display: inline-block; text-decoration: inherit; }

.CodeMirror-rulers {
  position: absolute;
  left: 0; right: 0; top: -50px; bottom: 0;
  overflow: hidden;
}
.CodeMirror-ruler {
  border-left: 1px solid #ccc;
  top: 0; bottom: 0;
  position: absolute;
}

/* DEFAULT THEME */

.cm-s-default .cm-header {color: blue;}
.cm-s-default .cm-quote {color: #090;}
.cm-negative {color: #d44;}
.cm-positive {color: #292;}
.cm-header, .cm-strong {font-weight: bold;}
.cm-em {font-style: italic;}
.cm-link {text-decoration: underline;}
.cm-strikethrough {text-decoration: line-through;}

.cm-s-default .cm-keyword {color: #708;}
.cm-s-default .cm-atom {color: #219;}
.cm-s-default .cm-number {color: #164;}
.cm-s-default .cm-def {color: #00f;}
.cm-s-default .cm-variable,
.cm-s-default .cm-punctuation,
.cm-s-default .cm-property,
.cm-s-default .cm-operator {}
.cm-s-default .cm-variable-2 {color: #05a;}
.cm-s-default .cm-variable-3, .cm-s-default .cm-type {color: #085;}
.cm-s-default .cm-comment {color: #a50;}
.cm-s-default .cm-string {color: #a11;}
.cm-s-default .cm-string-2 {color: #f50;}
.cm-s-default .cm-meta {color: #555;}
.cm-s-default .cm-qualifier {color: #555;}
.cm-s-default .cm-builtin {color: #30a;}
.cm-s-default .cm-bracket {color: #997;}
.cm-s-default .cm-tag {color: #170;}
.cm-s-default .cm-attribute {color: #00c;}
.cm-s-default .cm-hr {color: #999;}
.cm-s-default .cm-link {color: #00c;}

.cm-s-default .cm-error {color: #f00;}
.cm-invalidchar {color: #f00;}

.CodeMirror-composing { border-bottom: 2px solid; }

/* Default styles for common addons */

div.CodeMirror span.CodeMirror-matchingbracket {color: #0b0;}
div.CodeMirror span.CodeMirror-nonmatchingbracket {color: #a22;}
.CodeMirror-matchingtag { background: rgba(255, 150, 0, .3); }
.CodeMirror-activeline-background {background: #e8f2ff;}

/* STOP */

/* The rest of this file contains styles related to the mechanics of
   the editor. You probably shouldn't touch them. */

.CodeMirror {
  position: relative;
  overflow: hidden;
  background: white;
}

.CodeMirror-scroll {
  overflow: scroll !important; /* Things will break if this is overridden */
  /* 50px is the magic margin used to hide the element's real scrollbars */
  /* See overflow: hidden in .CodeMirror */
  margin-bottom: -50px; margin-right: -50px;
  padding-bottom: 50px;
  height: 100%;
  outline: none; /* Prevent dragging from highlighting the element */
  position: relative;
}
.CodeMirror-sizer {
  position: relative;
  border-right: 50px solid transparent;
}

/* The fake, visible scrollbars. Used to force redraw during scrolling
   before actual scrolling happens, thus preventing shaking and
   flickering artifacts. */
.CodeMirror-vscrollbar, .CodeMirror-hscrollbar, .CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  position: absolute;
  z-index: 6;
  display: none;
  outline: none;
}
.CodeMirror-vscrollbar {
  right: 0; top: 0;
  overflow-x: hidden;
  overflow-y: scroll;
}
.CodeMirror-hscrollbar {
  bottom: 0; left: 0;
  overflow-y: hidden;
  overflow-x: scroll;
}
.CodeMirror-scrollbar-filler {
  right: 0; bottom: 0;
}
.CodeMirror-gutter-filler {
  left: 0; bottom: 0;
}

.CodeMirror-gutters {
  position: absolute; left: 0; top: 0;
  min-height: 100%;
  z-index: 3;
}
.CodeMirror-gutter {
  white-space: normal;
  height: 100%;
  display: inline-block;
  vertical-align: top;
  margin-bottom: -50px;
}
.CodeMirror-gutter-wrapper {
  position: absolute;
  z-index: 4;
  background: none !important;
  border: none !important;
}
.CodeMirror-gutter-background {
  position: absolute;
  top: 0; bottom: 0;
  z-index: 4;
}
.CodeMirror-gutter-elt {
  position: absolute;
  cursor: default;
  z-index: 4;
}
.CodeMirror-gutter-wrapper ::selection { background-color: transparent }
.CodeMirror-gutter-wrapper ::-moz-selection { background-color: transparent }

.CodeMirror-lines {
  cursor: text;
  min-height: 1px; /* prevents collapsing before first draw */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  /* Reset some styles that the rest of the page might have set */
  -moz-border-radius: 0; -webkit-border-radius: 0; border-radius: 0;
  border-width: 0;
  background: transparent;
  font-family: inherit;
  font-size: inherit;
  margin: 0;
  white-space: pre;
  word-wrap: normal;
  line-height: inherit;
  color: inherit;
  z-index: 2;
  position: relative;
  overflow: visible;
  -webkit-tap-highlight-color: transparent;
  -webkit-font-variant-ligatures: contextual;
  font-variant-ligatures: contextual;
}
.CodeMirror-wrap pre.CodeMirror-line,
.CodeMirror-wrap pre.CodeMirror-line-like {
  word-wrap: break-word;
  white-space: pre-wrap;
  word-break: normal;
}

.CodeMirror-linebackground {
  position: absolute;
  left: 0; right: 0; top: 0; bottom: 0;
  z-index: 0;
}

.CodeMirror-linewidget {
  position: relative;
  z-index: 2;
  padding: 0.1px; /* Force widget margins to stay inside of the container */
}

.CodeMirror-widget {}

.CodeMirror-rtl pre { direction: rtl; }

.CodeMirror-code {
  outline: none;
}

/* Force content-box sizing for the elements where we expect it */
.CodeMirror-scroll,
.CodeMirror-sizer,
.CodeMirror-gutter,
.CodeMirror-gutters,
.CodeMirror-linenumber {
  -moz-box-sizing: content-box;
  box-sizing: content-box;
}

.CodeMirror-measure {
  position: absolute;
  width: 100%;
  height: 0;
  overflow: hidden;
  visibility: hidden;
}

.CodeMirror-cursor {
  position: absolute;
  pointer-events: none;
}
.CodeMirror-measure pre { position: static; }

div.CodeMirror-cursors {
  visibility: hidden;
  position: relative;
  z-index: 3;
}
div.CodeMirror-dragcursors {
  visibility: visible;
}

.CodeMirror-focused div.CodeMirror-cursors {
  visibility: visible;
}

.CodeMirror-selected { background: #d9d9d9; }
.CodeMirror-focused .CodeMirror-selected { background: #d7d4f0; }
.CodeMirror-crosshair { cursor: crosshair; }
.CodeMirror-line::selection, .CodeMirror-line > span::selection, .CodeMirror-line > span > span::selection { background: #d7d4f0; }
.CodeMirror-line::-moz-selection, .CodeMirror-line > span::-moz-selection, .CodeMirror-line > span > span::-moz-selection { background: #d7d4f0; }

.cm-searching {
  background-color: #ffa;
  background-color: rgba(255, 255, 0, .4);
}

/* Used to force a border model for a node */
.cm-force-border { padding-right: .1px; }

@media print {
  /* Hide the cursor when printing */
  .CodeMirror div.CodeMirror-cursors {
    visibility: hidden;
  }
}

/* See issue #2901 */
.cm-tab-wrap-hack:after { content: ''; }

/* Help users use markselection to safely style text background */
span.CodeMirror-selectedtext { background: none; }

.CodeMirror-dialog {
  position: absolute;
  left: 0; right: 0;
  background: inherit;
  z-index: 15;
  padding: .1em .8em;
  overflow: hidden;
  color: inherit;
}

.CodeMirror-dialog-top {
  border-bottom: 1px solid #eee;
  top: 0;
}

.CodeMirror-dialog-bottom {
  border-top: 1px solid #eee;
  bottom: 0;
}

.CodeMirror-dialog input {
  border: none;
  outline: none;
  background: transparent;
  width: 20em;
  color: inherit;
  font-family: monospace;
}

.CodeMirror-dialog button {
  font-size: 70%;
}

.CodeMirror-foldmarker {
  color: blue;
  text-shadow: #b9f 1px 1px 2px, #b9f -1px -1px 2px, #b9f 1px -1px 2px, #b9f -1px 1px 2px;
  font-family: arial;
  line-height: .3;
  cursor: pointer;
}
.CodeMirror-foldgutter {
  width: .7em;
}
.CodeMirror-foldgutter-open,
.CodeMirror-foldgutter-folded {
  cursor: pointer;
}
.CodeMirror-foldgutter-open:after {
  content: "\25BE";
}
.CodeMirror-foldgutter-folded:after {
  content: "\25B8";
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.CodeMirror {
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  border: 0;
  border-radius: 0;
  height: auto;
  /* Changed to auto to autogrow */
}

.CodeMirror pre {
  padding: 0 var(--jp-code-padding);
}

.jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-dialog {
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

/* This causes https://github.com/jupyter/jupyterlab/issues/522 */
/* May not cause it not because we changed it! */
.CodeMirror-lines {
  padding: var(--jp-code-padding) 0;
}

.CodeMirror-linenumber {
  padding: 0 8px;
}

.jp-CodeMirrorEditor {
  cursor: text;
}

.jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
  border-left: var(--jp-code-cursor-width0) solid var(--jp-editor-cursor-color);
}

/* When zoomed out 67% and 33% on a screen of 1440 width x 900 height */
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
    border-left: var(--jp-code-cursor-width1) solid
      var(--jp-editor-cursor-color);
  }
}

/* When zoomed out less than 33% */
@media screen and (min-width: 4320px) {
  .jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
    border-left: var(--jp-code-cursor-width2) solid
      var(--jp-editor-cursor-color);
  }
}

.CodeMirror.jp-mod-readOnly .CodeMirror-cursor {
  display: none;
}

.CodeMirror-gutters {
  border-right: 1px solid var(--jp-border-color2);
  background-color: var(--jp-layout-color0);
}

.jp-CollaboratorCursor {
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-top: none;
  border-bottom: 3px solid;
  background-clip: content-box;
  margin-left: -5px;
  margin-right: -5px;
}

.CodeMirror-selectedtext.cm-searching {
  background-color: var(--jp-search-selected-match-background-color) !important;
  color: var(--jp-search-selected-match-color) !important;
}

.cm-searching {
  background-color: var(
    --jp-search-unselected-match-background-color
  ) !important;
  color: var(--jp-search-unselected-match-color) !important;
}

.CodeMirror-focused .CodeMirror-selected {
  background-color: var(--jp-editor-selected-focused-background);
}

.CodeMirror-selected {
  background-color: var(--jp-editor-selected-background);
}

.jp-CollaboratorCursor-hover {
  position: absolute;
  z-index: 1;
  transform: translateX(-50%);
  color: white;
  border-radius: 3px;
  padding-left: 4px;
  padding-right: 4px;
  padding-top: 1px;
  padding-bottom: 1px;
  text-align: center;
  font-size: var(--jp-ui-font-size1);
  white-space: nowrap;
}

.jp-CodeMirror-ruler {
  border-left: 1px dashed var(--jp-border-color2);
}

/**
 * Here is our jupyter theme for CodeMirror syntax highlighting
 * This is used in our marked.js syntax highlighting and CodeMirror itself
 * The string "jupyter" is set in ../codemirror/widget.DEFAULT_CODEMIRROR_THEME
 * This came from the classic notebook, which came form highlight.js/GitHub
 */

/**
 * CodeMirror themes are handling the background/color in this way. This works
 * fine for CodeMirror editors outside the notebook, but the notebook styles
 * these things differently.
 */
.CodeMirror.cm-s-jupyter {
  background: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

/* In the notebook, we want this styling to be handled by its container */
.jp-CodeConsole .CodeMirror.cm-s-jupyter,
.jp-Notebook .CodeMirror.cm-s-jupyter {
  background: transparent;
}

.cm-s-jupyter .CodeMirror-cursor {
  border-left: var(--jp-code-cursor-width0) solid var(--jp-editor-cursor-color);
}
.cm-s-jupyter span.cm-keyword {
  color: var(--jp-mirror-editor-keyword-color);
  font-weight: bold;
}
.cm-s-jupyter span.cm-atom {
  color: var(--jp-mirror-editor-atom-color);
}
.cm-s-jupyter span.cm-number {
  color: var(--jp-mirror-editor-number-color);
}
.cm-s-jupyter span.cm-def {
  color: var(--jp-mirror-editor-def-color);
}
.cm-s-jupyter span.cm-variable {
  color: var(--jp-mirror-editor-variable-color);
}
.cm-s-jupyter span.cm-variable-2 {
  color: var(--jp-mirror-editor-variable-2-color);
}
.cm-s-jupyter span.cm-variable-3 {
  color: var(--jp-mirror-editor-variable-3-color);
}
.cm-s-jupyter span.cm-punctuation {
  color: var(--jp-mirror-editor-punctuation-color);
}
.cm-s-jupyter span.cm-property {
  color: var(--jp-mirror-editor-property-color);
}
.cm-s-jupyter span.cm-operator {
  color: var(--jp-mirror-editor-operator-color);
  font-weight: bold;
}
.cm-s-jupyter span.cm-comment {
  color: var(--jp-mirror-editor-comment-color);
  font-style: italic;
}
.cm-s-jupyter span.cm-string {
  color: var(--jp-mirror-editor-string-color);
}
.cm-s-jupyter span.cm-string-2 {
  color: var(--jp-mirror-editor-string-2-color);
}
.cm-s-jupyter span.cm-meta {
  color: var(--jp-mirror-editor-meta-color);
}
.cm-s-jupyter span.cm-qualifier {
  color: var(--jp-mirror-editor-qualifier-color);
}
.cm-s-jupyter span.cm-builtin {
  color: var(--jp-mirror-editor-builtin-color);
}
.cm-s-jupyter span.cm-bracket {
  color: var(--jp-mirror-editor-bracket-color);
}
.cm-s-jupyter span.cm-tag {
  color: var(--jp-mirror-editor-tag-color);
}
.cm-s-jupyter span.cm-attribute {
  color: var(--jp-mirror-editor-attribute-color);
}
.cm-s-jupyter span.cm-header {
  color: var(--jp-mirror-editor-header-color);
}
.cm-s-jupyter span.cm-quote {
  color: var(--jp-mirror-editor-quote-color);
}
.cm-s-jupyter span.cm-link {
  color: var(--jp-mirror-editor-link-color);
}
.cm-s-jupyter span.cm-error {
  color: var(--jp-mirror-editor-error-color);
}
.cm-s-jupyter span.cm-hr {
  color: #999;
}

.cm-s-jupyter span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}

.cm-s-jupyter .CodeMirror-activeline-background,
.cm-s-jupyter .CodeMirror-gutter {
  background-color: var(--jp-layout-color2);
}

/* Styles for shared cursors (remote cursor locations and selected ranges) */
.jp-CodeMirrorEditor .remote-caret {
  position: relative;
  border-left: 2px solid black;
  margin-left: -1px;
  margin-right: -1px;
  box-sizing: border-box;
}

.jp-CodeMirrorEditor .remote-caret > div {
  white-space: nowrap;
  position: absolute;
  top: -1.15em;
  padding-bottom: 0.05em;
  left: -2px;
  font-size: 0.95em;
  background-color: rgb(250, 129, 0);
  font-family: var(--jp-ui-font-family);
  font-weight: bold;
  line-height: normal;
  user-select: none;
  color: white;
  padding-left: 2px;
  padding-right: 2px;
  z-index: 3;
  transition: opacity 0.3s ease-in-out;
}

.jp-CodeMirrorEditor .remote-caret.hide-name > div {
  transition-delay: 0.7s;
  opacity: 0;
}

.jp-CodeMirrorEditor .remote-caret:hover > div {
  opacity: 1;
  transition-delay: 0s;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| RenderedText
|----------------------------------------------------------------------------*/

:root {
  /* This is the padding value to fill the gaps between lines containing spans with background color. */
  --jp-private-code-span-padding: calc(
    (var(--jp-code-line-height) - 1) * var(--jp-code-font-size) / 2
  );
}

.jp-RenderedText {
  text-align: left;
  padding-left: var(--jp-code-padding);
  line-height: var(--jp-code-line-height);
  font-family: var(--jp-code-font-family);
}

.jp-RenderedText pre,
.jp-RenderedJavaScript pre,
.jp-RenderedHTMLCommon pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
  border: none;
  margin: 0px;
  padding: 0px;
}

.jp-RenderedText pre a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}
.jp-RenderedText pre a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}
.jp-RenderedText pre a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* console foregrounds and backgrounds */
.jp-RenderedText pre .ansi-black-fg {
  color: #3e424d;
}
.jp-RenderedText pre .ansi-red-fg {
  color: #e75c58;
}
.jp-RenderedText pre .ansi-green-fg {
  color: #00a250;
}
.jp-RenderedText pre .ansi-yellow-fg {
  color: #ddb62b;
}
.jp-RenderedText pre .ansi-blue-fg {
  color: #208ffb;
}
.jp-RenderedText pre .ansi-magenta-fg {
  color: #d160c4;
}
.jp-RenderedText pre .ansi-cyan-fg {
  color: #60c6c8;
}
.jp-RenderedText pre .ansi-white-fg {
  color: #c5c1b4;
}

.jp-RenderedText pre .ansi-black-bg {
  background-color: #3e424d;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-red-bg {
  background-color: #e75c58;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-green-bg {
  background-color: #00a250;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-yellow-bg {
  background-color: #ddb62b;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-blue-bg {
  background-color: #208ffb;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-magenta-bg {
  background-color: #d160c4;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-cyan-bg {
  background-color: #60c6c8;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-white-bg {
  background-color: #c5c1b4;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-black-intense-fg {
  color: #282c36;
}
.jp-RenderedText pre .ansi-red-intense-fg {
  color: #b22b31;
}
.jp-RenderedText pre .ansi-green-intense-fg {
  color: #007427;
}
.jp-RenderedText pre .ansi-yellow-intense-fg {
  color: #b27d12;
}
.jp-RenderedText pre .ansi-blue-intense-fg {
  color: #0065ca;
}
.jp-RenderedText pre .ansi-magenta-intense-fg {
  color: #a03196;
}
.jp-RenderedText pre .ansi-cyan-intense-fg {
  color: #258f8f;
}
.jp-RenderedText pre .ansi-white-intense-fg {
  color: #a1a6b2;
}

.jp-RenderedText pre .ansi-black-intense-bg {
  background-color: #282c36;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-red-intense-bg {
  background-color: #b22b31;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-green-intense-bg {
  background-color: #007427;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-yellow-intense-bg {
  background-color: #b27d12;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-blue-intense-bg {
  background-color: #0065ca;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-magenta-intense-bg {
  background-color: #a03196;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-cyan-intense-bg {
  background-color: #258f8f;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-white-intense-bg {
  background-color: #a1a6b2;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-default-inverse-fg {
  color: var(--jp-ui-inverse-font-color0);
}
.jp-RenderedText pre .ansi-default-inverse-bg {
  background-color: var(--jp-inverse-layout-color0);
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-bold {
  font-weight: bold;
}
.jp-RenderedText pre .ansi-underline {
  text-decoration: underline;
}

.jp-RenderedText[data-mime-type='application/vnd.jupyter.stderr'] {
  background: var(--jp-rendermime-error-background);
  padding-top: var(--jp-code-padding);
}

/*-----------------------------------------------------------------------------
| RenderedLatex
|----------------------------------------------------------------------------*/

.jp-RenderedLatex {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
}

/* Left-justify outputs.*/
.jp-OutputArea-output.jp-RenderedLatex {
  padding: var(--jp-code-padding);
  text-align: left;
}

/*-----------------------------------------------------------------------------
| RenderedHTML
|----------------------------------------------------------------------------*/

.jp-RenderedHTMLCommon {
  color: var(--jp-content-font-color1);
  font-family: var(--jp-content-font-family);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
  /* Give a bit more R padding on Markdown text to keep line lengths reasonable */
  padding-right: 20px;
}

.jp-RenderedHTMLCommon em {
  font-style: italic;
}

.jp-RenderedHTMLCommon strong {
  font-weight: bold;
}

.jp-RenderedHTMLCommon u {
  text-decoration: underline;
}

.jp-RenderedHTMLCommon a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* Headings */

.jp-RenderedHTMLCommon h1,
.jp-RenderedHTMLCommon h2,
.jp-RenderedHTMLCommon h3,
.jp-RenderedHTMLCommon h4,
.jp-RenderedHTMLCommon h5,
.jp-RenderedHTMLCommon h6 {
  line-height: var(--jp-content-heading-line-height);
  font-weight: var(--jp-content-heading-font-weight);
  font-style: normal;
  margin: var(--jp-content-heading-margin-top) 0
    var(--jp-content-heading-margin-bottom) 0;
}

.jp-RenderedHTMLCommon h1:first-child,
.jp-RenderedHTMLCommon h2:first-child,
.jp-RenderedHTMLCommon h3:first-child,
.jp-RenderedHTMLCommon h4:first-child,
.jp-RenderedHTMLCommon h5:first-child,
.jp-RenderedHTMLCommon h6:first-child {
  margin-top: calc(0.5 * var(--jp-content-heading-margin-top));
}

.jp-RenderedHTMLCommon h1:last-child,
.jp-RenderedHTMLCommon h2:last-child,
.jp-RenderedHTMLCommon h3:last-child,
.jp-RenderedHTMLCommon h4:last-child,
.jp-RenderedHTMLCommon h5:last-child,
.jp-RenderedHTMLCommon h6:last-child {
  margin-bottom: calc(0.5 * var(--jp-content-heading-margin-bottom));
}

.jp-RenderedHTMLCommon h1 {
  font-size: var(--jp-content-font-size5);
}

.jp-RenderedHTMLCommon h2 {
  font-size: var(--jp-content-font-size4);
}

.jp-RenderedHTMLCommon h3 {
  font-size: var(--jp-content-font-size3);
}

.jp-RenderedHTMLCommon h4 {
  font-size: var(--jp-content-font-size2);
}

.jp-RenderedHTMLCommon h5 {
  font-size: var(--jp-content-font-size1);
}

.jp-RenderedHTMLCommon h6 {
  font-size: var(--jp-content-font-size0);
}

/* Lists */

.jp-RenderedHTMLCommon ul:not(.list-inline),
.jp-RenderedHTMLCommon ol:not(.list-inline) {
  padding-left: 2em;
}

.jp-RenderedHTMLCommon ul {
  list-style: disc;
}

.jp-RenderedHTMLCommon ul ul {
  list-style: square;
}

.jp-RenderedHTMLCommon ul ul ul {
  list-style: circle;
}

.jp-RenderedHTMLCommon ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol ol {
  list-style: upper-alpha;
}

.jp-RenderedHTMLCommon ol ol ol {
  list-style: lower-alpha;
}

.jp-RenderedHTMLCommon ol ol ol ol {
  list-style: lower-roman;
}

.jp-RenderedHTMLCommon ol ol ol ol ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol,
.jp-RenderedHTMLCommon ul {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon ul ul,
.jp-RenderedHTMLCommon ul ol,
.jp-RenderedHTMLCommon ol ul,
.jp-RenderedHTMLCommon ol ol {
  margin-bottom: 0em;
}

.jp-RenderedHTMLCommon hr {
  color: var(--jp-border-color2);
  background-color: var(--jp-border-color1);
  margin-top: 1em;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon > pre {
  margin: 1.5em 2em;
}

.jp-RenderedHTMLCommon pre,
.jp-RenderedHTMLCommon code {
  border: 0;
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  line-height: var(--jp-code-line-height);
  padding: 0;
  white-space: pre-wrap;
}

.jp-RenderedHTMLCommon :not(pre) > code {
  background-color: var(--jp-layout-color2);
  padding: 1px 5px;
}

/* Tables */

.jp-RenderedHTMLCommon table {
  border-collapse: collapse;
  border-spacing: 0;
  border: none;
  color: var(--jp-ui-font-color1);
  font-size: 12px;
  table-layout: fixed;
  margin-left: auto;
  margin-right: auto;
}

.jp-RenderedHTMLCommon thead {
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  vertical-align: bottom;
}

.jp-RenderedHTMLCommon td,
.jp-RenderedHTMLCommon th,
.jp-RenderedHTMLCommon tr {
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}

.jp-RenderedMarkdown.jp-RenderedHTMLCommon td,
.jp-RenderedMarkdown.jp-RenderedHTMLCommon th {
  max-width: none;
}

:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon td,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon th,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon tr {
  text-align: right;
}

.jp-RenderedHTMLCommon th {
  font-weight: bold;
}

.jp-RenderedHTMLCommon tbody tr:nth-child(odd) {
  background: var(--jp-layout-color0);
}

.jp-RenderedHTMLCommon tbody tr:nth-child(even) {
  background: var(--jp-rendermime-table-row-background);
}

.jp-RenderedHTMLCommon tbody tr:hover {
  background: var(--jp-rendermime-table-row-hover-background);
}

.jp-RenderedHTMLCommon table {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon p {
  text-align: left;
  margin: 0px;
}

.jp-RenderedHTMLCommon p {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon img {
  -moz-force-broken-image-icon: 1;
}

/* Restrict to direct children as other images could be nested in other content. */
.jp-RenderedHTMLCommon > img {
  display: block;
  margin-left: 0;
  margin-right: 0;
  margin-bottom: 1em;
}

/* Change color behind transparent images if they need it... */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-light-background {
  background-color: var(--jp-inverse-layout-color1);
}
[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-dark-background {
  background-color: var(--jp-inverse-layout-color1);
}
/* ...or leave it untouched if they don't */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-dark-background {
}
[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-light-background {
}

.jp-RenderedHTMLCommon img,
.jp-RenderedImage img,
.jp-RenderedHTMLCommon svg,
.jp-RenderedSVG svg {
  max-width: 100%;
  height: auto;
}

.jp-RenderedHTMLCommon img.jp-mod-unconfined,
.jp-RenderedImage img.jp-mod-unconfined,
.jp-RenderedHTMLCommon svg.jp-mod-unconfined,
.jp-RenderedSVG svg.jp-mod-unconfined {
  max-width: none;
}

.jp-RenderedHTMLCommon .alert {
  padding: var(--jp-notebook-padding);
  border: var(--jp-border-width) solid transparent;
  border-radius: var(--jp-border-radius);
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon .alert-info {
  color: var(--jp-info-color0);
  background-color: var(--jp-info-color3);
  border-color: var(--jp-info-color2);
}
.jp-RenderedHTMLCommon .alert-info hr {
  border-color: var(--jp-info-color3);
}
.jp-RenderedHTMLCommon .alert-info > p:last-child,
.jp-RenderedHTMLCommon .alert-info > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-warning {
  color: var(--jp-warn-color0);
  background-color: var(--jp-warn-color3);
  border-color: var(--jp-warn-color2);
}
.jp-RenderedHTMLCommon .alert-warning hr {
  border-color: var(--jp-warn-color3);
}
.jp-RenderedHTMLCommon .alert-warning > p:last-child,
.jp-RenderedHTMLCommon .alert-warning > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-success {
  color: var(--jp-success-color0);
  background-color: var(--jp-success-color3);
  border-color: var(--jp-success-color2);
}
.jp-RenderedHTMLCommon .alert-success hr {
  border-color: var(--jp-success-color3);
}
.jp-RenderedHTMLCommon .alert-success > p:last-child,
.jp-RenderedHTMLCommon .alert-success > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-danger {
  color: var(--jp-error-color0);
  background-color: var(--jp-error-color3);
  border-color: var(--jp-error-color2);
}
.jp-RenderedHTMLCommon .alert-danger hr {
  border-color: var(--jp-error-color3);
}
.jp-RenderedHTMLCommon .alert-danger > p:last-child,
.jp-RenderedHTMLCommon .alert-danger > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon blockquote {
  margin: 1em 2em;
  padding: 0 1em;
  border-left: 5px solid var(--jp-border-color2);
}

a.jp-InternalAnchorLink {
  visibility: hidden;
  margin-left: 8px;
  color: var(--md-blue-800);
}

h1:hover .jp-InternalAnchorLink,
h2:hover .jp-InternalAnchorLink,
h3:hover .jp-InternalAnchorLink,
h4:hover .jp-InternalAnchorLink,
h5:hover .jp-InternalAnchorLink,
h6:hover .jp-InternalAnchorLink {
  visibility: visible;
}

.jp-RenderedHTMLCommon kbd {
  background-color: var(--jp-rendermime-table-row-background);
  border: 1px solid var(--jp-border-color0);
  border-bottom-color: var(--jp-border-color2);
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
  display: inline-block;
  font-size: 0.8em;
  line-height: 1em;
  padding: 0.2em 0.5em;
}

/* Most direct children of .jp-RenderedHTMLCommon have a margin-bottom of 1.0.
 * At the bottom of cells this is a bit too much as there is also spacing
 * between cells. Going all the way to 0 gets too tight between markdown and
 * code cells.
 */
.jp-RenderedHTMLCommon > *:last-child {
  margin-bottom: 0.5em;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MimeDocument {
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-filebrowser-button-height: 28px;
  --jp-private-filebrowser-button-width: 48px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FileBrowser {
  display: flex;
  flex-direction: column;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  border-bottom: none;
  height: auto;
  margin: var(--jp-toolbar-header-margin);
  box-shadow: none;
}

.jp-BreadCrumbs {
  flex: 0 0 auto;
  margin: 8px 12px 8px 12px;
}

.jp-BreadCrumbs-item {
  margin: 0px 2px;
  padding: 0px 2px;
  border-radius: var(--jp-border-radius);
  cursor: pointer;
}

.jp-BreadCrumbs-item:hover {
  background-color: var(--jp-layout-color2);
}

.jp-BreadCrumbs-item:first-child {
  margin-left: 0px;
}

.jp-BreadCrumbs-item.jp-mod-dropTarget {
  background-color: var(--jp-brand-color2);
  opacity: 0.7;
}

/*-----------------------------------------------------------------------------
| Buttons
|----------------------------------------------------------------------------*/

.jp-FileBrowser-toolbar.jp-Toolbar {
  padding: 0px;
  margin: 8px 12px 0px 12px;
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  justify-content: flex-start;
}

.jp-FileBrowser-toolbar.jp-Toolbar .jp-Toolbar-item {
  flex: 0 0 auto;
  padding-left: 0px;
  padding-right: 2px;
}

.jp-FileBrowser-toolbar.jp-Toolbar .jp-ToolbarButtonComponent {
  width: 40px;
}

.jp-FileBrowser-toolbar.jp-Toolbar
  .jp-Toolbar-item:first-child
  .jp-ToolbarButtonComponent {
  width: 72px;
  background: var(--jp-brand-color1);
}

.jp-FileBrowser-toolbar.jp-Toolbar
  .jp-Toolbar-item:first-child
  .jp-ToolbarButtonComponent:focus-visible {
  background-color: var(--jp-brand-color0);
}

.jp-FileBrowser-toolbar.jp-Toolbar
  .jp-Toolbar-item:first-child
  .jp-ToolbarButtonComponent
  .jp-icon3 {
  fill: white;
}

/*-----------------------------------------------------------------------------
| Other styles
|----------------------------------------------------------------------------*/

.jp-FileDialog.jp-mod-conflict input {
  color: var(--jp-error-color1);
}

.jp-FileDialog .jp-new-name-title {
  margin-top: 12px;
}

.jp-LastModified-hidden {
  display: none;
}

.jp-FileBrowser-filterBox {
  padding: 0px;
  flex: 0 0 auto;
  margin: 8px 12px 0px 12px;
}

/*-----------------------------------------------------------------------------
| DirListing
|----------------------------------------------------------------------------*/

.jp-DirListing {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
  outline: 0;
}

.jp-DirListing:focus-visible {
  border: 1px solid var(--jp-brand-color1);
}

.jp-DirListing-header {
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  overflow: hidden;
  border-top: var(--jp-border-width) solid var(--jp-border-color2);
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
}

.jp-DirListing-headerItem {
  padding: 4px 12px 2px 12px;
  font-weight: 500;
}

.jp-DirListing-headerItem:hover {
  background: var(--jp-layout-color2);
}

.jp-DirListing-headerItem.jp-id-name {
  flex: 1 0 84px;
}

.jp-DirListing-headerItem.jp-id-modified {
  flex: 0 0 112px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-id-narrow {
  display: none;
  flex: 0 0 5px;
  padding: 4px 4px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
  color: var(--jp-border-color2);
}

.jp-DirListing-narrow .jp-id-narrow {
  display: block;
}

.jp-DirListing-narrow .jp-id-modified,
.jp-DirListing-narrow .jp-DirListing-itemModified {
  display: none;
}

.jp-DirListing-headerItem.jp-mod-selected {
  font-weight: 600;
}

/* increase specificity to override bundled default */
.jp-DirListing-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-DirListing-content mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.jp-DirListing-content .jp-DirListing-item.jp-mod-selected mark {
  color: var(--jp-ui-inverse-font-color0);
}

/* Style the directory listing content when a user drops a file to upload */
.jp-DirListing.jp-mod-native-drop .jp-DirListing-content {
  outline: 5px dashed rgba(128, 128, 128, 0.5);
  outline-offset: -10px;
  cursor: copy;
}

.jp-DirListing-item {
  display: flex;
  flex-direction: row;
  padding: 4px 12px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-DirListing-item[data-is-dot] {
  opacity: 75%;
}

.jp-DirListing-item.jp-mod-selected {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.jp-DirListing-item.jp-mod-dropTarget {
  background: var(--jp-brand-color3);
}

.jp-DirListing-item:hover:not(.jp-mod-selected) {
  background: var(--jp-layout-color2);
}

.jp-DirListing-itemIcon {
  flex: 0 0 20px;
  margin-right: 4px;
}

.jp-DirListing-itemText {
  flex: 1 0 64px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  user-select: none;
}

.jp-DirListing-itemModified {
  flex: 0 0 125px;
  text-align: right;
}

.jp-DirListing-editor {
  flex: 1 0 64px;
  outline: none;
  border: none;
}

.jp-DirListing-item.jp-mod-running .jp-DirListing-itemIcon:before {
  color: var(--jp-success-color1);
  content: '\25CF';
  font-size: 8px;
  position: absolute;
  left: -8px;
}

.jp-DirListing-item.jp-mod-running.jp-mod-selected
  .jp-DirListing-itemIcon:before {
  color: var(--jp-ui-inverse-font-color1);
}

.jp-DirListing-item.lm-mod-drag-image,
.jp-DirListing-item.jp-mod-selected.lm-mod-drag-image {
  font-size: var(--jp-ui-font-size1);
  padding-left: 4px;
  margin-left: 4px;
  width: 160px;
  background-color: var(--jp-ui-inverse-font-color2);
  box-shadow: var(--jp-elevation-z2);
  border-radius: 0px;
  color: var(--jp-ui-font-color1);
  transform: translateX(-40%) translateY(-58%);
}

.jp-DirListing-deadSpace {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-Document {
  min-width: 120px;
  min-height: 120px;
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
}

/*-----------------------------------------------------------------------------
| Main OutputArea
| OutputArea has a list of Outputs
|----------------------------------------------------------------------------*/

.jp-OutputArea {
  overflow-y: auto;
}

.jp-OutputArea-child {
  display: flex;
  flex-direction: row;
}

body[data-format='mobile'] .jp-OutputArea-child {
  flex-direction: column;
}

.jp-OutputPrompt {
  flex: 0 0 var(--jp-cell-prompt-width);
  color: var(--jp-cell-outprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);
  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

body[data-format='mobile'] .jp-OutputPrompt {
  flex: 0 0 auto;
  text-align: left;
}

.jp-OutputArea-output {
  height: auto;
  overflow: auto;
  user-select: text;
  -moz-user-select: text;
  -webkit-user-select: text;
  -ms-user-select: text;
}

.jp-OutputArea-child .jp-OutputArea-output {
  flex-grow: 1;
  flex-shrink: 1;
}

body[data-format='mobile'] .jp-OutputArea-child .jp-OutputArea-output {
  margin-left: var(--jp-notebook-padding);
}

/**
 * Isolated output.
 */
.jp-OutputArea-output.jp-mod-isolated {
  width: 100%;
  display: block;
}

/*
When drag events occur, `p-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated {
  position: relative;
}

body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/* pre */

.jp-OutputArea-output pre {
  border: none;
  margin: 0px;
  padding: 0px;
  overflow-x: auto;
  overflow-y: auto;
  word-break: break-all;
  word-wrap: break-word;
  white-space: pre-wrap;
}

/* tables */

.jp-OutputArea-output.jp-RenderedHTMLCommon table {
  margin-left: 0;
  margin-right: 0;
}

/* description lists */

.jp-OutputArea-output dl,
.jp-OutputArea-output dt,
.jp-OutputArea-output dd {
  display: block;
}

.jp-OutputArea-output dl {
  width: 100%;
  overflow: hidden;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dt {
  font-weight: bold;
  float: left;
  width: 20%;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dd {
  float: left;
  width: 80%;
  padding: 0;
  margin: 0;
}

/* Hide the gutter in case of
 *  - nested output areas (e.g. in the case of output widgets)
 *  - mirrored output areas
 */
.jp-OutputArea .jp-OutputArea .jp-OutputArea-prompt {
  display: none;
}

/*-----------------------------------------------------------------------------
| executeResult is added to any Output-result for the display of the object
| returned by a cell
|----------------------------------------------------------------------------*/

.jp-OutputArea-output.jp-OutputArea-executeResult {
  margin-left: 0px;
  flex: 1 1 auto;
}

/* Text output with the Out[] prompt needs a top padding to match the
 * alignment of the Out[] prompt itself.
 */
.jp-OutputArea-executeResult .jp-RenderedText.jp-OutputArea-output {
  padding-top: var(--jp-code-padding);
  border-top: var(--jp-border-width) solid transparent;
}

/*-----------------------------------------------------------------------------
| The Stdin output
|----------------------------------------------------------------------------*/

.jp-OutputArea-stdin {
  line-height: var(--jp-code-line-height);
  padding-top: var(--jp-code-padding);
  display: flex;
}

.jp-Stdin-prompt {
  color: var(--jp-content-font-color0);
  padding-right: var(--jp-code-padding);
  vertical-align: baseline;
  flex: 0 0 auto;
}

.jp-Stdin-input {
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  color: inherit;
  background-color: inherit;
  width: 42%;
  min-width: 200px;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
  flex: 0 0 70%;
}

.jp-Stdin-input:focus {
  box-shadow: none;
}

/*-----------------------------------------------------------------------------
| Output Area View
|----------------------------------------------------------------------------*/

.jp-LinkedOutputView .jp-OutputArea {
  height: 100%;
  display: block;
}

.jp-LinkedOutputView .jp-OutputArea-output:only-child {
  height: 100%;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapser {
  flex: 0 0 var(--jp-cell-collapser-width);
  padding: 0px;
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
  border-radius: var(--jp-border-radius);
  opacity: 1;
}

.jp-Collapser-child {
  display: block;
  width: 100%;
  box-sizing: border-box;
  /* height: 100% doesn't work because the height of its parent is computed from content */
  position: absolute;
  top: 0px;
  bottom: 0px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Header/Footer
|----------------------------------------------------------------------------*/

/* Hidden by zero height by default */
.jp-CellHeader,
.jp-CellFooter {
  height: 0px;
  width: 100%;
  padding: 0px;
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Input
|----------------------------------------------------------------------------*/

/* All input areas */
.jp-InputArea {
  display: flex;
  flex-direction: row;
  overflow: hidden;
}

body[data-format='mobile'] .jp-InputArea {
  flex-direction: column;
}

.jp-InputArea-editor {
  flex: 1 1 auto;
  overflow: hidden;
}

.jp-InputArea-editor {
  /* This is the non-active, default styling */
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0px;
  background: var(--jp-cell-editor-background);
}

body[data-format='mobile'] .jp-InputArea-editor {
  margin-left: var(--jp-notebook-padding);
}

.jp-InputPrompt {
  flex: 0 0 var(--jp-cell-prompt-width);
  color: var(--jp-cell-inprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  opacity: var(--jp-cell-prompt-opacity);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);
  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

body[data-format='mobile'] .jp-InputPrompt {
  flex: 0 0 auto;
  text-align: left;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Placeholder {
  display: flex;
  flex-direction: row;
  flex: 1 1 auto;
}

.jp-Placeholder-prompt {
  box-sizing: border-box;
}

.jp-Placeholder-content {
  flex: 1 1 auto;
  border: none;
  background: transparent;
  height: 20px;
  box-sizing: border-box;
}

.jp-Placeholder-content .jp-MoreHorizIcon {
  width: 32px;
  height: 16px;
  border: 1px solid transparent;
  border-radius: var(--jp-border-radius);
}

.jp-Placeholder-content .jp-MoreHorizIcon:hover {
  border: 1px solid var(--jp-border-color1);
  box-shadow: 0px 0px 2px 0px rgba(0, 0, 0, 0.25);
  background-color: var(--jp-layout-color0);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-cell-scrolling-output-offset: 5px;
}

/*-----------------------------------------------------------------------------
| Cell
|----------------------------------------------------------------------------*/

.jp-Cell {
  padding: var(--jp-cell-padding);
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Common input/output
|----------------------------------------------------------------------------*/

.jp-Cell-inputWrapper,
.jp-Cell-outputWrapper {
  display: flex;
  flex-direction: row;
  padding: 0px;
  margin: 0px;
  /* Added to reveal the box-shadow on the input and output collapsers. */
  overflow: visible;
}

/* Only input/output areas inside cells */
.jp-Cell-inputArea,
.jp-Cell-outputArea {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Collapser
|----------------------------------------------------------------------------*/

/* Make the output collapser disappear when there is not output, but do so
 * in a manner that leaves it in the layout and preserves its width.
 */
.jp-Cell.jp-mod-noOutputs .jp-Cell-outputCollapser {
  border: none !important;
  background: transparent !important;
}

.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputCollapser {
  min-height: var(--jp-cell-collapser-min-height);
}

/*-----------------------------------------------------------------------------
| Output
|----------------------------------------------------------------------------*/

/* Put a space between input and output when there IS output */
.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputWrapper {
  margin-top: 5px;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea {
  overflow-y: auto;
  max-height: 200px;
  box-shadow: inset 0 0 6px 2px rgba(0, 0, 0, 0.3);
  margin-left: var(--jp-private-cell-scrolling-output-offset);
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  flex: 0 0
    calc(
      var(--jp-cell-prompt-width) -
        var(--jp-private-cell-scrolling-output-offset)
    );
}

/*-----------------------------------------------------------------------------
| CodeCell
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| MarkdownCell
|----------------------------------------------------------------------------*/

.jp-MarkdownOutput {
  flex: 1 1 auto;
  margin-top: 0;
  margin-bottom: 0;
  padding-left: var(--jp-code-padding);
}

.jp-MarkdownOutput.jp-RenderedHTMLCommon {
  overflow: auto;
}

.jp-showHiddenCellsButton {
  margin-left: calc(var(--jp-cell-prompt-width) + 2 * var(--jp-code-padding));
  margin-top: var(--jp-code-padding);
  border: 1px solid var(--jp-border-color2);
  background-color: var(--jp-border-color3) !important;
  color: var(--jp-content-font-color0) !important;
}

.jp-showHiddenCellsButton:hover {
  background-color: var(--jp-border-color2) !important;
}

.jp-collapseHeadingButton {
  display: none;
}

.jp-MarkdownCell:hover .jp-collapseHeadingButton {
  display: flex;
  min-height: var(--jp-cell-collapser-min-height);
  position: absolute;
  right: 0;
  top: 0;
  bottom: 0;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-NotebookPanel-toolbar {
  padding: 2px;
}

.jp-Toolbar-item.jp-Notebook-toolbarCellType .jp-select-wrapper.jp-mod-focused {
  border: none;
  box-shadow: none;
}

.jp-Notebook-toolbarCellTypeDropdown select {
  height: 24px;
  font-size: var(--jp-ui-font-size1);
  line-height: 14px;
  border-radius: 0;
  display: block;
}

.jp-Notebook-toolbarCellTypeDropdown span {
  top: 5px !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-notebook-dragImage-width: 304px;
  --jp-private-notebook-dragImage-height: 36px;
  --jp-private-notebook-selected-color: var(--md-blue-400);
  --jp-private-notebook-active-color: var(--md-green-400);
}

/*-----------------------------------------------------------------------------
| Imports
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Notebook
|----------------------------------------------------------------------------*/

.jp-NotebookPanel {
  display: block;
  height: 100%;
}

.jp-NotebookPanel.jp-Document {
  min-width: 240px;
  min-height: 120px;
}

.jp-Notebook {
  padding: var(--jp-notebook-padding);
  outline: none;
  overflow: auto;
  background: var(--jp-layout-color0);
}

.jp-Notebook.jp-mod-scrollPastEnd::after {
  display: block;
  content: '';
  min-height: var(--jp-notebook-scroll-padding);
}

.jp-MainAreaWidget-ContainStrict .jp-Notebook * {
  contain: strict;
}

.jp-Notebook-render * {
  contain: none !important;
}

.jp-Notebook .jp-Cell {
  overflow: visible;
}

.jp-Notebook .jp-Cell .jp-InputPrompt {
  cursor: move;
  float: left;
}

/*-----------------------------------------------------------------------------
| Notebook state related styling
|
| The notebook and cells each have states, here are the possibilities:
|
| - Notebook
|   - Command
|   - Edit
| - Cell
|   - None
|   - Active (only one can be active)
|   - Selected (the cells actions are applied to)
|   - Multiselected (when multiple selected, the cursor)
|   - No outputs
|----------------------------------------------------------------------------*/

/* Command or edit modes */

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-InputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-OutputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

/* cell is active */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser {
  background: var(--jp-brand-color1);
}

/* cell is dirty */
.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt {
  color: var(--jp-warn-color1);
}
.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt:before {
  color: var(--jp-warn-color1);
  content: '???';
}

.jp-Notebook .jp-Cell.jp-mod-active.jp-mod-dirty .jp-Collapser {
  background: var(--jp-warn-color1);
}

/* collapser is hovered */
.jp-Notebook .jp-Cell .jp-Collapser:hover {
  box-shadow: var(--jp-elevation-z2);
  background: var(--jp-brand-color1);
  opacity: var(--jp-cell-collapser-not-active-hover-opacity);
}

/* cell is active and collapser is hovered */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser:hover {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/* Command mode */

.jp-Notebook.jp-mod-commandMode .jp-Cell.jp-mod-selected {
  background: var(--jp-notebook-multiselected-color);
}

.jp-Notebook.jp-mod-commandMode
  .jp-Cell.jp-mod-active.jp-mod-selected:not(.jp-mod-multiSelected) {
  background: transparent;
}

/* Edit mode */

.jp-Notebook.jp-mod-editMode .jp-Cell.jp-mod-active .jp-InputArea-editor {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-cell-editor-active-background);
}

/*-----------------------------------------------------------------------------
| Notebook drag and drop
|----------------------------------------------------------------------------*/

.jp-Notebook-cell.jp-mod-dropSource {
  opacity: 0.5;
}

.jp-Notebook-cell.jp-mod-dropTarget,
.jp-Notebook.jp-mod-commandMode
  .jp-Notebook-cell.jp-mod-active.jp-mod-selected.jp-mod-dropTarget {
  border-top-color: var(--jp-private-notebook-selected-color);
  border-top-style: solid;
  border-top-width: 2px;
}

.jp-dragImage {
  display: block;
  flex-direction: row;
  width: var(--jp-private-notebook-dragImage-width);
  height: var(--jp-private-notebook-dragImage-height);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
  overflow: visible;
}

.jp-dragImage-singlePrompt {
  box-shadow: 2px 2px 4px 0px rgba(0, 0, 0, 0.12);
}

.jp-dragImage .jp-dragImage-content {
  flex: 1 1 auto;
  z-index: 2;
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  line-height: var(--jp-code-line-height);
  padding: var(--jp-code-padding);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background-color);
  color: var(--jp-content-font-color3);
  text-align: left;
  margin: 4px 4px 4px 0px;
}

.jp-dragImage .jp-dragImage-prompt {
  flex: 0 0 auto;
  min-width: 36px;
  color: var(--jp-cell-inprompt-font-color);
  padding: var(--jp-code-padding);
  padding-left: 12px;
  font-family: var(--jp-cell-prompt-font-family);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: 1.9;
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
}

.jp-dragImage-multipleBack {
  z-index: -1;
  position: absolute;
  height: 32px;
  width: 300px;
  top: 8px;
  left: 8px;
  background: var(--jp-layout-color2);
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  box-shadow: 2px 2px 4px 0px rgba(0, 0, 0, 0.12);
}

/*-----------------------------------------------------------------------------
| Cell toolbar
|----------------------------------------------------------------------------*/

.jp-NotebookTools {
  display: block;
  min-width: var(--jp-sidebar-min-width);
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
    * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  overflow: auto;
}

.jp-NotebookTools-tool {
  padding: 0px 12px 0 12px;
}

.jp-ActiveCellTool {
  padding: 12px;
  background-color: var(--jp-layout-color1);
  border-top: none !important;
}

.jp-ActiveCellTool .jp-InputArea-prompt {
  flex: 0 0 auto;
  padding-left: 0px;
}

.jp-ActiveCellTool .jp-InputArea-editor {
  flex: 1 1 auto;
  background: var(--jp-cell-editor-background);
  border-color: var(--jp-cell-editor-border-color);
}

.jp-ActiveCellTool .jp-InputArea-editor .CodeMirror {
  background: transparent;
}

.jp-MetadataEditorTool {
  flex-direction: column;
  padding: 12px 0px 12px 0px;
}

.jp-RankedPanel > :not(:first-child) {
  margin-top: 12px;
}

.jp-KeySelector select.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: var(--jp-border-width) solid var(--jp-border-color1);
}

.jp-KeySelector label,
.jp-MetadataEditorTool label {
  line-height: 1.4;
}

.jp-NotebookTools .jp-select-wrapper {
  margin-top: 4px;
  margin-bottom: 0px;
}

.jp-NotebookTools .jp-Collapse {
  margin-top: 16px;
}

/*-----------------------------------------------------------------------------
| Presentation Mode (.jp-mod-presentationMode)
|----------------------------------------------------------------------------*/

.jp-mod-presentationMode .jp-Notebook {
  --jp-content-font-size1: var(--jp-content-presentation-font-size1);
  --jp-code-font-size: var(--jp-code-presentation-font-size);
}

.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-InputPrompt,
.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-OutputPrompt {
  flex: 0 0 110px;
}

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Cell-Placeholder {
  padding-left: 55px;
}

.jp-Cell-Placeholder-wrapper {
  background: #fff;
  border: 1px solid;
  border-color: #e5e6e9 #dfe0e4 #d0d1d5;
  border-radius: 4px;
  -webkit-border-radius: 4px;
  margin: 10px 15px;
}

.jp-Cell-Placeholder-wrapper-inner {
  padding: 15px;
  position: relative;
}

.jp-Cell-Placeholder-wrapper-body {
  background-repeat: repeat;
  background-size: 50% auto;
}

.jp-Cell-Placeholder-wrapper-body div {
  background: #f6f7f8;
  background-image: -webkit-linear-gradient(
    left,
    #f6f7f8 0%,
    #edeef1 20%,
    #f6f7f8 40%,
    #f6f7f8 100%
  );
  background-repeat: no-repeat;
  background-size: 800px 104px;
  height: 104px;
  position: relative;
}

.jp-Cell-Placeholder-wrapper-body div {
  position: absolute;
  right: 15px;
  left: 15px;
  top: 15px;
}

div.jp-Cell-Placeholder-h1 {
  top: 20px;
  height: 20px;
  left: 15px;
  width: 150px;
}

div.jp-Cell-Placeholder-h2 {
  left: 15px;
  top: 50px;
  height: 10px;
  width: 100px;
}

div.jp-Cell-Placeholder-content-1,
div.jp-Cell-Placeholder-content-2,
div.jp-Cell-Placeholder-content-3 {
  left: 15px;
  right: 15px;
  height: 10px;
}

div.jp-Cell-Placeholder-content-1 {
  top: 100px;
}

div.jp-Cell-Placeholder-content-2 {
  top: 120px;
}

div.jp-Cell-Placeholder-content-3 {
  top: 140px;
}

</style>

    <style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
The following CSS variables define the main, public API for styling JupyterLab.
These variables should be used by all plugins wherever possible. In other
words, plugins should not define custom colors, sizes, etc unless absolutely
necessary. This enables users to change the visual theme of JupyterLab
by changing these variables.

Many variables appear in an ordered sequence (0,1,2,3). These sequences
are designed to work well together, so for example, `--jp-border-color1` should
be used with `--jp-layout-color1`. The numbers have the following meanings:

* 0: super-primary, reserved for special emphasis
* 1: primary, most important under normal situations
* 2: secondary, next most important under normal situations
* 3: tertiary, next most important under normal situations

Throughout JupyterLab, we are mostly following principles from Google's
Material Design when selecting colors. We are not, however, following
all of MD as it is not optimized for dense, information rich UIs.
*/

:root {
  /* Elevation
   *
   * We style box-shadows using Material Design's idea of elevation. These particular numbers are taken from here:
   *
   * https://github.com/material-components/material-components-web
   * https://material-components-web.appspot.com/elevation.html
   */

  --jp-shadow-base-lightness: 0;
  --jp-shadow-umbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.2
  );
  --jp-shadow-penumbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.14
  );
  --jp-shadow-ambient-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.12
  );
  --jp-elevation-z0: none;
  --jp-elevation-z1: 0px 2px 1px -1px var(--jp-shadow-umbra-color),
    0px 1px 1px 0px var(--jp-shadow-penumbra-color),
    0px 1px 3px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z2: 0px 3px 1px -2px var(--jp-shadow-umbra-color),
    0px 2px 2px 0px var(--jp-shadow-penumbra-color),
    0px 1px 5px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z4: 0px 2px 4px -1px var(--jp-shadow-umbra-color),
    0px 4px 5px 0px var(--jp-shadow-penumbra-color),
    0px 1px 10px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z6: 0px 3px 5px -1px var(--jp-shadow-umbra-color),
    0px 6px 10px 0px var(--jp-shadow-penumbra-color),
    0px 1px 18px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z8: 0px 5px 5px -3px var(--jp-shadow-umbra-color),
    0px 8px 10px 1px var(--jp-shadow-penumbra-color),
    0px 3px 14px 2px var(--jp-shadow-ambient-color);
  --jp-elevation-z12: 0px 7px 8px -4px var(--jp-shadow-umbra-color),
    0px 12px 17px 2px var(--jp-shadow-penumbra-color),
    0px 5px 22px 4px var(--jp-shadow-ambient-color);
  --jp-elevation-z16: 0px 8px 10px -5px var(--jp-shadow-umbra-color),
    0px 16px 24px 2px var(--jp-shadow-penumbra-color),
    0px 6px 30px 5px var(--jp-shadow-ambient-color);
  --jp-elevation-z20: 0px 10px 13px -6px var(--jp-shadow-umbra-color),
    0px 20px 31px 3px var(--jp-shadow-penumbra-color),
    0px 8px 38px 7px var(--jp-shadow-ambient-color);
  --jp-elevation-z24: 0px 11px 15px -7px var(--jp-shadow-umbra-color),
    0px 24px 38px 3px var(--jp-shadow-penumbra-color),
    0px 9px 46px 8px var(--jp-shadow-ambient-color);

  /* Borders
   *
   * The following variables, specify the visual styling of borders in JupyterLab.
   */

  --jp-border-width: 1px;
  --jp-border-color0: var(--md-grey-400);
  --jp-border-color1: var(--md-grey-400);
  --jp-border-color2: var(--md-grey-300);
  --jp-border-color3: var(--md-grey-200);
  --jp-border-radius: 2px;

  /* UI Fonts
   *
   * The UI font CSS variables are used for the typography all of the JupyterLab
   * user interface elements that are not directly user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-ui-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-ui-font-scale-factor: 1.2;
  --jp-ui-font-size0: 0.83333em;
  --jp-ui-font-size1: 13px; /* Base font size */
  --jp-ui-font-size2: 1.2em;
  --jp-ui-font-size3: 1.44em;

  --jp-ui-font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica,
    Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';

  /*
   * Use these font colors against the corresponding main layout colors.
   * In a light theme, these go from dark to light.
   */

  /* Defaults use Material Design specification */
  --jp-ui-font-color0: rgba(0, 0, 0, 1);
  --jp-ui-font-color1: rgba(0, 0, 0, 0.87);
  --jp-ui-font-color2: rgba(0, 0, 0, 0.54);
  --jp-ui-font-color3: rgba(0, 0, 0, 0.38);

  /*
   * Use these against the brand/accent/warn/error colors.
   * These will typically go from light to darker, in both a dark and light theme.
   */

  --jp-ui-inverse-font-color0: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color1: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color2: rgba(255, 255, 255, 0.7);
  --jp-ui-inverse-font-color3: rgba(255, 255, 255, 0.5);

  /* Content Fonts
   *
   * Content font variables are used for typography of user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-content-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-content-line-height: 1.6;
  --jp-content-font-scale-factor: 1.2;
  --jp-content-font-size0: 0.83333em;
  --jp-content-font-size1: 14px; /* Base font size */
  --jp-content-font-size2: 1.2em;
  --jp-content-font-size3: 1.44em;
  --jp-content-font-size4: 1.728em;
  --jp-content-font-size5: 2.0736em;

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-content-presentation-font-size1: 17px;

  --jp-content-heading-line-height: 1;
  --jp-content-heading-margin-top: 1.2em;
  --jp-content-heading-margin-bottom: 0.8em;
  --jp-content-heading-font-weight: 500;

  /* Defaults use Material Design specification */
  --jp-content-font-color0: rgba(0, 0, 0, 1);
  --jp-content-font-color1: rgba(0, 0, 0, 0.87);
  --jp-content-font-color2: rgba(0, 0, 0, 0.54);
  --jp-content-font-color3: rgba(0, 0, 0, 0.38);

  --jp-content-link-color: var(--md-blue-700);

  --jp-content-font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji',
    'Segoe UI Symbol';

  /*
   * Code Fonts
   *
   * Code font variables are used for typography of code and other monospaces content.
   */

  --jp-code-font-size: 13px;
  --jp-code-line-height: 1.3077; /* 17px for 13px base */
  --jp-code-padding: 5px; /* 5px for 13px base, codemirror highlighting needs integer px value */
  --jp-code-font-family-default: Menlo, Consolas, 'DejaVu Sans Mono', monospace;
  --jp-code-font-family: var(--jp-code-font-family-default);

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-code-presentation-font-size: 16px;

  /* may need to tweak cursor width if you change font size */
  --jp-code-cursor-width0: 1.4px;
  --jp-code-cursor-width1: 2px;
  --jp-code-cursor-width2: 4px;

  /* Layout
   *
   * The following are the main layout colors use in JupyterLab. In a light
   * theme these would go from light to dark.
   */

  --jp-layout-color0: white;
  --jp-layout-color1: white;
  --jp-layout-color2: var(--md-grey-200);
  --jp-layout-color3: var(--md-grey-400);
  --jp-layout-color4: var(--md-grey-600);

  /* Inverse Layout
   *
   * The following are the inverse layout colors use in JupyterLab. In a light
   * theme these would go from dark to light.
   */

  --jp-inverse-layout-color0: #111111;
  --jp-inverse-layout-color1: var(--md-grey-900);
  --jp-inverse-layout-color2: var(--md-grey-800);
  --jp-inverse-layout-color3: var(--md-grey-700);
  --jp-inverse-layout-color4: var(--md-grey-600);

  /* Brand/accent */

  --jp-brand-color0: var(--md-blue-900);
  --jp-brand-color1: var(--md-blue-700);
  --jp-brand-color2: var(--md-blue-300);
  --jp-brand-color3: var(--md-blue-100);
  --jp-brand-color4: var(--md-blue-50);

  --jp-accent-color0: var(--md-green-900);
  --jp-accent-color1: var(--md-green-700);
  --jp-accent-color2: var(--md-green-300);
  --jp-accent-color3: var(--md-green-100);

  /* State colors (warn, error, success, info) */

  --jp-warn-color0: var(--md-orange-900);
  --jp-warn-color1: var(--md-orange-700);
  --jp-warn-color2: var(--md-orange-300);
  --jp-warn-color3: var(--md-orange-100);

  --jp-error-color0: var(--md-red-900);
  --jp-error-color1: var(--md-red-700);
  --jp-error-color2: var(--md-red-300);
  --jp-error-color3: var(--md-red-100);

  --jp-success-color0: var(--md-green-900);
  --jp-success-color1: var(--md-green-700);
  --jp-success-color2: var(--md-green-300);
  --jp-success-color3: var(--md-green-100);

  --jp-info-color0: var(--md-cyan-900);
  --jp-info-color1: var(--md-cyan-700);
  --jp-info-color2: var(--md-cyan-300);
  --jp-info-color3: var(--md-cyan-100);

  /* Cell specific styles */

  --jp-cell-padding: 5px;

  --jp-cell-collapser-width: 8px;
  --jp-cell-collapser-min-height: 20px;
  --jp-cell-collapser-not-active-hover-opacity: 0.6;

  --jp-cell-editor-background: var(--md-grey-100);
  --jp-cell-editor-border-color: var(--md-grey-300);
  --jp-cell-editor-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-cell-editor-active-background: var(--jp-layout-color0);
  --jp-cell-editor-active-border-color: var(--jp-brand-color1);

  --jp-cell-prompt-width: 64px;
  --jp-cell-prompt-font-family: var(--jp-code-font-family-default);
  --jp-cell-prompt-letter-spacing: 0px;
  --jp-cell-prompt-opacity: 1;
  --jp-cell-prompt-not-active-opacity: 0.5;
  --jp-cell-prompt-not-active-font-color: var(--md-grey-700);
  /* A custom blend of MD grey and blue 600
   * See https://meyerweb.com/eric/tools/color-blend/#546E7A:1E88E5:5:hex */
  --jp-cell-inprompt-font-color: #307fc1;
  /* A custom blend of MD grey and orange 600
   * https://meyerweb.com/eric/tools/color-blend/#546E7A:F4511E:5:hex */
  --jp-cell-outprompt-font-color: #bf5b3d;

  /* Notebook specific styles */

  --jp-notebook-padding: 10px;
  --jp-notebook-select-background: var(--jp-layout-color1);
  --jp-notebook-multiselected-color: var(--md-blue-50);

  /* The scroll padding is calculated to fill enough space at the bottom of the
  notebook to show one single-line cell (with appropriate padding) at the top
  when the notebook is scrolled all the way to the bottom. We also subtract one
  pixel so that no scrollbar appears if we have just one single-line cell in the
  notebook. This padding is to enable a 'scroll past end' feature in a notebook.
  */
  --jp-notebook-scroll-padding: calc(
    100% - var(--jp-code-font-size) * var(--jp-code-line-height) -
      var(--jp-code-padding) - var(--jp-cell-padding) - 1px
  );

  /* Rendermime styles */

  --jp-rendermime-error-background: #fdd;
  --jp-rendermime-table-row-background: var(--md-grey-100);
  --jp-rendermime-table-row-hover-background: var(--md-light-blue-50);

  /* Dialog specific styles */

  --jp-dialog-background: rgba(0, 0, 0, 0.25);

  /* Console specific styles */

  --jp-console-padding: 10px;

  /* Toolbar specific styles */

  --jp-toolbar-border-color: var(--jp-border-color1);
  --jp-toolbar-micro-height: 8px;
  --jp-toolbar-background: var(--jp-layout-color1);
  --jp-toolbar-box-shadow: 0px 0px 2px 0px rgba(0, 0, 0, 0.24);
  --jp-toolbar-header-margin: 4px 4px 0px 4px;
  --jp-toolbar-active-background: var(--md-grey-300);

  /* Statusbar specific styles */

  --jp-statusbar-height: 24px;

  /* Input field styles */

  --jp-input-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-input-active-background: var(--jp-layout-color1);
  --jp-input-hover-background: var(--jp-layout-color1);
  --jp-input-background: var(--md-grey-100);
  --jp-input-border-color: var(--jp-border-color1);
  --jp-input-active-border-color: var(--jp-brand-color1);
  --jp-input-active-box-shadow-color: rgba(19, 124, 189, 0.3);

  /* General editor styles */

  --jp-editor-selected-background: #d9d9d9;
  --jp-editor-selected-focused-background: #d7d4f0;
  --jp-editor-cursor-color: var(--jp-ui-font-color0);

  /* Code mirror specific styles */

  --jp-mirror-editor-keyword-color: #008000;
  --jp-mirror-editor-atom-color: #88f;
  --jp-mirror-editor-number-color: #080;
  --jp-mirror-editor-def-color: #00f;
  --jp-mirror-editor-variable-color: var(--md-grey-900);
  --jp-mirror-editor-variable-2-color: #05a;
  --jp-mirror-editor-variable-3-color: #085;
  --jp-mirror-editor-punctuation-color: #05a;
  --jp-mirror-editor-property-color: #05a;
  --jp-mirror-editor-operator-color: #aa22ff;
  --jp-mirror-editor-comment-color: #408080;
  --jp-mirror-editor-string-color: #ba2121;
  --jp-mirror-editor-string-2-color: #708;
  --jp-mirror-editor-meta-color: #aa22ff;
  --jp-mirror-editor-qualifier-color: #555;
  --jp-mirror-editor-builtin-color: #008000;
  --jp-mirror-editor-bracket-color: #997;
  --jp-mirror-editor-tag-color: #170;
  --jp-mirror-editor-attribute-color: #00c;
  --jp-mirror-editor-header-color: blue;
  --jp-mirror-editor-quote-color: #090;
  --jp-mirror-editor-link-color: #00c;
  --jp-mirror-editor-error-color: #f00;
  --jp-mirror-editor-hr-color: #999;

  /* Vega extension styles */

  --jp-vega-background: white;

  /* Sidebar-related styles */

  --jp-sidebar-min-width: 250px;

  /* Search-related styles */

  --jp-search-toggle-off-opacity: 0.5;
  --jp-search-toggle-hover-opacity: 0.8;
  --jp-search-toggle-on-opacity: 1;
  --jp-search-selected-match-background-color: rgb(245, 200, 0);
  --jp-search-selected-match-color: black;
  --jp-search-unselected-match-background-color: var(
    --jp-inverse-layout-color0
  );
  --jp-search-unselected-match-color: var(--jp-ui-inverse-font-color0);

  /* Icon colors that work well with light or dark backgrounds */
  --jp-icon-contrast-color0: var(--md-purple-600);
  --jp-icon-contrast-color1: var(--md-green-600);
  --jp-icon-contrast-color2: var(--md-pink-600);
  --jp-icon-contrast-color3: var(--md-blue-600);
}
</style>

<style type="text/css">
/* Misc */
a.anchor-link {
  display: none;
}

.highlight  {
  margin: 0.4em;
}

/* Input area styling */
.jp-InputArea {
  overflow: hidden;
}

.jp-InputArea-editor {
  overflow: hidden;
}

/* Using table instead of flexbox so that we can use break-inside property */
/* CSS rules under this comment should not be required anymore after we move to the JupyterLab 4.0 CSS */


.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  min-width: calc(
    var(--jp-cell-prompt-width) - var(--jp-private-cell-scrolling-output-offset)
  );
}

.jp-OutputArea-child {
  display: table;
  width: 100%;
}

.jp-OutputPrompt {
  display: table-cell;
  vertical-align: top;
  min-width: var(--jp-cell-prompt-width);
}

body[data-format='mobile'] .jp-OutputPrompt {
  display: table-row;
}

.jp-OutputArea-output {
  display: table-cell;
  width: 100%;
}

body[data-format='mobile'] .jp-OutputArea-child .jp-OutputArea-output {
  display: table-row;
}

.jp-OutputArea-output.jp-OutputArea-executeResult {
  width: 100%;
}

@media print {
  .jp-Collapser {
    display: none;
  }

  .jp-Cell-inputWrapper,
  .jp-Cell-outputWrapper {
    display: block;
  }

  .jp-OutputArea-child {
    break-inside: avoid-page;
  }
}
</style>

<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/latest.js?config=TeX-AMS_CHTML-full,Safe"> </script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    init_mathjax = function() {
        if (window.MathJax) {
        // MathJax loaded
            MathJax.Hub.Config({
                TeX: {
                    equationNumbers: {
                    autoNumber: "AMS",
                    useLabelIds: true
                    }
                },
                tex2jax: {
                    inlineMath: [ ['$','$'], ["\\(","\\)"] ],
                    displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
                    processEscapes: true,
                    processEnvironments: true
                },
                displayAlign: 'center',
                CommonHTML: {
                    linebreaks: { 
                    automatic: true 
                    }
                }
            });
        
            MathJax.Hub.Queue(["Typeset", MathJax.Hub]);
        }
    }
    init_mathjax();
    </script>
    <!-- End of mathjax configuration --></head>
<body class="jp-Notebook" data-jp-theme-light="true" data-jp-theme-name="JupyterLab Light">

<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Examining the Hidden Gems: Wine for Casuals Consumer</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Matthew Sebsibe</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Introduction</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>While researching topics to focus on I went to Total Wine to buy my sister a gift. There I felt overwhelmed by the analysis paralysis that is a Walmart for wine. Displayed in the chart below are some classifications of wine. It is very expanisve. There are over 10,000 wine grape varieties in the world. Some major categories include: red, white, rose, sparkling and fortified wine. Personally, I wanted to create a project that I felt would be useful to myself in understanding this massive space. In addition, my goal is to use Data Science to simplify the area. Wine is synonymous to snobbery, however, there are many great bottles for relatively cheap. I will also explore if higher priced wine is worth it, but that will be explained more in subsequent sections.</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><img src="https://thewinewankers.files.wordpress.com/2014/02/a-different-types-of-wine-infographic-chart3.png" width=1000 height=500 /></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Helpful resources: 
The image found above is from the book Wine Folly. I highly reccomend this for beginners intimdated by all the complexities of wine. This book is a good first step in understanding some terms Sommeliers use and different components that distinguish varieties of wine. As an added bonus, the book provides a lot of wine/food pairings. This book is good to get at libraries for its outstanding visuals.</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Youtube Channels:
<a href="https://www.youtube.com/user/askawinemaker/videos">https://www.youtube.com/user/askawinemaker/videos</a>
<a href="https://www.youtube.com/user/WineAlign">https://www.youtube.com/user/WineAlign</a></p>
<p>I learn best through visual and audio means so seeing someone explain features of bottles as well as basic wine ettiquette has helped me and I believe can be useful to others.</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>For the analysis of our data we will follow the The Data Science Pipeline in order to understand more about the data in front of us</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Disclaimer: This project is meant to explore the topic of wine in a healthy manner. Please practice safe and lawful consumption of alcohol. Be safe and know your limits.</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Data Collection/Curation</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>For my dataset, I was lucky to find one on Kaggle with over 100,000 entries. The link can be found here: <a href="https://www.kaggle.com/datasets/christopheiv/winemagdata130k">https://www.kaggle.com/datasets/christopheiv/winemagdata130k</a> . I was able to download this data in a CSV (Comma-separated values) file. What this means is a text-file that is seperated by commas to distinguish information. Within this dataset are many useful columns including the name of the bottle, country of origin, price, description, and points. Points refer to a score out of 100 that refer to the level of wine a sommelier would rate a wine. Wine Spectator a renowned wine magazine with 400000+ wine expert wine ratings has blind-taste tests of wine and scores wine using this scale:</p>
<p>95-100 Classic: a great wine</p>
<p>90-94 Outstanding: a wine of superior character and style</p>
<p>85-89 Very good: a wine with special qualities</p>
<p>80-84 Good: a solid, well-made wine</p>
<p>75-79 Mediocre: a drinkable wine that may have minor flaws</p>
<p>50-74 Not recommended</p>
<p>Different websites and magazines approach the scale differently, but the general trend is similar with preferences given to bottles over 90+ being excellent bottles. Without this dataset, the way I would approach scrapping is by doing a quick google search of wine data. Vivino is a great example of a website that stores many different reviewes of wine. However, it is very expansive and sorts by type of wine. So I would scrape a few thousand from each variety with a goal of about 10000+ reviews to have a good representation of bottom,mid, and high shelf wine from a multitude of wine varieties. Similar to Project 1, the data is tabulated fairly easily to scrape the HTML with BeautifulSoup. Luckly the dataset I found from Kaggle did a similar approach using data from WineMag. For the purposes of this project, the scale described above matches, but for Wine Magazine specific scale, that can be found in the link here: <a href="https://www.winemag.com/2010/04/09/you-asked-how-is-a-wines-score-determined/">https://www.winemag.com/2010/04/09/you-asked-how-is-a-wines-score-determined/</a> . Wine Enthusiast Magazine also referred to as Wine Mag has some great resources for finding bottles of wine for every budget and is a great resource for beginners and experts alike to learn something new.</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Data Management / Representation</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>For this project we will rely heavily on the Pandas library to represent our data. The matplot and seaborn library will be key in visualizing our data. Finally numpy will be key in preforming various operations on our data. As described above, the data is stored in a csv file. Once the file is imported into the Jupyter Notebook, all that is needed is to call the read_csv file to import all of the data stored. From there, it is the job of the data scientist to massage the data and make choices about missing data. For this data set, I can immediately drop the taster name, twitter handle, and unnamed column as none of these columns store useful data for our analysis.</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[1]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sns</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">from</span> <span class="nn">scipy</span> <span class="kn">import</span> <span class="n">stats</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Lets take a peek into our data.</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[2]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#wine set before dropping unnecessary operations</span>
<span class="n">wine_data</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;winemag-data-130k-v2.csv&quot;</span><span class="p">)</span>

<span class="c1">#Taster name and twitter tag are unnecesary for analysis</span>
<span class="n">wine_data</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="s2">&quot;taster_name&quot;</span><span class="p">,</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span> <span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="n">wine_data</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="s2">&quot;taster_twitter_handle&quot;</span><span class="p">,</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span> <span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="n">wine_data</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="s2">&quot;Unnamed: 0&quot;</span><span class="p">,</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span> <span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>For the dataset we have many different characteristics described in the kaggle spec:</p>
<p>country-The country that the wine originates from</p>
<p>description- An added description of some bottles in the dataset</p>
<p>designation-The vineyard within the winery where the grapes that made the wine are from</p>
<p>points-The point value that WineEnthusiast rated the wine on a scale of 1-100</p>
<p>price-The cost for a bottle of the wine</p>
<p>province-The province or state that the wine is from</p>
<p>region_1:The wine growing area in a province or state (ie Napa)</p>
<p>region_2:Sometimes there are more specific regions specified within a wine growing area (ie Rutherford inside the Napa Valley),</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[3]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">wine_data</span><span class="o">.</span><span class="n">info</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>&lt;class &#39;pandas.core.frame.DataFrame&#39;&gt;
RangeIndex: 129971 entries, 0 to 129970
Data columns (total 11 columns):
 #   Column       Non-Null Count   Dtype  
---  ------       --------------   -----  
 0   country      129908 non-null  object 
 1   description  129971 non-null  object 
 2   designation  92506 non-null   object 
 3   points       129971 non-null  int64  
 4   price        120975 non-null  float64
 5   province     129908 non-null  object 
 6   region_1     108724 non-null  object 
 7   region_2     50511 non-null   object 
 8   title        129971 non-null  object 
 9   variety      129970 non-null  object 
 10  winery       129971 non-null  object 
dtypes: float64(1), int64(1), object(9)
memory usage: 10.9+ MB
</pre>
</div>
</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>For this model, I have chosen to drop rows without a wine bottle name, price, and point value. These will be needed in later sections and since we have so many data points we will still have many values to work with as shown below.</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[4]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Dropping columns that do not have a price, point, or wine bottle name</span>
<span class="n">before</span> <span class="o">=</span> <span class="nb">len</span><span class="p">(</span><span class="n">wine_data</span><span class="o">.</span><span class="n">index</span><span class="p">)</span>

<span class="n">wine_data</span> <span class="o">=</span> <span class="n">wine_data</span><span class="o">.</span><span class="n">dropna</span><span class="p">(</span><span class="n">subset</span><span class="o">=</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">,</span><span class="s1">&#39;points&#39;</span><span class="p">,</span><span class="s1">&#39;title&#39;</span><span class="p">])</span>

<span class="n">after</span> <span class="o">=</span> <span class="nb">len</span><span class="p">(</span><span class="n">wine_data</span><span class="o">.</span><span class="n">index</span><span class="p">)</span>

<span class="n">tot</span> <span class="o">=</span> <span class="n">before</span> <span class="o">-</span> <span class="n">after</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Number of values dropped = &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">tot</span><span class="p">))</span>

<span class="n">tot</span> <span class="o">=</span> <span class="n">tot</span><span class="o">/</span><span class="n">before</span>
<span class="n">tot</span> <span class="o">=</span> <span class="n">tot</span><span class="o">*</span><span class="mi">100</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Percent of values dropped = &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">tot</span><span class="p">)</span> <span class="o">+</span> <span class="s2">&quot;%&quot;</span><span class="p">)</span>

<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Number of values left = &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">after</span><span class="p">))</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>Number of values dropped = 8996
Percent of values dropped = 6.921544036746659%
Number of values left = 120975
</pre>
</div>
</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Since we still have over 120000 values to work with we can move forward with this model.</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>In our model I utilized a CSV with data already in it. However, if we want to scrape data ourselves, we can take an approach similar to Project 1.</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>The approach I would take would be to find a website that has data formatted similar to the HTML table. There are many great websites to pick from like Vivino and WineMag. From there we can use, beautiful soup to help "prettify" our data and have it formatted to our liking. From there we call the pandas read_csv function in order to have that formatted into a data set similar to how we have our dataframe above. The import requests library I imported above is utilized to allow our data to get it using the requests library.</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Explanatory Data Analysis</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[5]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Analyze Stats for Price</span>
<span class="n">mean</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">mean</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">])</span>
<span class="n">median</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">median</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">])</span>
<span class="n">mini</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">min</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">])</span>
<span class="n">maxi</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">max</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">])</span>
<span class="n">stddev</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">std</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">])</span>

<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;SUMMARY STATS FOR PRICE OF WINE IN THE DATASET&#39;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Mean: &#39;</span><span class="p">,</span> <span class="n">mean</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Std Dev: &#39;</span><span class="p">,</span> <span class="n">stddev</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Median: &#39;</span><span class="p">,</span> <span class="n">median</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Min: &#39;</span><span class="p">,</span> <span class="n">mini</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Max: &#39;</span><span class="p">,</span> <span class="n">maxi</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>SUMMARY STATS FOR PRICE OF WINE IN THE DATASET
Mean:  35.363389129985535 
Std Dev:  41.022048119411714 
Median:  25.0 
Min:  4.0 
Max:  3300.0
</pre>
</div>
</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[6]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">20</span><span class="p">,</span><span class="mi">15</span><span class="p">))</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="s2">&quot;country&quot;</span><span class="p">,</span> <span class="n">data</span><span class="o">=</span><span class="n">wine_data</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">ax</span><span class="o">.</span><span class="n">get_xticklabels</span><span class="p">(),</span><span class="n">rotation</span> <span class="o">=</span> <span class="mi">75</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[7]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">20</span><span class="p">,</span><span class="mi">15</span><span class="p">))</span> 
<span class="n">ax</span> <span class="o">=</span> <span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="s2">&quot;points&quot;</span><span class="p">,</span> <span class="n">data</span><span class="o">=</span><span class="n">wine_data</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">ax</span><span class="o">.</span><span class="n">get_xticklabels</span><span class="p">(),</span><span class="n">rotation</span> <span class="o">=</span> <span class="mi">0</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[8]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Analyze Stats for Price</span>
<span class="n">mean</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">mean</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;points&#39;</span><span class="p">])</span>
<span class="n">median</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">median</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;points&#39;</span><span class="p">])</span>
<span class="n">mini</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">min</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;points&#39;</span><span class="p">])</span>
<span class="n">maxi</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">max</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;points&#39;</span><span class="p">])</span>
<span class="n">stddev</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">std</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;points&#39;</span><span class="p">])</span>

<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;SUMMARY STATS FOR POINTS OF WINE IN THE DATASET&#39;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Mean: &#39;</span><span class="p">,</span> <span class="n">mean</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Std Dev: &#39;</span><span class="p">,</span> <span class="n">stddev</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Median: &#39;</span><span class="p">,</span> <span class="n">median</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Min: &#39;</span><span class="p">,</span> <span class="n">mini</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Max: &#39;</span><span class="p">,</span> <span class="n">maxi</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>SUMMARY STATS FOR POINTS OF WINE IN THE DATASET
Mean:  88.42188055383343 
Std Dev:  3.044495379452498 
Median:  88.0 
Min:  80 
Max:  100
</pre>
</div>
</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span> 
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>As we can see, we have a pretty mixed dataset. Most of the wine is from the US, followed by France, Italy, Spain, and Portugal. However, we can see that there are a lot of different countries in our dataset. The points of the data set follow a fairly normal distribution centered around between 87 and 89 points. We can see that there are a lot of bottles in the 84-93 range and the values outside that range drop as they get further away from that range. There are a lot of wine prices in our datset, but the average is around x. The highest priced wine bottle in this dataset is x and the cheapest is x.</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Hypothesis Testing</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>To start this part of the process, I first want to examine some of the correlation</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[9]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">wine_data</span><span class="o">.</span><span class="n">corr</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[9]:</div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>points</th>
      <th>price</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>points</th>
      <td>1.000000</td>
      <td>0.416167</td>
    </tr>
    <tr>
      <th>price</th>
      <td>0.416167</td>
      <td>1.000000</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[10]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">less_than_100</span> <span class="o">=</span> <span class="n">wine_data</span><span class="p">[</span><span class="n">wine_data</span><span class="p">[</span><span class="s2">&quot;price&quot;</span><span class="p">]</span> <span class="o">&lt;=</span> <span class="mi">100</span><span class="p">]</span>
<span class="n">less_than_100</span><span class="o">.</span><span class="n">corr</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[10]:</div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>points</th>
      <th>price</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>points</th>
      <td>1.000000</td>
      <td>0.548092</td>
    </tr>
    <tr>
      <th>price</th>
      <td>0.548092</td>
      <td>1.000000</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[11]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">less_than_50</span> <span class="o">=</span> <span class="n">wine_data</span><span class="p">[</span><span class="n">wine_data</span><span class="p">[</span><span class="s2">&quot;price&quot;</span><span class="p">]</span> <span class="o">&lt;=</span> <span class="mi">50</span><span class="p">]</span>
<span class="n">less_than_50</span><span class="o">.</span><span class="n">corr</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[11]:</div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>points</th>
      <th>price</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>points</th>
      <td>1.000000</td>
      <td>0.497463</td>
    </tr>
    <tr>
      <th>price</th>
      <td>0.497463</td>
      <td>1.000000</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[12]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># store the feature matrix (X) and response vector (y)</span>
<span class="n">x</span> <span class="o">=</span> <span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span><span class="o">.</span><span class="n">reshape</span><span class="p">(</span><span class="o">-</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span>
<span class="n">y</span> <span class="o">=</span> <span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;points&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span><span class="o">.</span><span class="n">reshape</span><span class="p">(</span><span class="o">-</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span>

<span class="nb">print</span><span class="p">(</span><span class="n">x</span><span class="o">.</span><span class="n">size</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">y</span><span class="o">.</span><span class="n">size</span><span class="p">)</span>

<span class="c1">#Ensure both equal each other and match up</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>120975
120975
</pre>
</div>
</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[13]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">from</span> <span class="nn">sklearn.linear_model</span> <span class="kn">import</span> <span class="n">LinearRegression</span>


<span class="n">linear_regressor</span> <span class="o">=</span> <span class="n">LinearRegression</span><span class="p">()</span>  <span class="c1"># create object for the class</span>
<span class="n">linear_regressor</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>  <span class="c1"># perform linear regression</span>
<span class="n">Y_pred</span> <span class="o">=</span> <span class="n">linear_regressor</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>  
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[14]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">Y_pred</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;red&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>In this case we can see that a simple linear regression model may not make sense for all of the data points, However let's attempt it for the miniture data set we created earlier.</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[15]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">x1</span> <span class="o">=</span> <span class="n">less_than_100</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span><span class="o">.</span><span class="n">reshape</span><span class="p">(</span><span class="o">-</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span>
<span class="n">y1</span> <span class="o">=</span> <span class="n">less_than_100</span><span class="p">[</span><span class="s1">&#39;points&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span><span class="o">.</span><span class="n">reshape</span><span class="p">(</span><span class="o">-</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span>

<span class="n">linear_regressor</span> <span class="o">=</span> <span class="n">LinearRegression</span><span class="p">()</span>  <span class="c1"># create object for the class</span>
<span class="n">linear_regressor</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x1</span><span class="p">,</span> <span class="n">y1</span><span class="p">)</span>  <span class="c1"># perform linear regression</span>
<span class="n">Y_pred</span> <span class="o">=</span> <span class="n">linear_regressor</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">x1</span><span class="p">)</span>  
<span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x1</span><span class="p">,</span> <span class="n">y1</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">x1</span><span class="p">,</span> <span class="n">Y_pred</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;red&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>This seems to match our data somewhat better, however are there other approaches we can utilize.</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[16]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.linear_model</span> <span class="kn">import</span> <span class="n">SGDRegressor</span>
<span class="kn">from</span> <span class="nn">sklearn.datasets</span> <span class="kn">import</span> <span class="n">load_boston</span>
<span class="kn">from</span> <span class="nn">sklearn.datasets</span> <span class="kn">import</span> <span class="n">make_regression</span>
<span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">mean_squared_error</span>
<span class="kn">from</span> <span class="nn">sklearn.model_selection</span> <span class="kn">import</span> <span class="n">train_test_split</span>
<span class="kn">from</span> <span class="nn">sklearn.model_selection</span> <span class="kn">import</span> <span class="n">cross_val_score</span>
<span class="kn">from</span> <span class="nn">sklearn.preprocessing</span> <span class="kn">import</span> <span class="n">scale</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[23]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">xtrain</span><span class="p">,</span> <span class="n">xtest</span><span class="p">,</span> <span class="n">ytrain</span><span class="p">,</span> <span class="n">ytest</span><span class="o">=</span><span class="n">train_test_split</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">,</span> <span class="n">test_size</span><span class="o">=</span><span class="mf">0.25</span><span class="p">)</span>
<span class="n">sgdr</span> <span class="o">=</span> <span class="n">SGDRegressor</span><span class="p">()</span>

<span class="n">sgdr</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">xtrain</span><span class="p">,</span> <span class="n">ytrain</span><span class="p">)</span>

<span class="n">score</span> <span class="o">=</span> <span class="n">sgdr</span><span class="o">.</span><span class="n">score</span><span class="p">(</span><span class="n">xtrain</span><span class="p">,</span> <span class="n">ytrain</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;R-squared:&quot;</span><span class="p">,</span> <span class="n">score</span><span class="p">)</span>

<span class="n">cv_score</span> <span class="o">=</span> <span class="n">cross_val_score</span><span class="p">(</span><span class="n">sgdr</span><span class="p">,</span> <span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">,</span> <span class="n">cv</span> <span class="o">=</span> <span class="mi">10</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;CV mean score: &quot;</span><span class="p">,</span> <span class="n">cv_score</span><span class="o">.</span><span class="n">mean</span><span class="p">())</span>

<span class="n">ypred</span> <span class="o">=</span> <span class="n">sgdr</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">xtest</span><span class="p">)</span>

<span class="n">mse</span> <span class="o">=</span> <span class="n">mean_squared_error</span><span class="p">(</span><span class="n">ytest</span><span class="p">,</span> <span class="n">ypred</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;MSE: &quot;</span><span class="p">,</span> <span class="n">mse</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;RMSE: &quot;</span><span class="p">,</span> <span class="n">mse</span><span class="o">**</span><span class="p">(</span><span class="mi">1</span><span class="o">/</span><span class="mf">2.0</span><span class="p">))</span> 

<span class="n">x_ax</span> <span class="o">=</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">ytest</span><span class="p">))</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">x_ax</span><span class="p">,</span> <span class="n">ytest</span><span class="p">,</span> <span class="n">linewidth</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span> <span class="n">label</span><span class="o">=</span><span class="s2">&quot;original&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">x_ax</span><span class="p">,</span> <span class="n">ypred</span><span class="p">,</span> <span class="n">linewidth</span><span class="o">=</span><span class="mf">2.1</span><span class="p">,</span> <span class="n">label</span><span class="o">=</span><span class="s2">&quot;predicted&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Y-test and Y-predicted data for SGD Regressor&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;X-axis&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;Y-axis&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">loc</span><span class="o">=</span><span class="s1">&#39;best&#39;</span><span class="p">,</span><span class="n">fancybox</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span> <span class="n">shadow</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">grid</span><span class="p">(</span><span class="kc">True</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span> 
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>CV mean score:  -64.99471316517506
MSE:  8.387096044012836
RMSE:  2.8960483497367298
</pre>
</div>
</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Above we use SGDRegressor() to implement a plain stochastic gradient descent (SGD) learning routine. This routine utilizes different loss functions and penalties in order to fit linear regression models for the training data above. With the large Root and MSE value we can see this is not a perfect regression model. The pearson-correlation values we looked at prior to implementing this makes these graphs make sense. We can see this as price may not be the greatest indicator of points after a certain price. It appears that the point system</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Communication of insights attained</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Contrary to popular belief there are many bottles that are great and relatively cheap An example search with results is shown below.</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">less_than_15_dollars</span> <span class="o">=</span> <span class="n">wine_data</span><span class="p">[</span><span class="n">wine_data</span><span class="p">[</span><span class="s2">&quot;price&quot;</span><span class="p">]</span> <span class="o">&lt;=</span> <span class="mi">20</span><span class="p">]</span>
<span class="n">cheap_excellent</span> <span class="o">=</span> <span class="n">less_than_15_dollars</span><span class="p">[</span><span class="n">less_than_15_dollars</span><span class="p">[</span><span class="s2">&quot;points&quot;</span><span class="p">]</span> <span class="o">&gt;=</span> <span class="mi">95</span><span class="p">]</span>
<span class="n">cheap_excellent</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">5</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">one_hundred_points</span> <span class="o">=</span> <span class="n">wine_data</span><span class="p">[</span><span class="n">wine_data</span><span class="p">[</span><span class="s2">&quot;points&quot;</span><span class="p">]</span> <span class="o">==</span> <span class="mi">99</span><span class="p">]</span>
<span class="n">one_hundred_points</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>I intend on exploring some of the options above. However, one note is that with such a p-value it may seem like a done deal to not think that expensive bottles of wine may be worth it, but that is not the goal of this process. The process is meant to uncover the hidden gems that are not explored and to understand wine does not have to be elitist. Be safe, enjoy responsibly, and thank you for a great semester!
Visit local winery. For Maryland the link is provided below. This project was very insightful in seeing the value of that 20-25 bottle of wine. In that range, there appears to be a ton of value and the bottles listed above are just a small example of that.</p>
<p><a href="https://marylandwine.com/map/">Interactive Wine Map of Maryland</a></p>

</div>
</div>
</div>
</body>







</html>
