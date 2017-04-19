The **Flexbox Layout** is a CSS module that defines a CSS box model optimized for user interface design. In the flex layout model, the children of a flex container can be laid out in any direction, and can adjust their sizes, either growing to fill unused space or shrinking to avoid overflowing the parent. Both horizontal and vertical alignment of the children can be easily manipulated. Nesting of these boxes (horizontal inside vertical, or vertical inside horizontal) can be used to build layouts in two dimensions.

## Note
Flexbox is intented for components of an application and small-scale layouts, use the grid layout for large scale layouts.

### Flexbox model
The flexbox model consists of two basic property groups, the properties for the container and the properties for the children (items).

Container properties being able to define a flex container, manipulate the childrens direction, wrapping, justifying and aligning content.
Whereas the children properties can define their order, default size, whether they should grow to fill the space around it or to shrink and override their alignment set by the parent.

### Support
[Flexbugs](https://github.com/philipwalton/flexbugs) is a community-curated list of flexbox issues and cross-browser workarounds for them.