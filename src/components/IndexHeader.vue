<template >
  <div>
      <q-img style="position:absolute;  top:0;" src="https://xtrm.foxthemes.me/wp-content/uploads/2018/09/Group-2.png">
        <div class="text-center text">LIVE BRIGHT RIDE HARD</div>
        <div class="row justify-center content">
          <div class="text-center textheader">Live Bright</div>
          <div class="text-center textheader bg-black text-yellow q-ml-sm" >Ride Hard</div>
        </div>
        <div class="row justify-center btn-content q-mt-xl">
          <q-btn class="btn-header bg-yellow" label="FIND OUT HOW"/>
        </div>
      </q-img>

  </div>
</template>
<script>
export default {
  name:"IndexHeader"

}
</script >
<style scoped >
  div{
    background: none;
  }
  .content{
    width: 100%;
    margin-top: 250px;
  }
  .text{
    width: 100%;
    margin-top: 220px;
    font-size: 15px;
    font-family: sans-serif;

  }
  .textheader{
    font-size: 72px;
    font-family: sans-serif;

  }
  .btn-content{
    width: 100%;
    top: 350px;
  }
  .btn-header{
    padding: 10px 35px;
    border-radius:0;
    transition: 1s;
  }

</style>
