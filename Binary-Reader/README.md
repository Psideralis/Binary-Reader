# Binary-Reader
## Author: 
Psideralis<br/>
## License: 
GNU General Public License 3.0 and Psideralis Commune Public License<br/>
## Status:
Public - Progress: 15%<br/>
## Version
00.00.000.002<br/>
## Description:
Reads any file and ouput to file its binary (octal,hex,ascii) dump.<br/>

Windows requirments:<br/>
  - cl <br/>
  - nmake <br/>
  - cmake <br/>

Linux requirements:<br/>
  - gcc<br/>
  - g++<br/>
  - make <br/>
  - cmake <br/>

## Versions:<br/>
  ### Python : pydump  00.00.000.001<br/>
    Manual:
      Description:
      Parameters:
        -b: output binary format.
        -o: output octal format.
        -h: ouptut hexadecimal format.
        -a: output ASCII format. Can be used with -b, -o or -h.
        -u: output UTF-8 format. Can be used with -b, -o or -h.
  ### C++     : bindump++   00.00.000.001<br/>
    Manual:
      Description:
      Parameters:
        -b: output binary format.
        -o: output octal format.
        -h: ouptut hexadecimal format.
        -a: output ASCII format. Can be used with -b, -o or -h.
        -u: output UTF-8 format. Can be used with -b, -o or -h.
  ### C       : bindump     00.00.000.001<br/>
    Manual:
      Description:
      Parameters:
        -b: output binary format.
        -o: output octal format.
        -h: ouptut hexadecimal format.
        -a: output ASCII format. Can be used with -b, -o or -h.
        -u: output UTF-8 format. Can be used with -b, -o or -h.
## Output file format:
  ### HEADER:<br/>
    Output filename: "Filename"
    Output filepath: "Filepath"
    Date: "Date of read"
    Time: "Time of read"
  ### BODY:<br/>
    "DATA IN COLUMNS" | "ASCII OR UTF-8 TABLE IF -a or -u"
  ### FOOTER:<br/>
    Read filename: "Filename"
    Read filepath: "Filepath"
    Date: "Date of read"
    Time: "Time of read"
    Data: "bits read" Bits, "bytes read" Bytes, "KB read" KB, "MB read" MB, "GB read" GB, "TB read" TB.
    Read time: "Read time"
    Speed: "Read speed"
    File format: "Tries to output file format"
## Compilation:<br/>
  ### WINDOWS:<br/>
    Python  : No compilation!
    C++     : nmake or cmake
    C       : nmake or cmake
  ### LINUX:<br/>
    Python  : No compilation!
    C++     : make or cmake
    C       : make or cmake
## Installation:<br/>
  ### WINDOWS:
    PATH = ""%HOME%\AppData\LocalPrograms\Bindump"
    Python,C,C++  : ./Script/install.bat
  ### LINUX:
    PATH = "/usr/bin/Bindump"
    Python,C,C++  : ./Script/install.sh
## Uninstallation:<br/>
  ### WINDOWS:<br/>
    Python,C,C++  : ./Script/uninstall.bat
  ### LINUX:<br/>
    Python,C,C++  : ./Script/uninstall.sh
## Tools:<br/>
  ### Disassembler: 
  #### Tries to output assembly code from binary file. <br/>
    Author: Psideralis
    License: GNU GPL
    Status: Unfinished
    Versions: 00.00.000.001
  ### Decompiler: 
  #### Tries to output C or C++ code from binary file or assembly file. <br/>
    Author: Psideralis
    License: GNU GPL
    Status: Unfinished
    Versions: 00.00.000.001
  ### Disinterpreter: 
  #### Tries to output Python code from C++ file. <br/>
    Author: Psideralis
    License: GNU GPL
    Status: Unfinished
    Versions: 00.00.000.001