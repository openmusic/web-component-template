# openmusic-web-component-template

> A template for OpenMusic Web Components

[![Install with NPM](https://nodei.co/npm/openmusic-web-component-template.png?downloads=true&stars=true)](https://nodei.co/npm/openmusic-web-component-template/)

## Installation

Grab `index.js` from the repo or do `npm install openmusic-web-component-template`.

### If not using any package manager

Include `index.js` before you use the component:

```javascript
<script src="index.js"></script>
```

It will be registered automatically as `openmusic-web-component-template`, so you can `document.createElement('openmusic-web-component-template')` or just have `<openmusic-web-component-template>` elements in your HTML source.

### If using npm

You need to load the module and then register it--it is not automatically registered!

```javascript
require('openmusic-web-component-template').register('openmusic-web-component-template');
```

But you could even register it with other name, for example:

```javascript
require('openmusic-web-component-template').register('mega-web-component-template');
```

Up to you.

## Usage

Have a look at `demo/demo.js` for an example that does things in order to things.

### Attributes

#### `attribute`

Explanation of attribute.

Examples:

```javascript
<openmusic-web-component-template attribute="-1"></openmusic-web-component-template>
```

### Events

#### `event`

This event will be dispatched when x happens. To listen for `event` events on this component, add an event listener:

```javascript
component.addEventListener('event', function(ev) {
	var detail = ev.detail;
	// detail contains the values you want
});
```
