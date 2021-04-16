<template>
  <div id="app">
    <p>
      Вы можете заказать пины по своему дизайну.
    </p>
    <ol>
      <li>Минимальный тираж 50 штук одного вида.</li>
      <li>На цену влияют:</li>
      <ul>
        <li>Размер значка</li>
        <li>Цвет гальванического покрытия</li>
        <li>Количество цветов</li>
        <li>Наличие мелких деталей</li>
        <li>Вид эмали</li>
        <li>Количество креплений</li>
        <li>Логотип на обратной стороне</li>
      </ul>
    </ol>
    <a class="cta-button" href="mailto:dotilazarchuk@gmail.com">
    Оставить заявку
    </a>
  </div>
  <!-- <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div> -->
</template>

<style lang="sass">
#app
  font-family: Montserrat
  font-style: normal
  font-weight: 500
  font-size: 14px
  line-height: 145.4%
  color: #4F4F4F

ol
  padding: 0
  list-style-position: inside
  li
    font-weight: 600
  ul
    li
      font-weight: 400

.cta-button
  display: block
  max-width: 280px
  margin: 20px auto
  text-align: center
  padding: 13px 16px
  color: #fff
  text-transform: uppercase
  text-decoration: none
  background: #EB5757
  border-radius: 32px
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2), 0px 2px 3px rgba(0, 0, 0, 0.15)
  border-radius: 32px

#nav
  padding: 30px

  a
    font-weight: bold
    color: #2c3e50

    &.router-link-exact-active 
      color: #42b983

</style>
