/*
Plugin Name: LiveCalendar
Plugin URI: http://www.jonabad.com/2005/01/08/livecalendar-10/
Description: Calendar widget energized with the xmlhttprequest magic. Allows calendar navigation without refreshing the entire page.
Author: Jon Abad
Author URI: http://www.jonabad.com
Version: 1.1
*/

Install Instructions:
 1. copy the livecalendar folder to your wp-content folder.
 2. copy livecalendar.php to your wp-content/plugins folder.
 3. edit kcalendar.js in the livecalendar folder and edit siteurl with the root of your wordpress installation.
    For example for my site, this is: siteurl="http://www.jonabad.com"
    important: do not include a trailing slash, to do so would break things.
 4. activate the plugin in the Plugin Management section of your Wordpress install.
 5. enjoy!

If it breaks horribly, gimme a shout. It works fine on my 1.5 and 1.2.2 installs but its possible that it could break.


Release notes:
1.1 - added siteurl variable so the links aren't broken when using permalinks rewrite
1.0 - initial release

To-do
 - Provide a "loading" graphic to indicate that the calendar is waiting for data to return from the server.
 - Provide a link to display all of the posts in the displayed month.
 - Fix whatever 1.1 breaks.
