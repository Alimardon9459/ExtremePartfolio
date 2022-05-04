<template>
  <div class="row justify-center wrap">
    <div style="margin-top:120px ; width:100% " class="text-center text-h3 text-bold">
        Shop
    </div>
    <section class="row wrap justify-center" style="width:100%;" >
      <div style="width:90% ; margin-top:100px" class="row wrap justify-between"  >
      <div style="width:32% " class="bit-content" v-for="product in products " :key="product">
        <div class=" bg-grey-2 bit-img row justify-center items-center " >
          <q-img  width="60%" :src="product.img" />
        </div>

        <div class=" text-center bit-none row items-center">
          <div style="width:100%">
            <div style="width:100%">
              <q-btn class="btn-add bg-black text-white" label="ADD TO CARD"/>
            </div>
            <div class="text-bold text-h6" style="width:100%" >view</div>
          </div>
        </div>
        <div v-if="product.sale" class="bit-high">
          <span class="bg-deep-orange-5 q-pa-xs q-pl-md q-pr-md  text-white text-bold">Sale</span>
        </div>
        <div>
          <div class="row justify-between q-mt-md">
            <div class="text-h6" > {{product.name}} </div>
            <div> <del style="font-size:18px" class=" text-h text-grey-7">£{{product.skitki}}</del> <span class="text-h6">£{{product.cost}}</span></div>
          </div>
          <div class="q-mt-sm text-deep-orange-5 text-bold">
            <span>{{product.group}}</span>
          </div>

        </div>
      </div>
    </div>
    </section>
    <footer style="width:100%; margin-top:50px">
      <div>
        <div>
          <q-icon class="q-ml-xl" name="west" size="30px" color="grey-6" /> <span class=" text-nazad q-ml-md text-h5"  >previous page</span>
        </div>
        <div style="width:100%; margin-bottom:50px; margin-top:50px" class="text-center">
          <div>
            <q-icon class="q-mr-md" name="g_translate" size="20px"/>
            <q-icon class="q-mr-md"  name="g_translate" size="20px"/>
            <q-icon class="q-mr-md"  name="g_translate" size="20px"/>
            <q-icon class="q-mr-md"  name="g_translate" size="20px"/>
            <q-icon class="q-mr-md"  name="g_translate" size="20px"/>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
  data() {
    return {
      products:[
        {
          img:'https://xtrm.foxthemes.me/wp-content/uploads/2018/10/group-31-copy-1.png',
          sale:true,
          name:'Angry T-Shurt ',
          skitki:'289.00',
          cost:'259.00',
          group:'Sk Clothes'
        },
        {
          img:'https://xtrm.foxthemes.me/wp-content/uploads/2018/09/group-29-1.png',
          sale:true,
          name:'Asid Lemon Helmet',
          skitki:'359.00 ',
          cost:'341.00',
          group:'Sn Bodyguard'
        },
        {
          img:'	https://xtrm.foxthemes.me/wp-content/uploads/2018/10/group-29-1.png',
          sale:false,
          name:'Asid T-Shurt',
          skitki:'',
          cost:'289.00',
          group:'Sk Clothes'
        },
        {
          img:'	https://xtrm.foxthemes.me/wp-content/uploads/2018/09/3-2.png',
          sale:true,
          name:'Bike Shoes',
          skitki:'320.00 ',
          cost:'289.00',
          group:'Shoes'
        },
        {
          img:'https://xtrm.foxthemes.me/wp-content/uploads/2018/10/group-17.png',
          sale:true,
          name:'Bike Shoes',
          skitki:'289.00 ',
          cost:'266.00',
          group:'Fishing'
        },
        {
          img:'	https://xtrm.foxthemes.me/wp-content/uploads/2018/09/5.png',
          sale:true,
          name:'Black & Oragne Jersey',
          skitki:'289.00',
          cost:'260.00',
          group:'Clothes'
        },
        {
          img:'https://xtrm.foxthemes.me/wp-content/uploads/2018/10/group-31-copy-1.png',
          sale:true,
          name:'Angry T-Shurt ',
          skitki:'289.00',
          cost:'259.00',
          group:'Sk Clothes'
        },
        {
          img:'https://xtrm.foxthemes.me/wp-content/uploads/2018/09/group-29-1.png',
          sale:false,
          name:'Asid Lemon Helmet',
          skitki:'359.00 ',
          cost:'341.00',
          group:'Sn Bodyguard'
        },
        {
          img:'	https://xtrm.foxthemes.me/wp-content/uploads/2018/10/group-29-1.png',
          sale:false,
          name:'Asid T-Shurt',
          skitki:'',
          cost:'289.00',
          group:'Sk Clothes'
        },
        {
          img:'	https://xtrm.foxthemes.me/wp-content/uploads/2018/09/3-2.png',
          sale:true,
          name:'Bike Shoes',
          skitki:'320.00 ',
          cost:'289.00',
          group:'Shoes'
        },
        {
          img:'https://xtrm.foxthemes.me/wp-content/uploads/2018/10/group-17.png',
          sale:false,
          name:'Bike Shoes',
          skitki:'289.00 ',
          cost:'266.00',
          group:'Fishing'
        },
        {
          img:'	https://xtrm.foxthemes.me/wp-content/uploads/2018/09/5.png',
          sale:true,
          name:'Black & Oragne Jersey',
          skitki:'289.00',
          cost:'260.00',
          group:'Clothes'
        },
        {
          img:'	https://xtrm.foxthemes.me/wp-content/uploads/2018/09/5.png',
          sale:true,
          name:'Black & Oragne Jersey',
          skitki:'289.00',
          cost:'260.00',
          group:'Clothes'
        },
      ]

    }
  },
}
</script>
<style scoped >
  .bit-img{
    width: 100%;
    height: 60vh;
    box-shadow: 1px 5px 30px 0px rgb(206, 209, 214) ;
  }
  .bit-content{
    position: relative;
    margin-top: 70px;
  }
  .bit-high{
    position:absolute;
    top: 20px;
    left: 87%;
  }
  .bit-none{
    opacity: 0;
    position:absolute;
    top: 0px;
    width: 100%;
    height: 60vh;
    background:rgba(255, 255, 255, 0.557);
    transition: 0.2s;
  }
  .bit-none:hover{
    opacity: 1;
  }
  .btn-add{
    border-radius: 0px;
    padding: 15px 40px ;
  }
  .text-nazad{
    transition: 0.4s;
  }
  .text-nazad:hover{
    margin-left:50px
  }

</style>
