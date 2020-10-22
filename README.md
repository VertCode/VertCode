<h2> Hi, I'm Wesley (VertCode)</h2>
<img align='right' src="https://vertcode.eu/logo%27s/VertCode-Logo.png" width="230">
<p><img src="https://www.minecraft.net/etc.clientlibs/minecraft/clientlibs/main/resources/favicon.ico" width="30"> Minecraft Plugin Developer <br>
<p><img src="https://cdn.vertcode.eu/i/sys-admin.png" width="30"> System Admin
</p>


[![Twitter: VertCodeEU](https://img.shields.io/twitter/follow/VertCodeEU?style=social)](https://twitter.com/VertCodeEU)
[![GitHub VertCode](https://img.shields.io/github/followers/VertCode?label=follow&style=social)](https://github.com/VertCode)  

```java
public class Wesley {

  private String name;
  private int age;
  private boolean systemAdmin;

  public Wesley(String name, int age) {
    this.name = name;
    this.age = age;
    this.systemAdmin = true;
  }

  public String[] languages = new String[] {
    "Java", "PHP", "C++", "Javascript", "C#", "Bash"
  };

  public String getName() {
    return String.format("I am %s!", this.name); 
  }

  public String getAge() {
    return String.format("I am %s years old!", this.age);
  }

  public boolean isSystemAdmin() {
    return this.systemAdmin;
  }
}
```