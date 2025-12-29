#EXPERIMENT-2
##exp 2a title :To create a class
```java
class MyClass {
    void displayMessage() {
        System.out.println("Welcome to Java programming");
    }
    int add(int a, int b) {
        return a + b;
    }
    public static void main(String[] args) {
        MyClass obj = new MyClass();
        obj.displayMessage();
        int result = obj.add(10, 20);
        System.out.println("Sum: " + result);
    }
}

```
# OUTPUT
![OUTPUT OF exp-2a](exp2a.png)


##exp 2b tittle: method overloading
```java
class MethodOverloading {
    int add(int a, int b) {
        return a + b;
    }
    int add(int a, int b, int c) {
        return a + b + c;
    }
    double add(double a, double b) {
        return a + b;
    }
    public static void main(String[] args) {
        MethodOverloading obj = new MethodOverloading();
        System.out.println("Sum of 2 integers: " + obj.add(10, 20));
        System.out.println("Sum of 3 integers: " + obj.add(10, 20, 30));
        System.out.println("Sum of 2 doubles: " + obj.add(10.5, 20.5));
    }
}

```
#output
![output of exp 2b](ex2b.png)
