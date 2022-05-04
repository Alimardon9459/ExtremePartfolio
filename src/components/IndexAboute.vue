<template >
  <div>
    <div class="contanier-page q-ma-xl">
      <div class="title-page text-grey-6">ABOUT US</div>
      <div class="content-page row q-mt-md ">
        <div class="bit-content" >
          <div>
            <span class="text-h4">When Snowboard Is</span>
            <span class="text-h4 bg-black text-yellow">Your Life</span>
            <div class="q-mt-xl q-mr-lg text-grey-7 " style="line-height: 1.6; ">Incredible scenery, an adrenaline rush or simply being out in the mountains are a few of the reasons people enjoy snowboarding. It's a great activity to get involved in and is more affordable than you might think if you plan ahead and are clever about a few bits and bobs.</div>
            <div class="row q-mt-lg ">
              <div class="q-mt-xl" >
                <q-img width="50px" :ratio="1/1" src="https://xtrm.foxthemes.me/wp-content/uploads/2018/09/Group.png" />
                <span>Equipment</span>
              </div>
              <div class="q-ml-xl q-mt-xl">
                <q-img width="50px" :ratio="1/1" src="https://xtrm.foxthemes.me/wp-content/uploads/2018/09/Group.png" />
                <span>Clothes</span>
              </div>
              <div class="q-ml-xl q-mt-xl">
                <q-img width="50px" :ratio="1/1" src="https://xtrm.foxthemes.me/wp-content/uploads/2018/09/Group.png" />
                <span>Accessories</span>
              </div>
            </div>
          </div>
        </div>
        <div class="bit-content">
          <q-video :ratio="10/7" src="https://xtrm.foxthemes.me/wp-content/uploads/2018/09/Group-5.jpg"/>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name:"IndexAboute"
}
</script>
<style scoped>
  .bit-content{
    width: 50%;

  }
</style>
