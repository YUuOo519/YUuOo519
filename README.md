# Compiler_Project

Compiler_Project是一个实现编译器词法分析和语法分析功能的课程项目。它包含多个模块，主要实现了DFA（确定有限状态自动机）、NFA（非确定有限状态自动机）、LALR分析器和其他编译器设计中的关键组件。

## Authors

- 郭幸榆
- 20222131077
- 2022级
- 计科2班

## File catalogue

Compiler_Project/
├── Compiler_Project.pro       # 项目配置文件
├── Headers/                   # 头文件目录
│   ├── btree.h                # 二叉树相关头文件
│   ├── checklowercase.h       # 小写字母检查头文件
│   ├── customdelegate.h       # 自定义委托头文件
│   ├── dfa.h                  # DFA 功能实现头文件
│   ├── execute.cpp            # 执行相关模块头文件
│   ├── getcpp.h               # 数据获取头文件
│   ├── getfirstfollow.h       # FIRST/FOLLOW 集实现
│   ├── global.h               # 全局变量和宏定义
│   ├── lalr.h                 # LALR 分析器
│   ├── lr1.h                  # LR(1) 分析器
│   ├── mainwindow.h           # 主窗口头文件
│   ├── mindfa.h               # 最小化 DFA
│   ├── nfa.h                  # NFA 相关头文件
│   ├── scan.h                 # 词法扫描器
│   ├── showrules.h            # 展示语法规则
│   └── testcontent.h          # 测试数据相关头文件
├── Sources/                   # 源文件目录
│   ├── btree.cpp              # 二叉树功能实现
│   ├── checklowercase.cpp     # 小写字母检查功能实现
│   ├── dfa.cpp                # DFA 功能实现
│   ├── execute.cpp            # 执行相关逻辑
│   ├── getcpp.cpp             # 数据获取功能实现
│   ├── getfirstfollow.cpp     # FIRST/FOLLOW 集生成逻辑
│   ├── lalr.cpp               # LALR 分析器实现
│   ├── lr1.cpp                # LR(1) 分析器实现
│   ├── main.cpp               # 主程序入口
│   ├── mainwindow.cpp         # 主窗口逻辑实现
│   ├── mindfa.cpp             # 最小化 DFA
│   ├── nfa.cpp                # NFA 相关逻辑
│   ├── scan.cpp               # 词法扫描功能
│   ├── showrules.cpp          # 语法规则展示实现
│   └── testcontent.cpp        # 测试内容相关实现
├── Forms/                     # 界面文件目录
│   ├── btree.ui               # 二叉树界面
│   ├── checklowercase.ui      # 小写字母检查界面
│   ├── mainwindow.ui          # 主窗口界面
│   ├── showrules.ui           # 语法规则展示界面
│   └── testcontent.ui         # 测试内容界面
