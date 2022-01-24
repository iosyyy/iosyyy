![header-image](.//header_white_.png)

<div align="center">

[![HitCount](http://hits.dwyl.com/iosyyy/iosyyy.svg)](https://github.com/iosyyy/iosyyy)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square)](https://github.com/dwyl/hits/issues/74)

<!-- Docs badge not working ... if you have time to help investigate, please do.
[![Inline docs](http://inch-ci.org/github/dwyl/hits.svg?style=flat-square)](http://inch-ci.org/github/dwyl/hits)
-->

</div>
##  <img src="https://github.com/iosyyy/iosyyy/blob/main/%E5%A4%B4%E5%83%8F(3).gif" alt="image-20220102113009363" width="25" />  Prepared by JHX  📝
####  ☕ my common language
<div>
<img align="left" alt="Visual Studio Code" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" />
<img align="left" alt="java" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/java/java.png" />
<img align="left" alt="cpp" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/cpp/cpp.png" />
<img align="left" alt="python" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png" />
<img align="left" alt="HTML5" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" />
<img align="left" alt="CSS3" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" />
<img align="left" alt="Sass" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sass/sass.png" />
<img align="left" alt="JavaScript" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" />
<img align="left" alt="React" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/react/react.png" />
<img align="left" alt="GraphQL" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/graphql/graphql.png" />
<img align="left" alt="Node.js" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png" />
<img align="left" alt="Deno" width="26px" src="https://raw.githubusercontent.com/github/explore/361e2821e2dea67711cde99c9c40ed357061cf27/topics/deno/deno.png" />
<img align="left" alt="SQL" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sql/sql.png" />
<img align="left" alt="MySQL" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mysql/mysql.png" />
<img align="left" alt="MongoDB" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mongodb/mongodb.png" />
<img align="left" alt="Git" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png" />
<img align="left" alt="GitHub" width="26px" src="https://raw.githubusercontent.com/github/explore/78df643247d429f6cc873026c0622819ad797942/topics/github/github.png" />
<img align="left" alt="Terminal" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" />
</div>
<br />
<br />
<div>
  <a href="https://github.com/anuraghazra/github-readme-stats" >
    <img align="center" src="https://github-readme-stats.vercel.app/api?username=iosyyy&show_icons=true&count_private=true&count_private=true" />
  </a>
</div>
<div>
  <a href="https://github.com/anuraghazra/convoychat">
    <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=iosyyy&show_icons=true&hide_border=true&langs_count=15&layout=compact" />
  </a>
</div>
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
