# Visual C++ Files Redistributable

Contains only the required DLL(s) to run a Flutter app on Windows, as mentioned here: https://docs.flutter.dev/platform-integration/windows/building#building-your-own-zip-file-for-windows. 

The DLL files are extracted from the following location on my computer:
`C:\Program Files\Microsoft Visual Studio\2022\Community\VC\Redist\MSVC\14.42.34433\x64\Microsoft.VC143.CRT`.

Your path may vary. To locate the DLL files on your machine, refer to this article https://learn.microsoft.com/en-us/cpp/windows/redistributing-visual-cpp-files?view=msvc-170#locate-the-redistributable-files 

![image](https://github.com/user-attachments/assets/17b125ed-6f6f-4a69-817b-f472fb2b8e75)

## Usage 

This repository is suitable for use in a CI pipeline to automate the inclusion of the required DLL(s) when packaging a Flutter app for end users on Windows. 
