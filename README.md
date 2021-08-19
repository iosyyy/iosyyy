## Hello🤣

Here are some ideas to get you started:

- 🔭 I’m currently working on myself
- 🌱 I’m currently learning Android
- 🤔 I’m looking for help with All knowledge of the front-end and back-end
- 💬 Ask me about How are you?
- 📫 How to reach me: emmm,nothing
- ⚡ Fun fact: This is a private account


```java
import java.util.Arrays;

/**
 * @author 听风
 * @since EveryDay
 */
public class Life {
  private static final String[] languages =
      new String[] {
        "Java", "C++", "JavaScript", "HTML5", "Python", "flask", "SQL", "Android", "react"
      };
  private static final String education = "小地方的不知名大学";
  private static final String[] tech =
      new String[] {"open source", "APIs/SDKs", "clouds", "databases"};

  public Life() {
    this.has();
    this.learnIn();
    this.learnAbout();
  }

  private void learnAbout() {
    Arrays.stream(Life.tech).forEach(System.out::println);
  }

  private void learnIn() {
    System.out.println(Life.education);
  }

  private void has() {
    Arrays.stream(Life.languages).forEach(System.out::println);
  }
}
```
