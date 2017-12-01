插值

@for $i from 1 to 12{

​	.col-#{$i}{

​		width:$i/12*100%;

​	}

}

$arr : cat dog pig fish;

遍历数组

```
@each $i in $arr{
  .#{$i}{  
  background-image : url('.../img/#{$i}.png')
}
}
```

