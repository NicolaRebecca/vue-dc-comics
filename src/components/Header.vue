<template>
  <header class="container">
    <nav>
      <div class="logo">
        <img src="../assets/dc-logo.png" alt="Logo DC" />
      </div>

      <div class="menu">
        <ul>
          <li v-for="element in menuLinks" :key="element">
            {{element.name}} 
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script>
  export default {
    name: 'Header',
    data: function() {
      return {
        menuLinks: [
          {
            href: '#',
            name: 'CHARACTERS',
          },
          {
            href: '#',
            name: 'COMICS',
          },
          {
            href: '#',
            name: 'MOVIES',
          },
          {
            href: '#',
            name: 'TV',
          },
          {
            href: '#',
            name: 'GAMES',
          },
          {
            href: '#',
            name: 'COLLECTIBLES',
          },
          {
            href: '#',
            name: 'VIDEOS',
          },
          {
            href: '#',
            name: 'FANS',
          },
          {
            href: '#',
            name: 'NEWS',
          },
          {
            href: '#',
            name: 'SHOP',
          },
        ] 
      }
    },
  };
</script>


<style scoped lang="scss">
@import '../style/colors';

header {
  height: 80px;
  padding: 10px 0;

  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;

    img {
      height: 60px;
    }

    ul {
      display: flex;

      li {
        
        color: black;
        font-family: 'Roboto Condensed', sans-serif;
        font-weight: bold;
        margin-left: 24px;
        padding-bottom: 23px;

          &:hover {
            color: $dc-blue-color;
            border-bottom: 5px solid $dc-blue-color;
          }
        
      }
    }
  }
}
</style>
