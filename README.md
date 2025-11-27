<div align="center">

  <img src="https://img.icons8.com/fluency/96/000000/code.png" width="80" height="80" alt="CS Logo">

  

  <h1>💻 CS 11408 考研上岸知识库</h1>

  <p>

    <b>计算机学科专业基础综合 (408/11408) 一站式复习指南</b>

  </p>

  

  <p>

    <a href="#"><img src="https://img.shields.io/badge/Subject-CS%20Core-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" alt="Subject"></a>

    <a href="#"><img src="https://img.shields.io/badge/Plan-2026%20Target-success?style=flat-square" alt="Target"></a>

    <a href="#"><img src="https://img.shields.io/badge/Docs-Latest-orange?style=flat-square" alt="Status"></a>

    <a href="#"><img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License"></a>

  </p>

  

  <h4>

    <a href="#-知识板块-modules">知识板块</a> •

    <a href="#-详细考点-detailed-syllabus">详细考点</a> •

    <a href="#-备考时间轴-timeline-2025-2026">备考时间轴</a> •

    <a href="#-资源导航-repository-structure">资源导航</a>

  </h4>

</div>

  

<br>

📖 项目介绍 (Introduction)

本项目旨在构建一个系统化、模块化的计算机考研知识体系。内容紧扣 11408 / 408 统考大纲，涵盖数据结构、计算机组成原理、操作系统、计算机网络四大核心科目。

  

🚀 目标：不仅是资料仓库，更是你的备考仪表盘。从基础概念到真题实战，提供全流程的知识索引。

  

<br>

🧩 知识板块 (Modules)

我们采用分层结构管理知识点，点击下方链接直接跳转至对应章节：

  

<table> <tr> <td width="50%" align="center"> <h3>🌲 数据结构 (DS)</h3> <p><code>45分</code> | 逻辑思维与代码实现</p> <a href="./DataStructure">👉 查看笔记 & 代码</a> </td> <td width="50%" align="center"> <h3>⚡ 计算机组成原理 (CO)</h3> <p><code>45分</code> | 硬件底层与指令流</p> <a href="./ComputerOrganization">👉 查看笔记 & 难点</a> </td> </tr> <tr> <td align="center"> <h3>💿 操作系统 (OS)</h3> <p><code>35分</code> | 资源调度与并发控制</p> <a href="./OperatingSystem">👉 查看笔记 & 模型</a> </td> <td align="center"> <h3>🌐 计算机网络 (CN)</h3> <p><code>25分</code> | 协议栈与数据传输</p> <a href="./ComputerNetwork">👉 查看笔记 & 图解</a> </td> </tr> </table> <br>

🔍 详细考点 (Detailed Syllabus)

<details> <summary><b>🌲 数据结构 (Data Structures) - 点击展开详情</b></summary> <br>

核心思路：不仅要会写代码，还要会算复杂度。

  

1. 线性表 (Linear List)

基础：顺序表 vs 链表（优缺点对比、存储密度）。

  

代码题高频：单链表的逆置、归并有序表、找倒数第K个节点、去重。

  

难点：双向循环链表的插入与删除操作细节（指针修改顺序）。

  

2. 栈与队列 (Stack & Queue)

应用：括号匹配、表达式求值（中缀转后缀算法）、递归的实现机制。

  

特殊结构：共享栈、双端队列（输出序列合法性判断）。

  

3. 树与二叉树 (Tree & Binary Tree) ⭐⭐⭐

遍历：前中后序（递归/非递归）、层序遍历。

  

核心性质：节点数与度数关系、完全二叉树的性质。

  

高级结构：线索二叉树（构造与遍历）、哈夫曼树（WPL计算）、并查集（路径压缩）。

  

代码题核心：二叉树的深度、路径查找、节点统计、镜像反转。

  

4. 图 (Graph)

存储：邻接矩阵 vs 邻接表（空间复杂度）。

  

遍历：DFS vs BFS（通过遍历生成树判断图的连通性）。

  

核心算法：

  

最小生成树：Prim (选点) vs Kruskal (选边)。

  

最短路径：Dijkstra (贪心/非负权) vs Floyd (动态规划)。

  

拓扑排序 (AOV) & 关键路径 (AOE)。

  

