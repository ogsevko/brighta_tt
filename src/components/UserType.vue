<template>
  <div class="user-type">
    <select
      name="user-type"
      id="user-type"
      class="user-type__select"
    >
      <option value="Expert" class="user-type__option">
        Expert
      </option>
      <option value="Regular" class="user-type__option">
        Regular
      </option>
    </select>
    <div class="user-type__container">
      <img
        src="../assets/images/user-type.svg"
        alt="User type"
        class="user-type__icon"
      >
    </div>
  </div>
</template>

<script>
export default {
  name: "UserType"
}
</script>

<style lang="scss" scoped>
.user-type {
  position: absolute;
  top: 0;
  left: 0;
  min-width: 236px;
  height: 54px;

  display: flex;
  align-items: center;

  background: rgb(255, 255, 255);
  box-shadow: 0 10px 40px rgba(128, 158, 191, 0.2);
  border-radius: 10px;
  font-family: "PT Sans", Arial, Helvetica, sans-serif;

  &__select {
    width: 144px;
    margin-right: 39px;

    font-style: normal;
    font-weight: bold;
    font-size: 15px;
    line-height: 130%;
    text-align-last: center;
    background: rgb(255, 255, 255);

    border: none;
    outline: none;
  }
}
</style>