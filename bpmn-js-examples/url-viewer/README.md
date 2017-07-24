# bpmn-js Url Viewer Example

This example uses [bpmn-js](https://github.com/bpmn-io/bpmn-js) to implement a simple viewer for BPMN 2.0 process diagrams that can be loaded via their URL.

## About

The demo pulls bpmn-js via [bower](http://bower.io). It allows the user to input a url to fetch a process diagram from.

![demo application screenshot](https://raw.githubusercontent.com/bpmn-io/bpmn-js-examples/master/url-viewer/docs/screenshot.png "Screenshot of the example application")

Make sure you serve the application via a web server (nginx, apache, embedded) and ensure that the diagrams you want to access are either on the same server or [CORS](https://en.wikipedia.org/wiki/Cross-Origin_Resource_Sharing) enabled.