5. 查找与排序 (Search & Sort)

查找：折半查找判定树（ASL计算）、B树/B+树（插入删除分裂规则）、红黑树（性质与定义）、散列表（Hash冲突解决：开放定址/链地址）。

  

排序：快排（Pivot选择与划分）、堆排序（建堆过程）、归并排序。

  

考点：各种排序的时间/空间复杂度、稳定性、适用场景。

  

</details> <details> <summary><b>⚡ 计算机组成原理 (Computer Organization) - 点击展开详情</b></summary> <br>

核心思路：理解数据如何在电路中流动。

  

1. 数据表示 (Data Representation)

运算：原/反/补/移码转换、溢出判断（一位符号位/双符号位）。

  

浮点数：IEEE 754 标准（阶码偏置值）、浮点数加减运算步骤（对阶、尾数求和、规格化、舍入、溢出判断）。

  

2. 存储系统 (Memory) ⭐⭐⭐

层次结构：局部性原理（时间/空间）。

  

Cache：直接映射、全相联、组相联（地址映射计算、Tag位数、替换算法 LRU）。

  

虚拟存储：TLB + Cache + 主存 + 辅存 的访问流程与缺失处理（Page Fault）。

  

3. 指令系统 (Instruction Set)

寻址：基址寻址（面向OS） vs 变址寻址（面向数组） vs 相对寻址（面向PC）。

  

架构：CISC vs RISC 对比。

  

4. 中央处理器 (CPU)

数据通路：单总线/多总线结构下的微操作信号。

  

流水线：吞吐率计算、加速比、三大冒险（结构/数据/控制）及处理方法。

  

5. 总线与I/O (Bus & I/O)

总线：仲裁方式、定时方式。

  

I/O控制：

  

程序查询方式。

  

中断方式（中断隐指令、中断处理流程、多重中断）。

  

DMA方式（与中断的区别、总线接管时机）。

  

</details> <details> <summary><b>💿 操作系统 (Operating Systems) - 点击展开详情</b></summary> <br>

核心思路：管理硬件资源，为软件提供服务。

  

1. 进程管理 (Process Management) ⭐⭐⭐

状态：三态/五态/七态模型转换。

  

调度：FCFS, SJF, RR, 优先级调度（周转时间/带权周转时间计算）。

  

同步互斥：PV操作手写题（生产者-消费者、读者-写者、哲学家进餐、吸烟者问题）。

  

死锁：四个必要条件、银行家算法（安全序列检测）。

  

2. 内存管理 (Memory Management)

分配：连续分配（动态分区分配算法） vs 非连续分配。

  

分页/分段：逻辑地址到物理地址的转换、段页式管理。

  

虚拟内存：缺页中断、页面置换算法（OPT, LRU, CLOCK/NRU）。

  

3. 文件管理 (File Management)

逻辑/物理结构：索引文件（多级索引计算文件大小）。

  

目录：FCB、索引节点（i-node，硬链接 vs 软链接）。

  

外存管理：空闲表/位示图、磁盘调度算法（SSTF, SCAN, C-SCAN）。

  

</details>

<details>

<summary><b>🌐 计算机网络 (Computer Networks) - 点击展开详情</b></summary>

<br>

  

> **核心思路**：协议栈与数据包的封装解封装。

  

#### 1. 物理层 & 链路层

* **物理层**：奈奎斯特 vs 香农公式、编码与调制。

* **链路层**：组帧、差错控制（CRC/海明码）、CSMA/CD（以太网）、CSMA/CA（无线）、交换机自学习算法。

* **滑动窗口**：GBN vs SR（窗口大小限制、确认机制）。

  

#### 2. 网络层 (Network Layer) ⭐⭐⭐

* **IP协议**：IPv4首部格式、分片与重组、CIDR子网划分（超网聚合）、NAT。

* **路由协议**：RIP (距离向量/UDP), OSPF (链路状态/IP), BGP (路径向量/TCP)。

* **设备**：路由器结构与转发流程。

  

#### 3. 传输层 (Transport Layer)

* **UDP vs TCP**：首部格式、可靠性对比。

* **TCP核心**：三次握手/四次挥手（状态机转换）、拥塞控制（慢开始/拥塞避免/快重传/快恢复）。

  

#### 4. 应用层 (Application Layer)

