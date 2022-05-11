# Description
This program is a simple demonstration and benchmark of the AES-CBC encryption algorithm implemented in C# (10.0).

# Expected Behavior
Upon running the program, be patient and allow it a few seconds to complete its first encryption and decryption pass. The time this takes will vary from system to system. The program will run 20 passes of encryption and decryption on a target text (`.txt`) file and print the times each time it completes a pass. It will then print an average encryption and decryption times and the best encryption and decryption times upon completing all 20 runs.

# How to Run
## Installation
In order to run this program, you will need to have the latest version of Visual Studio 2022 (the Community Edition was used for development) and C# (version 10.0 or later) installed via .NET. You can follow the installation instructions [here](https://visualstudio.microsoft.com/downloads/). Make sure that you select the `.NET desktop development` package during installation to install all of the correct dependencies. The project was built and ran on Windows 10, so that is what the rest of the guide will reference for execution.

## Compilation and Execution
In order to run the program, you first must navigate to the project folder and, using the `AESCBC test.csproj` file to open the project in Visual Studio, edit the `Program.cs` file to use the correct file path to run the encryption and decryption processes on. Replace the file path with the **full path** to your file in the `original` variable on line 13. Be sure to save the file upon making your changes.
<br><br>
Finally, execute the program by selecting the drop-down at the top of the window and selecting release. Then, click the green run arrow that says "Run without debugging."