<div class="main">
  <div class="main-text">
    <h1>ERIK HAVETTA</h1>
    <h3>photography</h3>
  </div>
</div>


<style>

  @keyframes image-animation{
    from {
      background-size: auto 130%;
      background-position: 20% 80%;
    }

    to{
      background-size: auto 100%;
      background-position: 50% 50%;
    }
  }

  .main{
    width: 100vw;
    height: 100vh;
    background-image:linear-gradient(90.02deg, rgba(0, 0, 0, 0.5) -0.33%, rgba(0, 0, 0, 0.395) 14.22%, rgba(0, 0, 0, 0) 40.8%), url('./DSC03142.JPG');
    background-size: auto 100%;
    background-position: 50% 50%;
    display: flex;
    justify-content: center;
    align-items: center;

    animation-name: image-animation;
    animation-duration: 6s;
    animation-timing-function: linear;
  }

  @keyframes text-animation-h1{
    from{
      transform: scale(0.6) translateY(40%) translateX(-10%);
    }

    to{
      transform: scaleX(1) translateY(0) translateX(0);
    }
  }

  .main-text{
    max-width: 90vw;
    margin-bottom: 18%;
    transform-origin:center;
    animation-name: text-animation-h1;
    animation-duration: 6s;
    animation-timing-function: linear;
  }

  h1{
    font-style: normal;
    font-weight: 500;
    font-size: 120px;
    letter-spacing: 0.48em;
    color: #FFFFFF;
    margin-bottom: -20px;

  }

  h3{
    font-style: normal;
    font-weight: 500;
    font-size: 60px;
    letter-spacing: 0.4em;
    color: #FFFFFF;
    text-align: right;
    margin-right: 32px;
  }
</style>


