# Float
**UNDER DEVELOPMENT**
> Float is a simple CSS framework (based on LESS). It's heavily influenced by Twitters Bootstrap. The goal is to develop a much more lightweight framework which is responsive and still highly compatible with older browser-versions.

## Usage

Start customising **variables.less**

***

### Page

If you want to center your page horizontally you can use the page-wrap class.

#### .page-wrap
```html
<body>
    <div class="page-wrap">
        ...
    </div>
</body>
```
***

### Grid

The Grid is a simple 8-column-based setup. You can combine different classes to adjust your layout. Use ```.col-last``` for end column.

***

### Layout examples:

```    
| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |   
```

```html
<div class="col-1">{{ 1 }}</div><div class="col-1">{{ 1 }}</div><div class="col-1">{{ 1 }}</div><div class="col-1">{{ 1 }}</div><div class="col-1">{{ 1 }}</div><div class="col-1">{{ 1 }}</div><div class="col-1">{{ 1 }}</div><div class="col-1 col-last">{{ 1 }}</div>
```

*** 

```    
| 2 |  4  | 2 |  
```

```html
<div class="col-2">{{ 2 }}</div><div class="col-4">{{ 4 }}</div><div class="col-2 col-last">{{ 2 }}</div>
```

***