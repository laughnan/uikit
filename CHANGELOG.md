# Changelog

### WIP

  - Added overlay-area-content to overlay component
  - Added uk-margin-small classes to utility component
  - Added uk-text-nowrap to text component
  - Added data-uk-margin to utility component
  - Switcher now activates first toggler when no uk-active class is set
  - Extended Notify message api wit content+status methods
  - Fixed Offcanvas in RTL mode
  - Fixed Tooltips in Offcanvas
  - Removed hgroup in normalize because it was deprecated in HTML5
  - Fixed data-uk-grid-match

**Documentation and repository**

  - Updated overlay docs and tests
  - Updated utility docs and tests
  - Optimized docs and tests with data-uk-margin

### 2.1.0 (January 07, 2014)
  - Added notify add-on
  - Added border-circle to utility component
  - Added more variables to sortable add-on
  - Added modifier to flip form icons
  - Updated form icons to work with form size modifiers
  - Replace fixed value with variable in nav component
  - Fixed background position in RTL mode
  - Fixed delayed dropdown trigger on touch devices
  - Fixed jumping when dragging sortables
  - Fixed nested comments indention on small screens
  - Fixed style for inputs without type attribute

**Documentation and repository**

  - Added new notify add-on
  - Fixed tooltip component
  - Fixed tests link

### 2.0.0 (December 11, 2013)

  - Added toggle component
  - Added form-icon to form component
  - Added datepicker add-on
  - Added form-password add-on
  - Added markdown area add-on
  - Added sortable add-on
  - Added sticky add-on
  - Added timepicker add-on
  - Added outerclick support for dropdowns in hover mode
  - Added touch events support for Windows 8 phones
  - Added miscellaneous hooks
  - Updated icon component to Font Awesome to 4.0.3
  - Changed comments to compile nicer CSS output

**Documentation and repository**

  - Refactored repository structure
  - Refactored variables
  - Added Grunt task to index new themes ( usage: grunt indexthemes )
  - Added new UIkit add-ons and components
  - UIkit tests moved to /src

### 1.2.1 (December 03, 2013)

  - Fixed off canvas scrolling on windows phones
  - Fixed search more results in search js

**Documentation and repository**

  - Updated LESS to 1.5.1

### 1.2.0 (November 01, 2013)
  - Added shake animation
  - Added boundary check to tooltip component
  - Added delay and animation option to tooltip component
  - Added margin-left and margin-right to utility component
  - Added variables for width sub-modifiers to form component
  - Added size modifier support for textarea and multiple selects
  - Added renderer option for seach component
  - Added scrollspy-nav to scrollspy component
  - Auto-initialize dynamic components using MutationObserver if supported by browser
  - Changed box-sizing for scrollable-box
  - Fixed link-muted
  - Fixed form-controls-condensed margin
  - Fixed rare customizer unknown LESS var error
  - Fixed smooth-scroll offset position

### 1.1.0 (August 21, 2013)

  - Added scrollspy component
  - Added animation component
  - Added link-muted to utility component
  - Added subtitle support for navbar items
  - Off-canvas now uses hardware accelerated translateX for bar animation
  - Added responsive tab dropdown indicator
  - Added show specific tab using id target in the url as hash
  - Added flipDropdown option to search component
  - Added possibility to change modal width via inline-style or custom class
  - Fixed responsive tabs
  - Fixed links within alert components
  - Fixed open modals in a chain
  - Fixed off-canvas scroll position bug

**Documentation and repository**

  - Added scrollspy and animation docs and tests
  - Added bower definition file
  - Automated version and download link
  - Added heading large example

### 1.0.2 (July 31, 2013)

  - Added boundary option for dropdowns
  - Removed Navbar.js
  - Removed auto dropdown flip if navbar is flipped

**Documentation and repository**

  - Updated dropdown and navbar documentation

### 1.0.1 (July 26, 2013)

  - Added focus and blur events to tooltip component
  - Added smoother off-canvas effect
  - Added hook for uk-container
  - Fixed multiple off-canvas trigger
  - Fixed `select` height for multiple and size attributes

**Documentation and repository**

  - Added import LESS functionality to customizer
  - Remove absolute paths from CSS build in customizer
  - Disabled LESS cache in tests
  - Tests initialized on domready instead of on window load
  - Updated grunt script to auto compile themes
  - Fixed several typos and links
  - Updated favicon

### 1.0.0 (July 19, 2013)

  * Initial Release
