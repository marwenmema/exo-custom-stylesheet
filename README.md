# exo-custom-stylesheet
A custom CSS skin stylesheet for eXo Platform 4.3 with a more flat design

COMPATIBILITY: eXo Platform 4.3.0 in "Light" toolbar mode, Google Chrome

HOW TO IMPLEMENT:

1) Copy the CSS code and paste it in your text editor. Use your editor's "replace" feaure to auto-replace the 6 variables with your custom colors. (See the screenshot below.)
* #BASE_COLOR
* #BASE_COLOR_EMPH
* #BUTTON_COLOR
* #BUTTON_COLOR_HOVER
* #LINK_COLOR
* #LINK_COLOR_HOVER

![Alt text](https://github.com/marwenmema/exo-custom-stylesheet/blob/master/variables_legend_screenshot.png "Variables")

2) In eXo Platform, go to "Administration" > "Portal" > "Branding" and switch to the "Light" toolbar mode.

3) Create a new global stylesheet under the "intranet" or "shared" site following this guide and paste the new code in it: www.exoplatform.com/docs/PLF43/PLFUserGuide.AdministeringeXoPlatform.CustomizingLookAndFeel.CreatingGlobalStylesheet.html

4) Refresh your browser cache and page (CTRL+F5 on Windows, Command+Shift+R on Mac).

NOTE: A work in progress. Not optimized yet for all browsers. Uses the !important declaration everywhere (not a good practice) just out of laziness/to be certain it overrides everything. Therefore useful for demo purposes but not yet recommended for production. 
