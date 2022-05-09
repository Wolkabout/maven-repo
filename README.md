# maven-repo

## usage

```

repositories {
    mavenCentral()
    maven {
        url = uri("https://raw.github.com/wolkabout/maven-repo/main")
    }
}

dependencies {
    implementation "com.wolkabout:rest-java-client:0.0.1"
}
```
