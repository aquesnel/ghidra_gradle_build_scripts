# ghidra_gradle_build_scripts
 
## Usage

Example `build.gradle` file:

```
plugins {
    // eclipse IDE plugin for integrating Ghidra with the Eclipse
    id("io.github.aquesnel.ghidra_gradle_build_scripts.GhidraEclipse").version("0.0.1")
}

// apply the Ghidra build extention plugin
apply from: ext.getGhidraBuildExtentionPath()
```
