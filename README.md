# CIST4B1_AdvJava
A repository to document my Java learning journey

## About Me
A CS student passionate about learning Java and backend development.

## Goals for This Course
Deepen my understanding of Data Structure and Algorithms using Java.

## In-Class Java Coding Warm Up file
Week 1 
<details>
<summary>Click to see the code</summary>
  
```java
// Main Class
public class Week1 {
    public static void main(String[] args) {
        Class2 c = new Class2();
        c.print();
    }
}


// Parent Class
class Class1 {
    private int a;

    public Class1() {
        this.a = 10;
        System.out.println("a:10");
    }

    public void print() {
        System.out.println("A:" + a);
    }
}

// Child Class
class Class2 extends Class1 {
    public Class2() {
        super();
        System.out.println("class2 print");
    }
}
```

</details>
