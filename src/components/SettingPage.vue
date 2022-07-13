<template>
  <div class="privacy">
    <div class="main">
        <div class="privacy-content">
        <div class="flex">
          <h3>Settings</h3>
        </div>
       
      </div>
      <div class="privacy-content-1">
        <div class="flex">
          <div class="icon">
            <i class="las la-cog"></i>
          </div>
          <h3>Account</h3>
        </div>
        <div class="passage">
          <p>This Project would be available to anyone who has the link</p>
        </div>
      </div>
      <div class="privacy-content">
        <div class="flex">
          <div class="icon">
          <i class="las la-bell"></i>
          </div>
          <h3>Notifications</h3>
        </div>
        <div class="passage">
          <p>This Project would be available to anyone who has the link</p>
        </div>
      </div>
      <div class="privacy-content">
        <div class="flex">
          <div class="icon">
        <i class="las la-image"></i>
          </div>
          <h3>Appearance</h3>
        </div>
        <div class="passage">
          <p>This Project would be available to anyone who has the link</p>
        </div>
      </div>
       <div class="privacy-content">
        <div class="flex">
          <div class="icon">
          <i class="las la-wallet"></i>
          </div>
          <h3>Billings</h3>
        </div>
        <div class="passage">
          <p>This Project would be available to anyone who has the link</p>
        </div>
      </div>
       <div class="privacy-content">
        <div class="flex">
          <div class="icon">
          <i class="las la-university"></i>
          </div>
          <h3>Integrations</h3>
        </div>
        <div class="passage">
          <p>This Project would be available to anyone who has the link</p>
        </div>
      </div>
       <div class="privacy-content">
        <div class="flex">
          <div class="icon">
            <i class="las la-play-circle"></i>
          </div>
          <h3>Available to hire</h3>
        </div>
        <div class="passage">
          <p>This Project would be available to anyone who has the link</p>
        </div>
      </div>
       <div class="privacy-content">
        <div class="flex">
          <div class="icon">
            <i class="las la-play-circle"></i>
          </div>
          <h3>Available to hire</h3>
        </div>
        <div class="passage">
          <p>This Project would be available to anyone who has the link</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@media only screen and (max-width: 780px) {
  .privacy {
  display:block
  
}
}
.privacy-title {
  padding-bottom: 20px;
  padding-top: 20px;
}
.privacy-content {
  border: 1px solid #e5e4e2;
  padding-top: 20px;
  padding-bottom: 20px;
  padding-left: 20px;
  padding-right: 40px;
    /* border-radius: 5px; */
}

.flex {
  display: flex;
  
}
.privacy-content-1 {
  background: #F0F8FF;
  border: 1px solid #e5e4e2;
  /* border-radius: 5px; */
  padding-top: 20px;
  padding-bottom: 20px;
  padding-left: 20px;
  padding-right: 20px;
}
.las {
  padding-right: 20px;
  font-size: 19px;
}
button {
  float: right;
  padding: 10px 25px;
  border: none;
  margin: 20px 10px;
  font-size: 16px;
  border-radius: 7px;
}
.main p {
  margin-left: 40px;
}
.tips{
  margin-top: 40px;
}
label {
  font-weight: 600;
  display: inline-block;
  width: 100%;
  font-size: 1.2rem;
  margin-bottom: 15px;
}
input {
  border:2px solid #e5e4e2;
  width: 100%;
  height: 40px;
  /* border: none; */
  outline: none;
  font-size: 1.4rem;
  font-weight: 400;
  margin-bottom: 20px;
  border-radius: 5px;
}
input[type] {
  padding-left: 20px;
}
.cancel {
  background: whitesmoke;
  color: #0b4657;
}
.save {
  background: #00bfff;
  color: white;
}
</style>
