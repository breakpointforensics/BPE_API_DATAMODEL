Usage: Breakpoint Processing Engine API Mode [-h] [-v]
                                             (-J JSON | -JF JSONFILE | -A)
                                             [-I IMPORTPATH] [-O OUTPUTPATH]

options:
  -h, --help            show this help message and exit
  -v, --verbose         Allows verbose messages to be displayed
  -J JSON, --json JSON  Specifies JSON object mode for interfacing with API
  -JF JSONFILE, --jsonfile JSONFILE
                        Specifies JSON file mode for interfacing with API
  -A, --arg             Specifies argument mode for interfacing with API
  Optional(Only required in argument mode):
  -I IMPORTPATH, --importPath IMPORTPATH
                        Specify the import path for a forensic image
  -O OUTPUTPATH, --outputPath OUTPUTPATH
                        Specify output path for generated JSONS
                        
The JF mode is the prefered option at this time and fully functional.                        
Example:
BFIP4Griffeye.exe -v -JF "C:/Users/David/Desktop/Sample.json"

The use of '-v' enabled verbose messaging(optional).
-JF specifies the JSON data is contained in a file that will be read into BPE
