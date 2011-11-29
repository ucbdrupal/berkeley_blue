1. Purpose
2. Installation
3. Configuration
4. Authors

PURPOSE
-------

The Berkeley Blue theme is a Zen subtheme, developed at UC Berkeley.

INSTALLATION
------------
IMPORTANT: As this is a Zen subtheme, you must have Zen installed on your site (it doesn't have to be enabled).

CONFIGURATION
-------------
*TOP MENU CONFIGURATION*
To create a top menu (that sits at the very top of the page):
1. Create a new menu (e.g. "Secondary menu"), and add your links. This menu should have no more than 5 or 6 items, with short titles, and a flat hierarchy.
2. Go to your Menu Settings (admin/structure/menu/settings) and select the menu you just created as the "Source for Secondary Links"
3. In your theme settings (admin/appearance/settings/berkeleyblue), ensure that "Secondary Menu" is checked.

*MAIN MENU CONFIGURATION*
To create the Main Menu with sidebar submenu
1. This will use whatever menu you have set as the "Source for the Main Links" on admin/structure/menu/settings, so be sure that is set to the menu you want to use.
2. In your theme settings (admin/appearance/settings/berkeleyblue), ensure that "Main Menu" is checked.
3. The top level links will display across the navigation bar, just under the yellow bar.
4. To display the subpages in the left sidebar, download and enable the Menu Block module (http://drupal.org/project/menu_block)
5. Go to your Blocks page (admin/structure/block) and click the link to "Add menu block" at the top of the page
6. Recommended settings (Click the "Advanced Settings" to see all options) --
	-- Block title: leave blank (this will set the parent menu item as the title)
	-- Menu: <the menu selected by the page>
	-- Starting Level: 2nd level (secondary)
	-- Maximum Depth: 2
	-- Fixed parent item: <the menu selected by the page>
7. Place this block in the Left Sidebar.

*SEARCH FORM*
To add the Search form to the header, place the block "Search form" in the region "Header right".

AUTHORS
--------
Michelle Ziegmann, http://drupal.org/user/350804

  Initial port of D6 theme to D7.  Attempted to make the theme more general.

Kathleen Lu

  D6 version of this theme.  It was for a specific site.  Was not
  intended to be a general-use theme.
