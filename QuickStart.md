# Quick start guide

## Installing
Download the repository to your computer. All files are text files, except for a few images in the documentation folder. The documentation folder is not required to run the tool.

## Running the tool
Open the file scrumtool.html in Chrome. It has not been extensively tested on other browsers, and issues have been observed on the latest versions of newer browsers, including Edge.

## Usage
Fundamental philosophy: Software project = Team developing tasks in a series of sprints. This guide will work with the minimal setup to get started with a project, and expand on alternative workflows.

### First Plan
Open the scrumtool.html in your browser. You see the requirements screen, with a few colourfull rectangles on the left, near the top of the screen. Create a requirement for development, by dragging a coloured rectangle to the space below, which is the virtual project whiteboard. Then click the settings tab at the top of the screen - the one that looks like a gearbox. Thre are some icons for people - drag the blue one to the box below, to add a developer to the project. There are icons below the box for people, that represent sprints. Drag a blue one (with 'D' in the middle) to the box below it.
Select the scheduling tab, which is the third tab on the top of the screen - the calendar with a clock icon. The requiremen you created will be in the backlog box on the left. The sprint you created will appear in the table on the right. Drag the requirement to the table - on dragging something in the tool, the places you can drop them get highlighted. Drop the highlighted requirement in the first highlighted box. Click on the sprint icon at the start of the row to see the sprint editor.
There is a row for each developer, and the tasks created would be below the table. Drag the task to the row for the developer to assign the task in the appropriate status to that developer.
This is now a tiny project - one task to be done by the developer assigned, in the default time associated with a new task.

Thats all it takes to get started - the rest comes in the what if questions that ought to follow that minimalistic set of instructions above.

### Saving your work
Projects can be saved to local files in your download folder, using the save icon in the top right corner of the page. The browser settings to save a file created by a local web page will apply, so the browser settings will apply to where the file would be saved. The overwriting of existing files with the same name will be browser specific. On windows, Chrome creates a new version of a file if the name has already been used. THese files can be loaded to continue editing, so different versions of the plan over time can be saved and restored. Save before exiting the tool, to keep your last edits.

### Next plans
Since most projects are more complicated than the one task - one developer - one sprint project we created above, let us explore further usage. The next few sections can be done in any order.

### Common actions - Edit and Delete
The pencil icon is used to edit the item on which it is clicked. The X icon is used to delete the icon. These appear on the top and right sides of the items they affect. Both icons apear to the top and right of objects to change their settings or to delete them.

### Adding requirements to the backlog
More requirements can be added the same way as described earlier, by draging and dropping notes to the whiteboard. This is done on the backlog tab, the first tab on the top left. This tab stretches down a fair deal, so you can scroll for more space, or to group things together.

#### Editing requirements in the backlog
Edit the notes by clicking on the pencil icon on the top right of each note on the backlog tab (the first tab on the top left). You can enter the name of the requirement, add a description, set the priority, the size, and set the colors for the note on the form that pops up. The name is seen in other parts of the tool. Notes can be used for any purpose - details of requirements, status during execution, links to other places or anything else. The priority and size can individually set here, or also in the bulk editors for these.

#### Bulk editing of estimates and priorities
The backlog tab (the first tab on the top left) has 3 icons on the right - for bulk editing size, priority, and for the whiteboard view. The size view shows all items in the backlog. After the requirements for a project are created, ordering them by their priorities and estimates individually is time and effort consuming. The bulk editors provide a drag and drop interface for this, that allow the size and priorities of other requirements to be visible in the same screen, and hence easiely set relative to each other. These actions work only at the requirement level, which is to say that tasks created from a requirement inherit size and priority when created, which to not change after that. If the priority of a requirement is changed after a task is created, the task still has those set to the values at the time of creation. This reflects the philosophy that both these attributes could be independant at the task level.

### Project setting
The gear icon allows the settings of the project to be set. These include:
1. The name of the project
2. The start date
3. The developers and testers.
4. The sprints
5. The blackout weeks where no progress is likely (Holidays like Diwali, Christmas, Company weeks off for traininng, ...)
6. Tracking dates - working days, tracking days and holidays in a week
7. Editor defaults - to set default values for editing

The name of the project is used by default to set the name of the file to be used when saving the project.

The start date of the project. This cascades to the start date of the sprints. 

The list of pigs (I hope you know the Bacon and Eggs anecdote, I am not being disrepectful here) include the developers, leads and testers. The leads are created with lesser capacity for development by default, but which could be changed to even greater capacity, depending on what works in your organisation. The order of people in the box is not significant.

The order of the sprints in the next box is significant. The lengths of each sprint is specified. The start date of a sprint is calculated from the length of the previous sprints. Sprints do not overlap in time, work moves to a future sprint. Extending the end date of a sprint cascades to the start dates of following sprints being extended. The tool offers the mechanism to support the practise in use in your team without enforcing a process.

There are some weeks during the overall timeline of a project where work does not progress in general. These may include (but are not limited to) holday where most of the team will be on vacation, company wide events like executive visits, trainings, offsites, etc. This sets the available work that can be done in that window to 0 across all pigs, rather than needing to add those many days off to each ones settings, and edit each time a sprint shifted in the plan.

The tracking days are the dates for data entry in the tool, whether or not a physical standup happens. It is not recommended to change this afterthe strt of the project, as it does not adjust previously enterd data to the new tracking dates.

Default settings for data entry include:
1. The default capacity for a lead or developer when added to the project. This is set to 40% and 80% by default, and can be changed to any other number that reflect the team thats using it.
2. The default settings for estimate conversion to effort. This is set to the Fibonacci numbers to start with, but can be changed to anything else to reflet the number of days of effort required as the starting effort. That is turn can be changed to the actual number of days required by the developer doing the work.
3. The default days of unavailabity per developer in each sprint. The basic assumption is to factor in some time off by default to start with, that can be oevrwridden durning execution of the project.
4. The default priority for new tasks is set to "Should have", which will be the initial priority applyed to every new task, and can be changed to reflect the most frequently occuring value.
5. The defult size of a new task is set to "Pebble" by default, which will be the size set by default, and can be changed if something else is more commonly applicable. 
