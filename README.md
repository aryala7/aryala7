```java

package com.aryalavassani;

import java.util.Arrays;
import java.util.List;
import java.util.Map;

public class About extends Me {

    public Map<String, Object> getCurrentWorkplace() {
        return Map.of(
            "workplace", Map.of(
                "company", "Student",
                "position", "Back-end Developer"
            )
        );
    }

    public List<String> getDailyKnowledge() {
        return Arrays.asList(
             "Java",
            "Spring",
            "PHP",
            "Laravel", 
            "JavaScript",
            "GoLang",
            "GraphQL",
            "MySQL",
            "Elasticsearch"
        );
    }

    public String getFutureGoal() {
        return "To contribute to open source projects and make the world a better place";
    }
}

```
