Theme Documentation

ComicPress is a configurable theme, layouts to colors.

It is primarily to be used with the Comic Easel plugin.


ComicPress 4.0 -

ComicPress now does not include comic running code, this is handled with the plugin Comic Easel.

You will need to use the ComicPress to Comic Easel migrator plugin.

Please read information and faqs on comiceasel.com for more information.

== Changelog ==
= 4.1 =
* Added LGN and RGN (3 column) layouts back into ComicPress, layout-head.php and layout-foot.php updated
* Fixed problem with customizer not setting defaults
* Added #footer a, #footer a:hover and footer textcolor entries to the customizer which were missing
* Boxed scheme w/blue background image is now the default design
* added sidebar.php as a default to handle plugins that need it
* added missing .uentry entries for search.php 
* Changed the footer widgets to be specific widths instead of percent
* New browser window/tab when clicking social links in the menubar
* Titles no longer link on pages, static or otherwise
* Regenerated .pot/.mo files 
* Readded the default height and width for the custom header image in case the auto-sensing one doesn't work
* The home link .menu-item-home and the downarrows in the menubar can now all be skinned, i.e. replaced with your own images if you want to; I left examples inside the style.css for the home button
* Calendar widget removed for ComicPress; since Comic Easel has one, will re-add in a newer version when I update it to the new WordPress code; otherwise it's a liability until then
* Options to allow changing media content width in posts and pages
* a couple spelling fixes
* option to change the media width inside posts
* fix for 2 column wide layouts having that extra wide sidebar (that was a bug)
* random default avatar adjustments to work with facebook commenting / as user
* a plethora of author page fixes/adjustments


= 4.0.6 =
* Adjusted the page titles function in displaypost.php to allow the titles to be clicked on search and archive results /bugfix

= 4.0.4 =
* Archive pages now display comic thumbnails for ComiC Easel if show archives as links enabled
* CSS: body.wide set properly for when the sidebars get removed!important
* CSS: .header-info padding removal when used as click block
* CSS: 780px 980px #page instead of 782/982 .. extra 2px was wrong, fixed


= 4.0.3 =
* Correctly attribute the height to auto for images inside posts.
* fixed the archive - asc/desc setting in the comicpress options
* added #pagenav to the customizer for the uentry section for link:hover
* style.css added #pagenav to the rounded-style class
* show the customizer jquery ONLY on the customizer page!bugfix
* added high society scheme


= 4.0.2 =
* Added toggle to make header text into a hotspot for the entire header image.
* Don't show recommended plugins notice (it confuses people into installing them all)
* Better Handling of the help screen when first installing the new ComicPress theme

= 4.0.1 =
* Fixed the 'description' of the theme.

