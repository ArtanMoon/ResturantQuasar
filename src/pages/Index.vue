<template>
  <div class="window-height row" style="background:#000000">
      <q-img
        src="~assets/login_background.png"
        style="width: 100%"
      />
    <div class="q-pa-md full-width">
    <form>
      <q-input square filled v-model="text" label="USERNAME"  align="center" class="q-mt-l q-mb-none" bg-color="grey" label-color="white" />
      <q-input square filled v-model="password" type="password" label="PASSWORD"  class="q-mt-xs"  bg-color="grey" label-color="white"/>
      <q-btn round no-caps  class="q-mt-sm full-width" @click="$router.push('dashboard');">
        <q-img src="~assets/btn_login.png" style="width: 100%"/>
      </q-btn>
    </form>
    </div>
    <a href="" class="col-6 q-pl-md" style="color:red;">Forgot password?</a>
    <a href="" class="col-6 q-pr-md" style="text-align:right; color:white;">Client registration</a>
  </div>
</template>
<script>
export default {
  name: 'PageIndex'
}
</script>
