_QQC is back on MediaWiki with the hybrid Mustache/JS powered theme Evelution, from the makers of CPE Blocks and Qora Qore_

# Description
Evelution is a Next Gen Skin for MediaWiki. Designed to improve reading has four different thems that you can use them on a page-basis. With the inclusion of a Dark Mode, you can read pages with fewer eye stress.

With the inclusion of Sticky sidebars and Sticky Community Header, you can have many of the known tools MediaWiki following you.

Evelution Desktop Skin in three different main Breakpoint Sizes, 705px, 1280px & 1500px

# Requirements
To Run Evelution on your wiki, you must have MediaWiki 1.36 or greater. Older versions are not supported

# Installation
To Install Evelution, you must download the reposistory first. Make a folder called **Evelution** in **Skins** diractory where you have installed MediaWiki and extract the zipped file contents in **Evelution** folder.  Lastly, put this in **LocalSettings.php**:
```php
wfLoadSkin( 'Evelution' );
```

# Known Limitations
- Icons on OOUI elements can only appear in black for light themes and white for dark themes
- Toolbar can cover the page action dropdowns if the content area is too small. If it is that case, collapse it.
