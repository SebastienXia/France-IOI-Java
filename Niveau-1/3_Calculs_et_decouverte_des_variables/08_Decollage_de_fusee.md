# 8. Décollage de fusée

Faire le décompte de 100 à 0 puis dire "Décollage !" lorsque nous arrivons à 0 : 

```Java
class Main {
    public static void main(String[] args) {
        for (int i = 100; i >= 0; i--) {
            System.out.println(i);
        }
        System.out.println("Décollage !");
   }
}
```
