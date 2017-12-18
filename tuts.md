# confusing css
* float
* overflow
* clear
* box-sizing

tag select
class .
id #
attribute []
pseudo :
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