* **协议**：DNS (递归/迭代)、HTTP (1.0/1.1/2.0)、FTP (控制连接/数据连接)、SMTP/POP3。

  

</details>

<br>
## 📅 备考时间轴 (Timeline 2025-2026)

  

本计划基于 **2025年11月** 开始，目标为次年12月考试的

<div align="center">

  <img src="https://img.icons8.com/fluency/96/000000/code.png" width="80" height="80" alt="CS Logo">

  

  <h1>💻 CS 11408 考研上岸知识库</h1>

  <p>

    <b>计算机学科专业基础综合 (408/11408) 一站式复习指南</b>

  </p>

  

  <p>

    <a href="#"><img src="https://img.shields.io/badge/Subject-CS%20Core-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" alt="Subject"></a>

    <a href="#"><img src="https://img.shields.io/badge/Plan-2026%20Target-success?style=flat-square" alt="Target"></a>

    <a href="#"><img src="https://img.shields.io/badge/Docs-Latest-orange?style=flat-square" alt="Status"></a>

    <a href="#"><img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License"></a>

  </p>

  

  <h4>

    <a href="#-知识板块-modules">知识板块</a> •

    <a href="#-详细考点-detailed-syllabus">详细考点</a> •

    <a href="#-备考时间轴-timeline-2025-2026">备考时间轴</a> •

    <a href="#-资源导航-repository-structure">资源导航</a>

  </h4>

</div>

  

<br>


---

  

## 📖 项目介绍 (Introduction)

  

本项目旨在构建一个**系统化、模块化**的计算机考研知识体系。内容紧扣 **11408 / 408 统考大纲**，涵盖数据结构、计算机组成原理、操作系统、计算机网络四大核心科目。

  

> **🚀 目标**：不仅是资料仓库，更是你的**备考仪表盘**。从基础概念到真题实战，提供全流程的知识索引。

  

<br>

  

## 🧩 知识板块 (Modules)

  

我们采用分层结构管理知识点，点击下方链接直接跳转至对应章节：

  

<table>

  <tr>

    <td width="50%" align="center">

      <h3>🌲 数据结构 (DS)</h3>

      <p><code>45分</code> | 逻辑思维与代码实现</p>

      <a href="./DataStructure">👉 查看笔记 & 代码</a>

    </td>

    <td width="50%" align="center">

      <h3>⚡ 计算机组成原理 (CO)</h3>

      <p><code>45分</code> | 硬件底层与指令流</p>

      <a href="./ComputerOrganization">👉 查看笔记 & 难点</a>

    </td>

  </tr>

  <tr>

    <td align="center">

      <h3>💿 操作系统 (OS)</h3>

      <p><code>35分</code> | 资源调度与并发控制</p>

      <a href="./OperatingSystem">👉 查看笔记 & 模型</a>

    </td>

    <td align="center">

      <h3>🌐 计算机网络 (CN)</h3>

      <p><code>25分</code> | 协议栈与数据传输</p>

      <a href="./ComputerNetwork">👉 查看笔记 & 图解</a>

    </td>

  </tr>

</table>

  

<br>

  

## 🔍 详细考点 (Detailed Syllabus)

  

<details>

<summary><b>🌲 数据结构 (Data Structures) - 点击展开详情</b></summary>

<br>

  

> **核心思路**：不仅要会写代码，还要会算复杂度。

  

#### 1. 线性表 (Linear List)

* **基础**：顺序表 vs 链表（优缺点对比、存储密度）。

* **代码题高频**：单链表的逆置、归并有序表、找倒数第K个节点、去重。

* **难点**：双向循环链表的插入与删除操作细节（指针修改顺序）。

  

#### 2. 栈与队列 (Stack & Queue)

* **应用**：括号匹配、表达式求值（中缀转后缀算法）、递归的实现机制。

* **特殊结构**：共享栈、双端队列（输出序列合法性判断）。

  

#### 3. 树与二叉树 (Tree & Binary Tree) ⭐⭐⭐

* **遍历**：前中后序（递归/非递归）、层序遍历。

* **核心性质**：节点数与度数关系、完全二叉树的性质。

* **高级结构**：线索二叉树（构造与遍历）、哈夫曼树（WPL计算）、并查集（路径压缩）。

