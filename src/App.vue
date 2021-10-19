<template>
<head>
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
</head>
<body>
  <div class="wrapper">
    <div class="menu-bar">
      <span class="menu-left-btn"><i class="material-icons">menu</i></span>
      
      <span class="menu-right-btn material-icons">add_box</span>
      <br><br>
      <span class="menu-left-btn" style="color:white;  margin-bottom:5px; font-size:150%">Schedule</span>
       
      
    </div>
  </div>
  <br><br><br>
  <div style="position:fixed">
   
    
    
  </div>
</body>
  
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
#app {
  width: 100%;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}

.menu-bar{
  background-color: rgb(26, 115, 232);;
  position:fixed;
  padding:0;
  margin:0;

  top:0;
  left:0;
  padding-top: 10px;
  /* padding-left: 10px; */

  width: 100%;
  height: auto;
  color:white;
}

.menu-left-btn{
  float: left;
  margin-left: 12px;
} 

.menu-right-btn{
  float: right;
  margin-right: 12px;
  font-size: 150%;
}
</style>
