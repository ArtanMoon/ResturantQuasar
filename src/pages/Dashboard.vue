<template>
  <div class="window-height row" style="background:#000000;">
      <q-img
        src="~assets/dashboard_background.png" class="fit-width"
      />
      <div class="q-pt-none full-width row">
        <div  class="col-4" style="text-align:center;">
          <img src="~assets/btn_whatson.png" style="width:60%;"/>
        </div>
        <div  class="col-4"  style="text-align:center;">
        <img src="~assets/btn_food.png" style="width:60%;"/>
        </div>
        <div  class="col-4" style="text-align:center;">
        <img src="~assets/btn_findus.png" style="width:60%;"/>
        </div>
      </div>
      <div class="q-pa-md col-12">
      <q-btn round no-caps  class="full-width">
        <q-img src="~assets/btn_makeorder.png"/>
      </q-btn>
      </div>
  </div>
</template>
<script>
export default {
  name: 'PageIndex'
}
</script>
