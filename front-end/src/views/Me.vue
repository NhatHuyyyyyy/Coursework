<template>
  <div class="introduction">
    <h1>Hello, I'm {{ name }}!</h1>
    
    <p>{{ bio }}</p>
    <p>This is my email: <a :href="'mailto:' + email">{{ email }}</a></p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: "Nguyen An Nhat Huy",
      
      bio: "This is a coursework in Web Programming 2(COMP1842) ",
      email: "huynangcs220724@fpt.edu.vn"
    };
  }
};
</script>

  