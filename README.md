# firebase-unity-sdk-editor-python-fix

Firebase editor dll files with a fix for macOS Monterey 12.3 missing python:

To fix this issue, I replaced `python` reference with `python3` in `./firebase-unity-sdk/editor/app/src/PythonExecutor.cs`.

## Installation
Copy the files located in `Firebase.Editor` folder into your Unity project's `./Assets/Firebase/Editor` folder. 

You might need to restart Unity if it was open while replacing the files.