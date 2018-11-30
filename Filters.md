# Filtering events #
Filters can filter out an event from your view. Events are not deleted from memory. OtrosLogViewer provides set of filters. Custom filters can be also added as a plugin.


## Included filters ##
### Level filter ###
Filters out events with the level lower then the selected one.
### Time filter ###
Filters out events that do not match the selected time frame.

Filters can be edited by selecting ![https://raw.githubusercontent.com/otros-systems/otroslogviewer/master/OtrosLogViewer-app/src/main/resources/img/fugue/funnel--arrow.png](https://raw.githubusercontent.com/otros-systems/otroslogviewer/master/OtrosLogViewer-app/src/main/resources/img/fugue/funnel--arrow.png) in context menu.
### Mark/note filter ###
Filters out marked events or events with a note.
### Thread filter ###
You can use this filter to show events only from the selected thread.
Filter can be edited by selecting ![https://raw.githubusercontent.com/otros-systems/otroslogviewer/master/OtrosLogViewer-app/src/main/resources/img/fugue/arrow-turn-270.png](https://raw.githubusercontent.com/otros-systems/otroslogviewer/master/OtrosLogViewer-app/src/main/resources/img/fugue/arrow-turn-270.png) or ![https://raw.githubusercontent.com/otros-systems/otroslogviewer/master/OtrosLogViewer-app/src/main/resources/img/fugue/arrow-turn-090.png](https://raw.githubusercontent.com/otros-systems/otroslogviewer/master/OtrosLogViewer-app/src/main/resources/img/fugue/arrow-turn-090.png) in context menu.
### Class filter ###
You can ignore some classes/packages you do not want to see.


## Creating custom filter ##
See [Implementing log filter](ImplementingLogFilter.md).
