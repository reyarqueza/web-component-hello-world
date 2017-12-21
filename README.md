# web-component-hello-world
Native HTML5 web component example using template tag and HTML import.

HTML import is mostly only supported by Chrome so you will have to use a polyfill on other browsers. By the time you read this, more browsers may be supported, check here: https://caniuse.com/#search=import

I am aware that the current best way to do web components with cross browser support is using template literals, but I wanted to experiment with HTML imports.

## The building blocks
This hello world example of native web components demonstrates the following:

### ES6 new Class Syntax 
 * constructor
 * super
 * getters

### Custom Elements v1 
 * HTMLElement class
 * window.customElements.define
 * connectedCallback
 * template element tag

### Shadow DOM v1
 * attachShadow
 * slot element tag

### HTML Imports
 * rel="import"

## Requirements
HTML using web components needs to be served through an http server. For convenience, a local webserver is provided so that you don't have to setup your own.

If you don't have npm and node installed, [get npm](https://www.npmjs.com/get-npm).

1) Install the depedencies for web-component-hello-world:

```
npm install
```

2) Run the local http-server:

```
npm run dev
```

3) Now open your browser to the url specified on the terminal. You may see something similiar to this:

```
Starting up http-server, serving ./
Available on:
  http://127.0.0.1:8080
  http://192.168.1.76:8080
Hit CTRL-C to stop the server
```
