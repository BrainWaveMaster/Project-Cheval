# Project-Cheval
```
      ___           ___           ___           ___           ___           ___ 
     /\  \         /\__\         /\  \         /\__\         /\  \         /\__\
    /::\  \       /:/  /        /::\  \       /:/  /        /::\  \       /:/  /
   /:/\:\  \     /:/__/        /:/\:\  \     /:/  /        /:/\:\  \     /:/  / 
  /:/  \:\  \   /::\  \ ___   /::\~\:\  \   /:/__/  ___   /::\~\:\  \   /:/  /  
 /:/__/ \:\__\ /:/\:\  /\__\ /:/\:\ \:\__\  |:|  | /\__\ /:/\:\ \:\__\ /:/__/   
 \:\  \  \/__/ \/__\:\/:/  / \:\~\:\ \/__/  |:|  |/:/  / \/__\:\/:/  / \:\  \   
  \:\  \            \::/  /   \:\ \:\__\    |:|__/:/  /       \::/  /   \:\  \  
   \:\  \           /:/  /     \:\ \/__/     \::::/__/        /:/  /     \:\  \ 
    \:\__\         /:/  /       \:\__\        ~~~~           /:/  /       \:\__\
     \/__/         \/__/         \/__/                       \/__/         \/__/  
```

## Initialize Info

### Spring Initializr 세팅 
![Spring-Initializr](https://user-images.githubusercontent.com/134509240/240623602-8e5d3e2c-a8d4-457e-82b9-1578e9cc9663.png)

[https://start.spring.io/](https://start.spring.io/)

<b>feature</b>

JDK : Java 17 LTS
- [Windows Installer](https://download.oracle.com/java/17/latest/jdk-17_windows-x64_bin.exe)
- [Mac DMG](https://download.oracle.com/java/17/latest/jdk-17_macos-aarch64_bin.dmg)


<b>Dependencies</b>
<pre>
Spring Web
Spring Security
MySQL Driver
MyBatis Framework
Lombok
Spring Boot Dev Tools
</pre>

[프로젝트설정링크](https://start.spring.io/#!type=gradle-project&language=java&platformVersion=3.1.0&packaging=jar&jvmVersion=17&groupId=com.brainwave&artifactId=cheval&name=cheval&description=Demo%20project%20for%20Spring%20Boot&packageName=com.brainwave.cheval&dependencies=devtools,lombok,web,security,mysql,mybatis)




### Docker Images
    docker-compose up -d
- MySQL
- Redis
- Kafka
- Zookeeper
- WebServer (??? NginX 및 Next.JS 등 미정)

### GitHub Actions

- Deployment (예정)