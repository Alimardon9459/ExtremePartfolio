<template>
  <div>
    <div class=" container">
      <div class="text-h4">
        newsletter
      </div>
      <div class=" q-mt-xl text-grey-7">
        A well-executed brand strategy affects all aspects of a business and is connected to consumer needs & emotions.
      </div>
      <div class="row q-mt-xl" >
        <input
          v-model="search"
          style= " width:400px"
          placeholder="Your-email"
          class="inp"
        />
        <q-icon class="bg-yellow q-pa-md text-white "  size="24px" name="arrow_upward" />


      </div>
    </div>
    <div class="row q-pa-xl justify-between">
      <div style="font-size:16px">
        <span class="text-bold">© XTRM.</span> All Right Reserved 2019.
      </div>
      <div>
        <q-icon class="q-mr-md" name="g_translate" size="20px"/>
        <q-icon class="q-mr-md"  name="g_translate" size="20px"/>
        <q-icon class="q-mr-md"  name="g_translate" size="20px"/>
        <q-icon class="q-mr-md"  name="g_translate" size="20px"/>
        <q-icon class="q-mr-md"  name="g_translate" size="20px"/>

      </div>
    </div>

  </div>
</template>
<script>
export default {

}
</script>
<style scoped>
  .inp{
    border-left: 2px solid rgb(243, 241, 241);
    border-top: 2px solid rgb(243, 241, 241);
    border-bottom: 2px solid rgb(243, 241, 241);
    border-right: 0px ;
    outline: none;
  }
  .container{
    margin-top: 100px;
    margin-left: 200px;
    width:500px;
  }

</style>
