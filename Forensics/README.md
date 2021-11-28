# Forensics
- [Forensics Tools](https://github.com/mesquidar/ForensicsTools)<br>

- strings [Print the sequences of printable characters in files]
```
$ strings [-afovV] [-min-len]
               [-n min-len] [--bytes=min-len]
               [-t radix] [--radix=radix]
               [-e encoding] [--encoding=encoding]
               [-] [--all] [--print-file-name]
               [-T bfdname] [--target=bfdname]
               [-w] [--include-all-whitespace]
               [-s] [--output-separatorsep_string]
               [--help] [--version] file...
               
$ man strings (for other details)
```
- exiftool [Read and write meta information in files]
```
   Reading
        $ exiftool [OPTIONS] [-TAG...] [--TAG...] FILE...

   Writing
       $ exiftool [OPTIONS] -TAG[+-<]=[VALUE]... FILE...

   Copying
       $ exiftool [OPTIONS] -tagsFromFile SRCFILE [-SRCTAG[>DSTTAG]...] FILE...

   Other
       $ exiftool [ -ver | -list[w|f|r|wf|g[NUM]|d|x] ]
       
$ man exiftool (for other details)
```
- binwalk [Tool for searching binary images for embedded files and executable code]
```
$ binwalk [OPTIONS] [FILE1] [FILE2] [FILE3] ...

$ man binwalk (for other details)
```
- dd [Convert and copy a file]
```
$ dd [OPERAND]...
$ dd OPTION

$ man dd (for other details)
```
- foremost []

