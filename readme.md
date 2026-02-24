1. Difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll:

getElementById() → Selects one element by ID.
getElementsByClassName() → Selects multiple elements by class name (HTMLCollection).
querySelector() → Selects the first element matching a CSS selector.
querySelectorAll() → Selects all elements matching a CSS selector (NodeList).

2. How do you create and insert a new element into the DOM?

Use document.createElement() to create the element and appendChild() or append() to insert it into the DOM.

3. What is Event Bubbling? How does it work?

Event Bubbling is when an event starts from the target element and then propagates upward to parent elements in the DOM hierarchy.

4. What is Event Delegation in JavaScript? Why is it useful?

Event Delegation is attaching a single event listener to a parent element to handle events for its child elements.It is useful because it improves performance and works for dynamically added elements.

5. Difference between preventDefault() and stopPropagation():

preventDefault() → Stops the default browser behavior (e.g., form submission).
stopPropagation() → Stops the event from bubbling up to parent elements.