# Computer Architecture Course - Assembly Language Exercises

A comprehensive collection of x86 assembly language programming exercises from a university-level computer architecture course. These exercises cover fundamental concepts in low-level programming, including loops, conditionals, array operations, string handling, and mathematical computations.

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [File Descriptions](#file-descriptions)
- [Prerequisites](#prerequisites)
- [How to Run](#how-to-run)
- [Topics Covered](#topics-covered)
- [File Structure](#file-structure)
- [Contributing](#contributing)

## Project Overview

This repository contains practical assembly language exercises designed to deepen understanding of computer architecture fundamentals. Each `.asm` file demonstrates specific programming concepts and CPU operations, ranging from basic I/O operations to complex algorithms.

## File Descriptions

### Foundational Concepts
- **`Leggere e stampare un intero.asm`** - Reading and printing integers
- **`Leggere e stampare una stringa.asm`** - Reading and printing strings
- **`stampaStr.asm`** - String output operations

### String Operations
- **`Char_in_substring.asm`** - Finding characters in substrings
- **`conta_sottostringa_in_stringa.asm`** - Counting substring occurrences
- **`delete_spaces.asm`** - String space removal
- **`num_of_schars.asm`** - Character counting
- **`occorrenze.asm`** - Occurrence detection
- **`Palindromo.asm`** - Palindrome checking
- **`stampa_contrario.asm`** / **`StampaContr.asm`** - Reverse string printing
- **`vocali_upper.asm`** - Vowel uppercase conversion

### Mathematical Operations
- **`factorial.asm`** - Factorial calculation
- **`prodotto.asm`** - Multiplication operations
- **`SommaNum.asm`** - Number summation
- **`given_array_find_sum.asm`** - Array summation
- **`find_min_max_media.asm`** - Finding minimum, maximum, and average values
- **`max e media float.asm`** - Floating-point max and average operations
- **`MathTest.asm`** - Mathematical operation testing
- **`27_maggio_2022.asm`** - Exam exercise (May 27, 2022)

### Bit and Mask Operations
- **`bit_mask.asm`** - Bit masking techniques
- **`mask.asm`** - Mask operations
- **`maschere_divisibili.asm`** - Divisibility mask operations
- **`overflow.asm`** - Integer overflow handling

### Algorithms
- **`Bubblesort.asm`** - Bubble sort implementation
- **`sumArray.asm`** - Array summing algorithm

## Prerequisites

To run these assembly programs, you'll need:

- **MASM (Microsoft Macro Assembler)** or **NASM (Netwide Assembler)**
- **Windows or Linux environment** (MASM primarily Windows, NASM cross-platform)
- **Debugger** (e.g., WinDbg, GDB for debugging)
- Basic understanding of x86 assembly language and CPU registers
- A text editor or IDE supporting assembly syntax (VS Code, Visual Studio, etc.)

### Installation (Linux with NASM)

```bash
sudo apt-get install nasm
```

### Installation (Windows with MASM)

Download and install the Microsoft Visual Studio Build Tools or Visual Studio Community with C++ support.

## How to Run

### Using NASM (Linux/Cross-platform)

1. Assemble the `.asm` file:
   ```bash
   nasm -f elf64 filename.asm -o filename.o
   ```

2. Link the object file:
   ```bash
   ld -o filename filename.o
   ```

3. Run the program:
   ```bash
   ./filename
   ```

### Using MASM (Windows)

1. Assemble:
   ```bash
   ml64.exe /c filename.asm
   ```

2. Link:
   ```bash
   link filename.obj
   ```

3. Run:
   ```bash
   filename.exe
   ```

### Using a Debugger

For NASM/Linux with GDB:
```bash
gdb ./filename
```

For MASM/Windows with WinDbg:
```bash
windbg filename.exe
```

## Topics Covered

- **Input/Output Operations** - Reading from and writing to console
- **Data Types** - Integers, floats, characters, and strings
- **Control Flow** - Conditionals and loops (CMP, JMP, JNE, JE, etc.)
- **Array Operations** - Indexing, traversal, and processing
- **String Manipulation** - Concatenation, reversal, searching
- **Mathematical Operations** - Arithmetic, floating-point calculations
- **Bit Operations** - Masking, shifting, logical operations
- **Algorithms** - Sorting, searching, and other classic algorithms

## File Structure

```
Computer-Architecture-Course-Assembly-main/
├── README.md
├── Foundational exercises
│   ├── Leggere e stampare un intero.asm
│   └── Leggere e stampare una stringa.asm
├── String operations
│   ├── Palindromo.asm
│   ├── delete_spaces.asm
│   └── ...
├── Mathematical operations
│   ├── factorial.asm
│   ├── find_min_max_media.asm
│   └── ...
├── Bit and mask operations
│   ├── bit_mask.asm
│   └── overflow.asm
└── Algorithms
    ├── Bubblesort.asm
    └── sumArray.asm
```

## Educational Value

These exercises are designed to:
- Strengthen understanding of CPU architecture and instruction sets
- Practice low-level programming and memory management
- Develop debugging and problem-solving skills
- Prepare students for systems programming and reverse engineering
- Provide hands-on experience with assembly language concepts

## License

This repository is educational material from a university course. Please check with your institution for usage rights and licensing information.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Submit a pull request

For bug reports or suggestions, please open an issue.

## References

- [x86 Assembly Language Reference](https://www.cs.virginia.edu/~evans/cs216/guides/x86.html)
- [NASM Documentation](https://www.nasm.us/doc/)
- [Intel x86 Instructions Reference](https://www.felixcloutier.com/x86/)
- [Assembly Language Tutorials](https://www.tutorialspoint.com/assembly_language/index.htm)

---
**Course Level:** Intermediate  
**Language:** x86 Assembly
