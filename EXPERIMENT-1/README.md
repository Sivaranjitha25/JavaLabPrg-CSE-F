# EXPERIMENT-1
## Exp 1a Title : To Display Primitive Datatypes
```java
public class DefaultValues {
    byte b;
    short s;
    int i;
    long l;
    float f;
    double d;
    char c;
    boolean bool;

    public static void main(String[] args) {
        DefaultValues obj = new DefaultValues();

        System.out.println("Default values of primitive data types:");
        System.out.println("byte    : " + obj.b);
        System.out.println("short   : " + obj.s);
        System.out.println("int     : " + obj.i);
        System.out.println("long    : " + obj.l);
        System.out.println("float   : " + obj.f);
        System.out.println("double  : " + obj.d);
        System.out.println("char    : '" + obj.c + "'");
        System.out.println("boolean : " + obj.bool);
    }
}

```

#OUTPUT
![EXPERIMENT-1 OUTPUT](exp1a.png)




##exp 1b Title:Quadratic eqaution
```java
import java.util.Scanner;

public class QuadraticRoots {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter value of a: ");
        double a = sc.nextDouble();

        System.out.print("Enter value of b: ");
        double b = sc.nextDouble();

        System.out.print("Enter value of c: ");
        double c = sc.nextDouble();

        double discriminant = b * b - 4 * a * c;

        if (discriminant > 0) {
            double root1 = (-b + Math.sqrt(discriminant)) / (2 * a);
            double root2 = (-b - Math.sqrt(discriminant)) / (2 * a);
            System.out.println("Roots are real and different:");
            System.out.println("Root 1 = " + root1);
            System.out.println("Root 2 = " + root2);
        } 
        else if (discriminant == 0) {
            double root = -b / (2 * a);
            System.out.println("Roots are real and same:");
            System.out.println("Root = " + root);
        } 
        else {
            double realPart = -b / (2 * a);
            double imaginaryPart = Math.sqrt(-discriminant) / (2 * a);
            System.out.println("Roots are complex:");
            System.out.println("Root 1 = " + realPart + " + " + imaginaryPart + "i");
            System.out.println("Root 2 = " + realPart + " - " + imaginaryPart + "i");
        }

        sc.close();
    }
}

```
#OUTPUT
![CASE-1 D>0](case1.png)
![CASE-2 D==0](case2.png)
![CASE-3 D<0](case3.png)








