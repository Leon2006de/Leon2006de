<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To Do liste </title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
<link rel="stylesheet" href="https://code.getmdl.io/1.3.0/material.indigo-pink.min.css">
<link rel="stylesheet" href="Css.css">



<script defer src="https://code.getmdl.io/1.3.0/material.min.js"></script>

<style>
  /* Tut mir leid das der CSS Teil in HTML steht wollte einfach das ich Ihnen alles in einem Code schicken kann. */
    .page-content {padding: 0px 100px;}
</style>
<style>
    .demo-list-control {
      width: 300px;
    }
    
    .demo-list-radio { 
      display: inline;

    } 



    </style>
    <script>
function addTodo(){
  todolist.innerHTML += `
  <li class="mdl-list__item">
          <span class="mdl-list__item-primary-content">
            <i class="material-icons  mdl-list__item-avatar">label</i>
            ${todofield.value}
          </span>
          <span class="mdl-list__item-secondary-action">
            <label class="mdl-checkbox mdl-js-checkbox mdl-js-ripple-effect" for="list-checkbox-1">
              <input type="checkbox" id="list-checkbox-1" class="mdl-checkbox__input" checked />
            </label>
          </span>
        </li>
       ` ;
       todofield.value = '';
}


  
    </script>

<style>
        
  *{margin: 0;
padding: 0;
box-sizing: border-box;}

body{background: linear-gradient(180deg, #3ae4e1 0%,#7d4bf3 100%);


}



</style>
</head>
<body>

<div class="mdl-layout mdl-js-layout mdl-layout--fixed-header">
    <header class="mdl-layout__header">
      <div class="mdl-layout__header-row">
        
        <span class="mdl-layout-title">Todoliste von Leon</span>
        
        <div class="mdl-layout-spacer"></div>

        <nav class="mdl-navigation mdl-layout--large-screen-only">
         
          <a class="mdl-navigation__link" href="https://berufskolleg-viersen.de/">Meine aktuelle  Schule </a>
          <a class="mdl-navigation__link" href="https://rse-willich.de/">Meine alte Schule</a>
          <a class="mdl-navigation__link" href="https://www.realmadrid.com/en">Bester Verein</a>
          
        </nav>
        
      </div>
    </header>
    <div class="mdl-layout__drawer">
      <span class="mdl-layout-title">To do liste</span>
      <nav class="mdl-navigation">
        <a class="mdl-navigation__link" href="">Weiß nicht was ich sonst noch reinschreiben soll</a>
      
      </nav>
    
    </div>
    <main class="mdl-layout__content">
      <div class="page-content">

        <form onsubmit="addTodo(); return false;">

        <div class="mdl-textfield mdl-js-textfield">
          <input class="mdl-textfield__input" type="text" id="todofield">
          <label class="mdl-textfield__label" for="todofield">To do einfügen</label>
        </div>

        <button type="submit" class="mdl-button mdl-js-button mdl-button--raised mdl-button--colored">
            speichern
          </button>
      </form>
    


      
      <ul class="demo-list-control mdl-list" id="todolist">
        
  
        </ul>
    </div>
    </main>

    <footer style="background-color: rgb(0, 0, 0);" class="mdl-mini-footer">
      <div class="mdl-mini-footer__left-section">
        <div class="mdl-logo">Wo Ich JS lerne: </div>
        <ul class="mdl-mini-footer__link-list">
          <li><a href="https://www.youtube.com/@Programmierenlernen">programmier Youtuber</a></li>
          <li><a href="https://www.youtube.com/watch?v=UeZi8a99iS0&list=PLNmsVeXQZj7qOfMI2ZNk-LXUAiXKrwDIi">JS lern Videos</a></li>
          <li><a href="https://www.freecodecamp.org/">Website zu Coden lernen </a></li>
        </ul>
      </div>
    </footer>
  </div>



</body>
</html>
