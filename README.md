# Contents

- [IntelliJ short-cut keys](#intellij-short-cut-keys)
- [Creating runnable jar](#creating-runnable-jar)


## IntelliJ short-cut keys

### Essential IntelliJ Shortcut keys for Mac: 

- Run app and test 
  - CTRL+SHIFT+R (run the app/test) 
  - CTRL+R(rerun the app/test) 

- Editing 
  - CMD+B (go to the source code of a class or method) 
  - ALT+Return (Quick fix for compiler error) 
  - CMD+SHIFT+Return (Complete current statement) 
  - CMD+N (Generate) 
  - SHIFT+F6 (Rename) 
  - CMD+ALT+V (extract return value into a local variable) 
  - F2, SHIFT+F2 (Go to next/previous compile error) 
  - CMD+Left (navigate back) 
  - CMD+Right (navigate forward) 

- Window management 
  - CMD+SHIFT+F12 (maximize/minimize editor window) 
  - CMD+SHIFT+' (Maximize/minimize tool window) 

- Testing 
  - CMD+SHIFT+T (go to target/test code) 

- File search 
  - CMD+O (find class) 
  - CMD+SHIF+O (find file) 

- String search 
  - CMD+F (search within a file) 
  - CMD+SHIFT+F (search within the project) 
  - Double SHIFT (global search)

### Essential IntelliJ Shortcut keys for Windows: 

- Run app and test 
  - CTRL+SHIFT+F10 (run the app/test) 
  - SHIFT+F5 (rerun the app/test) 
  - SHIFT+F10 (rebuild/rerun) 

- Editing 
  - CTRL+B (go to the source code of a class or method) 
  - ALT+Enter (quick fix for compiler error) 
  - CTRL+SHIFT+Enter (complete current statement) 
  - Alt+Ins (generate) 
  - Shift+F6 (rename all instances of a variable) 
  - CTRL+ALT+V (extract return value into a local variable) 
  - F2, SHIFT+F2 (go to next/previous compile error) 
  - Alt+Left (navigate back between classes) 
  - Alt+Right (navigate forward between classes) 

- Window management 
  - CTRL+SHIFT+F12 (maximize/minimize editor window) 
  - CTRL+SHIFT+F12 (maximize/minimize tool window) 
  - Alt+F12 (open/close terminal window) 

- Testing 
  - CTRL+SHIFT+T (go to target/test code) 

- File search 
  - CTRL+N (find class) 
  - CTRL+SHIFT+F (find file) 
  - Double SHIFT (global search)

### [Complete IntelliJ shortcut keys](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf) 

## Creating runnable jar

### pom.xml

```xml
  <build>
    <plugins>
      <plugin>
        <groupId>org.apache.maven.plugins</groupId>
        <artifactId>maven-jar-plugin</artifactId>
        <configuration>
          <archive>
            <manifest>
              <addClasspath>true</addClasspath>
              <mainClass>fully.qualified.MainClass</mainClass>
            </manifest>
          </archive>
        </configuration>
      </plugin>
    </plugins>
  </build>
```

 