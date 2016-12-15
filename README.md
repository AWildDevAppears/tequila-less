# Tequilla

If everyone else can name their sass modules after alcoholic beverages, why don't I
do it too?

## Whats under the hood?

### Basic mixins

### Display flex
```
    .display-flex();
```

This one simply sets a block to display flex, use this on the outer row. Flex row uses this

### Display inline flex
```
    .display-inline-flex();
```

This one simply sets a block to display inline flex, use this on the outer row.

### Flex direction
```
   .flex-direction(row);
```

This changes the direction that the row will use flex, this defaults to row. To
find out all of the options, see [this link](https://developer.mozilla.org/en/docs/Web/CSS/flex-direction).

### Flex wrap
```
    .flex-wrap(nowrap);
```

This changes whether the row will wrap or not, this defaults to nowrap.
To find out all of the options, see [this link](https://developer.mozilla.org/en/docs/Web/CSS/flex-wrap).

### Flex flow - (NYI)
```
    .flex-flow(row nowrap);
```


Flex flow is a shorthand way of calling flex direction and flex flow

For more information see [this link](https://developer.mozilla.org/en/docs/Web/CSS/flex-flow).

### Align items
```
    .align-items(stretch);
```

This mixin aligns the flex items on the current flex line

For more information see [this link](https://developer.mozilla.org/en/docs/Web/CSS/flex-align).


### Align flex items - (NYI)
```
   .align-flex-items(stretch);
```

This mixin aligns a flex container's lines within the flex container when there is extra space on the cross-axis.

For more information see [this link](https://developer.mozilla.org/en/docs/Web/CSS/align-content).

### Justify content
```
    .justify-content(stretch);
```

This mixin aligns a flex container's lines within the flex container when there is extra space on the cross-axis.

For more information see [this link](https://developer.mozilla.org/en/docs/Web/CSS/align-content).

For more information see [this link](https://developer.mozilla.org/en/docs/Web/CSS/align-content).

### Flex
```
    .flex(0, 1, 1);
```

The flex mixin is a quick way of making flex items, it takes three properties,
all of which are optional, the 1st is the flex grow property, the second,
flex shrink and the third, flex basis.

The flex grow property is the amount of the row you want this item to take up,
the flex shrink property states by which factor the block should be shrunk,
the flex basis sets the base size of the flex item

For basic usage of the flex mixin you should be able to get away with not passing
any arguments to the mixin, for more complex stuff you will need to get to grips
on what the grow, shrink and basis options do

For more information see [this link](https://developer.mozilla.org/en/docs/Web/CSS/flex)
and all will be revealed (hopefully).

### Flex order - (NYI)
```
    .flex-order(3);
```

This mixin adjusts the position of a flex item, reordering it in the DOM

For more information see [this link](https://developer.mozilla.org/en/docs/Web/CSS/order).

### Align flex self
```
    .align-flex-self(3);
```

This mixin works a lot like `align-flex` except it acts on a single flex item</p>

For more information see [this link](https://developer.mozilla.org/en/docs/Web/CSS/align-self).

