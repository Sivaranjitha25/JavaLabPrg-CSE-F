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
