# DSA in C++

![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)
![GitHub stars](https://img.shields.io/github/stars/saqibbedar/DSA.svg)
![GitHub forks](https://img.shields.io/github/forks/saqibbedar/DSA.svg)
![GitHub issues](https://img.shields.io/github/issues/saqibbedar/DSA.svg)
![visitors](https://visitor-badge.laobi.icu/badge?page_id=saqibbedar.DSA)

Comprehensive repository for mastering Data Structures and Algorithms (DSA) in C++. This repo is organized in a structured, folder-first way so you can learn topic by topic, read full implementations, and revise later without losing the roadmap.

Repository focus:
- C++ implementations of data structures and algorithms
- A structured learning path (topics, labs, assignments, revision)
- Code you can study deeply and run locally

## Who this repository is for

This repo is useful if you are:
- learning DSA from scratch in C++
- preparing for interviews and want clean topic-wise practice
- looking for implemented data structures you can read and analyze
- a developer who wants to contribute improvements or new topics

## Quick start

If you only open one folder, start here:

Data Structures and Algorithms:
https://github.com/saqibbedar/dsa/tree/main/Data%20Structures%20%26%20Algorithms

## How to explore this repository

Recommended way to use this repo:
1. Pick one topic folder inside `Data Structures & Algorithms`
2. Read the implementation and trace the logic
3. Run the code locally
4. Modify or extend the code (add operations, add tests, refactor)
5. Move to the next topic

Tip: Don’t jump across topics randomly. Go one folder at a time and keep notes.

## Repository structure

Main folders you will use:

### Data Structures & Algorithms
Path: `Data Structures & Algorithms/`

This is the main content folder. Topics are organized into separate directories, for example:
- LinkedList
- Stack
- Queue
- Priority-Queue
- Binary Search Tree
- Sorting Algorithms
- Recursion
- Iterators

Direct link:
https://github.com/saqibbedar/dsa/tree/main/Data%20Structures%20%26%20Algorithms

### Assignments
Path: `Assignments/`

Coursework-style assignments for practice and reinforcement.

### DSA Friday Lab
Path: `DSA Friday Lab/`

Lab-style practice content. Good for building consistency and speed.

### Quick C++ Revision
Path: `Quick C++ Revision/`

A compact revision area for C++ basics that are important for DSA (pointers, references, templates, STL basics).

### Past Pappers
Path: `Past Pappers/`

Past-paper style material for revision and exam-style practice.

### docker-guide
Path: `docker-guide/`

Notes and guidance related to using Docker for a consistent environment.

### Notes
Files like `NOTES.yaml` and various `about-this-folder.yaml` files are included to keep the repo navigable and structured.

## Running code locally

This repository contains multiple independent topic folders. Most files are designed to compile and run individually.

Typical compile and run commands:

```bash
g++ -std=c++17 file.cpp -o app
./app
```

If a folder contains multiple `.cpp` files that depend on each other, compile them together:

```bash
g++ -std=c++17 main.cpp other.cpp -o app
./app
```

If you run into missing includes or name collisions, compile one folder at a time.

## Contributing

Contributions are welcome. If you are a developer, you can help by:
- fixing bugs
- improving code clarity and naming
- adding missing operations and edge case handling
- adding new topics in the same structured style
- adding small test drivers or usage examples

Contribution guidelines are available here:
- `Contribute/CONTRIBUTE.yaml`

General flow:
1. Fork the repository
2. Create a new branch
3. Make changes and test them
4. Open a pull request with a clear description

## Related repositories (C++ fundamentals)

This repo focuses on DSA. If you want more C++ fundamentals before going deep into DSA, you can also explore:
- C++ basics and pointers: `saqibbedar/CPlusPlusLearningHub`
- OOP notes: `saqibbedar/Cpp-OOP-Notes`

## License

MIT License. See `LICENSE`.
