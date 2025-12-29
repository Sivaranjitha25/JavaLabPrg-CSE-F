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
![OUTPUT OF EXP-2A](exp2a.png)
