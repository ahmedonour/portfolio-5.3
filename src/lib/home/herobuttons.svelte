<script>
  export let title;
  export let links;
</script>

<div class="heroBtns">
  <a href={links}><button>{title}</button></a>
  <div class="btnShadow" />
</div>

<style>
  .heroBtns {
    width: 780px;
    height: 20vh;
    display: flex;
    flex-direction: column;
    margin-top: 2rem;
    justify-content: space-between;
  }
  .heroBtns button {
    width: 250px;
    height: 70px;
    border-radius: 40px;
    border: none;
    background: #260090;
    font-family: var(--ff-montserrat);
    font-size: 1.7rem;
    color: var(--clr-White);
    box-shadow: inset 0px 9px 10px rgba(255, 255, 255, 0.25),
      inset 0px -10px 9px rgba(0, 0, 0, 0.25);
    cursor: pointer;
  }
  .btnShadow {
    width: 250px;
    height: 20px;
    border-radius: 30%;
    background-color: rgb(0, 0, 0, 0.5);
    filter: blur(10px);
  }
  @media screen and (max-width: 414px){
    .heroBtns a{
      width: 100%;
    }
    .heroBtns button{
      width: 100%;
      font-size: 1.5rem;
      font-weight: 600;
    }
    .btnShadow{
      display: none;
    }
    .heroBtns{
      width: 100%;
      height: 200px;
    }
  }
</style>
