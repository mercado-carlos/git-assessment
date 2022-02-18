# Introduction to ARIA

The ARIA is good for bridging areas with accessibility issues that can't be managed with native HTML. It works by allowing you to specify attributes that modify the way an element is translated into the accessibility tree.

## How it works?

-   ARIA works by changing and augmenting the standard DOM accessibility tree.
-   ARIA doesn't augment any of the element's inherent behavior.
-   Certain HTML elements have restrictions on what ARIA roles and attributes can be used on them.

## What can ARIA do?

-   Can add extra label and description text that is only exposed to assistive technology APIs.
-   Can express semantic relationships between elements that extend the standard parent/child connection.
-   Can make parts of the page "live", they immediately inform assistive technology when they change.
-   Keyboard interactions feature so prominently in screen reader usage.
-   Provides a vocabulary of patterns we can use via the "role" attribute.

## ARIA Labels and Relationships

-   aria-label: Specify a string to be used as the accessible label.
-   aria-labelledby: Specify the ID of another element in the DOM.
-   aria-owns: Allows to tell assistive technology that an element that is separate in the DOM should be treated as a child of the current element.
-   aria-activedescendant: Tell assistive technology that an element should be presented to the user as the focused element when its parent actually has the focus.
-   aria-describedby: Provides an accessible description.
-   aria-setsize: Can specify the actual set size.
-   aria-posinset: Related to aria-setsize, can specify the element's position in the set.
-   aria-hidden: Removes that element and all of its children.
-   aria-live="polite": Alert the user to a change.
-   aria-live="assertive": Tells assistive technology to interrupt.
-   aria-live="off": Temporarily suspend "aria-live" interruptions.
-   aria-atomic: Indicates whether the entire region should be considered as a whole when communicating updates.
-   aria-relevant: Indicates types of changes should be presented to the user.
-   aria-busy: Notify assistive technology that it should temporarily ignore changes to an element.
