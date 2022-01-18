##  <img src="https://github.com/iosyyy/iosyyy/blob/main/%E5%A4%B4%E5%83%8F(3).gif" alt="image-20220102113009363" width="25" />  Prepared by JHX  📝
<div>
  <a href="https://github.com/anuraghazra/github-readme-stats" >
    <img align="center" src="https://github-readme-stats.vercel.app/api?username=iosyyy&show_icons=true&count_private=true&count_private=true&hide_border=true&theme=tokyonight" />
  </a>
</div>
<br />

<div>
  <a href="https://github.com/anuraghazra/convoychat">
    <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=iosyyy&show_icons=true&hide_border=true&langs_count=15&layout=compact&theme=tokyonight" />
  </a>
</div>
<br />

<br />

### Languages and Tools:

[<img align="left" alt="Visual Studio Code" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" />][webdevplaylist]
[<img align="left" alt="java" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/java/java.png" />][webdevplaylist]
[<img align="left" alt="HTML5" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" />][webdevplaylist]
[<img align="left" alt="CSS3" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" />][cssplaylist]
[<img align="left" alt="Sass" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sass/sass.png" />][cssplaylist]
[<img align="left" alt="JavaScript" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" />][jsplaylist]
[<img align="left" alt="React" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/react/react.png" />][reactplaylist]
[<img align="left" alt="Gatsby" width="26px" src="https://raw.githubusercontent.com/github/explore/e94815998e4e0713912fed477a1f346ec04c3da2/topics/gatsby/gatsby.png" />][webdevplaylist]
[<img align="left" alt="GraphQL" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/graphql/graphql.png" />][webdevplaylist]
[<img align="left" alt="Node.js" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png" />][webdevplaylist]

[<img align="left" alt="Deno" width="26px" src="https://raw.githubusercontent.com/github/explore/361e2821e2dea67711cde99c9c40ed357061cf27/topics/deno/deno.png" />][webdevplaylist]
[<img align="left" alt="SQL" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sql/sql.png" />][webdevplaylist]
[<img align="left" alt="MySQL" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mysql/mysql.png" />][webdevplaylist]
[<img align="left" alt="MongoDB" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mongodb/mongodb.png" />][webdevplaylist]
[<img align="left" alt="Git" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png" />][webdevplaylist]
[<img align="left" alt="GitHub" width="26px" src="https://raw.githubusercontent.com/github/explore/78df643247d429f6cc873026c0622819ad797942/topics/github/github.png" />][webdevplaylist]
[<img align="left" alt="Terminal" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" />][webdevplaylist]

<br />
<br />

```java
import lombok.Builder;
import lombok.Data;

import java.util.Arrays;
import java.util.Calendar;

/**
 * @author 💕
 * @since 🌑🌒🌓🌔🌖🌗🌘🌚 🌕🌝☀️🌞🌟
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
    birthday.set(2️⃣0️⃣0️⃣1️⃣, Calendar.JULY, 1️⃣7️⃣);
    Life life =
        Life.builder()
            .birthday(birthday)
            .birthplace("china")
            .languages(
                new String[] {
                  "☕",
                  "C++",
                  "☕Script",
                  "HTML5",
                  "Python",
                  "flask",
                  "SQL",
                  "🤖",
                  "react",
                  "vue",
                  "go"
                })
            .education("🏫")
            .tech(
                new String[] {
                  "open source", "APIs/SDKs", "clouds", "databases", "🍃 boot", "🍃 cloud"
                })
            .build();
    System.out.println("Form " + life.getBirthplace() + "in " + life.getBirthday() + ".");
    System.out.println("I study in " + life.getEducation() + " Institute of technology.");
    System.out.println(
        "And I am familiar with the following languages"
            + Arrays.toString(life.getLanguages())
            + "has the following technologies"
            + Arrays.toString(life.getTech()));
  }
}

```
