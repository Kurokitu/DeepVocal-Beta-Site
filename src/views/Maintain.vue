<template>
  <div id="Maintain">
    <div class='icon-t'>
      <font-awesome-icon :icon="['fas','wrench']" />
      <!-- <img width="20%" src="@/assets/maintain.png"> -->
    </div>
    <h1 class='t1'>{{ $t("maintain") }}</h1>
  </div>
</template>

<script>
export default {
  name: "Maintain"
}
</script>

<style>
.t1 {
  position: absolute;
  top: 40%;
  font-size: 32px;
  width: 100%;
  text-align: center;
}
.icon-t {
  width: 100%;
  position: absolute;
  top: 20%;
  font-size: 100px;
  text-align: center;
}
</style>