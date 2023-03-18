### 안녕하세요! 배유연입니다! 👋
## 

 저는 기본을 중요하시하고, 새로운 것을 익할 때 언제 어떻게 활용할까를 고민하는 개발자입니다. 
 또 저는 원활한 커뮤니케이션을 중요하시하여 기획자 및 다른 직군분들과 적극적으로 대화를 하며, 개발자들과는 지식을 공유하며 토론을 즐깁니다. 

 
### **About me:)**
<!--
🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
``` java
package com.introduction.domain;
@Builder
class Member {
    String name;
    String job;
    String[] developmentFields;
    String[] languages;
    String[] backendSkills;
    String[] devOpsSkills
    String[] collaborationTools
    String[] interests;
}
public class Main() {
    public static void main(String[] args) {
    
        Member yuyueon = Member.builder()
                .name("배유연👸")
                .job("Back-end engineer🏽‍💻")
                .languages({"java☕"})
                .backendSkills({Spring🌱, Junit55️⃣, Gradle🐘})
                .devOpsSkills({Linux🐧,Tomcat🐱 Mysql🐬,Postgresql🐘, JSP, Javascript})
                .collaborationTools({Slack📑, Notion, Jira, Github project, Git, Intellij})
                .interests({"운동🏋️‍♂️", "베이킹🍞"})
                .build();
        introduce(yuyueon);
    }
}
```

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fbaeyuyeon&count_bg=%23E978EF&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)


[![Baeyuyeon's GitHub stats](https://github-readme-stats.vercel.app/api?username=baeyuyeon)](https://github.com/anuraghazra/github-readme-stats)
