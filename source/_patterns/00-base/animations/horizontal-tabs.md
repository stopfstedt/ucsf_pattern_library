--- 
title: Horizontal Tabs 
---

---
state: complete
---

### Description
This is a horizontal tab.

### Usage
Horizontal tabs should be used to compress related information that doesn't need to be displayed immediately on page load. Users can quickly navigate to content relevant to them. Horizontal tabs imply equal importance between all items, so should be used accordingly. The tabs shouldn't exceed the given tab area width.

### Accessibility Considerations
Complex menus, sliders, dialogs, tab panels, etc. must all be built to support keyboard accessibility. Please ensure accessibility by testing the whole page, including this element, in context.

* About menu accessibility properties: http://webaim.org/techniques/aria/

### SEO Considerations
This section is left intentionally blank and is for future consideration.

### Technical Considerations
To implement the horizontal-tab, use the markup structure shown here, with the class horizontal-tab.

Horizontal Tabs utilize the jquery-accessible-tabs.js library and is included via npm. The Js file can be found in the source/js/vendor folder. All compilation dependencies are listed in npm-shrinkwrap.json file.
