<template>
  <div class="form">
    <div class="form-title">
      <h3>Profile</h3>
      <p>
        This information will be publicly, so be with careful what you share
      </p>
    </div>
    <div class="flex">
      <div class="name">
        <div class="form-info">
          <div class="form-label">
            <label for="">First name</label>
          </div>
          <div class="inputs">
            <input
              class="Fname"
              type="text"
              name="firstName"
              v-model="lastName"
            />
          </div>
        </div>
      </div>
      <div class="name">
        <div class="form-info">
          <div class="form-label">
            <label for="">Last name</label>
          </div>
          <div class="inputs">
            <input
              class="Lname"
              type="text"
              name="lastName"
              v-model="lastName"
            />
          </div>
        </div>
      </div>
    </div>
    <form action="">
      <div class="form-info">
        <div class="flex">
          <div class="about">
            <div class="form-info">
              <div class="form-label">
                <label for="">Username</label>
              </div>
              <div class="flex">
                <div class="username"><span>workation.com/</span></div>

                <div class="inputs">
                  <input
                    class="user-input"
                    type="text"
                    name="Username"
                    placeholder="Username"
                    v-model="userName"
                  />
                </div>
              </div>
            </div>
            <div class="flex">
              <div class="photo">
                <h3>Photo</h3>
                <img src="../images/Dp.png" alt="" />
              </div>
              <div class="button">
                <button class="save">Change</button>
                <button class="cancel">Remove</button>
              </div>
            </div>

            <div class="form-info">
              <div class="form-label">
                <label for="">Description</label>
              </div>
              <div>
                <textarea class="textera-input" name=""> </textarea>
                <p>Brief descrition for your profile. URL are hyperlinked</p>
              </div>
            </div>
          </div>
        </div>

        <div class="form-info">
          <div class="form-label">
            <label for="">URL</label>
          </div>

          <div class="inputs">
            <input class="url" type="text" />
          </div>
        </div>
        <div class="form-info">
          <div class="form-label">
            <label for="">Company</label>
          </div>

          <div class="inputs">
            <input class="url" type="text" />
          </div>
        </div>
        <div class="line"></div>
      </div>
    </form>
    <Info />
  </div>
</template>

<script>
import Info from "./Info.vue";
export default {
  components: {
    Info,
  },
};
</script>

<style scoped>
/* @media only screen and (max-width: 780px) {
  .form  {
  display:block
  
}
} */
.form {
  background: #f0f8ff;
  padding: 20px 80px;
}
.form-title {
  padding-left: 10px;
}
.Fname,
.Lname {
  width: 520px;
  height: 38px;
}
.form p {
  padding: 5px 0px;
  color: #999;
  font-size: 14px;
}
.form h3 {
  color: #333;
  font-size: 16px;
}
.flex {
  display: flex;
}
.photo {
  padding-bottom: 20px;
}
form {
  padding-top: 25px;
}
.form-input {
  color: #999;
}
.username {
  border: 2px solid #999;
  background: whitesmoke;
  padding: 5px 10px;
  border-radius: 3px;
  cursor: pointer;
}

span {
  font-weight: 500;
}
.form-info {
  padding-bottom: 20px;
  padding-left: 15px;
}
/* inputs */

.inputs {
  border: 1px solid #e5e4e2;
  width: 100%;
  border-radius: 5px;
  color: #999;
}
label {
  font-weight: 600;
  display: inline-block;
  width: 100%;
  font-size: 1.2rem;
  margin-bottom: 5px;
}
.textera-input {
  border: 1px solid #e5e4e2;
}
textarea {
  font-size: 24px;
  border-radius: 5px;
  border: none;
  outline: none;
  width: 1050px;
  height: 120px;
  flex-grow: 1;
}
input {
  width: 100%;
  height: 35px;
  border-radius: 5px;
  border: none;
  outline: none;
  font-size: 1.4rem;
  font-weight: 400;
}
input:focus {
  /* border: none;
  outline: none; */
}
input:hover {
  /* border: none; */
  transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s;
}
input[type] {
  padding-left: 20px;
}
.form-label-1 {
}

/* photo */
.photo {
  padding: 0px 0px;
}
.photo h3 {
  padding: 0px -10px;
}
img {
  width: 40px;
  margin-left: 10px;
}
button {
  float: right;
  padding: 10px 25px;
  /* border: none; */
  margin: 20px 10px;
  font-size: 16px;
}
.cancel {
  background: white;
  color: #0b4657;
  border: none;
}
.save {
  background: transparent;
  color: #0b4657;
  border-color: transparent;
}
.line {
  margin-top: 20px;
  border: 0.5px solid #e5e4e2;
}
</style>
