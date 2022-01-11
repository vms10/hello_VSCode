# How to compile and run a C++ file in VS Code 
1. Select the Terminal > Run Build Task. 
2. Choose C/C++: g++.exe build active file. This will compile helloworld.cpp and create an executable file called helloworld.exe, which will appear in the File Explorer.
3. From a command prompt or a new VS Code Integrated Terminal, you can now run your program by typing ".\helloworld".


# How to debug a C++ file in VS Code
1. Run > Start debugging. Hay que poner antes el circulo rojo. Eso lo compila y ejecuta. (Elijo GDB y g++).

# How to debug a C++ multi file in VS Code
1. Watch this [tutorial](https://www.youtube.com/watch?v=DVyYnOHP4nY&t=4s).
1. Run > Start debugging. Hay que poner antes el circulo rojo. Eso lo compila y ejecuta. (Elijo GDB y g++). Eso me crea varios archivos .json.
2. En tasks.json en tasks > args reemplazar  "${file}" por "*.cpp".


## References
This is based on the [video](https://www.youtube.com/watch?v=7QvNY9245hY). If you want a more detailed version you can check the tutorials from VS Code: [Tutorial1](https://code.visualstudio.com/docs/languages/cpp) and
[Tutorial2](https://code.visualstudio.com/docs/cpp/config-mingw).
For this you need to have installed VS Code and MinGW. See this [tutorial](https://www.youtube.com/watch?v=jfVqzNU3gPg). For VS Code I install the **System version**, because it is simpler to unistall and to see where the APPDATA is. For more on VS Code see [this](https://code.visualstudio.com/docs/getstarted/introvideos).

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
- Push the Sync button at the bottom left corner (a cloud that says "Publish to github"). Se abre el command palette y podes cambiarle el nombre al repositorio y elegir publicarlo privado o publico. Asi se va a ver la primmera vez. Despues aparece unas flechitas de push y pull y hay que darle a eso para sincronizar con github.
- .gitignore: you put the folders that you dont want in github. Un ejemplo es tener un archivo llamado ".gitignore" y que adentro diga "data/*". Eso significa que todo lo que este adentro de la carpeta data lo va a ignorar. 

# How to download a repository from github
1. Go to a terminal in the desired folder that you want to clone.
2. Type "git clone https/github.com/repository".


# How to compile and run a java file in VS Code 
I set up a java environment in VSCode with this tutorials:
1. [tutorial1](https://www.youtube.com/watch?v=IJ-PJbvJBGs)
2. [tutorial2](https://www.youtube.com/watch?v=ClU9N4ub_Ko)
3. Con estos tutoriales no me andaba el Intellisense de VSCode. Lo arregle con esta [respuesta](https://stackoverflow.com/questions/63468403/vscode-not-suggesting-and-autocompleting-java-code).
