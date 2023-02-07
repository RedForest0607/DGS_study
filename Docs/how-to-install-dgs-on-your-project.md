### Gradle 의존성 설정
``` java
repositories {
    mavenCentral()
}

dependencies {
    implementation(platform("com.netflix.graphql.dgs:graphql-dgs-platform-dependencies:latest.release"))
    implementation "com.netflix.graphql.dgs:graphql-dgs-spring-boot-starter"
}
```
다음과 같이 Gradle의 의존성을 설정한다.