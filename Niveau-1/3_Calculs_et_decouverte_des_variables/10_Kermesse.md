# 10. Kermesse

Nous devons afficher ligne par ligne le nombre de bonbons en fonction du nombre de fois qu'on touche consécutivement la cible elle augmente de nbBonbon + n-ième tir à chaque fois : 

```Java
class Main {
   public static void main(String[] args) {
      int nbBonbon = 1;
      for (int i = 2; i <= 51; i++) {
         System.out.println(nbBonbon);
         nbBonbon += i;
      }
   }
}
```
