# 快速开始指南 / Quick Start Guide

## 中文版

### 环境要求

1. **C++编译器**：支持C++11或更高版本
   - Windows: MinGW, MSVC, Clang
   - Linux: GCC, Clang
   - macOS: Clang, GCC

2. **LaTeX环境**（可选，用于生成PDF报告）
   - TeX Live (推荐)
   - MiKTeX (Windows)
   - MacTeX (macOS)

### 快速运行代码

#### 方法一：直接编译运行
```bash
# 进入题目目录
cd "CSP Course Design/chapter3/exam201604_1"

# 提取C++代码并保存为.cpp文件
# 从.tex文件中复制代码到新文件 solution.cpp

# 编译运行
g++ -o solution solution.cpp
./solution
```

#### 方法二：使用VS Code
1. 安装C/C++扩展
2. 打开项目文件夹
3. 创建.cpp文件并复制代码
4. 按F5调试运行

#### 方法三：使用在线IDE
- [C++ Shell](http://cpp.sh/)
- [Compiler Explorer](https://godbolt.org/)
- [OnlineGDB](https://www.onlinegdb.com/)

### 生成完整PDF报告

```bash
# 进入主目录
cd "CSP Course Design"

# 编译LaTeX文档
xelatex csp.tex
xelatex csp.tex  # 第二次编译以生成正确的目录
```

### 学习建议

1. **按章节学习**：从第三章开始，逐步掌握各种数据结构
2. **理解算法思路**：不要只关注代码，重点理解解题思路
3. **多练习变种**：尝试修改题目条件，练习算法灵活应用
4. **总结模板**：整理常用的代码模板和算法套路

---

## English Version

### Environment Requirements

1. **C++ Compiler**: Supporting C++11 or higher
   - Windows: MinGW, MSVC, Clang
   - Linux: GCC, Clang
   - macOS: Clang, GCC

2. **LaTeX Environment** (Optional, for PDF generation)
   - TeX Live (Recommended)
   - MiKTeX (Windows)
   - MacTeX (macOS)

### Quick Code Execution

#### Method 1: Direct Compilation
```bash
# Navigate to problem directory
cd "CSP Course Design/chapter3/exam201604_1"

# Extract C++ code and save as .cpp file
# Copy code from .tex file to new file solution.cpp

# Compile and run
g++ -o solution solution.cpp
./solution
```

#### Method 2: Using VS Code
1. Install C/C++ extension
2. Open project folder
3. Create .cpp file and copy code
4. Press F5 to debug and run

#### Method 3: Using Online IDE
- [C++ Shell](http://cpp.sh/)
- [Compiler Explorer](https://godbolt.org/)
- [OnlineGDB](https://www.onlinegdb.com/)

### Generate Complete PDF Report

```bash
# Enter main directory
cd "CSP Course Design"

# Compile LaTeX document
xelatex csp.tex
xelatex csp.tex  # Second compilation for correct table of contents
```

### Learning Recommendations

1. **Study by Chapters**: Start from Chapter 3, gradually master different data structures
2. **Understand Algorithm Logic**: Focus on problem-solving approaches, not just code
3. **Practice Variations**: Try modifying problem conditions for flexible algorithm application
4. **Summarize Templates**: Organize commonly used code templates and algorithm patterns
