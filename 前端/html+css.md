# 框架

## tlidwindcss

# 组件库

##animate.css



# sass

- 使用`mixin`的时候一定要把这个申明放在代码块最前面，然后再用`include`进行引入，不然会找不到

  > css编译是有顺序的

``` css
@mixin border-radius($radius) {
  -webkit-border-radius: $radius;
  -moz-border-radius: $radius;
  -ms-border-radius: $radius;
  border-radius: $radius;
}


  #awesome {
    width: 150px;
    height: 150px;
    background-color: green;
  @include border-radius(15px);
  }
```

- ![image-20220409113049135](/Users/suhui/Library/Application Support/typora-user-images/image-20220409113049135.png)

- for 循环：

  ``` css
  <style type='text/scss'>
  
  @for $i from 1 through 5 {
    .text-#{$i} {
      font-size: 15px * $i ;
    }
  }
  
  </style>
  
  <p class="text-1">Hello</p>
  <p class="text-2">Hello</p>
  <p class="text-3">Hello</p>
  <p class="text-4">Hello</p>
  <p class="text-5">Hello</p>
  ```

- 变量的所有使用前面都要加上$

- 
