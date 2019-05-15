# Traning - Debugging in .NET

ASP.NET debug tips and tricks.

## Development debugging

* Run app in debug mode
* Attach to app process
    * IIS requires admin privileges 
* Breakpoints
* Breakpoint actions - trace breakpoints
* Breakpoint conditions  
* Step in the code 
    * Set to next statement - forward, backward
* Tools
    * Output window - always keep an eye on it
    * Breakpoints window
    * Call Stack window
    * Locals window
    * Autos window
    * Immediate window
    * Exceptions settings
* Pin variables 
* DebugerDisplayAttribute
* Visualizers 

## Complex environment setup and debugging

Application is integrated in bigger product or has external dependencies.  
Walk through the setup and debugging sample.

* Using of hosts file

## Production debugging

### Remote debugging

Tools for Visual Studio 2019  
https://visualstudio.microsoft.com/downloads/

### Time Travel Debugging 

Debug diagnostic tool to create Snapshots.  
https://www.microsoft.com/en-us/download/details.aspx?id=49924

* Create rule
* Activate rule and collect dumps
* Analyze dumps with DebugDiag Analysis
* Analyze and time travel debugging in Visual Studio

Production runtime app crashes

* Windows Reporting Tool crash dumps
* Analyze and time travel debugging in Visual Studio

## Tips

* Set proper language version
* Attach to more than one process
* Always include .pdb files