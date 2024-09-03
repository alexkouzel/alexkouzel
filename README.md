![banner](https://github.com/alexkouzel/alexkouzel/blob/master/banner.jpg?raw=true)

```java
import java.util.*;

public class AlexKouzel {
    
    private final String name;
    private final String position;
    private final Map<String, List<String>> skills;

    public AlexKouzel() {
        name = "Alex Kouzel";
        position = "Java Developer";

        skills = new LinkedHashMap<>();
        skills.put("Backend", List.of("Java", "Spring Boot", "REST APIs"));
        skills.put("Frontend", List.of("HTML", "CSS", "JavaScript"));
        skills.put("Databases", List.of("PostgreSQL", "MySQL"));
        skills.put("DevOps & Tools", List.of("Docker", "AWS", "Gradle", "Maven"));
        skills.put("Methodologies", List.of("Scrum", "SOLID", "TDD"));
    }

    @Override
    public String toString() {
        return String.format("Hey 👋 I'm %s, a %s", name, position);
    }

    public static void main(String[] args) {
        AlexKouzel me = new AlexKouzel();
        System.out.println(me);
    }

}

```
