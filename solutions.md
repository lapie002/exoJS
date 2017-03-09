#Solutions :

Mettre vos solutions dans un fichier solutions.md à la racine de votre dépot
```javascript
//REVISIONS
// Declarez une variable nommée "boucler" contenant true
var boucler = true;

// Declarez un tableau members contenant Aida67, lapie002, anneserrano,
//Jennysmille, nunkabuk, RCosson, kaonb-ax, FerEmilie, crazychouwi, KiluaZoldyc,
//patatobeur, Sam11360, elo062, hermeline, Biciclet,
var members = ["Aida67", "lapie002", "anneserrano", "Jennysmille", "nunkabuk", "RCosson", "kaonb-ax", "FerEmilie", "crazychouwi", "KiluaZoldyc", "patatobeur", "Sam11360", "elo062", "hermeline", "Biciclet"];
// SI la variable boucler vaut true ALORS


// autre methode pas besoin de onclick dans le html
//var clicked = document.getElementById('check');
//clicked.addEventListener("click", function(){...});

function myFunction(){
          if(boucler)
          // Bouclez sur le tableau que vous avez déclaré ci-dessus
          {
            for(var i=0;i<members.length;i++){
            // Mettre un switch pour qu'au moment où la boucle se trouve sur
            //votre pseudo cela ajoute "Affiche " devant votre pseudo dans
            //la console et sur l'écran et par defaut seulement le pseudo des autres
            switch(members[i]) {
              case "lapie002":
                  // sur ecran
                  var nouveauDiv = document.createElement("div");
                  var monP = document.getElementById('check');

                  nouveauDiv.innerHTML = "<p>Affiche " + members[i] + "</p>";
                  monP.appendChild(nouveauDiv);

                  console.log("Affiche "+"lapie002");

                  break;
              default:
                  // sur ecran
                  var nouveauDiv = document.createElement("div");
                  var monP = document.getElementById('check');

                  nouveauDiv.innerHTML = "<p>" + members[i] + "</p>";
                  monP.appendChild(nouveauDiv);

                  console.log(members[i]);}
                }
        }
}
```  
