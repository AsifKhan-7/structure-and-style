# Height

```
 child % me  height inherit nahi karega agar parent ki height % me set ki gayi hai. Parent
 ki height % ke alawa kisi aur unit me set karte hain to wo inherit hogi.
```

# Inset

```
It's a shorthand property of an element which sets top, right, bottom, and left properties of that element.This property works only positioned elements.

```

```
div {

    inset: 10px; top,right,bottom and left 10px for all
}
```

```
div {

    inset: 10px 20px; top, bottom = 10px and left, right = 20px
}
```

```
div {

    inset: 10px 20px 30px; top = 10px, left and right = 20px, bottom = 30px
}

```
```
div {

    inset: 10px 20px 30px 40px; top = 10px, right = 20px, bottom = 30px, left = 40px

}
```

## Exact Center an element

```
.container {
    position: relative;
    width: 300px;
    height: 300px;
    background-color: lightgray;
}
```
```
.child {
  position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  background-color: crimson;
}
```
## Position:fixed

```
position itself according to viewport
```
unset :  element ko static postion me convert karne ke liye