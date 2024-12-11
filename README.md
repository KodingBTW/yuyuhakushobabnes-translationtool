This tool allows you to extract the text from the questions in the game "Yu Yu Hakusho - Bakutou Ankoku Bujutsukai (J).nes", and then easily reinsert it. The pointer table will be updated automatically.
The tool can be found here: https://github.com/KodingBTW/hexstring

## Usage

Synopsis:
```
HexString [-d | -e] inFileName outFileName
```

The program doesn't handle many exceptions, so try to provide the correct information to avoid issues. For more information, read the attached readme.txt.

For easier use, I have created 2 batch files. Locate the files in the same directory as the ROM, then use "extractor.bat" to extract the text. It will create binaries files, which you can edit with any text editor; I recommend Notepad++. Then, edit the "encode.tbl" file and modify the table as you wish, adding any new graphics you need. Finally, use "inserter.bat" to insert the text.

If you need edit graphics use this tool:
https://github.com/KodingBTW/yuyuhakushobabnes-graphicsextractor

### Notes

If you get an error about lacking space when inserting the text, you will need to use empty space in the ROM, or perhaps expand it.

## Frecuency Answer Questions

### Can I use this tool in my personal project?

Of course, there's no need to ask. Feel free to use it in your project. I only ask that you mention me as contributor.

