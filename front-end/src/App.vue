<template>
<div id="app">
  <div class="header">
    <router-link to="/">
    </router-link>
    <div class="title"> 
    <a id="github"  href="http://creative4.ammonwarnick.me/" >Home</a>
    <h1>My Diary Entries</h1>
  </div>
  </div>
  <div class="content">
    <router-view />
  </div>
  <div class="footer">
    <router-link to="/admin">Make an entry here</router-link>
    <br>
    <a id="github" href="https://github.com/AmmonWarnick/Creative4/tree/master" >Github</a>
  </div>
</div>
</template>

<style>
html {
  box-sizing: border-box;
}
a{
  text-align: right;
}
body {
  font-size: 16px;
  background: #fff;
  padding: 0px;
  margin: 0px;
}

/* Header */
.header {
  display: flex;
  padding: 10px 100px 0px 100px;
  background-color: #c9827d;
  color: #1C454F;
}

.title {
  margin-top: 5px;
}

.title h1 {
  font-size: 30px;
}

.content {
  padding: 20px 100px;
  min-height: 500px;
}

/* Footer */
.footer {
  height: 75px;
  padding: 20px 100px 0px 100px;
  background: #e3e3e3;
  font-size: 25px;
}

.footer a {
  color: #000;
}

#github{
  text-align: right;
}

h1 {
  font-size: 20px;
}

h2 {
  font-size: 14px;
}
</style>
