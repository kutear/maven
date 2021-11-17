## 自用Maven仓库

```
allprojects {
    repositories {
        maven {
            url("https://raw.githubusercontent.com/kutear/maven/master/release/")
        }
        maven {
            url("https://raw.githubusercontent.com/kutear/maven/master/snapshots/")
        }
    }
}
```

由于仓库容量限制，snapshots版本会不定期删除，如有需要，请使用release版本
