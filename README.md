# scrumtool-2

Scrum tool 2 is a follow on project, but not fully compatible with the original scrum tool (in the same repository) (yet). The data model changed a bit to be more flexible, and this is not something that has been tested as yet. The inspiration behind this was to come to a more user friendly and lightweight way to do scrum, than the interfaces to industry strength tools with legacy UIs they cannot easily do away with.

The tool has reached a point where it can be used to run a development project for a single team. There is still some work in progress to impore the support for QA, and to make online cues make the interface usable. Right now, reading the document may be the only way to understand how to use the tool.

The tool is intended to provide an open ended workflow to manage a scrum project. The source code is in a single HTML file, a single CSS file, and some SVG images stored in the img folder. To run the tool, simply open the HTML file in your browser. Chrome was used for development. It has not been tested on any other browser. There is no need to run a web server, just opening the HTML file in the browser to bring up the UI.

There are 5 tabs accessable from the top navigation:

1. The backlog tab, with the dog eared papers icon
2. The setting tab, with a gear wheel icon 
3. The tracking tab, with a calendar and clock icon
4. The graph tab, with a graph icon
5. The checklist tab, with checkboxes in the icon

The workflow to use the tool is deliberately flexible. You can navigate across tabs even before setting up all the data. Online tool tips to assist data entry provides hints on using the UI. This is the usage document for now, and is work in progress. 

## Usage
The workflow is lenient, and allows switching tabs at any stage to allow planning, execution and reviews to happen at any time. There is no workflow mandated, but obviously certain tool feature that depend on entered data do not work until data is entered.

The backlog tab provides a sticky notes like UI to have a bunch of notes visually arranged with requirement descriptions. This is intended for use for someone in a product owner role, to provide inputs for a project that is being planned. It is not mandatory for the to have data entered before working on the tracking tab.

![Alt text](docs/requirements.jpg?raw=true "Project setup")

The project team and sprints are set up on the project settings tab. If there are any weeks where no burndown is likely, due to seasonal holidays, or company events, those too may be specified. A start date for the project is needed before the graphs can be seen. This happens on the settings tab.

![Alt text](docs/setup.jpg?raw=true "Project setup")

The tracking tab contains a project layout view, which shows a table of sprints witch the assigned tasks for each sprint, and allows a sprint editor view to be opened, which then shows the list of developers, and allows requirements to be moved across developers and statuses.

![Alt text](docs/projecteditor.jpg?raw=true "Project setup")

A sprint editor can be invoked from the list of sprints in the project editor.

![Alt text](docs/sprinteditor.jpg?raw=true "Project setup")

The graph tab facilitates tracking by showing a number of graphs:
* A sprint burndown graphs shows the burndown in the current sprint
* Side by side, the developer burndown graph shows the burndown and task allocation per developer
* The project burndown graph shows the burndown across all sprints in the project
* The feature details graph shows the feature by feature burndown in the sprint
* Side by side, the developer load graph shows the work per developer view of the remaining work

![Alt text](docs/graphs.jpg?raw=true "Project setup")

The checklist tab summarises the health of the project execution.
