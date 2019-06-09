### maven default address
```gradle
buildscript{
  repositories{
    mavenLocale() //默认路径在C:\Users\{user}\.m2\repository\下
    jcenter() //https://jcenter.bintray.com/
    google() //https://dl.google.com/dl/android/maven2/
    mavenCenter() //https://repo.maven.apache.org/maven2/
  }
}
```