* **代码题核心**：二叉树的深度、路径查找、节点统计、镜像反转。

  

#### 4. 图 (Graph)

* **存储**：邻接矩阵 vs 邻接表（空间复杂度）。

* **遍历**：DFS vs BFS（通过遍历生成树判断图的连通性）。

* **核心算法**：

    * 最小生成树：Prim (选点) vs Kruskal (选边)。

    * 最短路径：Dijkstra (贪心/非负权) vs Floyd (动态规划)。

    * 拓扑排序 (AOV) & 关键路径 (AOE)。

  

#### 5. 查找与排序 (Search & Sort)

* **查找**：折半查找判定树（ASL计算）、B树/B+树（插入删除分裂规则）、红黑树（性质与定义）、散列表（Hash冲突解决：开放定址/链地址）。

* **排序**：快排（Pivot选择与划分）、堆排序（建堆过程）、归并排序。

* **考点**：各种排序的时间/空间复杂度、**稳定性**、适用场景。

  

</details>

  

<details>

<summary><b>⚡ 计算机组成原理 (Computer Organization) - 点击展开详情</b></summary>

<br>

  

> **核心思路**：理解数据如何在电路中流动。

  

#### 1. 数据表示 (Data Representation)

* **运算**：原/反/补/移码转换、溢出判断（一位符号位/双符号位）。

* **浮点数**：IEEE 754 标准（阶码偏置值）、浮点数加减运算步骤（对阶、尾数求和、规格化、舍入、溢出判断）。

  

#### 2. 存储系统 (Memory) ⭐⭐⭐

* **层次结构**：局部性原理（时间/空间）。

* **Cache**：直接映射、全相联、组相联（地址映射计算、Tag位数、替换算法 LRU）。

* **虚拟存储**：TLB + Cache + 主存 + 辅存 的访问流程与缺失处理（Page Fault）。

  

#### 3. 指令系统 (Instruction Set)

* **寻址**：基址寻址（面向OS） vs 变址寻址（面向数组） vs 相对寻址（面向PC）。

* **架构**：CISC vs RISC 对比。

  

#### 4. 中央处理器 (CPU)

* **数据通路**：单总线/多总线结构下的微操作信号。

* **流水线**：吞吐率计算、加速比、三大冒险（结构/数据/控制）及处理方法。

  

#### 5. 总线与I/O (Bus & I/O)

* **总线**：仲裁方式、定时方式。

* **I/O控制**：

    * 程序查询方式。

    * 中断方式（中断隐指令、中断处理流程、多重中断）。

    * DMA方式（与中断的区别、总线接管时机）。

  

</details>

  

<details>

<summary><b>💿 操作系统 (Operating Systems) - 点击展开详情</b></summary>

<br>

  

> **核心思路**：管理硬件资源，为软件提供服务。

  

#### 1. 进程管理 (Process Management) ⭐⭐⭐

* **状态**：三态/五态/七态模型转换。

* **调度**：FCFS, SJF, RR, 优先级调度（周转时间/带权周转时间计算）。

* **同步互斥**：PV操作手写题（生产者-消费者、读者-写者、哲学家进餐、吸烟者问题）。

* **死锁**：四个必要条件、银行家算法（安全序列检测）。

  

#### 2. 内存管理 (Memory Management)

* **分配**：连续分配（动态分区分配算法） vs 非连续分配。

* **分页/分段**：逻辑地址到物理地址的转换、段页式管理。

* **虚拟内存**：缺页中断、页面置换算法（OPT, LRU, CLOCK/NRU）。

  

#### 3. 文件管理 (File Management)

* **逻辑/物理结构**：索引文件（多级索引计算文件大小）。

* **目录**：FCB、索引节点（i-node，硬链接 vs 软链接）。

* **外存管理**：空闲表/位示图、磁盘调度算法（SSTF, SCAN, C-SCAN）。

  

</details>

  

<details>

<summary><b>🌐 计算机网络 (Computer Networks) - 点击展开详情</b></summary>

<br>

  

> **核心思路**：协议栈与数据包的封装解封装。

  

#### 1. 物理层 & 链路层

* **物理层**：奈奎斯特 vs 香农公式、编码与调制。

