- [数理逻辑](#数理逻辑)
  - [命题逻辑基本概念](#命题逻辑基本概念)
    - [命题](#命题)
      - [简单命题与复合命题](#简单命题与复合命题)
      - [联结词](#联结词)
    - [命题公式（简称公式）](#命题公式简称公式)
      - [命题公式的层次和公式的赋值](#命题公式的层次和公式的赋值)
      - [真值表](#真值表)
      - [公式的类型](#公式的类型)
    - [题型](#题型)
  - [命题逻辑等值演算](#命题逻辑等值演算)
    - [等值演算](#等值演算)
      - [等值的定义](#等值的定义)
      - [16个常用等值式](#16个常用等值式)
      - [置换定律](#置换定律)
      - [对口问题](#对口问题)
    - [析取范式与合取范式](#析取范式与合取范式)
      - [简单析取(合取)式](#简单析取合取式)
      - [析取(合取)范式](#析取合取范式)
      - [范式存在定理](#范式存在定理)
      - [极小项，极大项](#极小项极大项)
      - [主析取(合取)范式](#主析取合取范式)
      - [作用](#作用)
    - [联结词的完备集](#联结词的完备集)
  - [命题逻辑的推理理论](#命题逻辑的推理理论)
    - [推理的形式结构](#推理的形式结构)
      - [推理的定义](#推理的定义)
      - [推理正确与蕴涵](#推理正确与蕴涵)
      - [推理定律（重言蕴涵式）](#推理定律重言蕴涵式)
    - [自然推理系统$P$](#自然推理系统p)
      - [形式系统$I$](#形式系统i)
      - [推理系统$P$定义](#推理系统p定义)
      - [推理规则](#推理规则)
      - [构造证明定义](#构造证明定义)
      - [证明方法](#证明方法)
    - [题型](#题型-1)
  - [一阶逻辑基本概念](#一阶逻辑基本概念)
    - [一阶逻辑中命题符号化](#一阶逻辑中命题符号化)
      - [个体词](#个体词)
      - [谓词](#谓词)
      - [量词](#量词)
    - [一阶逻辑](#一阶逻辑)
      - [字母表$\mathscr{L}$](#字母表mathscrl)
      - [项](#项)
      - [一阶逻辑公式](#一阶逻辑公式)
      - [解释$I$](#解释i)
      - [代换实例](#代换实例)
    - [题型](#题型-2)
  - [一阶逻辑等值演算与推理](#一阶逻辑等值演算与推理)
    - [等值式](#等值式)
      - [基本量词变换等值式](#基本量词变换等值式)
      - [基本规则](#基本规则)
    - [前束范式](#前束范式)
    - [推理理论](#推理理论)
      - [推理定律](#推理定律)
      - [自然推理系统](#自然推理系统)
      - [新的推理规则](#新的推理规则)
      - [构造证明](#构造证明)
    - [题型](#题型-3)
- [集合论](#集合论)
  - [集合代数](#集合代数)
    - [集合的基本概念](#集合的基本概念)
      - [表示法](#表示法)
      - [特殊集合](#特殊集合)
      - [关系](#关系)
    - [集合的运算](#集合的运算)
    - [有穷集的计数问题](#有穷集的计数问题)
    - [集合恒等式](#集合恒等式)
      - [主要算律](#主要算律)
      - [对偶原理](#对偶原理)
      - [证明](#证明)
      - [重要结果](#重要结果)
    - [集合论的悖论与公理系统](#集合论的悖论与公理系统)
    - [题型](#题型-4)
  - [关系](#关系-1)
    - [有序对与笛卡儿积](#有序对与笛卡儿积)
    - [二元关系](#二元关系)
      - [常用二元关系](#常用二元关系)
      - [表示法](#表示法-1)
    - [关系的运算](#关系的运算)
      - [运算的性质](#运算的性质)
    - [关系的性质](#关系的性质)
      - [性质与运算之间的联系](#性质与运算之间的联系)
    - [关系的闭包](#关系的闭包)
      - [闭包求法](#闭包求法)
      - [闭包的性质](#闭包的性质)
    - [等价关系与划分](#等价关系与划分)
      - [等价关系性质](#等价关系性质)
      - [商集与划分](#商集与划分)
    - [偏序关系](#偏序关系)
      - [盖住与哈斯图](#盖住与哈斯图)
      - [特殊元素](#特殊元素)
    - [题型](#题型-5)
  - [函数](#函数)
    - [函数(映射)定义与性质](#函数映射定义与性质)
      - [函数的定义](#函数的定义)
      - [函数的性质](#函数的性质)
      - [常用的函数](#常用的函数)
    - [函数的运算](#函数的运算)
      - [复合](#复合)
      - [反函数](#反函数)
    - [双射函数与集合的基数](#双射函数与集合的基数)
      - [集合的等势](#集合的等势)
      - [集合的优势](#集合的优势)
      - [集合的基数](#集合的基数)

# 数理逻辑
## 命题逻辑基本概念

### 命题

#### 简单命题与复合命题

- 命题: 可以**判断真假**的**陈述句**
  - 真值 只有真假命题之分
- 简单命题（原子命题）: 不能再被分为更小的简单**陈述句**
- 复合命题: ~~简单命题的复合~~ 简单命题（陈述句）通过**联结词**联结
  
#### 联结词
运算优先级如下排列，均在括号()之后：
- $\lnot$: 否定，非
- $\land$: 合取，与
- $\lor$: 析取，或
- $\to$: **实质**蕴涵，如果…就…
- $\leftrightarrow$: **等价**，双向蕴含，当且仅当
  
### 命题公式（简称公式）
- 命题常项（元）: 原子命题、复合命题等
- 命题变项（元）: 不确定真假，**取值为0或1**的**陈述句**
- 无论变项还是常项，均可用小写字母$p,q,r$表示
- 命题合式公式
  - （命题常项$\cup$命题变量）+ 括号 + 联结词
  - **有限个**
  - 用大写字母表示，如$A,B
  
#### 命题公式的层次和公式的赋值
- 层次 $n+1$
  - $\lnot B$, B为$n$层
  - 其余由两个$B,C$联结的，$n=max(i,j)$ ,$i,j$为$B,C$层次
- 赋值
  - 命题变项$p_1,p_2 \cdots p_n$的一个指定**真值**
  - 成真赋值
  - 成假赋值
  
#### 真值表
所有赋值的公式真值列表
- 哑元: 对于公式$A,B$，$B$的一些命题变项可能不会影响$A$的取值

#### 公式的类型
- 重言式（永真式）
- 矛盾式（永假式）
- 可满足式: 非矛盾式，**包含重言式**

### 题型
1. （复杂）命题符号化
2. 求命题的真值
3. 求公式成真（成假）赋值
4. 判断公式类型: 永真、永假、可满足式
   
## 命题逻辑等值演算

### 等值演算

#### 等值的定义
$A \leftrightarrow B$为重言式，即$A \iff B$


#### 16个常用等值式
1. 双重否定律 $A \iff \lnot\lnot A$
2. 幂律 $A \iff A \land A,A \iff A \lor A$
3. 交换律 $A \land B \iff B \land A, A \lor B \iff B \lor A$
4. 结合律 $(A \land B) \land C \iff A \land (B \land C), \\(A \lor B) \lor C \iff A \lor (B \lor C)$
5. 分配律 $(A \land B) \lor C \iff (A \lor C) \land (B \lor C),\\(A \lor B) \land C \iff (A \land C) \lor (B \land C)$
6. 德摩根律 $\lnot (A \land B) \iff (\lnot A \lor \lnot B), \\ \lnot (A \lor B) \iff (\lnot A \land \lnot B)$
7. 吸收律 $A \lor (A \land B) \iff A,A \land (A \lor B) \iff A$
8. 零律 $A \land 0 \iff 0$
9. 同一律 $A \lor 1 \iff 1$
10. **排中律** $A \lor \lnot A \iff 1$
11. **矛盾律** $A \land \lnot A \iff 0$
12. 蕴涵 $A \to B \iff \lnot A \lor B$
13. 等价 $A \leftrightarrow B \iff (A \to B) \land (B \to A)$
14. 假言易位 $A \to B \iff \lnot B \to \lnot A$
15. 等价否定等值式 $A \leftrightarrow B \iff \lnot B \leftrightarrow \lnot A$
16. 归谬律 $(A \to B) \land (A \to \lnot B)\iff \lnot A$
    
#### 置换定律
置换定律: 如果$A \iff B$, 则$\Phi(A) \iff \Phi(B)$

#### 对口问题
可以处理真值表法解决起来繁琐的问题:
1. 求等值式
2. 求成真/成假赋值
3. 化简
4. 解决实际问题

### 析取范式与合取范式
文字: 命题变元以及其否定被称为文字

#### 简单析取(合取)式
**仅有** **有限** 文字的析取（合取）形成的命题公式
- 排中律: 简单析取式为真当且仅当**同时**包含文字及其否定式
- 矛盾律: 简单合取式为假当且仅当**同时**包含文字及其否定式

#### 析取(合取)范式
- 析取范式: 由简单合取式析取得到的命题公式
  - 析取范式为真当且仅当所有简单合取式为真
- 合取范式: 由简单析取式合取得到的命题公式
  - 合取范式为假当且仅当所有简单析取式为假
#### 范式存在定理
1. 等值式消去蕴涵$\to$和等价$\leftrightarrow$
2. 德莫根律消去否定词$\lnot$
3. 分配律消去不想要的析取$\lor$（合取$\land$）

#### 极小项，极大项
如果析取(合取)范式中的**每一个**简单合取(析取)式中，每个命题变项及其否定这两者出现且仅出现一个，那么这是一个极小(大)项。
- 极小项$m_i$-析取范式-成真赋值
- 极大项$M_j$-合取范式-成假赋值
- 下标和成真(假)赋值一致
- 按下标从小到大或按字典顺序排列

#### 主析取(合取)范式
- 每一个命题公式存在且只有一个主析取(合取)范式与之等价
- 极小项下标$\cup$极大项下标=全$2^n$下标
  - 极小项下标$\cap$极大项下标=$\emptyset$
- 和以下等价
  - 等值演算
    - 除去永假（永真）
    - 化简重复的
    - 添加没出现的文字或其否定
  - 真值表
    - 利用成真（成假）赋值找极小（大）项

#### 作用
1. 求公式类型
   1. 完全不含/含/包含所有极小（大）项
2. 求成真/成假赋值
3. **判断两个公式是否等值**
4. 解决实际问题

### 联结词的完备集
- 命题函数: $f: \{0,1\}^n\to {0,1}$为**n元真值函数**
  - 每个命题公式只和一个命题函数对应
    - 也只有一个主析取/合取范式
  - n元有$2^{2^{n}}$个真值函数
- 完备集: 可以表示所有$n>1$的命题函数的联结词集合
  - $\{\lnot,\land,\lor\}$
  - $\{\uparrow\}$: 与非
  - $\{\downarrow\}$: 或非
  - 待证实的就可以试着表示已知的

## 命题逻辑的推理理论
### 推理的形式结构
#### 推理的定义
- $A_1,A_2,A_3\cdots A_n$推$B$的推理是**正确/有效**的，当且仅当对于$A_1,A_2,A_3\cdots A_n$和$B$的**所有命题变项**的**任意一组赋值**有
  - 或者$A_1 \land A_2 \land A_3 \cdots A_n$ 为假
  - 或者$A_1 \land A_2 \land A_3 \cdots A_n$

- 前提: 命题公式的合集，$\Gamma = \{A_1,A_2,A_3\cdots A_n\}$
- 结论：一个命题公式$B$
- 由$\Gamma$推$B$的推理记为$\Gamma \vdash B$
  - 推理正确$\Gamma \models B$
  - 推理错误$\Gamma \nvDash B$


#### 推理正确与蕴涵
 $A_1,A_2,A_3\cdots A_n\models B$ 当且仅当$A_1 \land A_2 \land A_3 \cdots A_n \to B$ 为重言式
- 记作$A_1 \land A_2 \land A_3 \cdots A_n \implies B$
- 逻辑蕴涵

#### 推理定律（重言蕴涵式）
1. 附加律 $A \implies A \lor B$
2. 化简律 $A \land B \implies A$
3. 假言推理 $(A \to B) \land A \implies B$
4. 拒取式 $(A \to B) \land \lnot B \implies \lnot A$
5. 析取三段论 $(A \lor B) \land \lnot B \implies A$
6. 假言三段论 $(A \to B) \land (B \to C) \implies (A \to C)$
7. 等值三段论 $(A \leftrightarrow B) \land (B \leftrightarrow C) \implies (A \leftrightarrow C)$
8. 构造性二难 $(A \to B) \land (C \to D) \land (A \lor C)\implies (B \lor D)$
   1. 简单版本 $(A \to B) \land (\lnot A \to D) \land (A \lor \lnot A)\implies (B \lor D)$
9.  破坏性二难 $(A \to B) \land (C \to D) \land (\lnot B \lor \lnot D)\implies (\lnot A \lor \lnot C)$
    1.  简单版本 $(A \to B) \land (A \to D) \land (\lnot B \lor \lnot D)\implies (\lnot A)$

### 自然推理系统$P$
#### 形式系统$I$
1. 形式**语言**系统
   1. 字符表集$A(I)$
   2. **合式**公式集$E(I)$
2. 形式演算系统
   1. 公理集$A_X(I)$: $E(I)$已经证明过的特殊公式
   2. 规则集$R(I)$
#### 推理系统$P$定义
1. 文字
   1. 命题变项字母 $p,q,r\cdots$
   2. 联结词$\{\lnot,\land,\lor,\to,\leftrightarrow\}$
   3. 括号和逗号
2. 命题合式公式
3. 推理规则
#### 推理规则
在证明的任何步骤上
- 前提引入规则: 任何时候都能引入前提
- 结论引入规则: 已经证明的结论可以引入
- 置换规则: 命题公式的**子公式**可以置换成等值的命题公式
- 16个等值式（双向）
- 重言蕴涵式
- 合取: $A,B \therefore A \land B$
#### 构造证明定义
引入符合推理规则的一系列命题公式**序列**$C_1 \land C_2 \land C_3 \cdots C_l$, 其中每一项:
- 或是属于前提$\Gamma$
- 或是属于前提推理出的结论
- $C_l$和待证结论$B$等值
称公式**序列**$C_1 \land C_2 \land C_3 \cdots C_l$为$A_1,A_2,A_3\cdots A_n$推$B$的证明
#### 证明方法
- 直接法
- 附加前提法: 如果结论形式为$A\to B$，引入$A$作为前提并证明B
- 归谬法/反证法: 引入$\lnot B$作为前提，推理出矛盾式
### 题型
1. 构造前提下的有效结论
2. 构造自然语言下的推理
   1. 命题变项简单陈述句**符号化**
3. 证明/判断推理正确
   1. 真值表法
   2. 等值演算法
   3. 主析取范式法
   4. 自然推理系统中构造证明
      1. 直接法
      2. 附加前提法
      3. 归谬法/反证法

## 一阶逻辑基本概念

### 一阶逻辑中命题符号化

#### 个体词
可以独立存在的**研究客体**
- 个体常项: **具体、特定**，$a,b,c\cdots$
- 个体变项: **抽象、泛指**，$x,y,z\cdots$
- 个体域: 取值范围
  - 有限: $\{a,b\}$  $\{x,y,z\}$
  - 无限: $N, R$
- 全总个体域: universe，包罗万象
#### 谓词
表示性质或关系
- 谓词常项: **具体、特定** $F,G,H$
- 谓词变项: **抽象、泛指**
- n(n≥1)元谓词: 包含$n$个个体变项的谓词
- 0元谓词: 只包含个体常项的谓词
  - 如果谓词为常项，即为命题
- **特性谓词**: 个体域下指出个体变量变化范围


#### 量词
- $\forall$: 全称量词
  - $\forall x (F(x) \to G(x))$
  - $\forall x \forall y (F(x) \land G(y) \to H(x,y))$
- $\exist$: 存在量词
  - $\exists x (F(x) \land G(x))$
  - $\exists x \exists y (F(x) \land G(y) \land H(x,y))$


在 $\forall x F(x,y)$中
- 指导变元: 中间的$x$
- 辖域: $F(x, y)$
- 约束出现: $x$在$F(x, y)$中约束出现
- 自由出现: $y$在$F(x, y)$中自由出现
### 一阶逻辑

#### 字母表$\mathscr{L}$
- 个体常项
- 个体变项
- **谓词**
- 函数
- 联结词
- 量词
- 括号和逗号

#### 项
- 个体常项、个体变项
- 函数
- 以上有限次叠加

#### 一阶逻辑公式
- 原子公式: 项+谓词
- 合式公式（或公式）
  - 原子公式
  - 量词
  - 联结词
  - 有限
- 闭式: 公式中所有**命题变项**都是约束出现
  - 在**任何解释下**都是命题
  - 
#### 解释$I$
- 个体域: $D_I$
- 个体常项: $a' \in D_I$ 为 $a$ 在 $I$ 中的解释
- 函数: $f': D^n_{I} \to D{I}$ 为 $f$ 在 $I$ 中的解释
- 谓词: $F$
- $I$下赋值$\sigma$针对自由出现
对于公式$A$，替换后的公式为$A'$，称
- $A'$ 为 $A$ 在 $I$ 上的解释
- $A$ 在 $I$ 上被解释为$A'$

一阶逻辑公式的分类
- 逻辑有效式（或永真式）
- 矛盾式（或永假式）
- 可满足式
  
#### 代换实例
一阶逻辑公式$A$中的项$A_1,A_2,A_3\cdots A_n$带入命题公式$A_0$中的命题变项$p_1,p_2,p_3\cdots p_n$，称$A$为$A_0$的代换实例
- 重言式的代换实例一定是永真式
- 矛盾式的代换实例一定是永假式

### 题型
1. 一阶逻辑命题符号化
   1. 数学命题
2. 证明是不是永真/永假式
3. 给定解释和赋值，**解释**一阶逻辑公式

## 一阶逻辑等值演算与推理

### 等值式
一阶逻辑公式$A \leftrightarrow B$为重言式，称$A$和$B$等值$A \iff B$为等值式

#### 基本量词变换等值式
1. 有限个体域$\{a_1, a_2, a_3 \cdots a_n\}$中消去量词等值式
   1. $\forall x F(x) \iff F(a_1) \land F(a_2) \land F(a_3) \cdots \land F(a_n)$
   2. $\exists x F(x) \iff F(a_1) \lor F(a_2) \lor F(a_3) \cdots \lor F(a_n)$
2. 量词否定等值式
   1.  $\lnot \forall x F(x) \iff \exists x \lnot F(x)$
   2.  $\lnot \exists x F(x) \iff \forall x \lnot F(x)$
3. 量词辖域收缩与扩张等值式
   1.  $\forall x (A(x) \land B) \iff \forall x A(x) \land B$
   2.  $\forall x (A(x) \lor B) \iff \forall x A(x) \lor B$
   3.  $\color{red} \forall x (A(x) \to B) \iff \exists x A(x) \to B$
       1.  前件，符号变换
   4.  $\forall x (B\to A(x)) \iff B \to \forall x A(x)$
       1.  后件，符号不变
   5.  $\exists x (A(x) \land B) \iff \exists x A(x) \land B$
   6.  $\exists x (A(x) \lor B) \iff \exists x A(x) \lor B$
   7.  $\color{red} \exists x (A(x) \to B) \iff \forall x A(x) \to B$
   8.  $\exists x (B\to A(x)) \iff B \to \exists x A(x)$
4. 量词分配等值式
   1. $\forall x (A(x) \land B(x)) \iff \forall x A(x) \land \forall x B(x)$
   2. $\exists x (A(x) \lor B(x)) \iff \exists x A(x) \lor \exists x B(x)$


#### 基本规则
1. 置换规则: 置换一阶逻辑公式中的命题公式$A$
2. 换名规则: 换名指导变元及其辖域内所有约束出现
3. 代替规则: 换名辖域内的自由出现的个体


### 前束范式

形如$\Delta x_1 \Delta x_2 \cdots \Delta x_n B$的一阶逻辑公式
- $\Delta$指$\{\forall, \exists\}$
任意一阶逻辑公式必然存在与之等值的前束范式 
### 推理理论

$A_1,A_2,A_3\cdots A_n \to B$是永真式即推理正确
记为$A_1,A_2,A_3\cdots A_n \implies B$

#### 推理定律
为永真式的蕴涵式
1. 命题逻辑推理定律的代换实例
2. 等值式
   1. 命题逻辑
   2. **量词变换等值式**
3. 其他推理定律
   1. 量词分配
      1. $\forall x (A(x) \lor B(x)) \implies \forall x A(x) \lor \forall x B(x)$
      2. $\exists x (A(x) \land B(x)) \implies \exists x A(x) \land \exists x B(x)$
   2. 量词收缩
         1. $\forall x (A(x) \to B(x)) \implies \forall x A(x) \to \forall x B(x)$
      1. $\forall x (A(x) \to B(x)) \implies \exists x A(x) \to \exists x B(x)$
#### 自然推理系统
1. 字母表
2. **合式公式**
3. 推理规则: 同命题逻辑
   
#### 新的推理规则
U-Universal E-Existential I-Instantiation G-Generalization
1. UI/$\forall -$: 全称量词消除 
   1. $\forall x A(x)$ $\therefore A(y)$
      1. $y$不在A中**约束**出现
   2. $\forall x A(x)$ $\therefore A(c)$
      1. $c$为个体常项
2. UG/$\forall +$: 全称量词引入
   1. $A(y)$ $\therefore \forall x A(x)$
   2. 对任意的$y$都有$A(y)$成立
   3. $x$不是A(y)中的约束出现
3. EI/$\exists -$: 存在量词消除
   1. $\exists x A(x)$ $\therefore A(c)$
   2. $c$为使$A(c)$为真的特定个体常项
   3. $A(x)$中没有$x$以外**其他自由出现的变项**
4. EG/$\exists +$: 存在量词引入
   1. $A(c)$ $\therefore \exists x A(x)$
   2. $x$没有在带入前出现过


#### 构造证明
引入符合推理规则的一系列一阶逻辑公式**序列**$C_1 \land C_2 \land C_3 \cdots C_l$, 其中每一项:
- 或是属于前提$\Gamma$
- 或是属于前提推理出的结论
- $C_l$和待证结论$B$等值
称公式**序列**$C_1 \land C_2 \land C_3 \cdots C_l$为$A_1,A_2,A_3\cdots A_n$推$B$的证明

### 题型
1. 根据已知等值式证明新的等值式
2. 在有限个体域下消除量词
3. 求前束范式
4. 在自然推理系统下构建（自然语言的）推理证明

# 集合论
## 集合代数

### 集合的基本概念
把一些**确定的**、**有区别的**、具象/抽象的事物汇聚在一起看作一个整体，称之为集合，事物被称之为集合的元素。

#### 表示法
- 列元素法: $S=\{1,2,3\}$
- 谓词表示法: $S=\{x|F(x)\}$
#### 特殊集合
- 常见集合: $N,Z,Q,R,C$
- 全集$E$: 针对具体问题，所有集合都是$E$的子集
- 空集$\emptyset$
  - 是任何（除了空集以外的）子集
- n元集: 集合中有n个元素


#### 关系
- 元素和集合的关系:$\in$或$\notin$
  - 元素互相不同
  - 元素无序
- $\subseteq$: 子集, $A \subseteq B \iff \forall x (x \in A \to x \in B)$
- $=$: 相等， $A = B \iff  A \subseteq B \land B \subseteq A$
- $\subset$: 真子集，$A \subset B \iff   A \subseteq B \land B \neq A$
- $\nsubseteq$: 不被包含，$A \nsubseteq B \iff \exists x (x \in A \land x \notin B)$


### 集合的运算
- 第二类运算，从左往右
  - $\cap$: 并，$A \cap B = \{x|x \in A \land x \in B\}$
  - $\cup$: 交，$A \cup B = \{x|x \in A \lor x \in B\}$
  - $-$: **相对补**，$A - B = \{x|x \in A \land x \notin B\} = A \cap \sim B$
  - $\oplus$: 对称差，$A \oplus B = (A - B) \cup (B - A) = (A \cup B) - (A \cap B)$
- 第一类运算，从右往左
  - $\sim$: 绝对补，$\sim A =  \{x|x \in E \land x \notin A\}$
  - $P(A)$: 幂集，$A$的所有子集的集合
  - 广义交: $\bigcap A = \{x| \forall z (z \in A \to x \in z)\}$
    - 对$\emptyset$无意义
  - 广义并: $\bigcup A = \{x| \exist z (z \in A \land x \in z)\}$
    -  $\bigcup \emptyset = \emptyset$

### 有穷集的计数问题
- 文氏图
  - 长方形$E$+圆形
  - 圆形默认相交
  - 列一次方程组
- 包含排斥原理
  - $|\bar A_1 \cap \bar A_2 \cap \bar A_3 \cdots \cap \bar A_n| = |E| - \sum_{i=1}^n|A_i| + \sum_{1\leq i \leq j \leq n}|A_i \cap A_j| + \cdots + (-1)^n|A_1 \cap  A_2 \cap  A_3 \cdots \cap A_n|$
  - 推论:$|A_1 \cup  A_2 \cup  A_3 \cdots \cup A_n| =  \sum_{i=1}^n|A_i| - \sum_{1\leq i \leq j \leq n}|A_i \cap A_j| + \cdots + (-1)^{n-1}|A_1 \cap  A_2 \cap  A_3 \cdots \cap A_n|$
- 抽屉原理（鸽巢原理）
  - n个元素，n-1个集合，必有一个集合有至少2个元素
### 集合恒等式
#### 主要算律
1. **幂等律**: $A\cup A = A, A\cap A = A$
   1. 幂归零: $A \oplus A = \emptyset$
2. 交换律: $A\cup B = B \cup A, A\cap B = B \cap A, A \oplus B = B \oplus A$
3. 结合律: $(A\cup B) \cup C = A\cup (B \cup C), (A\cap B) \cap C = A\cap (B \cap C), (A\oplus B) \oplus C = A\oplus (B \oplus C)$
4. 分配律: $(A \cup B) \cap C = (A \cap C) \cup (B \cap C), (A \cap B) \cup C = (A \cup C) \cap (B \cup C), (A \cap B) \oplus C = (A \oplus C) \cap (B \oplus C)$
5. 零律: $A \cap \emptyset = \emptyset,$ $A \cap E = E$, $A \oplus \emptyset = \emptyset$
6. 同一律: $A \cup \emptyset = A$,$A \cup E = A$, 
7. 矛盾律: $A \cap \sim A = \emptyset$
8. 排中律: $A \cup \sim A = E$
9.  **吸收律**: $A \cup (A \cap B) = A, A \cap (A \cup B) = A$
10. 德摩根律: $(A-B) \cup (A-C) = A - (B\cap C)$,$(A-B) \cap (A-C) = A - (B\cup C)$,$\sim(B\cap C) = (\sim B \cup \sim C),\sim(B\cup C) = (\sim B \cap \sim C)$
11. 双重否定律: $\sim (\sim A)=A$


#### 对偶原理
对偶式同真假
- $\subseteq$对应$\supseteq$
- $\emptyset$对应$E$ 
- $\cap$对应$\cap$

#### 证明
- 等值演算法
  - $A = B$: $\forall x, x \in A \iff \cdots \iff x \in B$
    - 或$A \subseteq B \land B \subseteq A$
  - $A \subseteq B$: $\forall x, x \in A \implies \cdots \implies x \in B$
- 集合演算法
  - $A = B$: $A = \cdots = B$
  - $A \subseteq B$: $A \subseteq \cdots \subseteq B$

#### 重要结果
1. 子集恒成立
   1. 化简: $A \cap B \subseteq A, A \cap B \subseteq B$
   2. 附加: $A \subseteq A \cup B, B \subseteq A \cup B$
   3. 相对补：$A - B \subseteq A, A - B \subseteq B$
2. 相等的四种写法(互相等值)
   1. $A = B$
   2. $A \cup B = B$
   3. $A \cap B = A$
   4. $A - B =\emptyset$
3. 对称差证相等: $A\oplus B＝A\oplus C \implies B＝C$


### 集合论的悖论与公理系统

### 题型
1. 集合计算题
2. 集合的计算性质
3. 判断隶属关系
4. 判断/证明集合间包含/相等
5. **有穷集合**的计数问题

##  关系


### 有序对与笛卡儿积
- 序偶: 有序二元组
  - $<x,y> = <u,v>\iff x= u \land y =v$
- 笛卡尔积: $A \times B=\{<x,y>|x \in A \land y \in B\}$
- $A \subseteq C \land B \subseteq D \implies A \times B \subseteq C \times D$

### 二元关系
- A到B的关系$R$: $A\times B$的子集
  - 包括$\emptyset$
- A上关系: $A=B$
- $xRy \iff <x,y> \in R$
  - $x \not{R} y \iff <x,y> \notin R$

#### 常用二元关系
- $E_A$: 全域关系$\{<x,y>|x,y\in A\}$
- $I_A$: **恒等**关系$\{<x,x>|x\in A\}$
- $\emptyset$: 空关系
- $L_A$: 小于等于关系
- $D_A$: 整除关系
- $R_{\subseteq}$: 包含关系

#### 表示法
- 集合表达式
- 关系矩阵
- 关系图
### 关系的运算
优先于集合运算
- $R^{-1}$: 逆，$\{<y,x>|<x,y>\in R\}$
- 域
  - $dom R$: 定义域，$\{x|\exists y( <x,y> \in R)\}$
  - $ran R$: 值域，$\{x|\exists x( <x,y> \in R)\}$
  - $fld R = dom R \cup ran R$
- $F^{\circ}G$: 复合，$\{<x,y>|\exists t (<x,t>\in F \land <t,y>\in G)\}$
- 限制和像
  - $R \uparrow A = \{<x,y>|xRy \land x \in A\}$
  - $R[A] = ran(R \uparrow A)$
- 幂运算
  - $R^0 = I_A$
  - $R^{m+1} = R^{m\circ}R$


#### 运算的性质
- 逆
  - $(F^{-1})^{-1} = F$
  - $dom F^{-1} = ran F$,$ran F^{-1} = dom F$
- 复合
  - 结合律: $(F^{\circ}G)^{\circ}H = F^{\circ}(G^{\circ}H)$
  - $(F^{\circ}G)^{-1}=G^{-1\circ}F^{-1}$
  - 同一律: $R^{\circ}I_A = I_A^{\circ}R = R$
  - 分配律
    - $F^{\circ}(G \cup H) = F^{\circ} G \cup F^{\circ} H$
    - $(G \cup H) ^{\circ} F = G^{\circ} F \cup H^{\circ} F$
    - $F^{\circ}(G \cap H) {\color{red}\subseteq}  F^{\circ} G \cap F^{\circ} H$
    - $(G \cap H) ^{\circ} F {\color{red}\subseteq} G^{\circ} F \cap H^{\circ} F$
- 限制和像的分配律
  - $R \uparrow (A \cup B) = R \uparrow A \cap R \uparrow B$
  - $ran[A \cup B] = ran[A] \cup ran[B]$
  - $R \uparrow (A \cap B)  {\color{red}\subseteq} R \uparrow A \cap R \uparrow B$
  - $ran[A \cap B] {\color{red}\subseteq} ran[A] \cap ran[B]$
- 幂运算
  - 周期性: $\exists s,t\in N, s<t,  R^s=R^t$
    - $\forall k \in N, R^{s+k}=R^{t+k}$
    - $\forall k \in N, R^{s+kp+i}=R^{t+kp+i}, p = t-s$
    - $\forall q \in N, R^q \in \{R^0, R^1, R^2, \cdots, R^{t-1}\}$
  - $R^{m\circ}R^n = R^{m+n}$ 
  - $(R^{m})^{n} = R^{mn}$ 

### 关系的性质
- 自反性: $\forall x (x \in A \to {<x,x> \in R}) \iff I_A \subseteq R$
- 反自反性: $\forall x (x \in A \to {<x,x> \notin R}) \iff R \cap I_A = \emptyset$
- 对称性: $\forall x\forall y (x,y \in A \land <x,y> \in R\to {<y,x> \in R}) \iff R = R^{-1}$
- 反对称性: $\forall x\forall y (x,y \in A \land <x,y> \in R \land <y,x> \in R \to {x=y}) \iff R \cap R^{-1} \subseteq I_A$
- 传递性: $\forall x\forall y \forall z(x,y,z \in A \land <x,y> \in R \land <x,y> \in R \to {<x,z> \in R}) \iff R^{2} {\color{red}\subseteq} R$

#### 性质与运算之间的联系
- 逆: 性质全保留
- 交: 性质全保留
- 并: 可能失去传递性和反自反性
- 相对补: 可能失去对称性和传递性
- 复合: 只保留自反性

### 关系的闭包
- 自反闭包$r(R)$
- 对称闭包$s(R)$
- 传递闭包$t(R)$
  
对于闭包$R'$
1. 是具有这个性质的二元关系
2. $R \subseteq R'$
3. $\forall R''(R'' \in A \times A \land R \subseteq R'')$, $R' \subseteq R''$


#### 闭包求法
1. 集合表达式
   1. $r(R) = R \cup I_A$
   2. $s(R) = R \cap R^{-1}$
   3. $t(R) = R \cup R^2 \cup R^3 \cup \cdots$
      1. 可以为有限项
2. 关系矩阵
   1. $M_r = M + I$
   2. $M_s = M + M^{T}$
   3. $M_t = M + M^2 + M^3 + \cdots$
3. 关系图
   1. 加环
   2. 加反向边
   3. 加步长为$1,2,3,\cdots,n$的边
4. Warshell算法求传递闭包
   1. $M_{k+1}[i,j]=M_k[i,j]+M_k[i,k+1]*M_k[k+1,j]$
   2. 已有的边+以该点为中间节点的边
   3. 逐步扩大包含的节点

#### 闭包的性质
- 判断$R$性质
  - $R$自反$\iff R=r(R)$
  - $R$对称$\iff R=s(R)$
  - $R$传递$\iff R=t(R)$
- 包含关系传递$R_1 \subseteq R_2$
  - $r(R_1)\subseteq r(R_2)$
  - $s(R_1)\subseteq s(R_2)$
  - $t(R_1)\subseteq t(R_2)$
- 性质在闭包后的保持
  - 除了传递性在$s(R)$以外都行
  - tsr(R)安全顺序

### 等价关系与划分
- 等价关系$\sim$: 自反的，对称的，传递的非空关系
  - 注意$t$在$s$前面的闭包运算才是等价关系

#### 等价关系性质
等价类: $[x]_R = [x] = \bar{x} = \{y|{\color{red}y\in A} \land xRy\}$

$\forall x,y \in A$
1. 等价类$[x]$为$A$的非空子集
2. $xRy \implies [x]=[y]$
3. $x\not{R}y \implies [x] \cap  [y] = \emptyset$
4. $\cup{[x]|x\in A} = A$ 广义并

#### 商集与划分
- 商集: $A/R = {[x]|x\in A}$
- 划分$\pi \subseteq P(A)$
  - $\emptyset \notin \pi$
  - $\color{red} \forall x \forall y (x,y \in \pi \land x \neq y \to x \cap y = \emptyset)$
  - $\cup \pi = A$
  - 和等价类一一对应

### 偏序关系
- 偏序关系$\le$: 自反的，反对称的，传递的非空关系
- $\forall x \forall y, x<y \iff x \le y \land x \neq y$
- $x,y$可比$\iff x \le y \lor y \le x$
  - $E$: 全序关系，所有元素之间都可比
- 偏序集$<A,\le>$
#### 盖住与哈斯图
- y盖住x: $x < y \land \lnot \exists z \in A(x < z<y )$
- 哈斯图
  - 一个元素一个圈
  - x小于y，x在y下方
  - 覆盖的用线段连接

#### 特殊元素
$B\subseteq A, \le$ 为$A$上偏序关系
- 极大（小）元: $\{y|y\in B, \forall x(x \in B \land x \ge{\color{blue}(\le)} y\to x=y)\}$
- 最大（小）元: $\{y|y\in B, \forall x(x \in B \land ) \to x \le{\color{blue}(\ge)} y\}$
- 上（下）界: $\{y|y\in A, \forall x(x \in B \to x \le{\color{blue}(\ge)} y)\}$
- 上（下）确界: 上界的最小元（下界的最大元）
- 唯一: 最大（小）元，上（下）确界
- 一定存在: 极大（小）元

### 题型
1. 求有序对和笛卡尔积
2. 表示关系
3. 关系的运算
4. 求闭包
5. 判断/证明关系的性质
6. 证明涉及关系的恒等/包含
7. 等价关系
   1. 商集，划分，等价类的对应
8. 偏序关系
   1. 画哈斯图
   2. 求特殊元素

## 函数
### 函数(映射)定义与性质
#### 函数的定义
$\forall x \in {\color{red} dom F}, \exists唯一y \in {\color{red} ran F}使得<x,y> \in F$
- $y = f(x)$为$x$在$f$上的值
- $F = G \iff F \subseteq G \land G \subseteq F$
  - $dom F = dom G$
  - $\forall x \in { dom F}, F(x) = G(x)$
- $f:A \mapsto B$: $f$为$A$到$B$的函数 $dom f = A \land ran f \subseteq B$
- $B^A$: $B$上$A$ $\{f|f:A \mapsto B\}$
- 像
  - $f(A_1) = \{f(x)|x\in A_1\}, A_1\subseteq A = dom f$: $A_1$在$f$下的像
    - 函数的像: $f(A),A_1 = A$ 
  - 完全原像: $f^{-1}(B_1) = \{x|x \in A \land f(x)\in B_1\},B_1\subseteq B = ran f$

#### 函数的性质
$f:A \mapsto B, m = |A|, n = |B|$
- 满射：$ran f = B$
  - $m \ge n$
- 单射：$\forall y \in ran f$，存在唯一的$x \in dom f$， 使得$y = f(x)$
  - $m \le n$
- 双射：满射且单射
  - $m = n$
#### 常用的函数
- 常函数: $f(x) = c, c$为常数
- 恒等函数: $I_A(x)=x$
- 特征函数: $\{0,1\}^A$的子集
- 自然划分: $g: A \mapsto A/R, g(x) = [x]_Rs$
- 隶属函数: $f(x) \in [0,1]$
  - 模糊子集即存在对应隶属函数的一个子集
- 递增(递减): 对于偏序关系$\le$，$x_1 < x_2$有$f(x_1) \le{\color{blue}(\ge)} f(x_2)$
  - 严格：$f(x_1) <{\color{blue}(>)} f(x_2)$
- 计数函数
  - $O(n)$: $\exists c, n_0, n>n_0时0 < f(n) < cO(n)$
  - $\Omega(n)$: $\exists c, n_0, n>n_0时0 <  c\Omega (n) < f(n)$
  - $\Theta(n)$: $O(n) = \Omega(n)$
### 函数的运算

#### 复合
- $F^{\circ}G$
  - $dom F^{\circ}G = {x|x\in dom F \land F(x) \in dom G}$
  - $\forall x \in dom F^{\circ}G,F^{\circ}G(x) = G(F(x))$
- 结合律
  - $(F^{\circ}G)^{\circ}H = F^{\circ}(G^{\circ}H)$
  - $f:A \mapsto B, g:B \mapsto C \implies f^{\circ}g :A \mapsto C$
- 性质保持：如果复合存在，且两个函数都具有某个性质（单射、满射、双射），则复合后性质仍然保持
- 同一律：$f^{\circ}I_A = I_A^{\circ}f = f$
#### 反函数
- 函数的逆关系不一定是函数
- $f:A \mapsto B \nRightarrow dom {f^{-1}} = B$
- 双射函数必存在反函数，且反函数也为双射函数
- $f^{\circ} f^{-1}= I_A = f^{-1\circ} f$
### 双射函数与集合的基数
#### 集合的等势
- $A\approx B$: 存在双射函数$f:A \mapsto B$
  - 等价关系
  - $A\approx A$
  - $A\approx B, \implies B \approx A$
  - $A\approx B, B\approx C \implies A \approx C$
- 康托定理
  - $N \not{\approx} R$
  - $P \not{\approx} P(A)$
    - 构造$P(A) \supseteq B = \{x| x \in A \land x \notin g(x)\}$
- $N \approx Z \approx Q \approx N \times N$
- $R \approx [a,b] \approx (a,b) \approx \{0,1\}^N \approx P(N)$
- $\{0,1\}^A \approx P(A)$
#### 集合的优势
- $A \preceq \cdot B$: 存在单射函数$f:A \mapsto B$
- $A \prec \cdot B$: $A \preceq \cdot B \land A \not{\approx} B$
- 伯恩斯坦定理
  - $A \preceq \cdot A$
  - $A \preceq \cdot B, B\preceq \cdot C \implies A \preceq \cdot C$
  - $A \preceq \cdot B, B\preceq \cdot A \implies A \approx C$
#### 集合的基数
- $a^+$: 后继 $\{a, \{a\}\}$
- 自然数的集合定义
  - $0=\emptyset$
  - $1=\{\emptyset\} = {0}$
  - $2=\{\emptyset, \{\emptyset\}, \{\{\emptyset\}\}\}= \{0,1\}$
  - $n=\{0,1,2,\cdots,n-1\}$
- 自然数的性质
  - $n \approx n$
  - $m \subset n \implies m \not{\approx} n$
  - $m\in n \implies m \subseteq n$
  - 三歧性:$m\approx n, m \in n, n \in m$
- 有穷集: **当且仅当与某个自然数等势**
  - 以外都是无穷集
- $card A$基数
  - 有穷集为等势的自然数
  - $card \mathbb{N} = \aleph_0$
  - $card \mathbb{R} = \aleph$
- 基数性质
  - $card A = card B \iff A\approx B$
  - $card A \le card B \iff A\preceq \cdot B$
  - $card A < card B \iff A\preceq \cdot B \land A \not{\approx} B$
- 可数集:$card A < \aleph_0$
  - 可数个可数集的并是可数集
  - 可数集的子集也是可数集
  - 两个可数集的笛卡尔积也是可数集
