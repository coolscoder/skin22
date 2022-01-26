<template>
  <div container>
    <div title>SAVAGE FENTY</div>
    <div link>#SAVAGEX</div>
    <div link>#NEWDROPS</div>
    <div link>#SAVAGE X FIT</div>
    <div link>#X SURVIVORS</div>
    <div footer>@SAVAGEFENTY</div>
  </div>
</template>

<script>
  export default {
    name: 'App',
  }
</script>

<style>
  * {
    box-sizing: border-box;
    background: #edc5e9;
    color: #b83439;
    font-family: Helvetica;
    font-weight: bold;
    text-align: center;
    margin: 0;
  }
  [container] {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding: 3vh;
    min-height: 100vh;
  }
  [title] {
    font-size: 42px;
    display: flex;
    align-items: center;
  }
  [link] {
    font-size: 42px;
    border-bottom: 3px solid #b83439;
    width: fit-content;
    margin: auto;
  }
  [footer] {
    font-size: 18px;
  }
</style>
