# King of the Ladder Premium
First of all special thanks to everyone who purchased our plugin and support us. <3

King of the Ladder is an old Minecraft minigame and this version is a premium version of that plugin. That premium version has so much more features than free one. In this minigame each player have to kick other players out of the ladders to be the king. The king tries to stand on the top of the ladders while not letting others to climb and punching them out of the way! If you have any problem with this plugin check out our [wiki](https://github.com/Despical/KOTLPremium/wiki). If you still didn't find an answer see documentation section below. Also a [tutorial video](https://www.youtube.com/watch?v=O_vkf_J4OgY) is available for the plugin by SpigotFAQ.

## Documentation
More detailed information can be found on the [wiki](https://github.com/Despical/KOTLPremium/wiki).
The Java documentation cannot be browsed due to privacy.<br>For questions or isseus use [issue tracker](https://github.com/Despical/KOTLPremium/issues).
Also you can join our [Discord community](https://www.discord.gg/rVkaGmyszE) to get support and news early.

## Translations
We are supporting multiple languages such as English, Turkish and German for now.<br>
If you want to help us with translating take a look at our [language repository](https://github.com/Despical/LocaleStorage).

## Contributing
We can not accept contributions via anyway because of the privacy of the code.

## Using King of the Ladder API
We do not recommend using the public API to not let anyone who didn't buy the plugin won't have access to files.<br>To access
our API we recommend to add it as a system library with using some shading systems such as Maven or Gradle.

Firstly, create a folder and put the plugin in that folder then follow the instructions below.

### Maven dependency

```xml
<dependency>
    <groupId>me.despical</groupId>
    <artifactId>kotl-premium</artifactId>
    <version>${version-here}</version>
    <scope>system</scope>
    <systemPath>${project.basedir}/libs/king-of-the-ladder-premimum-1.0.2.jar</systemPath>
</dependency>
```

### Gradle dependency
```
dependencies {
    compile files('libs/king-of-the-ladder-premimum-1.0.2.jar')
    // or include all the jars in the folder
    compile fileTree(dir: 'libs', include: '*.jar')
}
```
