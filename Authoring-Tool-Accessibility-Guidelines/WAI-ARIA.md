###### tags: `Accesibility Fundamentals - Disabilities, Guidlines, and Laws` `WAI-ARIA (Accessible Rich Internet Applications) 1.0`

# Overview
WAI-ARIA—or just ARIA, for short—is a somewhat recent invention, intended to help fill in the gaps between the accessibility features of HTML and the real-world accessibility needs of today's robust, dynamic web applications, especially with regard to JavaScript. ARIA allows developers to specify the name, role, state, and property of HTML elements in both static and dynamic content. ARIA is not an entirely new language. It is an add-on to the HTML syntax. For example, to add a role of "navigation" to an HTML element, simply type it as an attribute

:::info
To designate the navigation role with ARIA:

```htmlembedded=
<div role="navigation">
```

To add the aria-haspopup property with ARIA:
```htmlembedded=
<div aria-haspopup="true">
```
:::

## ARIA Features
ARIA is almost entirely for screen reader users (and for speech recognition users and some keyboard-only users), in the sense that the markup is hidden, and ARIA allows screen reader users to know what's happening visually on the screen. The types of things that ARIA can help screen reader users know is:

* If a link opens a popup window
* If an object (like a folder icon) is expandable
* If an object is currently expanded or collapsed
* If something has changed or been updated on the page (via "live regions")
* What type of object or widget it is; for example:
    * A tab panel
    * A tab
    * A slider
    * An alert dialog
    * A tooltip
    * A menu
    * A menu item
    * A hierarchical tree view
    * And several other pre-defined roles

This overview barely scratches the surface of what ARIA can do. ARIA is primarily to be used by web developers and programmers, because implementing ARIA usually requires JavaScript skills. Learning ARIA can also take a fair amount of time because of the complexities of the programming logic and also the nuances of ensuring that ARIA widgets work well across different browsers and screen readers.

### WAI-ARIA Authoring Practices 1.1
One of the best places to go to learn how to implement ARIA is the WAI-ARIA Authoring Practices 1.1 opens in a new window documentation. This is considered the official guide to structure and methods of ARIA widgets, including keyboard behaviors, markup, interaction patterns and so on.
