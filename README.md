# C File I/O

Programs covering file handling in C — opening, reading, writing, and closing files.

## Files

| File | Concept |
|---|---|
| `01_file.c` | File basics — `fopen`, `fclose` |
| `02_quickquiz.c` | Check whether a file exists before opening it |
| `03_file_write.c` | Writing to a file using `fprintf` |
| `04_fget_put.c` | Reading/writing characters using `fgetc` and `fputc` |
| `05_readingfles_cb.c` | Reading files (char by char / callback-based approach) |

## Concepts covered
- Opening files in different modes (`r`, `w`)
- Reading from files (`fscanf`, `fgetc`)
- Writing to files (`fprintf`, `fputc`)
- Checking file existence before opening
- Closing files properly with `fclose`

## How to run
```bash
gcc <filename>.c -o output
./output
