<template>
  <header class="header">
      <div class="header__container">
        <div class="header__logo">
          <img
            src="../assets/images/ojowo.svg"
            alt="Ojowo logo"
            class="header__image"
          >
          <h2 class="header__subtitle">
            Beta
          </h2>
        </div>

        <div class="header__settings">
          <button type="submit" class="header__notification-button">
            <img
              src="../assets/images/bell.svg"
              alt="Notification bell"
              class="header__bell"
            >
          </button>
          <select
            name="user"
            id="user"
            class="header__user"
          >
            <option value="Artem" class="header__user-option">
              Artem
            </option>
            <option value="Roman" class="header__user-option">
              Roman
            </option>
          </select>
          <button type="button" class="header__search">
            <img
              src="../assets/images/lens.svg"
              alt="Search"
              class="header__lens"
            >
          </button>
          <select name="language" id="language" class="header__language">
            <option value="Ru" class="header__language-option">
              En
            </option>
            <option value="Ua" class="header__language-option">
              Ua
            </option>
          </select>
        </div>
      </div>
    </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped lang="scss">
.header {
  font-family: "Montserrat", Arial, Helvetica, sans-serif;

  margin-bottom: 48px;

  &__container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
  }

  &__logo {
    display: flex;
    flex-direction: row;
    align-items: flex-end;
    height: 26px;
  }

  &__image {
    display: block;
    width: 83.61px;
    height: 14.78px;
    object-fit: contain;
    margin-right: 9px;
  }

  &__subtitle {
    font-weight: normal;
    font-size: 13px;
    line-height: 140%;
    align-self: flex-start;
  }

  &__settings {
    min-width: 322px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  &__notification-button {
    border: none;
    outline: none;

    width: 43px;
    height: 43px;
    background: rgb(255, 255, 255);
    box-shadow: 0 10px 40px rgba(213, 221, 230, 0.6);
    border-radius: 50%;
  }

  &__user {
    width: 120px;
    height: 43px;
    background: rgb(255, 255, 255);
    box-shadow: 0 10px 40px rgba(213, 221, 230, 0.6);
    border-radius: 100px;

    font-weight: bold;
    font-size: 14px;
    line-height: 17px;
    text-align-last: center;

    border: none;
    outline: none;
  }

  &__user-option {
    font-weight: bold;
    font-size: 14px;
    line-height: 17px;
    text-align: center;
  }

  &__search {
    border: none;
    outline: none;
    border-radius: 50%;

    width: 43px;
    height: 43px;
    background: rgba(203, 215, 228, 0.4);

    display: flex;
    justify-content: center;
    align-items: center;
  }

  &__language {
    width: 64px;
    height: 43px;
    background: rgba(203, 215, 228, 0.4);
    border-radius: 100px;

    font-style: normal;
    font-weight: bold;
    font-size: 14px;
    line-height: 17px;
    text-align-last: center;

    border: none;
    outline: none;
  }
}
</style>
