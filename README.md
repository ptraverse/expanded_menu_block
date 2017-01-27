## Expanded Menu Block

Attempting to use the same (main) menu in multiple blocks in Drupal 8, showing only the siblings of the current menu item.

See

* http://drupal.stackexchange.com/questions/183201/get-menu-link-siblings
* http://drupal.stackexchange.com/questions/204349/show-parent-menu-children-in-sidebar

### Installation

* `git clone https://github.com/ptraverse/expanded_menu_block.git web/modules/contrib/expanded_menu_block`
* Enable in Drupal 8 -> Extend (or use drush)
* Go to Structure -> Block Layout and then "Place Block" wherever you want your 2nd copy of the menu to show
* Pick the menu you want withe "Menu - Expanded" category

Note that this is a fork of another repo that was not quite working and is therefore not guaranteed to work at all. As of this writing it is still a work in progress.


