#Conditions :
- Forkez ce repositorie et travaillez sur ce fork en pushant vos solutions directement dessus votre fork, ne clonez ou ne téléchargez pas car il ne sera pas possible de pushé directement sur le dépot de Simplon Narbonne, vous n'avez pas les droits, sur votre fork oui  

Mettre vos solutions dans un fichier solutions.md à la racine de votre dépot
```javascript
//REVISIONS
// Declarez une variable nommée "boucler" contenant true
var boucler = true;

// Declarez un tableau members contenant Aida67, lapie002, anneserrano, Jennysmille, nunkabuk, RCosson, kaonb-ax, FerEmilie, crazychouwi, KiluaZoldyc, patatobeur, Sam11360, elo062, hermeline, Biciclet,
var members = ["Aida67", "lapie002", "anneserrano", "Jennysmille", "nunkabuk", "RCosson", "kaonb-ax", "FerEmilie", "crazychouwi", "KiluaZoldyc", "patatobeur", "Sam11360", "elo062", "hermeline", "Biciclet"];
// SI la variable boucler vaut true ALORS
function myFunction(){
          if(boucler)
          // Bouclez sur le tableau que vous avez déclaré ci-dessus
          {
            for(var i=0;i<members.length;i++){
            // Mettre un switch pour qu'au moment où la boucle se trouve sur votre pseudo cela ajoute "Affiche " devant votre pseudo dans la console et sur l'écran et par defaut seulement le pseudo des autres
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

#REVISION JS:
Reprenez le cours JS d'OpenClass et normalement le premier exo ne devrait pas trop vous poser de probleme :  
Voir les commentaires dans le fichier app.js  
https://github.com/Simplon-Narbonne/exoJS  
