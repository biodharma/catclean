# CatClean

CatClean is a command-line utility written in C++ that removes comment lines and blank lines from a text file.

## Prerequisites

Make sure you have a C++ compiler installed on your system. You can use GCC or any other compiler of your choice.

## Compilation

To compile the program, run the following command in the terminal:

```bash
g++ -o catclean catclean.cpp 
```

This will generate an executable named `catclean`.

## Usage

```bash
catclean [FILE] [-o OUTPUT_FILE]
```

- `[FILE]`: Specify the input file to be processed.
- `-o [OUTPUT_FILE]` (optional): Specify the output file. If not provided, the result will be printed to the screen.

### Usage Examples

- Process a file and print the result to the screen:

```bash
catclean text.txt
```

- Process a file and save the result to an output file:

```bash
catclean text.txt -o clean_text.txt
```


## Contributing

Contributions are welcome! Feel free to open issues and submit pull requests with improvements, bug fixes, or new features.

## License

This project is licensed under the [MIT License](LICENSE).

