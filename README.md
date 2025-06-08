# Huffman Compressor & Decompressor

This C++ project implements **Huffman Coding**, a popular lossless data compression algorithm. It provides a command-line interface to **compress** and **decompress** text files using Huffman encoding.

## Features

- Counts character frequencies in a file
- Builds a Huffman Tree
- Generates Huffman codes
- Compresses input text files using the Huffman codes
- Stores both the encoded data and the Huffman map in a binary file
- Decompresses encoded binary files back to the original text

##  Project Structure


├── .vscode/ # VSCode configuration folder

├── compressor.cpp # Main source code file (Huffman implementation)

├── compressor.exe # Compiled executable for Windows

├── file.txt # Input file to be compressed

├── output.txt # Compressed binary output

└── README.md # Project documentation


---

##  How It Works

### Compression:
1. Reads `file.txt`.
2. Counts the frequency of each character.
3. Builds a Huffman Tree.
4. Generates binary Huffman codes for each character.
5. Encodes and writes compressed output to `output.txt`.

### Decompression:
1. Reads `output.txt`.
2. Reconstructs Huffman codes and the encoded content.
3. Decodes the original text and saves it to `decompressed.txt`.

---

## 🛠 Build & Run

### Requirements
- C++ Compiler (`g++` recommended)
- Windows (for using `compressor.exe`) or any OS with C++ compiler

### Compile from Source (if needed)
```bash
g++ compressor.cpp -o compressor
```

Run the Program
```bash
./compressor     # or ./compressor.exe on Windows
```
Interface
```bash
x-x-x-x-x-x-x-x-x
|     MENU      |
x-x-x-x-x-x-x-x-x
| 1.Compress    |
| 2.Decompress  |
x-x-x-x-x-x-x-x-x
```
(•_• | •-•) Author


@jeevan1978

Feel free to fork, star, or contribute!


---

Let me know if you want me to include a compression size comparison or images in Markdown (e.g., a flowchart or example input/output).











