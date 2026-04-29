# cpp-algorithms-datastructures

![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)
![GitHub stars](https://img.shields.io/github/stars/saqibbedar/dsa.svg)
![GitHub forks](https://img.shields.io/github/forks/saqibbedar/dsa.svg)
![GitHub issues](https://img.shields.io/github/issues/saqibbedar/dsa.svg)

Structured **Data Structures & Algorithms (DSA) in C++**: topic-wise implementations, labs, assignments, revision notes, and interview practice.

> This repository is organized “folder-first” so you can study one topic at a time, run code locally, and build strong fundamentals for problem solving and coding interviews.

---

## What’s inside (high level)

- **Topic-wise DSA implementations (C++)**  
  Path: `Data Structures & Algorithms/`
- **Assignments** (coursework-style practice)  
  Path: `Assignments/`
- **DSA Friday Lab** (lab-style practice to build consistency)  
  Path: `DSA Friday Lab/`
- **Quick C++ Revision** (C++ concepts used frequently in DSA)  
  Path: `Quick C++ Revision/`
- **Past Papers** (exam-style / revision material)  
  Path: `Past Papers/`
- **Docker guide** (notes for a consistent environment)  
  Path: `docker-guide/`
- **Notes/structure helpers** (`NOTES.yaml` and other YAML files)  
  These help document folders and keep the repo navigable.

---

## Recommended way to use this repo

1. Start from the main folder:  
   `Data Structures & Algorithms/`
2. Pick **one** topic folder (example: `LinkedList`, `Stack`, `Queue`, `Sorting Algorithms`).
3. Read the code, trace the logic, and run it locally.
4. Modify it:
   - add edge cases
   - add missing operations
   - refactor for clarity
5. Move to the next topic.

Tip: progress becomes much faster when you go **topic-by-topic** instead of jumping randomly.

---

## Quick links

- Main content:  
  https://github.com/saqibbedar/dsa/tree/main/Data%20Structures%20%26%20Algorithms
- Assignments:  
  https://github.com/saqibbedar/dsa/tree/main/Assignments
- DSA Friday Lab:  
  https://github.com/saqibbedar/dsa/tree/main/DSA%20Friday%20Lab
- Quick C++ Revision:  
  https://github.com/saqibbedar/dsa/tree/main/Quick%20C%2B%2B%20Revision

---

## Topics (examples you’ll see in the repo)

Inside `Data Structures & Algorithms/` you’ll find topic folders such as:

- Linked List
- Stack
- Queue
- Priority Queue
- Trees / Binary Search Tree
- Sorting Algorithms
- Recursion
- Iterators

(Exact folders may vary—this repo is intended to grow over time.)

---

## Run code locally

Most code is designed to compile and run independently (file-by-file or folder-by-folder).

### Compile and run a single file

```bash
g++ -std=c++17 file.cpp -o app
./app
```

### Compile multiple files together (if a topic uses more than one `.cpp`)

```bash
g++ -std=c++17 main.cpp other.cpp -o app
./app
```

Notes:
- If you get missing include errors or symbol collisions, compile **one topic folder at a time**.
- Prefer a modern compiler (GCC/Clang) and at least **C++17**.

---

## Contribution

Contributions are welcome—especially improvements that keep the repo consistent and easy to learn from.

Suggested contributions:
- improve naming + comments
- add missing operations + edge cases
- add small driver examples (`main.cpp`) for topics
- fix bugs and simplify implementations

General flow:
1. Fork the repo
2. Create a branch
3. Make changes and test
4. Open a PR with a clear description

---

## License

MIT License — see [`LICENSE`](./LICENSE).