* **链路层**：组帧、差错控制（CRC/海明码）、CSMA/CD（以太网）、CSMA/CA（无线）、交换机自学习算法。

* **滑动窗口**：GBN vs SR（窗口大小限制、确认机制）。

  

#### 2. 网络层 (Network Layer) ⭐⭐⭐

* **IP协议**：IPv4首部格式、分片与重组、CIDR子网划分（超网聚合）、NAT。

* **路由协议**：RIP (距离向量/UDP), OSPF (链路状态/IP), BGP (路径向量/TCP)。

* **设备**：路由器结构与转发流程。

  

#### 3. 传输层 (Transport Layer)

* **UDP vs TCP**：首部格式、可靠性对比。

* **TCP核心**：三次握手/四次挥手（状态机转换）、拥塞控制（慢开始/拥塞避免/快重传/快恢复）。

  

#### 4. 应用层 (Application Layer)

* **协议**：DNS (递归/迭代)、HTTP (1.0/1.1/2.0)、FTP (控制连接/数据连接)、SMTP/POP3。

  

</details>

  

<br>

  

## 📅 备考时间轴 (Timeline 2025-2026)

  

本计划基于 **2025年11月** 开始，目标为次年12月考试的 **长线备考策略**。

  

```mermaid

gantt

    title 408/1

````1408 备考全景图 (Start: Nov 2025)

    dateFormat

````  YYYY-MM-DD

    axisFormat  %Y-%m

    section 🟢 预热阶段

````    C语言/指针回顾            :done,    2025-11-01, 2

````025-11-30

    离散数学/数学基础          :active,  2025

````-11-15, 2025-12-15

  

    section 🔵

```` 基础一轮 (地基)

    数据结构 (DS) 精读         :crit,    202

````5-12-01, 2026-02-15

    计算机组成 (CO)

```` 精读       :         2026-02-16, 2026-04-15

````    操作系统 (OS) 精读         :         2026-04-16, 2

````026-05-31

    计算机网络 (CN) 精读       :         202

````6-06-01, 2026-06-30

  

    section 🟡

```` 强化二轮 (提分)

    跨科考点串联 & 难点攻关     :

````         2026-07-01, 2026-08-31

````    历年真题 (2009-2020)      :         2026-0

````8-01, 2026-09-30

    section 🔴

```` 冲刺三轮 (实战)

    近5年真题全真模拟          :crit,    2

````026-10-01, 2026-11-15

    押

````题卷 & 错题回顾          :         2026-11-16, 20

````26-12-20

    考前心态调整               :         2026-12

````-21, 5d

📌 阶段说明：

  

----- * 🟢 预热阶段 (2025.11 - 2025.12)：重点解决 C 语言指针、结构体问题，为数据结构代码题扫清障碍。

  

----- * 🔵 基础一轮 (2025.12 - 2026.06)：地毯式学习，不留死角。建议顺序：DS -> CO -> OS -> CN。

  

**🟡🟡 强化二轮 (2026.07 - 2026.09)：暑期黄金期，重点刷《王道》或《天勤》习题，开始接触真题。

  

🔴 冲刺三轮 (2026.10 - 考前)：全真模拟，严格控制时间（3小时），整理错题本。

  

<br>

📂 资源导航 (Repository Structure)

text

复制代码

11408-CS-Guide/

├── 📁 00-Prerequisite       # C语言基础、离散数学复习

├── 📁 01-DataStructure      # DS 核心笔记、手撕代码模板 (C++)

├── 📁 02-ComputerArch       # 计组难点图解 (Cache, Pipeline)

├── 📁 03-OperatingSys       # PV操作题集、内存管理计算

├── 📁 04-Network            # 协议分析、Wireshark 抓包图示

├── 📁 98-Flashcards         # 记忆卡片 (Anki 格式)

└── 📁 99-RealExams          # 历年真题分类解析 (2009-Present)

<br>

🤝 贡献与反馈 (Contribution)

如果你发现资料有误，或者有更好的解题思路，欢迎提交 Pull Request 或 Issue。

  

Fork 本仓库

  

新建分支 Feat_xxx

  

提交代码

  

新建 Pull Request

  

<br>

<div align="center">

<p>Made with ❤️ by <a href="https://github.com/yourusername"\>Your Name</a></p>

</div>