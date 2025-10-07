# Simple SVG shape manipulation demo

This should give you an idea how to populate a scene with SVG shapes (circle) and animate them.

Compare:
- **SVG** draws a scene of **vector** graphics onto the browser's page
- **Canvas** draws **pixel** graphics onto the browser's page

Canvas is generally faster for performance-intensive applications with many rapidly changing objects, while SVG is faster for static graphics or scenes with fewer, more complex objects.

- Canvas uses an "immediate" rendering mode (drawing when function is called).
- SVG "retains" the vector elements in a tree.

Interactive interfaces: Because SVG elements are part of the DOM, they have built-in event handlers. This makes it easier and potentially faster for developers to create interactive elements like hover effects or drag-and-drop features. 

