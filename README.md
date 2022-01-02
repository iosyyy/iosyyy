## Prepared by JHX 📝
[![iosyyy's GitHub stats](https://github-readme-stats.vercel.app/api?username=iosyyy)](https://github.com/anuraghazra/github-readme-stats)
[![iosyyy's Most used languages](https://github-readme-stats.vercel.app/api/top-langs/?username=iosyyy&layout=compact&hide_border=true&langs_count=10)

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
