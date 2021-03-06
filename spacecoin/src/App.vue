<template>
  <div>
    <div class="container">
      <a href="https://mycoin-space.herokuapp.com/"><img class= "logo" src="@/assets/logo.svg" alt="Coin Space Logo"></a>

      <form @submit.prevent="handleSubmitForm">
        <div class="form-group">
          <label for="crypto">Crypto:</label>
         
          <div class="form-group-inner">
            <input type="text" class="crypto" placeholder="BTC" required>
            <button class="add">Add</button>
          </div>
          <p class="info">Use Abbreviations</p>
        </div>

      </form>

    <div class="crypto-contianer">
      <div class="crypts">
        <p class="price">$48,549.90</p>
        <div class="lower">
          <p class="crypto-label">BTC</p>
          <button class="delete-btn"><img src="@/assets/DeleteIcon.svg" alt="delete crypto"></button>
        </div>
      </div>

    </div>
    </div>
  </div>
</template>

<script>

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;700&display=swap');
# {
  box-sizing: border-box;
  }
  body {
    background: white;
    color: black;
    margin: 0;
    height: 100vh;
    font-family: 'Poppins';
  }

  .logo {
    width: 10em;
    margin: 3em 0;
  }

  .container {
    text-align: center;
    margin: 0 1em;
  }

.form-group { 
  text-align: left;
  width: 300px;
  margin: 7em auto;
}

.label {
  font-weight: bold;
  margin-bottom: .7em;
  display: block;
}

.input {
  padding: 1em;
  outline: none;
  border: none;
  border-top-left-radius: .3em;
  border-bottom-left-radius: .3em;
  font-size: 1.3em;
}

.form-group-inner {
  display: grid;
  grid-template-columns: 100px auto;
}

button.add {
  font-size: 1em;
  font-weight: bold;
  color: white;
  background: #21BC5C;
  border: none;
  outline: none;
  padding: 1em 3em;
  border-top-right-radius: .3em;
  border-bottom-right-radius: .3em;
}
</style>
