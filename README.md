<div align="center">

# Vladislav «Vlad» Nalowo

**Low-level C++ developer** — Linux kernel · modern C++ · networking & self-hosted infra

<a href="https://github.com/Nalowo?tab=repositories">
  <img src="https://img.shields.io/badge/focus-Linux%20kernel%20%26%20systems-1e2327?style=flat-square&logo=linux&logoColor=white" />
</a>
<img src="https://img.shields.io/badge/C%2B%2B-17%20%2F%2020%20%2F%2023-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img src="https://komarev.com/ghpvc/?username=Nalowo&style=flat-square&color=1e2327&label=profile+views" />

</div>

---

## 👋 About

- 🧩 C++ developer working on **CAD / PLM geometric modeling** — geometry, algorithms, performance.
- 🐧 Moving deeper into **Linux kernel & low-level systems engineering** (loadable modules, netfilter, debugging with QEMU + GDB).
- 🛠 Comfortable across the stack — from kernel modules and `std::execution` down to Boost.Asio proxies and Laravel back-ends.
- 📚 Currently studying **Linux kernel development** and prepping for a systems / network engineering role.
---

## 🧰 Tech Stack

**Languages**

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Systems & Linux**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Linux Kernel](https://img.shields.io/badge/Linux%20Kernel-modules-informational?style=for-the-badge&logo=linux&logoColor=white)
![QEMU](https://img.shields.io/badge/QEMU-FF6600?style=for-the-badge&logo=qemu&logoColor=white)
![GDB](https://img.shields.io/badge/GDB-A42E2B?style=for-the-badge&logo=gnu&logoColor=white)

**Networking & Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white)
![HAProxy](https://img.shields.io/badge/HAProxy-106DA9?style=for-the-badge&logo=haproxy&logoColor=white)
![Boost.Asio](https://img.shields.io/badge/Boost.Asio-async-orange?style=for-the-badge)

**Tools**

![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---

## 🚩 Showcase · Витрина

### 🐧 Linux kernel

| Project | What it is |
|---|---|
| **[KernelBitMap](https://github.com/Nalowo/KernelBitMap)** | Kernel module: a **bitmap block allocator** over a pre-allocated pool — contiguous-region search, spinlock-based thread safety. `10 MiB` pool / `4 KiB` blocks. |
| **[HelloKernel](https://github.com/Nalowo/HelloKernel)** | Kernel module skeleton with a **sysfs parameter interface** and custom `kernel_param_ops` (set/get handlers). |
| **[KernelHashtableSearch](https://github.com/Nalowo/KernelHashtableSearch)** | Kernel hash table with **binary search inside each bucket**, controlled via sysfs. |
| **[KernelFifo](https://github.com/Nalowo/KernelFifo)** · **[KernelStack](https://github.com/Nalowo/KernelStack)** | Kernel data structures: a `kfifo`-based FIFO and a LIFO stack on kernel linked lists, both driven through sysfs. |

### ⚙️ Modern C++ · systems

| Project | What it is |
|---|---|
| **[MandelbrotFractal](https://github.com/Nalowo/MandelbrotFractal)** | Interactive Mandelbrot renderer built on the **`std::execution` (sender/receiver)** model, parallelised across a thread pool. |
| **[TaskDispatcher](https://github.com/Nalowo/TaskDispatcher)** | Multithreaded **priority task dispatcher** over a custom thread pool and priority queue (bounded/unbounded per priority). |
| **[ScanDynamic](https://github.com/Nalowo/ScanDynamic)** | Type-safe **`scan` — the inverse of `std::format`**: parses a string by a runtime format into a tuple of requested types. |
| **[BookDatabase](https://github.com/Nalowo/BookDatabase)** | Templated in-memory DB with **C++20 concepts**, heterogeneous lookup (`string_view`, no temporary allocs) and composable filters. |
| **[GeomLib](https://github.com/Nalowo/GeomLib)** | Computational-geometry library — **convex hull, triangulation, intersections** and geometric queries, with a visual demo. |

### 🌐 Networking & tooling

| Project | What it is |
|---|---|
| **[HttpProxy](https://github.com/Nalowo/HttpProxy)** | Asynchronous **HTTP proxy** on **Boost.Asio + C++20 coroutines** — one coroutine per session. |
| **[CryptoGuard](https://github.com/Nalowo/CryptoGuard)** | CLI for file **encryption / decryption and checksums** over the OpenSSL EVP API (AES, SHA-256). |
| **[Analyser](https://github.com/Nalowo/Analyser)** | Source-code analyser: extracts functions and computes complexity metrics via **tree-sitter + C++20 ranges**. |
| **[CodeRefactor](https://github.com/Nalowo/CodeRefactor)** | Automated C++ refactoring on the **Clang AST (LibTooling)** — fixes non-virtual dtors, missing `override`, and more. |

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Nalowo&show_icons=true&count_private=true&hide_border=true&theme=tokyonight" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nalowo&layout=compact&langs_count=8&hide_border=true&theme=tokyonight" />

<img src="https://streak-stats.demolab.com/?user=Nalowo&hide_border=true&theme=tokyonight" />

</div>

<div align="center">
  <sub>Собрано на C++ и кофе ☕ · рабочий стол под Debian/WSL2</sub>
</div>
