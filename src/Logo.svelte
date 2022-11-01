<div class="name-logo-div">
    <div class="name-definition">
        <div class="name-box">
        <h1>Proof</h1>
        <h1>Of</h1>
        <h1>Listenership</h1>
        <h1>Platform</h1>
        </div>
    </div>
    <div class="logo-box">
        <img id="logo" src="./logo.png" alt="POLP: A Fresh Squeeze">
    </div>
</div>

<style>
    @media (max-width: 800px) {
    .name-logo-div {
      flex-direction: column;
    }
  }
  .name-logo-div {
    display: flex;
    /* justify-content: center; */
    min-height: 300px;
  }
  .name-definition {
    text-align: left;
    background-color: #ffac33;
    color: white;
    padding:0;
    min-width:42%;
    display: flex;
    /* width: 100%; */
    align-items: center;
 
  }
  .name-box {
    padding-left: 5%;
    padding-right: 10%;
    display: flex;
    flex-direction: column;
   
  }
  h1 {
    flex: 2 4 auto;
    margin:0.5em;
    width: min-content;
  }
  .logo-box {
    align-items: center;
    justify-items: center;
    display: flex;
    /* border-style: solid;
    border-color: #ffac33; */
  }
  #logo {
    max-width: 60%;
    min-width: 100px; 
    margin: auto;

  }
  
</style>