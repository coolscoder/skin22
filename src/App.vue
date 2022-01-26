<template>
  <div container>
    <div title>SAVAGE FENTY</div>
    <div socials twitter>TWITTER</div>
    <div link>#SAVAGEX</div>
    <div socials instagram>INSTAGRAM</div>
    <div link>#NEWDROPS</div>
    <div socials youtube>YOUTUBE</div>
    <div link>#SAVAGE X FIT</div>
    <div link mt-80>#X SURVIVORS</div>
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
    text-decoration: underline;
    margin: 0 auto;
  }
  [footer] {
    font-size: 18px;
    margin-top: auto;
  }
  [mt-80] {
    margin-top: 80px;
  }
  [socials] {
    width: fit-content;
    background-color: #fbfa24;
    text-decoration: underline;
    border-radius: 50%;
    padding: 20px;
    margin: 6px;
  }
  [twitter] {
    transform: rotate(-15deg);
  }
  [instagram] {
    transform: rotate(15deg);
    margin-left: auto;
  }
  [youtube] {
    transform: rotate(-15deg);
  }
</style>
