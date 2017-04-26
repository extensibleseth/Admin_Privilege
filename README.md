# Admin_Privilege
TL;DR
Grants admins the ability to restrict access to otherwise editable nodes.

Admin Privilege gives users with administrator roles the ability to restrict access to the update, and delte operations for non-admins on nodes who's author has an admin role.

For exmaple if a node has an author with an privileged role, a user with a privileged role can check a box on node creation, or update, that would deny users without a privileged role from executing an update or delete.


The plan is to create a service which returns access denied when the access checks are called. There will be an admin menu where privileged roles can be selected. An additional checkbox will be displayed on the user edit form of users with any privileged roles warning that by removing all privileged roles their content will become accessable to users with non-privileged roles who normally have access to update and delete nodes of that content type. This checkbox must be checked before all privileged roles can be removed from the user. An option to reassign protected nodes to anothter user with a privileged role may be added in the future.


