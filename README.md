# pybossa_missingmaps
This is a template for the Missing Maps pybossa task. Have a look and contribute: 

- http://crowdmap.geog.uni-heidelberg.de/app/missing_maps_follow_up/

You can find additional information how to create such a task also at this blogpost:
- https://disastermappers.wordpress.com/2015/09/23/how-to-create-your-own-missing-maps-like-pybossa-task/


Feel free to use this template for your own project (e.g. at crowdcrafting.org).

#Design the task presenter

There is a "new" version of the task_presenter.html --> task_presenter_geom.html
- This template uses the geometry of your input geometry (e.g. your grid polygon) and will adjust the map view centered on that polygon.
- replace 'your_project_name' with the shortname of your project at line 149 and line 254.

The template "task_presenter" uses the columns "x_center" and "y_center" to set the center of your map view.
- replace 'your_project_name' with the shortname of your project at line 145 and line 221.


The shortname of your project is the one that is also displayed in the weblink to your project. (e.g. https://crowdcrafting.org/project/test_project/tasks/) --> "test_project")

#Further issues:
- You should consider to get an access key from microsoft if you would like to use Bing imagery.
- you may have to change the links to the javascript libraries

