<script lang="ts" setup>
defineProps({
  tweet: Object
});
</script>
<template>

      <div class="tweet">
        <img src="https://i.imgur.com/9yw1Fyw.jpg" 
        alt="Imagen de perfil" class="profile-img" />
    
      <div class="body">
     
      <div class="top">
        
        <span class="user">
         
           <span class="name"><strong>{{ tweet.user.name }}</strong></span>
          <span class="handle">{{ tweet.user.twitterHandle }}</span>
          
        </span>

        <span class="timestamp">{{ tweet.date }}</span>
      </div>

      <p class="message">{{ tweet.message }}</p>

      <div class="actions">
        <!-- Font Awesome icons -->
      <button> <i class="far fa-comment">💬 </i></button>
    <button> <i class="fas fa-retweet">🔁</i></button>
  <button>    <i class="far fa-heart">🔁</i></button>
  <button>     <i class="fas fa-share">📤</i> </button>
      </div>
      
    </div>

    <i class="fas fa-ellipsis-h"></i>












  </div>









</template>

<style scoped>
a {
  color: #42b983;
}

.tweet {
  border: 1px solid #ddd;
  padding: 15px;
  border-radius: 10px;
  max-width: 600px;
  margin: 20px auto;
  background-color: #fff;
}

.header {
  display: flex;
  align-items: center;
}

.profile-img {
  width: 50px;
  height: 50px;
  border-radius: 50%;
  margin-right: 10px;
}

.user-info {
  display: flex;
  flex-direction: column;
}

strong {
  font-weight: bold;
}



p {
  margin: 10px 0;
}

.actions {
  display: flex;
  justify-content: space-around;
  margin-top: 10px;
}

button {
  background: none;
  border: none;
  cursor: pointer;
  font-size: 1.2em;
}



</style>



