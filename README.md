```java
public class About extends Me {
    public Map<String, Map<String, String>> getCurrentWorkplace() {
        Map<String, Map<String, String>> workplace = new HashMap<>();
        workplace.put("workplace", new HashMap<String, String>() {{
            put("company", "???");
            put("position", "???");
        }});
        return workplace;
    }

    public List<String> getKnowledge() {
        List<String> knowledge = new ArrayList<>();
        knowledge.add("java");
        knowledge.add("javascript");
        knowledge.add("rust");
        knowledge.add("python");
        knowledge.add("html");
        knowledge.add("css");
        return knowledge;
    }

    public List<String> getFrameworks() {
        List<String> frameworks = new ArrayList<>();
        frameworks.add("spring");
        frameworks.add("flask");
        frameworks.add("react");
        frameworks.add("next");
        return frameworks;
    }

    public String getFutureGoal() {
        return "Maybe learn Golang.";
    }
}
```
