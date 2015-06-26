# lay
Awesome dynamic layout helpers using css tables

### Component

* `.lay` - **Main component**. Setup the layout container

#### Markup

```
<div class="lay">
  <div></div> // 1/3 column
  <div></div> // 1/3 column
  <div></div> // 1/3 column
</div>
```

```
<div class="lay">
  <div></div> // 1/4 column
  <div></div> // 1/4 column
  <div></div> // 1/4 column
  <div></div> // 1/4 column
</div>
```

### Container Modifiers

#### Variants

* `.lay--fixed` - **Fixed table**. All columns same size **or** keep size of specific columns

#### Spacing

* `.lay--s` - **Small** padding
* `.lay--m` - **Medium** padding
* `.lay--l` - **large** padding

#### Vertical Align

* `.lay--top` - **Top** align
* `.lay--middle` - **Middle** align
* `.lay--bottom` - **Bottom** align

#### Text Align

* `.lay--left` - **Left** text align
* `.lay--center` - **Center** text align
* `.lay--right` - **Right** text align

### Colum Modifiers

#### Widths

* `.lay--w0` - **Smallest width possible**. Depending on the content
* `.lay--w10` - **10%**
* `.lay--w20` - **20%**
* `.lay--w30` - **30%**
* `.lay--w40` - **40%**
* `.lay--w50` - **50%**
* `.lay--w60` - **60%**
* `.lay--w70` - **70%**
* `.lay--w80` - **80%**
* `.lay--w90` - **90%**

### Rows

* `.lay--rows` - *Nested rows*

#### Markup

```
<div class="lay lay-rows">
  <div> // Row
    <div></div> // 1/3 column
    <div></div> // 1/3 column
    <div></div> // 1/3 column
  </div>
  <div> // Row
    <div></div> // 1/3 column
    <div></div> // 1/3 column
    <div></div> // 1/3 column
  </div>
</div>
```

### Media queries

* `.lay--offMobile` - **Disable mobile layout**. Defaults to block elements
* `.lay--offTablet` - **Disable tablet layout**. Defaults to block elements
* `.lay--offDesktop` - **Disable desktop layout**. Defaults to block elements
