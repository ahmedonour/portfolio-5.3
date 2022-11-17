<svelte:head>
  <script
    src="https://kit.fontawesome.com/f3c7bd6f07.js"
    crossorigin="anonymous"
  ></script>
</svelte:head>
<div class="socialIcons">
  <a href="https://www.github.com/ahmedonour" target="_blank" rel="noreferrer"><i class="fab fa-github" /></a>
  <a href="https://www.dev.to/ahmed_onour" target="_blank" rel="noreferrer"><i class="fab fa-dev" /></a>
  <a href="mailto:ahmedonour.49@gmail.com"  target="_blank" rel="noreferrer"><i class="fas fa-envelope" /></a>
  <a href="https://www.twitter.com/ahmed_onour" target="_blank" rel="noreferrer"><i class="fab fa-twitter" /></a>
</div>

<style>
    .socialIcons{
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: center;
        width: 30px;
        height: 150px;
        grid-row: 2;
    }
    .socialIcons a i:hover{
      font-size: 35px;
    }
    .socialIcons a i{
        font-size: 24px;
        transition: all 550ms ease-in-out;
        color: var(--clr-Dark-Purple);
    }
    @media screen and (max-width: 414px){
      .socialIcons{
        flex-direction: row;
        display: none;
      }
    }
</style>
