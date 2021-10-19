# How to compile and run a C++ file in VS Code 
1. Select the Terminal > Run Build Task. 
2. Choose C/C++: g++.exe build active file. This will compile helloworld.cpp and create an executable file called helloworld.exe, which will appear in the File Explorer.
3. From a command prompt or a new VS Code Integrated Terminal, you can now run your program by typing ".\helloworld".


# How to debug a C++ file in VS Code
1. Run > Start debugging. Hay que poner antes el circulo rojo. Eso lo compila y ejecuta. (Elijo GDB y g++).


# References
This is based on the [video](https://www.youtube.com/watch?v=7QvNY9245hY). If you want a more detailed version you can check the tutorials from VS Code: [Tutorial1](https://code.visualstudio.com/docs/languages/cpp) and
[Tutorial2](https://code.visualstudio.com/docs/cpp/config-mingw).

# How to create a git repository in VS Code 
Based on this [tutorial](https://github.com/dsb-lab/SoftwareReproducibilityTutorial).
1. Source control (left pannel) > initialize a repository
2. To commit: write a comment in the left pannel and select the tick > Yes

## Extras
- Bottom left corner: me dice en que branch estoy (master). Si la toco puedo crear una nueva branch, pasar a otra branch (antes tengo que hacer un commit).
- El signo + en el Source control (left pannel) es para elegir que cambios son "staged" (es el equivalente a git add). Lo default es commitear TODOS los cambios. 
- "git log" en la terminal para ver los commits. Hay que tipear "q" para salir.
- "ls -a" en la terminal para ver los archivos ocultos en una carpeta (los de git).
- "gitk" en la terminal te muestra todo el arbol de branches y eso.

# How to publish to github in VS Code 
- Create a git repository first.
- Push the Sync button at the bottom left corner (a cloud that says "Publish to github").