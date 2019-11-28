Image Field Caption
===================

Provides a caption text area for image fields.

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

- Flush all Backdrop caches.

Documentation
-------------

Usage:
- Configuration is done on a per field basis.
- Add a new image field to a content type, or use an existing image field and
  configure it to show the caption elements.
- Add or edit a node or any other entity with an image field
- Go to the image field on the entity form
- Enter text into the caption text area and choose format
- Save the entity
- View the entity to see your image field caption


Caption Theme:
By default, an image field's caption will be rendered below the image. To
customize the image caption display, copy the image_field_caption.tpl.php file
to your theme's directory and adjust the html for your needs. Flush Drupal's
theme registry cache to have it recognize your theme's new file:

  themes/MY_THEME/image_field_caption.tpl.php


Caption CSS:

To make changes to the caption css, use this CSS selector:

  blockquote.image-field-caption { /* add custom css here */ }

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/image-field-caption/issues.

Current Maintainers
-------------------

- [sternhagel](https://github.com/sternhagel).

Credits
-------

- Ported to Backdrop CMS by [sternhagel](https://github.com/sternhagel).
- Originally written for Drupal by [Tyler Frankenstein](https://github.com/signalpoint).

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
