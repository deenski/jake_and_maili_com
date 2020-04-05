<template>
<div class="container gallery">
  <div>
   <img src="/gallery/1.jpg" alt>
  </div>
  <div>
   <img src="/gallery/3.jpg"alt>
  </div>
  <div>
   <img src="/gallery/2.jpg" alt>
  </div>
  <div>
   <img src="/gallery/4.jpg" alt>
  </div>
  <div>
    <img src="/gallery/5.jpg" alt>
  </div>
  <div>
    <img src="/gallery/7.jpg" alt>
  </div>
  <div>
    <img src="/gallery/6.jpg" alt>
  </div>
  <div>
    <img src="/gallery/8.jpg" alt>
  </div>
  <div>
    <img src="/gallery/9.jpg" alt>
  </div>
  <div>
    <img src="/gallery/10.jpg" alt>
  </div>
</div>
</template>


<style>
body { margin: 0; background: #333; }
.gallery {
  padding: .5vw;
  font-size: 0;
  display: -ms-flexbox;
  -ms-flex-wrap: wrap;
  -ms-flex-direction: column;
  -webkit-flex-flow: row wrap;
  flex-flow: row wrap;
  display: -webkit-box;
  display: flex;
}
.gallery div {
  -webkit-box-flex: auto;
  -ms-flex: auto;
  flex: auto;
  width: 500px;
  margin: .5vw;
}
.gallery div img {
  width: 100%;
  height: auto;
}
@media screen and (max-width: 400px) {
  .gallery div { margin: 0; }
  .gallery { padding: 0; }

}
</style>
