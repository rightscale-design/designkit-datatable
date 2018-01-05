# Designkit Datatable

## Install

```bash
npm install designkit-datatable --save
```

## The CSS

```css
.ag-theme-designkit {
  position: relative;
}

.ag-theme-designkit.loading {
  height: 100%;
}

.ag-theme-designkit .ag-header {
  background-color: #fff;
  border-bottom: 1px solid #D1D6DC;
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}

.ag-theme-designkit .ag-header .ag-header-cell {
  font-size: 11px;
  font-weight: 600;
  line-height: 28px;
  color: #0A83F6;
}

.ag-theme-designkit .ag-header .ag-header-cell:focus, .ag-theme-designkit .ag-header .ag-header-cell:hover {
  color: #0769c6;
  cursor: pointer;
}

.ag-theme-designkit .ag-header .ag-header-cell:first-of-type:focus, .ag-theme-designkit .ag-header .ag-header-cell:first-of-type:hover {
  color: #0769c6;
  cursor: default;
}

.ag-theme-designkit .ag-header .ag-header-cell.align-right .ag-header-cell-label {
  padding: 4px 12px 4px 4px;
}

.ag-theme-designkit .ag-header .ag-header-cell.align-right .ag-header-cell-menu-button {
  float: left;
  margin-left: 16px;
}

.ag-theme-designkit .ag-header .ag-header-cell .ag-header-cell-resize {
  position: relative;
}

.ag-theme-designkit .ag-header .ag-header-cell .ag-header-cell-resize:after {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 4px;
  z-index: 1;
  content: "";
  border-right: solid 2px #f5f5f5;
  opacity: 1;
}

.ag-theme-designkit .ag-header .ag-header-cell .ag-header-cell-resize:hover:after {
  border-right: solid 2px #ebebeb;
  opacity: 1 !important;
}

.ag-theme-designkit .ag-header .ag-header-cell .ag-header-cell-menu-button {
  float: right;
  margin-right: 16px;
}

.ag-theme-designkit .ag-header .ag-header-cell-label {
  position: relative;
  padding: 4px 20px;
}

.ag-theme-designkit .ag-header .ag-icon-none {
  background-position: 2px 4px;
  background-size: 6px 9.8px;
  opacity: 1;
}

.ag-theme-designkit .ag-header .ag-icon-asc {
  background-position: 2px 3px;
  background-size: 6px 6px;
  opacity: 1;
}

.ag-theme-designkit .ag-header .ag-icon-desc {
  background-position: 2px 7px;
  background-size: 6px 6px;
  opacity: 1;
}

.ag-theme-designkit .ag-header .ag-icon-menu {
  margin-top: 12px;
  background-size: 10px;
}

.ag-theme-designkit .ag-body .ag-cell-not-inline-editing {
  padding: 4px 20px;
}

.ag-theme-designkit .ag-body .ag-row {
  border-bottom: 1px solid #e2e5e9;
}

.ag-theme-designkit .ag-body .ag-row a.label:hover:focus {
  color: #fff;
  text-decoration: none;
}

.ag-theme-designkit .ag-body .ag-row.ag-row-hover {
  background-color: #FAFAFA;
}

.ag-theme-designkit .ag-body .ag-row:first-of-type {
  border-top: 0 none;
}

.ag-theme-designkit .ag-body .ag-row.ag-row-selected .ag-cell {
  background: #F4F5F7;
}

.ag-theme-designkit .ag-body .ag-row.ag-row-selected .ag-cell a.label {
  text-decoration: none;
}

.ag-theme-designkit .ag-body .ag-cell {
  line-height: 24px;
  -webkit-user-select: auto;
     -moz-user-select: auto;
      -ms-user-select: auto;
          user-select: auto;
}

.ag-theme-designkit .ag-body .ag-cell.ag-cell-not-inline-editing:focus {
  outline: none;
}

.ag-theme-designkit .ag-body .ag-cell.checkbox-cell {
  padding-right: 0;
}

.ag-theme-designkit .ag-body .ag-cell.savings-cell {
  text-align: right;
}

.ag-theme-designkit .ag-body .ag-cell.actions-cell {
  padding-right: 24px;
  text-align: right;
}

.ag-theme-designkit .ag-body .ag-group-expanded span,
.ag-theme-designkit .ag-body .ag-group-contracted span {
  position: relative;
  top: 2px;
  margin-right: 12px;
}

.ag-theme-designkit .ag-body .ag-row .ag-row-group-indent-1 {
  padding-left: 2.4rem;
}

.ag-theme-designkit .ag-body .ag-row .ag-row-group-indent-2 {
  padding-left: 4.8rem;
}

.ag-theme-designkit .ag-body .ag-row .ag-row-group-indent-3 {
  padding-left: 7.2rem;
}

.ag-theme-designkit .ag-body .ag-icon-expanded {
  -webkit-transform: rotate3d(0, 0, 1, 0deg);
          transform: rotate3d(0, 0, 1, 0deg);
  -webkit-transform-origin: center center;
          transform-origin: center center;
}

.ag-theme-designkit .ag-body .ag-icon-contracted {
  -webkit-transform: rotate3d(0, 0, 1, -180deg);
          transform: rotate3d(0, 0, 1, -180deg);
  -webkit-transform-origin: center center;
          transform-origin: center center;
}

.ag-theme-designkit .ag-body .ag-group-child-count {
  margin-left: .4rem;
}

.ag-theme-designkit .ag-body .ag-cell-focus {
  outline: initial;
  box-shadow: 0 0 0 1px #0A83F6 inset;
}

.ag-theme-designkit .ag-body .ag-cell-range-selected-1:not(.ag-cell-focus) {
  color: #fff;
  background-color: rgba(35, 144, 247, 0.9);
}

.ag-theme-designkit .ag-header-cell-moving {
  background-color: rgba(226, 229, 233, 0.35);
}

.ag-theme-designkit .ag-menu {
  z-index: 5;
  padding: 4px;
  padding: 0;
  background: #fff;
  border: 1px solid #d1d6dc;
  border-radius: 2px;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05);
}

.ag-theme-designkit .ag-menu .ag-tab-header {
  width: 100%;
  min-width: 220px;
  background-color: #f4f5f7;
  box-shadow: 0 -1px 0 0 #d1d6dc inset;
}

.ag-theme-designkit .ag-menu .ag-tab-header .ag-tab {
  display: inline-block;
  height: 16px;
  box-sizing: initial;
  padding: 4px 8px;
  margin: 4px;
  margin-bottom: 0;
  text-align: center;
  vertical-align: middle;
  border: 1px solid transparent;
  border-bottom: 2px solid transparent;
}

.ag-theme-designkit .ag-menu .ag-tab-header .ag-tab.ag-tab-selected {
  background-color: #fff;
  border-color: #d1d6dc;
  border-bottom: 2px solid #fff !important;
}

.ag-theme-designkit .ag-menu .ag-tab-body {
  padding: 4px 0;
}

.ag-theme-designkit .ag-menu .ag-tab-body .ag-menu-list {
  margin-top: 0;
  margin-bottom: 0;
}

.ag-theme-designkit .ag-menu .ag-menu-list {
  display: table;
  width: 100%;
  margin-top: 4px;
  margin-bottom: 4px;
  cursor: default;
  border-collapse: collapse;
}

.ag-theme-designkit .ag-menu .ag-menu-option {
  display: table-row;
  padding-right: 8px;
  padding-left: 8px;
  line-height: 24px;
}

.ag-theme-designkit .ag-menu .ag-menu-option > span {
  display: table-cell;
  vertical-align: middle;
}

.ag-theme-designkit .ag-menu .ag-menu-option .ag-menu-option-icon {
  padding-right: 4px;
  padding-left: 4px;
}

.ag-theme-designkit .ag-menu .ag-menu-option .ag-menu-option-shortcut {
  padding-left: 8px;
}

.ag-theme-designkit .ag-menu .ag-menu-option .ag-menu-option-popup-pointer {
  width: 20px;
}

.ag-theme-designkit .ag-menu .ag-menu-option .ag-menu-option-text {
  color: #0A83F6;
}

.ag-theme-designkit .ag-menu .ag-menu-separator > span {
  height: 8px;
  background-image: url("data:image/svg+xml;utf8,<svg width='1' height='8px' viewBox='0 0 1 8px' xmlns='http://www.w3.org/2000/svg'> <line x1='0' y1='4px' x2='1' y2='4px' stroke-width='1' stroke='#E2E5E9'/> </svg>");
}

.ag-theme-designkit .ag-menu .ag-menu-separator-cell {
  display: table-cell;
}

.ag-theme-designkit .ag-menu .ag-menu-option-active {
  background: #F4F5F7;
}

.ag-theme-designkit .ag-column-select-panel .ag-column-select-column .ag-column-select-checkbox {
  margin-right: 4px;
  vertical-align: middle;
}

.ag-theme-designkit .ag-tool-panel {
  background-color: #fff;
  border-color: #D1D6DC;
  border-style: solid;
  border-width: 0 0 0 1px;
}

.ag-theme-designkit .ag-tool-panel .ag-column-select-panel {
  margin-top: 10px;
}

.ag-theme-designkit .ag-tool-panel .ag-pivot-mode {
  height: 25px;
  box-sizing: border-box;
  line-height: 25px;
  border-bottom: 1px solid #e2e5e9;
}

.ag-theme-designkit .ag-tool-panel .ag-pivot-mode .ag-pivot-mode-select {
  margin-left: 4px;
}

.ag-theme-designkit .ag-tool-panel .ag-column-drop {
  padding: 4px 0;
  padding-bottom: 8px;
  overflow: auto;
  clear: both;
  border-bottom: 1px solid #e2e5e9;
}

.ag-theme-designkit .ag-tool-panel .ag-column-drop .ag-column-drop-title {
  float: left;
  width: calc(100% - 20px);
  height: 20px;
  clear: right;
  line-height: 20px;
}

.ag-theme-designkit .ag-tool-panel .ag-column-drop .ag-column-drop-empty-message {
  padding-right: 4px;
  padding-left: 21px;
  clear: both;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 12px;
  font-weight: 400;
  line-height: 1;
  color: rgba(118, 137, 154, 0.8);
}

.ag-theme-designkit .ag-tool-panel .ag-column-drop .ag-icon {
  float: left;
  height: 20px;
  margin: 0 4px;
}

.ag-theme-designkit .ag-icon-menu {
  background-image: url("data:image/svg+xml;utf8,<svg width='10' height='10' viewBox='0 0 10 10' xmlns='http://www.w3.org/2000/svg'><g fill='#8596A4' fill-rule='evenodd'><path d='M0 0h10v2H0zM0 4h10v2H0zM0 8h10v2H0z'/></g></svg>");
}

.ag-theme-designkit .ag-icon-none {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='6' height='11' viewBox='0 0 6 11'><path fill='#fff' d='M6 7.1S5.9 7 5.8 7H.2c-.1 0-.2.1-.2.1v.1l.1.2 2.8 3.4H3l.1-.1 2.8-3.4.1-.2zM0 4.7c0 .1.1.1.2.1h5.6c.1 0 .2 0 .2-.1v-.1l-.1-.1-2.8-3.4L3 1l-.1.1L.1 4.5l-.1.2z'/><path fill='#2390F7' d='M6 6.1S5.9 6 5.8 6H.2c-.1 0-.2.1-.2.1v.1l.1.2 2.8 3.4H3l.1-.1 2.8-3.4.1-.2zM0 3.7c0 .1.1.1.2.1h5.6c.1 0 .2 0 .2-.1v-.1l-.1-.1L3.1.1 3 0l-.1.1L.1 3.5l-.1.2z'/></svg>");
}

.ag-theme-designkit .ag-icon-asc {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='6' height='6' viewBox='0 0 6 6'><path fill='#fff' d='M0 6c0 .1.1.1.2.1h5.6c.1 0 .2 0 .2-.1v-.1l-.1-.2-2.8-3.4h-.2L.1 5.7 0 6z'/><path fill='#2390F7' d='M0 4.7c0 .1.1.1.2.1h5.6c.1 0 .2 0 .2-.1v-.1l-.1-.1-2.8-3.4L3 1l-.1.1L.1 4.5l-.1.2z'/></svg>");
}

.ag-theme-designkit .ag-icon-desc {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='6' height='6' viewBox='0 0 6 6'><path fill='#fff' d='M6 2.3c0-.1-.1-.1-.2-.1H.2c-.1 0-.2 0-.2.1v.1l.1.2L2.9 6H3l.1-.1 2.8-3.4.1-.2z'/><path fill='#2390F7' d='M6 1.3c0-.1-.1-.1-.2-.1H.2c-.1 0-.2 0-.2.1v.1l.1.2L2.9 5H3l.1-.1 2.8-3.4.1-.2z'/></svg>");
}

.ag-theme-designkit .ag-icon-expanded {
  background-image: url("data:image/svg+xml;utf8,<svg width='12' height='8' viewBox='0 0 12 8' xmlns='http://www.w3.org/2000/svg'><title>Path 5</title><path d='M1 1l5.01 5L11 1.02' stroke='#0A83F6' stroke-width='2' fill='none' fill-rule='evenodd'/></svg>");
}

.ag-theme-designkit .ag-icon-contracted {
  background-image: url("data:image/svg+xml;utf8,<svg width='12' height='8' viewBox='0 0 12 8' xmlns='http://www.w3.org/2000/svg'><title>Path 5</title><path d='M1 1l5.01 5L11 1.02' stroke='#0A83F6' stroke-width='2' fill='none' fill-rule='evenodd'/></svg>");
}

.ag-theme-designkit .ag-icon-menu {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12'><g fill='#57626C' fill-rule='evenodd'><path d='M1 1h10v2H1zM1 5h10v2H1zM1 9h10v2H1z'/></g></svg>");
}

.ag-theme-designkit .ag-icon-columns {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12'><g fill='#57626C' fill-rule='evenodd'><path d='M1 1h4v2H1zM7 1h4v2H7zM1 5h4v2H1zM7 5h4v2H7zM1 9h4v2H1zM7 9h4v2H7z'/></g></svg>");
}

.ag-theme-designkit .ag-icon-pin {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12'><g fill='none' fill-rule='evenodd'><path fill='#57626C' d='M3 2h6v1H8v4l2 1H7l-1 3-1-3H2l2-1V3H3'/><path fill='#FFF' fill-opacity='.5' d='M5 3h1v4H5z'/><path fill='#FFF' fill-opacity='.28' d='M4 3h1v3H4z'/></g></svg>");
}

.ag-theme-designkit .ag-icon-small-right {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12'><path fill='#57626C' fill-rule='evenodd' d='M5 2l4 4-4 4'/></svg>");
}

.ag-theme-designkit .ag-icon-tick {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12'><path fill='none' fill-rule='evenodd' stroke='#57626C' stroke-width='2' d='M1.5 5.5l3 3 6-6'/></svg>");
}

.ag-theme-designkit .ag-icon-arrows {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='20' height='20' viewBox='0 0 20 20'><g fill='#57626C' fill-rule='nonzero'><path d='M16 6l-1.41 1.41L16.17 9H4v2h12.17l-1.58 1.59L16 14l4-4'/><path d='M4 6l1.41 1.41L3.83 9H16v2H3.83l1.58 1.59L4 14l-4-4'/><path d='M6 16l1.41-1.41L9 16.17V4h2v12.17l1.59-1.58L14 16l-4 4'/><path d='M14 4l-1.41 1.41L11 3.83V16H9V3.83L7.41 5.41 6 4l4-4'/></g></svg>");
}

.ag-theme-designkit .ag-icon-checkbox-unchecked {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12' xmlns:xlink='http://www.w3.org/1999/xlink'><defs><rect id='a' width='12' height='12' rx='1'/></defs><g fill='none' fill-rule='evenodd'><use fill='#FFF' xlink:href='#a'/><rect width='11' height='11' x='.5' y='.5' stroke='#57626C' rx='1'/></g></svg>");
}

.ag-theme-designkit .ag-icon-checkbox-checked {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12' xmlns:xlink='http://www.w3.org/1999/xlink'><defs><rect id='a' width='12' height='12' rx='1'/></defs><g fill='none' fill-rule='evenodd'><use fill='#FFF' xlink:href='#a'/><rect width='11' height='11' x='.5' y='.5' stroke='#80C11A' rx='1'/><path stroke='#80C11A' d='M9 3L6 8.5l-2.5-2'/></g></svg>");
}

.ag-theme-designkit .ag-icon-checkbox-unchecked-readonly {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12' xmlns:xlink='http://www.w3.org/1999/xlink'><defs><rect id='a' width='12' height='12' rx='1'/></defs><g fill='none' fill-rule='evenodd'><use fill='#DADEE3' xlink:href='#a'/><rect width='11' height='11' x='.5' y='.5' stroke='#57626C' rx='1'/></g></svg>");
}

.ag-theme-designkit .ag-icon-checkbox-checked-readonly {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12' xmlns:xlink='http://www.w3.org/1999/xlink'><defs><rect id='a' width='12' height='12' rx='1'/></defs><g fill='none' fill-rule='evenodd'><use fill='#DADEE3' xlink:href='#a'/><rect width='11' height='11' x='.5' y='.5' stroke='#80C11A' rx='1'/><path stroke='#80C11A' d='M9 3L6 8.5l-2.5-2'/></g></svg>");
}

.ag-theme-designkit .ag-icon-group {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='12'><g fill='none' fill-rule='evenodd'><path stroke='#57626C' d='M7.5 1.5h3v2h-3zM7.5 5.5h3v2h-3zM7.5 9.5h3v2h-3z'/><path fill='#57626C' d='M2 3h1v8H2zM3 6h4v1H3zM5 2h3v1H5z'/><path fill='#57626C' d='M2 10h5v1H2z'/><path stroke='#57626C' d='M1.5 1.5h3v2h-3z'/></g></svg>");
}

.ag-theme-designkit .ag-icon-aggregation {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='12'><path fill='none' fill-rule='evenodd' stroke='#57626C' stroke-width='2' d='M9.5 2.5h-6l2 3.5-2 3.5h6'/></svg>");
}

.ag-theme-designkit .ag-icon-pivot {
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='12'><g fill='none' fill-rule='evenodd' stroke='#57626C'><rect width='9' height='9' x='1.5' y='1.5' rx='1'/><path stroke-linecap='square' d='M10.5 3.5h-9M3.5 1.5v9'/><path d='M7.5 6.5l1-1 1 1M6.5 7.5l-1 1 1 1'/><path d='M8.5 5.5v3h-3'/></g></svg>");
}

.ag-dnd-ghost.ag-fresh {
  z-index: 5;
  height: 25px !important;
  padding: 4px;
  padding: 0 8px;
  margin: 0;
  font: 700 12px "Helvetica Neue", sans-serif;
  line-height: 25px;
  color: #57626C;
  background: #f4f5f6;
  border: 1px solid #d1d6dc;
  border-bottom: 1px solid #c8ced5;
  border-radius: 2px;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05);
  -webkit-transform: translatey(8px);
          transform: translatey(8px);
}

.ag-dnd-ghost.ag-fresh span,
.ag-dnd-ghost.ag-fresh div {
  float: left;
  height: 100%;
  padding: 0;
  margin: 0;
}

.ag-dnd-ghost.ag-fresh .ag-dnd-ghost-icon {
  display: inline-block;
  float: left;
  padding: 2px;
  margin-right: 4px;
  opacity: 1;
}

.ag-dnd-ghost.ag-fresh .ag-dnd-ghost-icon .ag-icon-arrows {
  background: transparent url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='20' height='20' viewBox='0 0 20 20'><g fill='#57626C' fill-rule='nonzero'><path d='M16 6l-1.41 1.41L16.17 9H4v2h12.17l-1.58 1.59L16 14l4-4'/><path d='M4 6l1.41 1.41L3.83 9H16v2H3.83l1.58 1.59L4 14l-4-4'/><path d='M6 16l1.41-1.41L9 16.17V4h2v12.17l1.59-1.58L14 16l-4 4'/><path d='M14 4l-1.41 1.41L11 3.83V16H9V3.83L7.41 5.41 6 4l4-4'/></g></svg>") center no-repeat;
  background-size: 12px 12px;
}

.ag-dnd-ghost.ag-fresh .ag-dnd-ghost-icon .ag-icon-pin {
  background: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12'><g fill='none' fill-rule='evenodd'><path fill='#57626C' d='M3 2h6v1H8v4l2 1H7l-1 3-1-3H2l2-1V3H3'/><path fill='#FFF' fill-opacity='.5' d='M5 3h1v4H5z'/><path fill='#FFF' fill-opacity='.28' d='M4 3h1v3H4z'/></g></svg>") center no-repeat;
  background-size: 12px 12px;
}

.ag-dnd-ghost.ag-fresh .ag-dnd-ghost-icon .ag-icon-eye-slash {
  background: transparent url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12'><g fill='none' fill-rule='evenodd'><path fill='#000' d='M3 3.908V4c0 1.657 1.343 3 3 3s3-1.343 3-3v-.092C8.1 3.303 7.1 3 6 3s-2.1.303-3 .908z'/><path stroke='#979797' d='M4 4.5c.667-.333 1.667-.5 3-.5'/><path stroke='#57626C' d='M1 6c1.333-2 3-3 5-3s3.667 1 5 3C9.667 8 8 9 6 9S2.333 8 1 6z'/><path stroke='#57626C' d='M4.004 2.835l4.992 6.33' stroke-linecap='square'/><path stroke='#FFF' d='M3.004 2.835l4.992 6.33' stroke-linecap='square'/></g></svg>") center no-repeat;
  background-size: 12px 12px;
}

.ag-dnd-ghost.ag-fresh .ag-dnd-ghost-icon .ag-icon-right {
  background: transparent url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='11' height='10' viewBox='0 0 11 10'><g fill='none' fill-rule='evenodd'><path fill='#D8D8D8' d='M9 4v2H0V4z'/><path stroke='#57626C' d='M8.5 4.5v1h-8v-1z'/><g><path fill='#D8D8D8' d='M4.786 1.957L5.993.75l4.242 4.243-4.242 4.242-1.207-1.207L7.82 4.993'/><path stroke='#57626C' d='M5.493 1.957l.5-.5 3.535 3.536-3.535 3.535-.5-.5 3.035-3.035z'/></g></g></svg>") center no-repeat;
  background-size: 12px 12px;
}
```

## Author

Jason Melgoza

## License

MIT
