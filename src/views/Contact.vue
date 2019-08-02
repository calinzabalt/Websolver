<template>
<v-container fluid style="margin: 0px; padding: 0px; width: 100%">
  <div class="contact">
      <v-parallax
    height="500"
    src="/imagini/bulletin-board-3127287_1920.webp">
      </v-parallax>
      <div class="grid">
      <p class="subtitle">
        If you have a project that you want to get started, or if you want
        my help to accomplish something, you can contact me on this platform:
      </p>
      </div>
        <form method="post">
          <input type="hidden" name="form-name" value="contact" />
          <p>
            <label><h3>Your Name:</h3> <input type="text" name="name"/></label>
          </p>
          <p>
            <label><h3>Your Email:</h3> <input type="email" name="email"/></label>
          </p>
          <p>
            <label><h3>Message:</h3> <textarea name="message"></textarea></label>
          </p>
          <p>
            <button aria-label="contact" type="submit">Send</button>
          </p>
        </form>
    </div>
</v-container>
</template>  

<script>
export default {
  name: 'contact',
  metaInfo: {
    title: 'Contact',

  meta: [
    {name: 'description', content:'Welcome!- Here you can contact me for more information'}
  ] 
  }
}
  
</script>

<style scoped>

.contact{
  background-color: #e9ebee;
  padding-bottom: 10px;
}

.subtitle{
  max-width: 900px;
  text-align: center;
  margin-left: auto;
  margin-right: auto;

}

p {
  font-size: 25px;
  font-family: "eurostile",sans-serif;
  font-weight: 300;
  margin: 0;
}

.grid {
      padding: 20px;
      color: #293347;
}

form{
    width:100%;
    max-width: 900px;
    margin:10px auto;
}

@media screen and (max-width:996px) {
    form{
        width:100%;
        max-width: 500px;
        margin:20px auto;
        margin-bottom: 40px;
    }
  }

  @media screen and (max-width:550px) {
    form{
        width:100%;
        max-width: 280px;
        margin:20px auto;
        margin-bottom: 40px;
    }
  }
  
  form p{
     font-size: 20px;
     font-family: "eurostile",sans-serif;
     font-weight: 300;
     margin: 5px;
     color: white;
}

  form h3{
    color: #293347;
    font-size: 20px;
  }

  input, textarea, text{
    width: 900px;
    max-width: 100%;
    resize: none;
    background-color: teal;
    height: 35px;
}

  @media screen and (max-width:996px) {
    input, textarea{
        width: 500px;
        max-width: 100%;
        resize: none;
    }
  }

  @media screen and (max-width:550px) {
    input, textarea{
        width: 280px;
        max-width: 100%;
        resize: none;
    }
  }

  textarea{
    height: 200px;
}

  label{
    text-align: left;
    font-weight: 400;
}

  form button{
    background: #4A96AD;
    font-weight: bold;
    text-transform: uppercase;
    padding: 20px 30px;
    font-size: 18px;
    border:none;
    color:#fff;
}

  form p{
    text-align: left;
}

form textarea, input{
  padding:5px;
}

</style>

