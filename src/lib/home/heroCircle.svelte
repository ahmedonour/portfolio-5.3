<script>
</script>

<div class="heroCircle">
  <div class="circle" />
  <div class="circleShadow" />
</div>

<style>
  .heroCircle {
    height:61vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    grid-column: 4;
    grid-row: 2;
  }
  .circle {
    width: 21rem;
    height: 21rem;
    border-radius: 400px;
    background-color: #260090;
    box-shadow: inset 0px 15px 22px rgba(255, 255, 255, 0.51),
      inset 0px -21px 39px 5px rgba(0, 0, 0, 0.5);
  }
  .circleShadow {
    width: 21rem;
    height: 1.25rem;
    border-radius: 30%;
    background-color: rgb(0, 0, 0, 0.5);
    filter: blur(10px);
  }
  @media screen and (max-width: 414px){
    .circle{
      width: 60vw;
      height: 60vw;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      z-index: 0;
    }
    .circleShadow{
      display: none;
    }
  }
</style>
