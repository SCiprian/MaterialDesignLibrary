![Material design library logo](images/logo.png)

# Material Design Android Library

This is a fork of the original <a href="https://github.com/navasmdc/MaterialDesignLibrary"> Material Design Library Project </a>. I have just renamed the attributes in the resource file to eliminate the the conflict error ""Error:Attribute "rippleColor" has already been defined"" which occurs when you use Material Design Library.

You can use the gradle dependency, you have to add these lines in your build.gradle file:

```xml
repositories {
    maven { url "https://jitpack.io" }
}

dependencies {
	  compile 'com.github.SCiprian:MaterialDesignLibrary:1.6'
}
```
Most of the forks of the original Material Design Library Project have <b>minSdkVersion 16</b> this fork has <b>minSdkVersion 14</b>.<br><br>
To know more about how to use the controls and elements, check out the <a href="https://github.com/vajro/MaterialDesignLibrary/blob/master/OriginalREADME.md">Original ReadMe file.</a>
