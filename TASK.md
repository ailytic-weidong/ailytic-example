# Title

Presenting a schedule in Bryntum and Ext Grid

# Description

Design a HTML page to display a multi-machine schedule. The schedule should be rendered in two components: a Bryntum Gantt chart and an Ext Grid, with the Bryntum chart displayed on the top part of the page and Ext Grid on the bottom. The two components should be separated with splitter which the user can use to resize the heights of the components.

The schedule to be displayed has a list of activities, and each activity has the following fields: `id`, `startTime`, `endTime`, `product`, `quantity` and `machine`. Activies for different machines should be rendered in different rows in the Bryntum chart. Drag and drop should be enabled in both components. When an activity is drag and dropped in one component, the change should be reflected in the other one synchronously. In particular, when an activity is dragged from one machine and dropped onto another, the `machine` field of that activity should be changed to the code of target machine.

When needed, CDN can be used for the following libraries: `React.js`, `Ext.js`, `Bryntum` and `jQuery`. Apart from the official components from the above libraries, no other 3rd party javascrip libraries should be used.

Attached is a sample schedule which can be used for this task.

Note: the online version of Bryntum should be sufficient for this task, but please contact us if you need an official version.
