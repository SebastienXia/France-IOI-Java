# 6. Page d'écriture

3 boucles `for` qui vont répéter 30 fois `a_`, `b_` et `c_` avec un saut à la ligne après chaques boucles `System.out.println();`.

```Java
class Main{
   public static void main(String[] args) {
      for (int i = 1; i <= 30; i++){
         System.out.print("a_");
      }
      System.out.println();
      for (int i = 1; i <= 30; i++){
         System.out.print("b_");
      }
      System.out.println();
      for (int i = 1; i <= 30; i++){
         System.out.print("c_");
      }
   }
}
```
