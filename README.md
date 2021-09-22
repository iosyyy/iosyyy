## Prepared by JHX 📝
 
```java
import lombok.Builder;
import lombok.Data;

import java.util.Arrays;
import java.util.Calendar;

/**
 * @author jhx
 * @since Good morning,and in case I don't see you,good afternoon,good evening and good night.
 */
@Builder
@Data
public class Life {
  private String[] languages;

  private String education;

  private String[] tech;

  private Calendar birthday;

  private String birthplace;

  public static void main(String[] args) {
    Calendar birthday = Calendar.getInstance();
    birthday.set(2001, Calendar.JULY, 17);
    Life life =
        Life.builder()
            .birthday(birthday)
            .birthplace("china")
            .languages(
                new String[] {
                  "Java",
                  "C++",
                  "JavaScript",
                  "HTML5",
                  "Python",
                  "flask",
                  "SQL",
                  "Android",
                  "react",
                  "vue",
                  "go"
                })
            .education("somewhere")
            .tech(
                new String[] {
                  "open source", "APIs/SDKs", "clouds", "databases", "spring boot", "spring cloud"
                })
            .build();
    System.out.print("Form " + life.getBirthplace() + "in " + life.getBirthday() + ".");
    System.out.print("I study in " + life.getEducation() + " Institute of technology.");
    System.out.print(
        "And I am familiar with the following languages"
            + Arrays.toString(life.getLanguages())
            + "has the following technologies"
            + Arrays.toString(life.getTech()));
  }
}

```
