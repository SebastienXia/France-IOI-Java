# 4. Dans le fourre

<img src="ressources/fourre.png">

Ici nous voulons faire en sorte de le robot parte prendre la clé, sans le code de retour, nous disposons des fonctions suivantes, `haut(); , bas(); , gauche(); , droite(); ` et avec l'importation de `import static algorea.Robot.*;` tout au début de notre code.
```Java
import static algorea.Robot.*;
 
class Main {
   public static void main(String[] args) {
      haut();
      haut();
      haut();
      droite();
      droite();
      bas();
      bas();
      droite();
   }
}
```
