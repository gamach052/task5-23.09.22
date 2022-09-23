###  [Task 7kyu](https://www.codewars.com/kata/56606694ec01347ce800001b/train/java)

Count the number of divisors of a positive integer n.
### My solution
```Java
class TriangleTester{
    public static boolean isTriangle(int a, int b, int c){
        if(a<b+c && b<a+c && c<a+b){return true;}
        else{return false;}
    }
}}
```

### Fav solution

```Java
class TriangleTester{
    public static boolean isTriangle(int a, int b, int c){
        if(a+b <= c || b+c <= a || a+c <= b){
            return false;
        }
        return true;
    }
}
```
I like this solution because I like it
