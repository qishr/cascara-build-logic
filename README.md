# Cascara Build Logic

A Gradle conventions plugin for building Cascara modules.

This plugin provides:

### **Java setup**

- Java toolchain 25
- `sourcesJar`
- `javadocJar`
- Manifest attributes
- Automatic module name
- Build date

### **Testing**

- JUnit Platform enabled
- Test logging configured
- Jacoco wired in
- Jacoco report generation

### **Tasks**

- `runtimeModulePath`
- `build` finalizes `runtimeModulePath`

### **Publishing**

- Maven publication
- POM metadata
- Developer info
- SCM info
- Local staging repository

### **Signing**

- Publication signing wired in

### **Configuration cache safety**

- No custom tasks holding project references
- No unsafe provider evaluation
- No task creation inside task configuration


