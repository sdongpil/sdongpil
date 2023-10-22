### About me

```java
package com.example.introduction;

import lombok.Builder;

import java.util.Arrays;
import java.util.List;
@Builder
class Member {
    String name;
    String job;
    String developmentFields;
    String languages;
    List<String> backendSkills;
    List<String> devOpsSkills;
    List<String> collaborationTools;
    List<String> interests;
}

public class Main {
    public static void main(String[] args) {
        Member dongpil = Member.builder()
                .name("손동필")
                .job("Software engineer")
                .developmentFields("Back-end")
                .languages("java")
                .backendSkills(Arrays.asList("Spring", "JPA", "MyBatis", "Junit5", "Gradle"))
                .devOpsSkills(Arrays.asList("Ubuntu", "Github Actions", "MySQL", "Docker", "AWS EC2"))
                .collaborationTools(Arrays.asList("Slack", "Notion", "Github", "Intellij"))
                .build();
    }
}
```
  
</code></pre>

<!--
**sdongpil/sdongpil** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=sdongpil&show_icons=true&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
