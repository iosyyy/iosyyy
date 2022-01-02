##  <img src="https://github.com/iosyyy/iosyyy/blob/main/%E5%A4%B4%E5%83%8F(3).gif" alt="image-20220102113009363" width="25" />Prepared by JHX  📝



<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=iosyyy&show_icons=true&count_private=true&count_private=true&hide_border=true" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=iosyyy&show_icons=true&hide_border=true&langs_count=15&layout=compact" />
</a>

```java
import lombok.Builder;
import lombok.Data;

import java.util.Arrays;
import java.util.Calendar;

/**
 * @author ![](https://github.com/iosyyy/iosyyy/blob/main/%E5%A4%B4%E5%83%8F(2).jpg)
 * @since 🌑🌒🌓🌔🌕🌖🌗🌘🌚🌝
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
