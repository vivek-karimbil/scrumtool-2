# scrumtool-2

Scrum tool 2 is a follow on project, but not fully compatible with the original scrum tool (in the same repository) (yet). The data model changed a bit to be more flexible, and this is not something that has been tested as yet. The inspiration behind this was to come to a more user friendly and lightweight way to do scrum, than the interfaces to industry strength tools with legacy UIs they cannot easily do away with.

There is still some work in progress to impore the support for QA, and to make online cues make the interface usable. Right now, reading the document may be the only way to understand how to use the tool.

The tool is intended to provide an open ended workflow to manage a scrum project. The source code is in a single HTML file, a single CSS file, and SVG images stored in the img folder. To run the tool, simply open the HTML file in your browser. Chrome was used for development. It has not been tested on any other browser, but the usual yada-yada aboout usage of standatds, etc. applies, it ought to work in other browsers. There is no need to run a web server, just opening the HTML file in the browser will bring up the UI.

There are 4 tabs accessable from the top navigation:

1. The setting tab, with a gear wheel icon
2. The requirements tab, with the dog eared paper icon
3. The tracking tab, with a calendar and clock icon
4. The graph tab, with a graph icon

The workflow to use the tool is deliberately flexible. You can navigate across tabs even before setting up all the data needed. Right no, online tool tips to assist data entry is a pending task. This is the usage document for now, and is work in progress. Feature enhacements being considered are support for definition of ready and definition of done criteria for features, and a stronger model for QA.