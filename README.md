# Float
**UNDER DEVELOPMENT**
> Float is a simple grid framework.

## Usage

Start customising **variables.less**

***

### Container class

To center the content horizontally you can use the grid class.

#### .grid
```html
<div class="grid">
    ...
</div>
```
***

### Grid

The grid is a simple 12-column-based setup. You can combine different classes to adjust your layout. Use ```.col-last``` for the last column.

***

### Layout examples:

```    
| 4 |   8   |   
```

```html
<div class="grid">
    <div class="col-4">{{ 4 }}</div><div class="col-8 col-last">{{ 8 }}</div>
</div>
```

*** 

```    
| 3 |  6  | 3 |  
```

```html
<div class="grid">
    <div class="col-3">{{ 3 }}</div><div class="col-6">{{ 6 }}</div><div class="col-3 col-last">{{ 3 }}</div>
</div>
```

***