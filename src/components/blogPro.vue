<template>
  <div>
    <div class="container mt-5 ">
      <div class="row mt-5">
        <div class="col-12">
          <h4 class="text-center blog cont">Our Blog</h4>
        </div>
      
      </div>
      <div class="row">
        <div class="col-12 col-md-4">
          <div class="card car" style="width: 18rem;">
  <img src="../assets/Frame 81 (1).png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5>Headline Text</h5>
    <p class="">Some qu</p>
  </div>
</div>
        </div>
        <div class="col-12 col-md-4">
          <div class="card car" style="width: 18rem;">
  <img src="../assets/Frame 81.png" class="card-img-top" alt="...">
  <div class="card-body">
    <p class="">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
  </div>
</div>
        </div>
        <div class="col-12 col-md-4">
          <div class="card car" style="width: 18rem;">
  <img src="../assets/Frame 81 (2).png" class="card-img-top" alt="...">
  <div class="card-body">
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
  </div>
</div>
        </div>
      </div>
      
      <div class="row">
      <div class="col-12 co">
        <button class="btn-lg bt button-nav mar mt-4 text-center">Read More</button>
      </div>
    </div>
    </div>
  </div>
</template>

<script>
export default {
     name: 'blogPro'
}
</script>

<style>
.co{
  display: flex;
      justify-content: center; 
      /* align-items: center; */
      height: 15vh;
      margin-bottom:100px;
      margin-top:20px;
}
.button-nav{
  background-color: #258576;
  width:135px;
  height:42px;
  border: 0px;
  border-radius:34px;
  color:white !important;
  font-size: 16px !important;
}
.car{
  /* box-shadow: 5px 10px #888888; */
  box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 12px;
}
.cont{
  margin-top:50px;
  margin-bottom:30px !important;
}
</style>