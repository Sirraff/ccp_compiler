# ccp_compiler

CPP Compiler Simplifier
A simple Bash script to automate C++ compilation and execution for a single file.

DESCRIPTION
This Bash script takes in a single argument, file_name.cpp, compiles it using g++, 
and runs the resulting executable if no errors are detected during the compilation process.

SETUP
To make using this script even more convenient, you can create an alias for it in your .zshrc or .bashrc:

    alias ccpp="bash /path/to/your/script/compile_cpp.sh"
    Make sure to replace /path/to/your/script with the actual path to the script on your system.
    
    more on how to create aliases: 
        windows(example 4): https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.utility/set-alias?view=powershell-7.3
        Linux/Mac(3.1): https://phoenixnap.com/kb/linux-alias-command 

USAGE
To compile and run a C++ file, simply use the ccpp alias followed by the file name:

    ccpp file_name.cpp



Future Enhancements:
Support for handling multiple files and projects with multiple source files.
Additional customization options, such as specifying compiler flags and output file names.
