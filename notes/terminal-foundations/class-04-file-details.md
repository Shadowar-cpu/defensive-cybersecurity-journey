# Class 4 - File Details and Metadata

## What I Practised

- I used `file notes.txt` to identify a plain-text file.
- I used `wc -c notes.txt` to count file size in bytes.
- I used `wc -l notes.txt` to count line endings and `wc -w notes.txt` to count words.
- I used `stat notes.txt` to inspect file metadata, including permissions, size, and times.
- I created `class-04-file-details.txt` and confirmed it was ASCII (pronounced “ASS-key”) text.
- I used `cat class-04-file-details.txt` to display and verify the file's contents safely.

## What I Learned

- File type, size, contents, permissions, and time metadata are useful clues when inspecting a file.
- ASCII text means the file contains readable basic characters. It does not automatically prove that a file is safe.
- `wc -l` counts line-ending markers. A file can look like it has three lines but show two when its final line has no line ending.
