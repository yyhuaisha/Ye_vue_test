<template>
  <div id="myComponent">
    <h1>I'm a title, I'm not a biaoti！</h1>
    <p>{{youAre}}</p>
  </div>
</template>

<script type="text/javascript">
  export default{
    data() {
      return {
        youAre: `"你是大傻逼吗？" ， "是的，你是！"`
      }
    } 
  }
</script>