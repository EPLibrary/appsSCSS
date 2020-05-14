apps.epl.ca Stylesheets
=======================

This is the source (in Sass SCSS format) for EPL's staff application's website stylesheets.

appsDarkForced.css is written using plain CSS, but apps.css is created using SCSS, so ensure you edit the correct source files then compile using the following command:

```sass apps.scss apps.css

After compilation, apps.css, appsDark.css, and appsDarkForced.css should all be copied to the root of apps.epl.ca.


Compiled Files
--------------
 - *apps.css*  The compiled main stylesheet
 - *appsDarkForced.css*  The dark mode stylesheet. If this is included by itself, it forces dark mode on all clients.
 - *appsDark.css*  Use this stylesheet to respect the user agent's prefers-color-scheme dark/light setting via media query.

Source SCSS Files
-----------------
 - *apps.css*  @use all _files, includes mixins and generators for buttons and stuff.
 - *_appForm.scss*  Responsive form styles
 - *_base.scss*  Fonts and basic base styles for elements (with no classes/ids).
 - *_header.scss*  Styles that apply to the header of apps used on all pages, including the popover modal dialogue.
 - *_markdown.css*  Style for elements within markdown containers, (usually markdown is rendered to HTML with JS)
 - *_other.scss*  The bulk of other styles for elements on apps (eg table formatting). This is the largest component.
 - *_variables.scss*  Variables with EPL colors, highlight colors, and font-sizes that are used in multiple SCSS files.