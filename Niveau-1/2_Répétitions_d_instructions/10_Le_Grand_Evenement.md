# 10. Le Grand Événement

<img src="ressources/robot_grid.png">

Le robot doit passer par toutes les cases et revenir à son point de départ qui se trouve en bas à gauche de l'imga ci-dessus :

```Java
import static algorea.Robot.*;
 
class Main {
   public static void main(String[] args) {
      for (int i = 1; i <= 9; i++) {
         haut();
      }
      for (int x = 1; x <= 4; x++) {
         droite();
         for (int y = 1; y <= 8; y++) {
            bas();
         }
         droite();
         for (int y = 1; y <= 8; y++) {
            haut();
         }
      }
      droite();
      for (int i = 1; i <= 9; i++) {
         bas();
      }
      for (int i = 1; i <= 9; i++) {
         gauche();
      }
   }
}
```
