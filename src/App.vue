<!--
跟 Vue 说 Hello World！
-->

<script>
export default {
  data() {
    return {
      message: 'Hello World!'
    }
  }
}
</script>

<template>
  <h1 class="header italic code">Pro/g/ramming Challenge, v4.0</h1>
  <spam class="easy italic code"> Easy </spam>
  <spam class="medium italic code"> Medium</spam>
  <spam class="difficult italic code"> Difficult</spam>
  <spam class="fukyu italic code"> Fuck you</spam>
</template>
<style>
.header {
  color:dodgerblue;
}
.easy {
 color: green; 
}
.medium {
  color: yellow;
} 
.difficult {
  color: red;
}
.fukyu {
  color: purple;
}
.italic {
  font-style: italic;
}
.code {
  font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif ;
  padding: 3px;
}
</style>