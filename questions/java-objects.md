[topic]: java-objects

[question]: begin
[level]: 2
Consider the following code:

*Person.java*
````java
public class Person {
    private String firstName;
    private String lastName;
    
    public Person(String firstName, String lastName) {
        this.firstName = firstName;
        this.lastName = lastName;
    }
    
    public String getFirstName() {
        return firstName;
    }
}
````

*Main.java*
````java
public class Main {
    public static void main(String[] args) {
        Person p = new Person("Chris");
        System.out.println(p.getFirstName());
    }
}
````

What will be displayed as a result of running the `Main` class?

[answers]: begin

- "Chris"
- Nothing will be displayed
- "null"
- A compiler error prevents the code from compiling

[answers]: end
[question]: end