# <center><b> Using GCC with MinGW </b></center>


### **INSTALLATION:**

* Visual Studio Code
* C/C++ extension for VS Code ------ Using c++ in the extension window (Ctrl + Shitf + X)
* Mingw-w64 ------ via SourceForge website

Add path folder to Mingw-w64 to pc.

Check version of MinGW: `g++ --version`



### **CREATE HELLO WORLD!**

Creating folder projects and subfolder helloworld----

```
mkdir projects
cd projects
mkdir helloworld
cd helloworld
code .
```

the code . commands opens:

* tasks.json (build instructions)
* launch.json (debugger settings)
* c_cpp_properties.json (compiler path and IntelliSense settings)

Add file and by using '+' option in explorer



### **Builling .cpp file:**

- create a `tasks.json`
- choose `Terminal > Configure Default Build Task`
- select `g++.exe` build active file

This will create a `tasks.json` file in a .vscode folder and open it in the editor.



### **Running the build file---**

* Go back to helloworld.cpp
* To run the build task defined in tasks.json, press `Ctrl+Shift+B` ........or from the Terminal main menu choose Run Build Task.
* Integrated Terminal panel appear below the source code editor
* Create a new terminal using the `+` button
* Run `dir` ------ should now see the executable helloworld.exe
* Run by typeing ------ `helloworld.exe`
