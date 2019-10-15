<!-- <link rel="stylesheet" href="css/style.css"> -->

<div class="main col sc">
    <div class="fullW ham-title cold-dark">
        <label>CSHAM</label>
        <div class="ham-subtitle cold-darkblue">W.I.P css and js library</div>
    </div>
    <div class="fullW col sc ham-blue pdg20">
        <div class="maxW350 fullW ham-title cold-light">Cold
            <div class="ham-subtitle cold-blue">Nuevo</div>
        </div>
        <div class="fullW maxW350">
        <div class="maxW350 fullW ham-btn cold-dark pdgV20">.cold-dark</div>
        <div class="maxW350 fullW ham-btn cold-darkblue pdgV40">.cold-darkblue</div>
        <div class="maxW350 fullW ham-btn cold-blue pdgV20">.cold-blue</div>
        <div class="maxW350 fullW ham-btn cold-lightgrey pdgV10">.cold-lightgrey</div>
        <div class="maxW350 fullW ham-btn cold-light">.cold-light</div>
        </div>
        <div class="maxW350 fullW ham-title cold-dark">
            <label>Registro</label>
            <div class="ham-subtitle cold-darkblue">Maestros</div>
        </div>
        <div class="maxW350 fullW ham-title cold-lightgrey">
            <label>Registro</label>
            <div class="ham-subtitle cold-blue">Niños</div>
        </div>
    </div>
</div>

<style>
    *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

html, body{
    width: 100%;
    height: 100vh;
    overflow: hidden;
}
@media (max-height: 400px){
    html, body{
        height: 120vh;
        overflow-y: auto;
    }
}

.main{
    width: 100%;
    height: calc(100% - 65px);
    padding: 25px;
    overflow-y: auto;
}
.cold-darkblue {
  background: #23374D;
  color: #E5E5E5;
}

.cold-blue {
  background: #1089FF;
  color: #EEEEEE;
}

.cold-lightgrey {
  background: #E5E5E5;
  color: #272121;
}

.cold-light {
  background: #EEEEEE;
  color: #272121;
}

.cold-dark {
  background: #272121;
  color: #EEEEEE;
}

.col {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  /* X: variable; Y: en el inicio;*/
  /* X: variable; Y: en el centro;*/
  /* X: variable; Y: en el fin;*/
}
.col.sc {
  -webkit-box-pack: start;
      -ms-flex-pack: start;
          justify-content: flex-start;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}
.fullW {
  width: 100%;
}

.fullH {
  height: 100%;
}
.ham-btn{
    display: grid;
    padding: .6em .8em;
    cursor: pointer;
    user-select: none;
}
.ham-title{
    padding: .45em;
    font-size: 35px;
    margin-bottom: 8px;
    border-radius: 5px;
    transition: .2s ease-in-out;
}
.ham-subtitle{
    padding: .35em 1.9em;
    font-size: 18px;
    margin: 4px 0;
    margin-left: 1.9em;
    border-radius: 5px;
    transition: .2s ease-in-out;
    font-weight: 100;
}

@media (max-width: 500px){
    .ham-title{
        padding-right: 0;
    }
    .ham-subtitle{
        max-width: 500px;
    }
}

</style>