### About me

```java
package com.example.introduction;

import lombok.Builder;

import java.util.Arrays;
import java.util.List;
@Getter
@Builder
public class Developer {
        private String name;
        private String dream;
        private String developmentFields;
        private String languages;
        private List<String> backendSkills;
        private List<String> devOpsSkills;
        private List<String> hobby;

    public static Developer introduce() {
        return Developer.builder()
                .name("Dongpil Son")
                .dream("IFBB PRO")
                .developmentFields("BackEnd")
                .languages("Java")
                .backendSkills(Arrays.asList("Java", "Spring", "JPA", "MyBatis", "Redis", "MySQL"))
                .devOpsSkills(Arrays.asList("AWS","Jenkins","Docker"))
                .hobby(Arrays.asList("bodybuilding","ProteinIntake"))
                .build();
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
