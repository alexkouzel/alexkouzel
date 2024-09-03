![banner](https://github.com/alexkouzel/alexkouzel/blob/master/banner.jpg?raw=true)

```java
import java.util.*;

public class AlexKouzel {
    
    private final String name;
    
    private final Map<String, List<String>> skills;

    public AlexKouzel() {
        name = "Alex Kouzel";

        skills = new LinkedHashMap<>();
        skills.put("Backend", List.of("Java", "Spring Boot", "Hibernate"));
        skills.put("Frontend", List.of("HTML", "CSS", "JavaScript"));
        skills.put("Cloud Services", List.of("AWS (EC2, S3, RDS)"));
        skills.put("Build Tools", List.of("Gradle", "Maven"));
        skills.put("Databases", List.of("PostgreSQL"));
    }

    @Override
    public String toString() {
        return String.format("Hey, I'm %s 👋", name);
    }

    public static void main(String[] args) {
        AlexKouzel me = new AlexKouzel();
        System.out.println(me);
    }

}

```
