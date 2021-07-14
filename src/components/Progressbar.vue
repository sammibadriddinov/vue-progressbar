<template>
  <div class="progress-bar">
    <div class="progress-inner">
      <span>0%</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'progressbar'
}
</script>

<style>
  .progress-bar{
    width: 100%;
    height: 20px;
    background: #fff;
    position: relative;
  }
  .progress-inner{
    height: 100%;
    background: linear-gradient(to right, #ED008D, #2484E4);
    border-radius: 0 10px 10px 0;
  }
  .progress-inner span{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #313131;
    font-size: 14px;
  }
</style>