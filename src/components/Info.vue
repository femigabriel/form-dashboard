<template>
  <div class="personal-info">
    <div class="form-title">
      <h3>Personal Information</h3>
      <p>
        This information will be publicly, so be with careful what you share
      </p>
    </div>
    <div class="flex">
      <div class="name">
        <div class="form-info">
          <div class="form-label">
            <label for="">Email address </label>
          </div>
          <div class="inputs">
            <input class="Fname" type="text" />
          </div>
        </div>
      </div>
      <div class="name">
        <div class="form-info">
          <div class="form-label">
            <label for="">Phone number </label>
          </div>
          <div class="inputs">
            <input class="Lname" type="text" />
          </div>
        </div>
      </div>
    </div>
    <div class="flex">
      <div class="name">
        <div class="form-info">
          <div class="form-label">
            <label for="">Country </label>
          </div>
          <div class="inputs">
            <input class="Fname" type="text" />
          </div>
        </div>
      </div>
      <div class="name">
        <div class="form-info">
          <div class="form-label">
            <label for="">Language </label>
          </div>
          <div class="inputs">
            <input class="Lname" type="text" />
          </div>
        </div>
      </div>
    </div>
    <div class="form-title">
      <p>
        This information will be publicly, so be with careful what you share
      </p>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
};
</script>

<style scoped>
.form-title {
  padding-left: 10px;
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
  width: 100%;
}
.form-info {
  padding-bottom: 20px;
  padding-left: 15px;
}
.Fname,
.Lname {
  width: 520px;
  height: 38px;
}
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

input {
  width: 100%;
  height: 35px;
  border-radius: 5px;
  border: none;
  outline: none;
  font-size: 1.4rem;
  font-weight: 400;
}
</style>
