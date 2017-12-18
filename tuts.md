# explaining confusing css
* float
* overflow
* clear
* box-sizing

~~~html
<style>
.parent {
  overflow: hidden;
}
.child {
  float: left;
  width: 33%;
  padding: 20px;
}
.uncle {
  clear: both;
}
</style>

<div class="parent">
  <div class="child"></div>
  <div class="child"></div>
  <div class="child"></div>
</div>
<div class="uncle"></div>
~~~

### border-radius property

to make any object rounded we will be 50% border-radius 
~~~css
img {
  border-radius: 50%;
}
~~~
### css selector again
* tag selector
* class 
* id 
* attribute
* pseudo 

### nested selector
~~~css
body header {
  
}
~~~

### writing same css for multiple selector 
~~~css
h1, h2, h3 {
  color: white;
}
~~~
