```java
public class CedricMapilisan {
    public String name = "Cedric Mapilisan";
    public String role = "2nd Year Computer Science Student";
    public String[] languages = {"Java", "PHP", "JavaScript", "Python", "C++", "C#"};
    public String contact = "cedricmapilisan@gmail.com";
    public String github = "https://github.com/cedricjamesm";
    public String linkedin = "https://www.linkedin.com/in/cedric-mapilisan-40b186269";

    public CedricMapilisan() {
        System.out.println("Hello, I'm " + name + ".");
        System.out.println("I'm a " + role + ".");
        System.out.println("You can reach me at " + contact + ".");
        System.out.println("Connect with me:");
        System.out.println("GitHub: " + github);
        System.out.println("LinkedIn: " + linkedin);
    }

    public void sayHi() {
        System.out.println("How's it going!");
    }

    public static void main(String[] args) {
        CedricMapilisan cedric = new CedricMapilisan();
        cedric.sayHi();
    }
}
```
