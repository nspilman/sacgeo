<template>
  <div id="about">
    <div class="main-text-wrapper">
      <h2>About Sac Geo</h2>
      {{ mainText }}
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      mainText: `I believe everyone can agree the world could use more creativity and joy. The problem is it seems these things are harder and harder to find, even in our own lives. I’d like to think my ideas can inspire and motivate others to create in their lives and share with others what we all lack. That’s why I started Sac Geo. 
            I want to help people learn more about themselves so we can find ways to achieve success professionally and personally. Only through this process can we find the best version of ourselves. 
            With your generous support, I can make my project a reality and continue to build a community of people who could use a new source of powerful inspiration. I have some exciting and interesting rewards in mind for my contributors, and I’m looking forward to keeping you updated on the new projects I have planned for the future. I appreciate your support and hope you enjoy what we have to offer. Thank you for your time.`
    };
  }
};
</script>

<style scoped>
#about {
  color: white;
  display: flex;
  align-items: center;
  height: 100vh;
  background-image: url("http://66.media.tumblr.com/2ec65923381028fcbdc0a6924910da45/tumblr_n65d4b1NZF1rflzz4o1_500.gif");
  background-repeat: no-repeat;
  background-position: 50%, 50%;
  /* background-size: 100%; */
  background-color: black;
  background-attachment: fixed;
}

.main-text-wrapper {
  padding: 3vw;
  margin: 15vw;
  background-color: rgba(255, 234, 0, 0.8);
  border-radius: 2em;
}
</style>
