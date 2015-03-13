# Float
**UNDER DEVELOPMENT**
> Float is a simple CSS framework (based on LESS). It's heavily influenced by Twitters Bootstrap. The goal is to develop a more lightweight framework which is highly compatible with various browser-versions.

## Usage

Start customising **src/variables.less**

***

### Page

If you want to center your page horizontally you can use the page-wrap class.

#### .page-wrap

    <body>
        <div class="page-wrap">
            ...
        </div>
    </body>
    
***

### Grid

The Grid is a simple 4-column-based setup. You can combine different classes to adjust your layout. Keep in mind that all columns (except number 4) are using margin-right values.

***

#### .col-1, .col-2, .col-3, .col-4 

```    
| 1 | 2 | 3 | 4 |     
```

    <div class="col-1">...</div><div class="col-2">...</div><div class="col-3">...</div><div class="col-4">...</div>
  
*** 

#### .col-1-2, .col-3-4

```    
| 1 - 2 | 3 - 4 |     
```

    <div class="col-1-2">...</div><div class="col-3-4">...</div>

***

#### .col-1, .col-2-4

```    
| 1 | 2 - 4 |     
```

    <div class="col-1">...</div><div class="col-2-4">...</div>

***

#### .col-1-3, .col-4 

```    
| 1 - 3 | 4 |     
```

    <div class="col-1-3">...</div><div class="col-4">...</div>

***

#### .col-1-4 ( @todo: this should be .row )

```    
| 1 - 4 |     
```

    <div class="col-1-4">...</div>
