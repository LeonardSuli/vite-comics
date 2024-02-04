<script>
export default{
  name: 'AppHeader',
  data(){
    return{
      menu: [
        {
          href: '#',
          text: 'CHARACTERS'
        },
        {
          href: '#',
          text: 'COMICS',
          class: 'active'
        },
        {
          href: '#',
          text: 'MOVIES'
        },
        {
          href: '#',
          text: 'TV'
        },
        {
          href: '#',
          text: 'GAMES'
        },
        {
          href: '#',
          text: 'COLLECTIBLES'
        },
        {
          href: '#',
          text: 'VIDEOS'
        },
        {
          href: '#',
          text: 'FANS'
        },
        {
          href: '#',
          text: 'NEWS'
        },
        {
          href: '#',
          text: 'SHOP'
        }
      ]
    }
  }
}
</script>

<template>

  <header>

    <div class="container">

      <div class="logo">
        <img src="/img/dc-logo.png">
      </div>

      <nav>
        
        <!-- Menu dinamico -->
        <ul class="main_menu">
          <li v-for="menu in menu">
            <a :href="menu.href" :class="menu.class">{{ menu.text }}</a>
          </li>
        </ul>

      </nav>

    </div>

  </header>

</template>

<style scoped>

.container{
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 0;
}

.logo img{
  width: 60px;
}

.main_menu{
  display: flex;
}

.main_menu a{
  padding: 2.15rem 0.75rem;
  color: var(--dc-secondary);
  font-size: 10px;
  font-weight: 700;
  transition: all;
}

.main_menu a:hover{
  border-bottom: 5px solid var(--dc-primary);
  color: var(--dc-primary);
}

.main_menu a.active{
  border-bottom: 5px solid var(--dc-primary);
  color: var(--dc-primary);
}


</style>