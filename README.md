# 翻译参考材料
- [ISTQB<sup>®</sup>高级模拟题文档 - CSTQB](https://www.cstqb.cn/AL%20Simulation.html)
- [ISTQB<sup>®</sup>CTAL 2012 Technical Test Analyst Sample Exam Questions_v1_01 (English).pdf](https://www.cstqb.cn/userfiles/files/ISTQB%E9%AB%98%E7%BA%A7%E6%A8%A1%E6%8B%9F%E9%A2%98%E6%96%87%E6%A1%A3/ISTQB%C2%AECTAL%202012%20Technical%20Test%20Analyst%20Sample%20Exam%20Questions_v1_01%20(English).pdf)
- [ISTQB<sup>®</sup>CTAL 2012 Technical Test Analyst Sample Exam-Answer and Justification_v1_02 (English).pdf](https://www.cstqb.cn/userfiles/files/ISTQB%E9%AB%98%E7%BA%A7%E6%A8%A1%E6%8B%9F%E9%A2%98%E6%96%87%E6%A1%A3/ISTQB%C2%AECTAL%202012%20Technical%20Test%20Analyst%20Sample%20Exam-Answer%20and%20Justification_v1_02%20(English).pdf)
- [ISTQB<sup>®</sup>2012高级-测试分析师 模拟题v1_02版（中文）.pdf](https://www.cstqb.cn/userfiles/files/ISTQB%E9%AB%98%E7%BA%A7%E6%A8%A1%E6%8B%9F%E9%A2%98%E6%96%87%E6%A1%A3/ISTQB%C2%AE2012%E9%AB%98%E7%BA%A7-%E6%B5%8B%E8%AF%95%E5%88%86%E6%9E%90%E5%B8%88%20%E6%A8%A1%E6%8B%9F%E9%A2%98v1_02%E7%89%88%EF%BC%88%E4%B8%AD%E6%96%87%EF%BC%89.pdf)
- [ISTQB<sup>®</sup> 高级-技术测试分析师大纲2012版（中文版）.pdf](https://www.cstqb.cn/userfiles/files/ISTQB%E9%AB%98%E7%BA%A7%E5%A4%A7%E7%BA%B2%E6%96%87%E6%A1%A3/ISTQB%C2%AE%20%E9%AB%98%E7%BA%A7-%E6%8A%80%E6%9C%AF%E6%B5%8B%E8%AF%95%E5%88%86%E6%9E%90%E5%B8%88%E5%A4%A7%E7%BA%B22012%E7%89%88%EF%BC%88%E4%B8%AD%E6%96%87%E7%89%88%EF%BC%89.pdf)
- [ISTQB<sup>®</sup> Advanced Level Syllabus-Technical Test Analyst-2012Version(English).pdf](https://www.cstqb.cn/userfiles/files/ISTQB%E9%AB%98%E7%BA%A7%E5%A4%A7%E7%BA%B2%E6%96%87%E6%A1%A3/ISTQB%C2%AE%20Advanced%20Level%20Syllabus-Technical%20Test%20Analyst-2012Version(English).pdf)

# ISTQB TTA模拟题及答案（中文版）

由于时间仓促和译者水平有限，许多不足之处敬请各位谅解。使用中发现问题可以直接提Issue或者Pull Request。

### 1. CTAL-TTA_LO-1.3.1

> TTA-1.3.1 (K2) 总结技术测试分析师需要考虑的、典型的风险因素。

**问题：**

下面哪些是测试技术分析师通常需要考虑的风险因素？请选择**三个**选项。

**答案选项：**

- A. 工具的复杂性与可用性等技术因素；
- B. 项目干系人之间的潜在冲突；
- C. 大量与软件可靠性相关的缺陷；
- D. 大量与之前版本可用性相关的缺陷；
- E. 来自遗留系统的用于验证计算精度的文档是否可用；
- F. 项目的预算限制；
- G. 业务用例的高变化率。

**解释：**

- A. 正确：根据大纲描述；
- B. 正确：根据大纲描述；
- C. 正确：根据大纲描述；
- D. 不正确：属于TA的职责；
- E. 不正确：属于TA的职责；
- F. 不正确：属于TM的职责；
- G. 不正确：业务用例的高变化率影响功能测试。

分值：1分

### 2. CTAL-TTA_LO-1.x.1

> TTA-1.x.1 (K2) 总结在基于风险的测试方法中，技术测试分析师在测试计划和测试执行过程中的相关活动。

**问题：**

在参与风险分析时，技术测试分析师最可能与下面哪一类人群工作关系密切？

**答案选项：**

- A. 开发人员
- B. 用户
- C. 业务分析师
- D. 项目赞助商

**解释：**

- A. 正确：根据大纲描述。TTA最可能与项目上的技术人员（包括开发人员）一起工作；
- B. 不正确：属于TA的职责；
- C. 不正确：属于TA的职责；
- D. 不正确：属于TA的职责。

分值：1分

### 3. CTAL-TTA_LO-2.2.1

> TTA-2.2.1 (K2) 理解如何实现条件覆盖以及为何判定覆盖比条件覆盖更严谨。

**问题：**

下面关于条件覆盖的陈述，哪句是正确的？

**答案选项：**

- A. 条件覆盖只需要设置每个原子条件的两个真值（真和假），而不需要评估整个判定的真/假结果；
- B. 条件覆盖既需要设置每个原子条件的两个真值（真和假），同时也需要评估整个判定的真/假结果；
- C. 条件覆盖只需要评估整个判定的真/假结果，不需要关心每个原子条件的真值；
- D. 条件覆盖比判定覆盖具有全面的覆盖率。

**解释：**

- A. 正确：根据大纲描述。条件测试只是对原子条件进行测试，并不考虑原子条件的组合结果；
- B. 不正确：整个判定的真/假结果不需要全部被测试；
- C. 不正确：被评估的是原子条件，而不是整个判定；
- D. 不正确：满足条件覆盖的测试用例并不一定会满足判定覆盖。

分值：1分

### 4. CTAL-TTA_LO-2.3.1

> TTA-2.3.1 (K3) 应用判定条件测试的测试设计技术设计测试用例以达到规定的覆盖率

**问题：**

您正在测试一个用于十字路口交通管制的摄像抓拍系统。如果以下两个条件同时为真，则进行一次抓拍：红灯(RED)，并且汽车前轮越过十字路口界线(WHEELS)。

考虑下面这些值的组合：
1. RED + WHEELS
2. RED + not WHEELS
3. not RED + WHEELS
4. not RED + not WHEELS

假设代码逻辑如下：

```
if RED and WHEELS then
  进行抓拍
Else
  不进行抓拍
```

根据以上信息，下面哪个组合可以用最少的测试来达到100%的判定条件覆盖率？

**答案选项：**
- A. 1，4；
- B. 1，2或1，3；
- C. 1，2，3，4；
- D. 2，3。

**解释:**
- A. 正确：根据大纲描述。这两组测试既对每个原子条件值进行了测试（条件覆盖），也对判定结果值进行了测试（判定覆盖）；
- B. 不正确：这两组测试都是只对其中一个原子条件进行了测试而遗漏了另外一个原子条件；
- C. 不正确：这组需要的测试数量并不是最少的；
- D. 不正确：没有对判定结果值为真的情况进行测试。

分值：1分

### 5. CTAL-TTA_LO-2.4.1

> TTA-2.4.1 (K3) 应用改进的条件/判定覆盖(MC/DC)测试的测试设计技术设计测试用例以达到规定的覆盖率。

**问题：**

您正在测试一个用于十字路口交通管制的摄像抓拍系统。已知如果以下三个条件之一为真，则进行一次抓拍：红灯(RED)，或者汽车超速(SPEED)，或者汽车前轮越过十字路口界线(WHEELS)。

考虑下面这些值的组合：
1. RED + SPEED + WHEELS
2. RED + SPEED + not WHEELS
3. RED + not SPEED + WHEELS
4. RED + not SPEED + not WHEELS
5. not RED + SPEED + WHEELS
6. not RED + SPEED + not WHEELS
7. not RED + not SPEED + WHEELS
8. not RED + not SPEED + not WHEELS

假设代码逻辑如下：

```
if ((RED or SPEED) and WHEELS) then
  进行抓拍
Else
  不进行抓拍
```

根据以上信息，下面哪个组合可以用最少的测试来达到100%的改进的条件/判定测试(MC/DC)覆盖率？

**答案选项：**

- A. 3，4，5，7；
- B. 1，3，8；
- C. 2，8；
- D. 1，5，7，8。

**解释：**

- A. 正确：该组合进行了如下测试：
  - (T of F) + T
  - (T or F) + F
  - (F or T) + T
  - (F or F) + T

  从而用最少的测试，既测试到了原子条件的所有取值，也测试到了所有的判定结果；
- B. 不正确：覆盖了所有判定结果，但是没有覆盖到单个原子条件改变判定结果的情况；
- C. 不正确：没有完全覆盖到单个原子条件改变判定结果的情况；
- D. 不正确：没有完全覆盖到单个原子条件改变判定结果的情况；

分值：1分

### 6. CTAL-TTA_LO-2.5.1

> TTA-2.5.1 (K3) 应用复合条件测试的测试设计技术设计测试用例以达到规定的覆盖率

**问题：**

您正在测试一个用于十字路口交通管制的摄像抓拍系统。需求如下：红灯(RED)，或者汽车超速(SPEED)，并且汽车前轮越过十字路口界线(WHEELS)，则进行一次抓拍。

考虑下面这些值的组合：
1. RED + SPEED + WHEELS
2. RED + SPEED + not WHEELS
3. RED + not SPEED + WHEELS
4. RED + not SPEED + not WHEELS
5. not RED + SPEED + WHEELS
6. not RED + SPEED + not WHEELS
7. not RED + not SPEED + WHEELS
8. not RED + not SPEED + not WHEELS

假设代码逻辑如下：

```
if ((RED or SPEED) and WHEELS) then
  进行抓拍
Else
  不进行抓拍
```

根据以上信息，下面哪个组合可以用最少的测试来达到100%的复合条件测试覆盖率？

**答案选项**

- A. 所有组合
- B. 3，4，5，7；
- C. 1，3，8；
- D. 1，5，7，8。

**解释：**

- A. 正确：复合条件测试需要对整个真值表（所有真与假的组合）进行测试。这需要本题中所有的组合都被测试到。
- B、C、D：不正确。

### 7. CTAL-TTA_LO-2.6.1

> TTA-2.6.1 (K3) 应用路径测试的测试设计技术来设计测试用例。

**问题：**

您正在测试一个用于十字路口交通管制的摄像抓拍系统。需求如下：红灯(RED)，或者汽车超速(SPEED)，并且汽车前轮越过十字路口界线(WHEELS)，则进行一次抓拍。

考虑下面这些值的组合：
1. RED + SPEED + WHEELS
2. RED + SPEED + not WHEELS
3. RED + not SPEED + WHEELS
4. RED + not SPEED + not WHEELS
5. not RED + SPEED + WHEELS
6. not RED + SPEED + not WHEELS
7. not RED + not SPEED + WHEELS
8. not RED + not SPEED + not WHEELS

假设代码逻辑如下：

```
if ((RED or SPEED) and WHEELS) then
  进行抓拍
Else
  不进行抓拍
```

根据以上信息，下面哪个组合可以用最少的测试来达到100%的路径覆盖率？

**答案选项：**

- A. 2，3；
- B. 3，4，5，7；
- C. 1，3，8；
- D. 1。

**解释：**

- A. 正确：路径测试需要测试语句判定结果为真和为假的两种情况。第2组结果为假，第3组结果为真；
- B. 不正确：第3组和第5组路径相同；
- C. 不正确：第1组和第3组路径相同；
- D. 不正确：只测试了为真的情况，没有测试为假的情况。

分值：2分

### 8. CTAL-TTA_LO-2.7.1

> TTA-2.7.1 (K2) 理解API测试的适用性以及它所能发现的各种缺陷。

**问题：**

API测试的目标是发现下面哪些缺陷？请选择**三个**选项。

**答案选项：**

- A. 数据处理错误；
- B. 时序问题；
- C. 交易的丢失；
- D. 与代码标准的不一致；
- E. 可用性不足；
- F. 安装缺陷；
- G. GUI故障。

**解释：**

- A. 正确：此条已在大纲“缺陷类型”中列出；
- B. 正确：此条已在大纲“缺陷类型”中列出；
- C. 正确：此条已在大纲“缺陷类型”中列出；
- D. 不正确：这是可维护性测试的目标；
- E. 不正确：此条未在大纲“缺陷类型”中列出；
- F. 不正确：此条未在大纲“缺陷类型”中列出；
- G. 不正确：此条未在大纲“缺陷类型”中列出。

分值：1

### 9. CTAL-TTA_LO-2.8.1

> TTA-2.8.1 (K4) 基于特定的项目状况选择一种适合的基于结构的测试技术。

**问题：**

您是一名技术测试分析师，您正在测试一款将被用于新建成的能够容纳十万名观众的国家体育场的软件，该软件的作用是控制体育场屋盖的移动。一项失效分析表明，如果软件系统失效，将可能导致屋盖碎裂并砸落到观众身上。为此政府部门要求，对这个软件进行的测试必须要**超过**根据通常相关规定标准所需进行的测试。

在测试这款控制体育场屋盖移动的软件时，您应该考虑使测试达到下面哪种测试覆盖级别？

**答案选项：**
- A. 复合条件覆盖
- B. 分支覆盖 + 改进的条件/判定(MC/DC)覆盖
- C. 分支覆盖 + 语句覆盖
- D. 改进的条件/判定(MC/DC)覆盖

**解释：**
- A. 正确：本题中，如软件失效，可能会造成几千名观众受伤或死亡的严重后果。对于最高关键等级的软件，在大纲提到的两种示例标准 *（译者注：DO-178B或欧洲标准ED-12B、IEC-61508，见中文版大纲16-17页）* 中，都要求达到MC/DC覆盖。而复合条件测试提供了比MC/DC更高的覆盖等级，满足本场景中“超过”MC/DC（根据通常相关规定标准所需进行的测试）的要求，因而为正确选项；
- B. 不正确：MC/DC覆盖（见选项D）包括了分支覆盖；
- C. 不正确：分支覆盖包含了语句覆盖。同时，分支覆盖不如MC/DC和复合条件覆盖更严格；
- D. 不正确：对于最高关键等级的软件，在大纲提到的两种示例标准中，都要求达到MC/DC覆盖。但是在本场景中，要求的测试覆盖等级需要超过MC/DC，因此本选项不正确。

分值：2分

### 10. CTAL-TTA_LO-3.2.1

> TTA-3.2.1 (K3) 运用控制流分析来检测代码是否存在控制流异常。

**问题：**

下面是TRICKY程序的伪代码：
```
0   program TRICKY
1   var1, var2, var3 : integer
2   begin
3       read(var2)
4       read(var1)
5       while var2 < 10 loop
6           var3 = var2 + var1
7           var2 = 4
8           var1 = var2 + 1
9           print(var3)
10          if var1 = 5 then
11              pring(var1)
12          else
13              print(var1+1)
14          endif
15          var2 = var2 + 1
16      endloop
17      write("哇，这也太复杂了吧！")
18      write("但是答案是...")
19      write(var2 + var1)
20  end program TRICKY
```

下面关于TRICKY程序的陈述中，哪句最正确地描述了代码中存在的控制流异常？

**答案选项：**

- A. TRICKY程序中包含不可到达语句和一个无限循环
- B. TRICKY程序中不包含控制流异常
- C. TRICKY程序中包含不可到达语句
- D. TRICKY程序中包含一个有多个入口的循环体

**解释：**

- A. 正确：第10行代码的判断结果始终为`true`，因为`var1`在第10行的值始终为`5`，因此第13行代码不可到达。第5行的循环只有当`var2`大于等于`10`的时候才会离开循环，但是每次经过第7行代码时，`var2`的值都会被重新设置为`4`，只是每次循环到第15行代码的时候才增加了`1`，因此`var2`的值最多只能到达`5`；
- B、C、D：不正确。

分值：2分

### 11. CTAL-TTA_LO-3.2.2

> TTA-3.2.2 (K3) 运用数据流分析来检测代码是否存在数据流异常

**问题：**

下面是用于计算并打印销售佣金的程序的伪代码：

```
0   program Calculate Commission
1   total, number : integer
2   commission_hi, commission_lo : real
3   begin
4       read(number)
5       while number ≠ -1 loop
6           total = total + number
7           read(number)
8       endloop
9       if toal > 1000 then
10          commission_hi = 100 + 0.2 * (total - 1000)
11      else
12          commission_lo = 0.15 * total
13      endif
14      write("销售佣金为：")
15      write(commission_hi)
16  end program Calculate Commission
```

下面哪个选项正确列出了计算佣金程序中存在的数据流异常？

**答案选项：**

- A. total: 第6行; commission_lo: 第12行; commission_hi: 第15行；
- B. commission_hi: 第10行; commission_lo: 第6行；
- C. number: 第5行; number: 第6行
- D. total: 第6行; commission_hi: 第10行; commission_lo: 第12行

**解释：**
```
0   program Calculate Commission
1   total, number : integer
2   commission_hi, commission_lo : real
3   begin
4       read(number)                                        number(d)
5       while number ≠ -1 loop                              number(u)
6           total = total + number                          total(u,d); number(u)
7           read(number)                                    number(d)
8       endloop
9       if toal > 1000 then                                 total(u)
10          commission_hi = 100 + 0.2 * (total - 1000)      commission_hi(d)
11      else
12          commission_lo = 0.15 * total                    commission_lo(d); total(u)
13      endif
14      write("销售佣金为：")
15      write(commission_hi)                                commission_hi(u)
16  end program Calculate Commission
```
- A. 正确：控制流异常如下：
    - total：在第6行被使用，但使用前未被定义；
    - commission_lo：在第12行被定义，但之后未被使用；
    - commission_hi：在第15行被使用，但是如果程序走的是第12行的分支而不是第10行，则使用前未被定义。
- B、C、D：不正确。

分值：2分

### 12. CTAL-TTA_LO-3.2.3

> TTA-3.2.3 (K3) 提出运用静态分析的方法来提高代码的维护性

**问题：**

现有W、X、Y、Z四个系统的典型系统度量值如下表所示：

**系统** | **W** | **X** | **Y** | **Z**
---|---|---|---|---
**圈复杂度(CC)**| 23 | 8 | 12 | 7
**内聚度(CH)** | 高 | 中 | 低 | 高
**耦合度(CP)** | 低 | 高 | 中 | 中
**有注释的代码(CO)** | 60% | 10% | 45% | 8%
**重复的代码实例(RE)** | 9 | 2 | 3 | 12

通过将静态分析的结果应用于各个组件，可以使用预算来提高每个系统中代码的可维护性。如果每个系统只有两个度量值可以得到预算的支持，下面哪个选项**最好地**应用了静态分析的结果？

**答案选项：**

- A. W – CC, RE; X – CP, CO; Y – CC, CH; Z – CO, RE；
- B. W – CO, RE; X – CC, CH; Y – CP, CO; Z – CC, RE；
- C. W – CC, CP; X – CH, CO; Y – CC, CH; Z – CO, RE；
- D. W – CH, CO; X – CC, RE; Y – CP, RE; Z – CC, CH。

**解释：**

- A. 正确：
    - 圈复杂度(CC)如果为10或者更高，则意味着需要被解决；
    - 内聚度(CH)如果偏低，则意味着需要被解决；
    - 耦合度(CP)如果偏高，则意味着需要被解决；
    - 有注释的代码(CO)如果为10%或者更低，则意味着需要被解决；
    - 重复的代码实例(RE)如果为9个或者更多，则意味着需要被解决。
- B、C、D：不如选项A更正确。

分值：3分

### 13. CTAL-TTA_LO-3.2.4

> TTA-3.2.4 (K2) 解释调用图在建立集成测试策略中的作用。

**问题：**

下面哪个选项是在确定集成测试需求时运用调用图的一种方式？

**答案选项：**

- A. 确定在软件中有多少点（接口）在调用模块或系统；
- B. 确定在软件中有多少点（接口）在调用函数或方法；
- C. 为进行性能分析而区分有条件调用和无条件调用；
- D. 检测有内存泄漏可能的目标区域。

**解释：**

- A. 正确：根据大纲描述；
- B. 不正确：根据大纲描述，这种对调用图的使用方法只在组件/单元测试中使用，而不在集成测试中使用；
- C. 不正确：区分有条件调用与无条件调用确实可以用于集成，但是将它们用于性能分析则不属于集成的范畴；
- D. 不正确：调用图无法检测内存泄漏或者有内存泄漏可能的区域。

分值：1分

### 14. CTAL-TTA_LO-3.3.1

> TTA-3.3.1 (K3) 列举运用动态分析所能达到的目标

**问题：**

您是一名技术测试分析师，您所在的项目组正在开发一款全新的救护车调度系统(ADS)。ADS能够在以下方面辅助接线员的工作：接听事故电话、识别可用的救护车、调动救护车来处理事故。您知道ADS的设计采用了面向对象的方法，并使用了一款具有自动垃圾回收功能的语言来实现。在系统和验收测试期间，测试人员发现虽然系统通常情况下都可以正确运行，但是运行速度相当缓慢，并且偶尔也会“崩溃”。随后进行了一些（简短的）调查，但尚无定论。

下面哪项陈述能够最好地说明在此情况下应当采用动态分析？

**答案选项：**

- A. 动态分析能够识别由野指针造成的内存访问冲突引起的偶尔“崩溃”；
- B. 动态分析可用于测量各种功能的响应时间，以便随后进行系统调优；
- C. 动态分析可用于生成系统的调用图，从而有针对性地增强性能；
- D. 动态分析可用于确定造成“崩溃”的缺陷是否是由于程序员未能释放分配的内存而引入的。

**解释：**

- A. 正确：动态分析能够识别由野指针造成的内存访问冲突，这可能是造成偶尔“崩溃”的原因；
- B. 不正确：动态分析通常不用于测量响应时间（测量响应时间需要仪器，因而不切实际），而是提供较低级别的性能指标——这些指标可用于性能调优；
- C. 不正确：调用图通常由静态分析生成；
- D. 不正确：题目中的场景告诉我们，系统采用了自动垃圾回收系统，因而程序员不太可能需要去释放内存。（未能释放分配的内存）也可能的情况是内存泄漏通常造成的性能下降，最终导致操作系统端出现“资源不足”的报错。

分值：2分

### 15. CTAL-TTA_LO-4.2.1

> TTA 4.2.1 (K4) 针对特定的项目和被测系统，对非功能需求进行分析，并编写测试计划的相关部分。

**问题：**

假设假设您是一名技术测试分析师，为一个正在开发全新银行系统的项目工作。这个系统将会存储客户财务数据，包括个人识别信息、账号、余额和历史交易。根据此信息，下面这些主题中，哪个**最需要**您来做出贡献来添加到测试计划中？

**答案选项：**

- A. 测试数据加密；
- B. 测试数据匿名化；
- C. 协调分布式组件；
- D. 在生产环境中测试。

**解释：**

- A. 正确：银行很可能根据监管要求需要对客户财务数据进行加密，这会对测试产生影响；
- B. 不正确：因为这是一个全新的系统，并不存在既有客户的信息（尽管后续发布的版本有可能会使用真实顾客数据进行测试）；
- C. 不正确：题目中并没有提到这是一个分布式系统；
- D. 不正确：目前尚不清楚这个系统是将会在内部使用（可能会有生产环境）还是会销售给客户（很可能不会有生产环境）。

分值：2分

### 16. CTAL-TTA_LO-4.3.1

> TTA-4.3.1 (K3) 为安全性测试定义方法和设计概要测试用例。

**问题：**

在一个系统中有一个可编辑的、自由格式的输入字段，标记为“要打开的文件名”。仅根据此信息，您应该要对下面哪种安全威胁进行测试？

**答案选项：**

- A. 缓冲区溢出；
- B. 跨站脚本攻击；
- C. 服务拒绝；
- D. 破解加密。

**解释：**

- A. 正确：输入字段的自由格式性质将可能允许攻击者尝试插入大段的、恶意的输入；
- B. 不正确：我们目前尚不清楚这个系统是否是基于浏览器的，以及这个文件的用途是什么；
- C. 不正确：拒绝服务攻击(DOS)是通过计算机接口进行的，而不是用户界面；
- D. 不正确：题目中并没有提到涉及加密的内容。

分值：1分

### 17. CTAL-TTA_LO-4.4.1

> TTA-4.4.1 (K3) 为可靠性质量特性及其相应的ISO 9126子特性定义方法和设计概要用例。

**问题：**

场景1：

假设您正在为一家雄心勃勃但初始资金有限的初创公司工作。

他们正在创建这样一个系统：为在网上向顾客销售产品的中小型企业提供定制的顾客忠诚度和奖励计划。这些企业可以在系统的网上商店进行注册，这使得企业可以创建自定义按钮，放置在他们自己的网站上，从而让顾客可以注册加入企业的忠诚度和奖励计划。顾客之后的每次购买都会获得积分，企业和顾客都可以对该计划进行管理，如：企业可以确定顾客获得免费产品或服务所需的积分，顾客也可以随时查看自己的积分。

您公司的市场营销人员正在大力推广这个系统，为新加入的公司提供有竞争力的首年费用折扣。销售材料表明，该服务对企业及其顾客来说非常可靠，速度极快。

此时，需求已经确定完毕，软件开发刚刚开始。按照目前的时间安排，企业及其顾客在三个月内可以开始注册。

您公司打算使用云计算资源来托管此服务，并且除了普通的办公电脑之外，不会为公司的开发、测试人员和其他工程师、管理人员提供任何硬件资源。采用行业标准的基于Web的应用软件组件将被用于构建系统。

生产环境将被用于测试，运维团队也已经根据需要定义并测试了配置此环境的过程。

在场景1的条件下，假设市场部门要求平均故障间隔时间不短于3个月，当系统确实发生故障时，平均修复时间不超过10分钟。在正式发布前规划系统的可靠性测试时，下面**哪三个**选项最可能是将会面临的挑战？

**答案选项：**

- A. 可靠性测试环境的成本；
- B. 可靠性测试的持续时间；
- C. 迫使硬件和操作系统发生故障；
- D. 定义可靠性需求；
- E. 配置类似生产环境的测试环境；
- F. 确定系统的可用性目标；
- G. 在生产中监控可靠性。

**解释：**

- A. 正确：测试环境必须模拟生产环境并且需要长期可用（见B选项）；
- B. 正确：市场部门要求3个月的平均故障间隔时间，根据时间安排，由于开发工作刚刚开始，我们只剩下三个月的时间；
- C. 正确：容错性测试是可靠性测试的一部分，但是因为硬件和操作系统都处于云计算服务商的控制下，测试中想要不中断其他客户的使用来强制产生故障可能将会非常困难；
- D. 不正确：D选项并不是一个挑战，因为我们在题目中已经清晰地定义了可靠性需求；
- E. 不正确：您将使用最终的生产托管环境——云资源——来随意创建类似生产环境的环境，这已经是一个得到了解决的问题；
- F. 不正确：可用性目标在该场景中已经给出来了，是由市场部门提供的平均故障间隔时间和平均修复时间；
- G. 不正确：和生产前进行的测试无关；

分值：2分

### 18. CTAL-TTA_LO-4.5.1

> TTA-4.5.1 (K3) 为性能测试定义方法和设计概要测试用例。

**问题：**

场景1：

假设您正在为一家雄心勃勃但初始资金有限的初创公司工作。

他们正在创建这样一个系统：为在网上向顾客销售产品的中小型企业提供定制的顾客忠诚度和奖励计划。这些企业可以在系统的网上商店进行注册，这使得企业可以创建自定义按钮，放置在他们自己的网站上，从而让顾客可以注册加入企业的忠诚度和奖励计划。顾客之后的每次购买都会获得积分，企业和顾客都可以对该计划进行管理，如：企业可以确定顾客获得免费产品或服务所需的积分，顾客也可以随时查看自己的积分。

您公司的市场营销人员正在大力推广这个系统，为新加入的公司提供有竞争力的首年费用折扣。销售材料表明，该服务对企业及其顾客来说非常可靠，速度极快。

此时，需求已经确定完毕，软件开发刚刚开始。按照目前的时间安排，企业及其顾客在三个月内可以开始注册。

您公司打算使用云计算资源来托管此服务，并且除了普通的办公电脑之外，不会为公司的开发、测试人员和其他工程师、管理人员提供任何硬件资源。采用行业标准的基于Web的应用软件组件将被用于构建系统。

生产环境将被用于测试，运维团队也已经根据需要定义并测试了配置此环境的过程。

在场景1的条件下，假设市场部门希望确保系统速度很快，在正式发布前规划系统的性能测试时，下面**哪三个**  *（译者注：原文此选项为“哪两个”，应属谬误）* 选项最可能是将会面临的挑战？

**答案选项：**

- A. 确定性能需求；
- B. 性能测试工具的成本；
- C. 测试数据的选择；
- D. 性能测试工具的兼容性；
- E. 配置类似生产环境的测试环境；
- F. 开发复杂的模拟器；
- G. 测试数据的匿名化。

**解释：**

- A. 正确：市场部门只是说他们需要一个“特别快”的系统，这实际意味着什么（到底要有多快）并不明确；
- B. 正确：性能测试可能会很昂贵，尤其在模拟大量用户时；
- C. 正确：您需要对用户数量、企业最终拥有的程序类型、企业和顾客操作的类型和频率等等作出有根据的猜测；
- D. 不正确：系统采用了标准的Web接口；
- E. 不正确：您将使用最终的生产托管环境——云资源——来随意创建类似生产环境的环境，这已经是一个得到了解决的问题；
- F. 不正确：在此场景下不需要任何模拟器，只需要通过标准的性能测试工具来模拟用户；
- G. 不正确 *（译者注：原文此选项为“正确”，应属谬误）*：此时还不存在需要匿名化的生产数据。

分值：2分

### 19. CTAL-TTA_LO-4.x.1

> TTA-4.x.1 (K2) 理解和解释在测试策略和/或测试方法中包括维护性测试、可以执行测试和资源利用性测试的原因。

**问题：**

现有如下的一个软件控制系统：

- 将被集成到另外一个更广泛的系统中
- 预计将产生多个变体
- 预计将在10年的时间范围内经历一系列环境变化

对于如上软件控制系统，下面**哪两种**测试类型将会是最重要的？

**答案选项：**

- A. 适应性测试；
- B. 维护性测试；
- C. 易恢复性测试；
- D. 易替换性测试；
- E. 安全性测试。

**解释：**

- A. 正确：适应性测试很可能很重要，因为这个系统将会安装在各种各样的环境中；
- B. 正确：维护性测试很重要，因为题目中提到了持续开发和多种配置的需求；
- C. 不正确：易恢复性测试在此场景中不建议使用，因为从软件或硬件故障中恢复可能并不符合操作的预期结果（比如单程操作流程）；
- D. 不正确：易替换性测试在此场景中不建议使用，因为题目中并没有提到组件更换；
- E. 不正确：在此场景下安全并不是一个值得关注的问题。

分值：2分

### 20. CTAL-TTA_LO-4.x.2

> TTA-4.x.2 (K3) 给定一个特定的产品风险，定义最适合的非功能性的测试类型。

**问题：**

请考虑如下的产品风险：

- 网络连接失败引起的应用非正常终止

下面哪种测试类型最适合对应这种风险？

**答案选项：**

- A. 可靠性测试；
- B. 性能测试；
- C. 易操作性测试；
- D. 可移植性测试。

**解释：**

- A. 正确：容错性测试是可靠性测试的一部分；
- B. 不正确：此场景下我们并不关心响应时间、吞吐量或者资源利用等；
- C. 不正确：题目中的风险与可用性测试并不相关；
- D. 不正确：题目中并没有提到特定的网络类型。

分值：1分

### 21. CTAL-TTA_LO-4.x.3

> TTA-4.x.3 (K2) 理解和解释在应用程序的生命周期中，需要实施非功能测试的各个阶段。

**问题：**

场景1：

假设您正在为一家雄心勃勃但初始资金有限的初创公司工作。

他们正在创建这样一个系统：为在网上向顾客销售产品的中小型企业提供定制的顾客忠诚度和奖励计划。这些企业可以在系统的网上商店进行注册，这使得企业可以创建自定义按钮，放置在他们自己的网站上，从而让顾客可以注册加入企业的忠诚度和奖励计划。顾客之后的每次购买都会获得积分，企业和顾客都可以对该计划进行管理，如：企业可以确定顾客获得免费产品或服务所需的积分，顾客也可以随时查看自己的积分。

您公司的市场营销人员正在大力推广这个系统，为新加入的公司提供有竞争力的首年费用折扣。销售材料表明，该服务对企业及其顾客来说非常可靠，速度极快。

此时，需求已经确定完毕，软件开发刚刚开始。按照目前的时间安排，企业及其顾客在三个月内可以开始注册。

您公司打算使用云计算资源来托管此服务，并且除了普通的办公电脑之外，不会为公司的开发、测试人员和其他工程师、管理人员提供任何硬件资源。采用行业标准的基于Web的应用软件组件将被用于构建系统。

生产环境将被用于测试，运维团队也已经根据需要定义并测试了配置此环境的过程。

在场景1的条件下，假设合适的系统响应时间被认为是系统最重要的产品风险之一，下面哪项陈述是正确的？

**答案选项：**

- A. 性能测试应该从系统的初期构建(Initial builds)开始；
- B. 性能测试应该在功能测试结束后进行；
- C. 动态性能测试应该在代码审查时进行；
- D. 可靠性测试应该在性能测试之后进行。

**解释：**

- A. 正确：我们应该尽可能早地去解决重要风险；
- B. 不正确：见A选项；
- C. 不正确：代码审查属于静态测试，不属于动态测试；
- D. 不正确：题目中没有可靠性相关风险的信息。

分值：1分

### 22. CTAL-TTA_LO-4.x.4

> TTA-4.x.4 (K3) 对于一个给定的场景，定义通过运用非功能测试类型能找到的缺陷类型。

**问题：**

场景1：

假设您正在为一家雄心勃勃但初始资金有限的初创公司工作。

他们正在创建这样一个系统：为在网上向顾客销售产品的中小型企业提供定制的顾客忠诚度和奖励计划。这些企业可以在系统的网上商店进行注册，这使得企业可以创建自定义按钮，放置在他们自己的网站上，从而让顾客可以注册加入企业的忠诚度和奖励计划。顾客之后的每次购买都会获得积分，企业和顾客都可以对该计划进行管理，如：企业可以确定顾客获得免费产品或服务所需的积分，顾客也可以随时查看自己的积分。

您公司的市场营销人员正在大力推广这个系统，为新加入的公司提供有竞争力的首年费用折扣。销售材料表明，该服务对企业及其顾客来说非常可靠，速度极快。

此时，需求已经确定完毕，软件开发刚刚开始。按照目前的时间安排，企业及其顾客在三个月内可以开始注册。

您公司打算使用云计算资源来托管此服务，并且除了普通的办公电脑之外，不会为公司的开发、测试人员和其他工程师、管理人员提供任何硬件资源。采用行业标准的基于Web的应用软件组件将被用于构建系统。

生产环境将被用于测试，运维团队也已经根据需要定义并测试了配置此环境的过程。

在场景1的条件下，假设你正在对系统进行安全测试，下面哪种类型的缺陷是你在测试中预期会找到的？

**答案选项：**

- A. 系统允许对数据的未授权访问；
- B. 登陆系统后屏幕立即被清空（清空速度过快）；
- C. 登出系统后，系统移除用户临时文件；
- D. 系统允许来自不支持的浏览器的访问。

**解释：**

- A. 正确：这是一种典型的安全缺陷；
- B. 不正确：这是一个可用性缺陷，不是安全缺陷；
- C. 不正确：这是一个安全性特性，不是缺陷；
- D. 不正确：如果这是一个缺陷，这最可能是一个可移植性缺陷。

分值：1分

### 23. CTAL-TTA_LO-5.1.1

> TTA-5.1.1 (K2) 解释为何评审准备工作对技术测试分析师很重要。

**问题：**

一名技术测试分析师被邀请参与一个架构设计规范的评审，评审将在第二天随时通知随时进行。分析师的记录本上虽然没有内容，但也来不及准备了。对于这个邀请，最合适的回复方式是什么？

**答案选项：**

- A. 我没有时间来准备明天的评审会议，所以如果评审不能延期，我必须要拒绝这次邀请；
- B. 到时候我有空，很乐意参加；
- C. 我虽然没有时间去准备，但我还是会参加，要不会议就可能会延期了；
- D. 我不能参加评审，因为我对这个规范不熟悉。

**解释：**

- A. 正确：这是正确的回应；
- B. 不正确：这个回应虽然表明了想要通过合作来完成评审的意愿，但是分析师如果不做好充分的准备，就无法做出足够的贡献，因而评审将会更加低效；
- C. 不正确：这个回应虽然指出了缺乏准备时间的问题，但是没有去坚持争取到足够的准备时间；
- D. 不正确：这个回应虽然比较准确，但实际上如果做足准备，障碍（对规范的不熟悉）将会消除。因此这不是拒绝评审会议时最佳的回应。

分值：1分

### 24. CTAL-TTA_LO-5.2.1

> TTA-5.2.1 (K4) 根据大纲提供的检查表来分析架构设计及识别问题。

**问题：**

您正在参加对一个新产品设计的架构评审。这是一款嵌入式产品，有着严格的内存限制。思考一下下面的编程实践及其可能带来的问题的列表：

编程实践：

1. 连接池
2. 数据缓存
3. 延迟实例化
4. 并发事务

问题：

1. 需要实例化时对性能的影响
2. 处理器不可用导致的事务丢失
3. 多线程逻辑错误
4. 过期数据

在题目场景中，哪种编程实践可以用来减少不必要的内存使用，同时可能带来的问题是什么？

**答案选项：**

- A. 编程实践3，问题1；
- B. 编程实践2，问题4；
- C. 编程实践4，问题3；
- D. 编程实践1，问题2；

**解释：**

- A. 正确：这可以减少不必要的内存使用，但当需要加载类时也可能会带来性能上的延迟；
- B. 不正确：数据缓存可以帮助优化性能，而不是内存使用；
- C. 不正确：并发事务会使用更多的内存；
- D. 不正确：连接池可以优化内存和性能，但是可能带来的问题是连接用尽，而不是丢失进程。

分值：2分

### 25. CTAL-TA_LO-5.2.2

> TTA-5.2.2 (K4) 根据大纲提供的检查表来分析一部分代码或伪代码及识别问题。

**问题：**

你正在参加一场代码审查，在下面这段伪代码中发现了一个问题（假设\*\*\*代表的是注释）

```
*** this code checks for valid card type ***
If credit card is type "Discover" then
    Display error message 437
Else if credit card is type "Visa" or "MasterCard" then
    Process purchase
Else if credit card is type "AmericanExpress" then
    Display error message 439
Else
    Display error message 440
End if
```

请指出下面选项中的哪个问题出现在了这段代码中，以及为什么需要被修改：

**答案选项：**

- A. 可能性最大的情况没有最先被检查到，导致潜在的对性能的影响；
- B. 代码里的注释不正确，导致对可维护性的影响；
- C. 未使用外部库来验证信用卡，没有重用现有组件，导致效率低下；
- D. 没有加上`default`语句，导致某些情形无法被处理到。

**解释：**

- A. 正确：信用卡最可能是Visa或者Mastercard，所以应该最先检查这两种；
- B. 不正确：注释没有错误；
- C. 不正确：我们无法知道是否存在外部库；
- D. 不正确：`else`可以处理到没有被`if`检查到的其他所有情况。

分值：2分

### 26. CTAL-TTA_LO-6.1.1

> TTA-6.1.1 (K2) 描述多个工具同时使用时技术层面需要考虑的内容。

**问题：**

场景2：

假设你参与测试一款成熟应用。这是一款在线约会服务软件，用户可以：填写个人资料、与适合他们的人会面、跟其他人安排社交活动、拉黑不想再去联系的人等。

缺陷和测试用例是通过一款现有的商业测试管理工具来管理的，一切使用正常。源代码和其他项目工作产品被保存在一个开源的配置管理系统上。

您的经理希望您可以帮助她选择一款自动化测试工具来使大部分的回归测试可以自动化完成。

在场景2的条件下，从和现有工具关系的角度考虑，下面那个选项是一个重要的考虑因素？

**答案选项：**

- A. 自动化测试的保存和版本管理的过程；
- B. 测试自动化执行工具的成本；
- C. 移除自动化测试生成的重复缺陷报告的过程；
- D. 从测试管理工具供应商那里选择测试自动化执行工具。

**解释：**

- A. 正确：这个可能会成为低效和/或风险的来源；
- B. 不正确：和现有工具无关;
- C. 不正确：真正的问题是要避免重复，而不是移除重复；
- D. 不正确：这并不保证会带来成功的集成。

分值：1分

### 27. CTAL-TTA_LO-6.2.1

> TTA-6.2.1 (K2) 总结建立一个测试自动化项目时，技术测试分析师需要执行的任务。

**问题：**

下面**哪两个**选项是建立一个自动化测试项目时，技术分析师的典型任务？

**答案选项：**

- A. 定义项目测试管理工具与测试自动化工具之间的接口需求；
- B. 安排测试自动化项目并且与测试经理一起分配维护时间；
- C. 为自动化测试用例设计测试数据；
- D. 当采用关键字驱动测试技术时，定义测试用例中使用的业务流程关键字；
- D. 确定谁将负责测试分析和设计需要自动化的测试用例。

**解释：**
- A. 正确：根据大纲描述；
- B. 正确：根据大纲描述；
- C. 不正确：测试数据通常是测试分析师(TA)和业务分析师(BA)的职责；
- D. 不正确：定义关键字一般由测试分析师(TA)和业务分析师(BA)来完成；
- E. 不正确：谁来进行测试分析和设计（甚至包括谁来自动化测试用例）都不是由TTA来决定的。

分值：1分

### 28. CTAL-TTA_LO-6.2.2

> TTA-6.2.2 (K2) 总结数据驱动自动化和关键字驱动自动化的区别。

**问题：**

下面哪项陈述最能说明数据驱动和关键字驱动测试自动化的区别？

**答案选项：**

- A. 关键字驱动的测试自动化通过定义关键字对应业务流程，扩展了数据驱动自动化；
- B. 数据驱动的测试自动化通过定义数据对应业务流程，扩展了关键字驱动自动化；
- C. 数据驱动的测试自动化比关键字驱动的测试自动化更容易维护；
- D. 关键字驱动的测试自动化比数据驱动的测试自动化更容易开发；

**解释：**

- A. 正确：关键字驱动的测试本身也是数据驱动的，但也有基于流程的关键字；
- B. 不正确：该选项描述了相反的事实；
- C. 不正确：关键字驱动的测试更容易维护（由于角色分离 *[译者注：通常是由TA或BA来选择关键字]* ）；
- D. 不正确：为关键字驱动框架定义正确的架构是困难的。

分值：1分

### 29. CTAL-TTA_LO-6.2.3

> TTA-6.2.3 (K2) 总结引起自动化项目不能达到预期投资回报的普遍技术问题。

**问题：**

下面哪个选项描述了一个引起自动化项目不能达到与其投资回报的普遍技术问题？

**答案选项：**

- A. 在测试件中未将代码和可变数据很好地分离开；
- B. 消除了跨工具间的重复信息；
- C. 移除了对工具之间数据交换的人工检查；
- D. 使用一个集成开发环境来简化工具之间的集成

**解释：**

- A. 正确：根据大纲描述；
- B. 不正确：消除重复对工具集有利；
- C. 不正确：数据交换无需人工干预是理想状态；
- D. 不正确：只要工具“适合”集成开发环境(IDE)，使用IDE通常是值得的。

分值：1分

### 30. CTAL-TTA_LO-6.2.4

> TTA-6.2.4 (K2) 根据给出的业务流程创建关键字列表。

**问题：**

场景2：

假设你参与测试一款成熟应用。这是一款在线约会服务软件，用户可以：填写个人资料、与适合他们的人会面、跟其他人安排社交活动、拉黑不想再去联系的人等。

缺陷和测试用例是通过一款现有的商业测试管理工具来管理的，一切使用正常。源代码和其他项目工作产品被保存在一个开源的配置管理系统上。

您的经理希望您可以帮助她选择一款自动化测试工具来使大部分的回归测试可以自动化完成。

在场景2的条件下，假设你正在采用关键字驱动自动化方法，对于这个应用来说，下面**哪三个**选项**最有可能**是应该采用的关键字？

**答案选项：**

- A. Enter_Profile（输入_资料）；
- B. Block_Person（拉黑_联系人）；
- C. Find_Match（寻找_合适的人）；
- D. Delete_Profile（删除_资料）；
- E. Enter_Test_Data（输入_测试_数据）；
- F. Remove_Test_Data（移除_测试_数据）；
- G. Pay_Bill（支付_账单）；
- H. Exclude_Non_Smokers（排除_非_吸烟者）；
- I. Take_Hottie_to_Dinner（带_小心肝_去_吃饭）。

**解释：**

- A. 正确：A、B、C是正确选项，因为题目场景中明确地提到了这些都属于该应用的功能；
- B. 正确：A、B、C是正确选项，因为题目场景中明确地提到了这些都属于该应用的功能；
- C. 正确：A、B、C是正确选项，因为题目场景中明确地提到了这些都属于该应用的功能；
- D. 不正确：D有可能是这个应用的功能，但是并未在题目场景中提及，因而这不是最可能采用的关键字；
- E. 不正确：E、F是不正确的选项，因为关键字应与应用支持的业务流程而不是测试流程有关；
- F. 不正确：E、F是不正确的选项，因为关键字应与应用支持的业务流程而不是测试流程有关；
- G. 不正确：G选项和D选项不正确的原因相同，并且题目场景中也没有提及产品会向使用者收取费用；
- H. 不正确：H选项不正确，因为这很可能只是在输入资料时的一个小步骤，关键字的颗粒度不能太细；
- I. 不正确：I选项作为关键字的可能性很小，因为该选项描述的是真实世界中的行动，而不是应用的业务流程。同时，使用具有滑稽色彩的、文化特异性和暗示性的词语“小心肝”并不是一个好的习惯。

分值：1分

### 31. CTAL-TTA_LO-6.3.1

> TTA-6.3.1 (K2) 总结缺陷散播和缺陷注入工具的使用目的。

**问题：**

下面哪项关于缺陷散播工具的描述是**不正确**的？

**答案选项：**

- A. 这些工具将缺陷插入到源代码中从而测试软件的输入检查功能；
- B. 这些工具将缺陷插入到源代码中从而检查软件的容错性级别；
- C. 这些工具将缺陷插入到源代码中从而检查测试套件的测试效率；
- D. 这些工具将缺陷插入到源代码中，作为变异测试（植入测试）的一部分。

**解释：**

- A. 正确：输入检查可以通过改变测试输入来实现，但是需要改变的是测试输入（而不是源代码）；
- B. 不正确：根据大纲描述；
- C. 不正确：根据大纲描述；
- D. 不正确：根据大纲描述；

分值：1分

### 32. CTAL-TTA_LO-6.3.2

> TTA-6.3.2 (K2) 总结性能测试和监控工具的主要特性和实施方面的问题。

**问题：**

下面关于性能测试和监控工具的哪项描述是正确的？

**答案选项：**

- A. 这些工具通过按照指定的操作配置文件模拟大量虚拟用户来生成特定数量的输入数据，从而生成负载；
- B. 这些工具是从通信协议级别（而不是通过用户界面）来驱动应用程序，从而可以更精确地测量响应时间；
- C. 这些工具录制单个用户的操作来生成脚本，然后复制多个相同脚本，并行同时回放，来代表各种范围级别的用户量所进行的操作；
- D. 这些工具在测试执行之后进行了广泛测量，从而能够分析测试对象最重要的性能特征。

**解释：**

- A. 正确：根据大纲描述；
- B. 不正确：通过用户界面来驱动应用程序通常会比通信协议级别获取到更准确的响应时间；
- C. 不正确：脚本需要进行修改以考虑不同用户及其事务的多变性；
- D. 不正确：测量需要在执行过程中进行。

分值：1分

### 33. CTAL-TTA_LO-6.3.3

> TTA-6.3.3 (K2) 解释基于网页测试工具的一般目的。

**问题：**

下面**哪两个**选项**最好地**描述了支持基于网页测试的工具的目的？

**答案选项：**

- A. 扫描服务器以检查孤立文件；
- B. 检查是否违反无障碍访问标准；
- C. 通过执行一个“预期执行行为”的模型来生成测试用例；
- D. 在逐行执行时更改变量值从而在用户界面隔离故障；
- E. 向测试对象中注入缺陷从而评估测试套件的质量。

**解释：**

- A. 正确：根据大纲描述；
- B. 正确：根据大纲描述；
- C. 不正确：该选项描述的是一种MBT（Model-Based Testing，基于模型的测试）工具；
- D. 不正确：该选项描述的是一种调试器；
- E. 不正确：该选项描述的是一种缺陷散播工具。

分值：1分

### 34. CTAL-TTA_LO-6.3.4

> TTA-6.3.4 (K2) 解释工具如何支持基于模型测试的概念。

**问题：**

下面那个选项**最好地**描述了工具是如何支持基于模型的测试(MBT)的概念的？

**答案选项：**

- A. MBT工具可以通过保存有趣的执行线程来生成测试用例；
- B. MBT工具显著地增加了模型中能够生成的路径的数目；
- C. MBT工具提供了对于被测系统的内部结构的另外一种思路；
- D. MBT工具通常提供了一个允许用户“执行”模型的引擎，但无法保存测试用例。

**解释：**

- A. 正确：这是正确的选项；
- B. 不正确：MBT工具通常会减少可能的路径；
- C. 不正确：MBT工具为功能测试提供了不同的思路；
- D. 不正确：MBT工具的“引擎”确实可以保存一些执行线程（尤其是那些和失败测试用例相关的）。

分值：1分


### 35. CTAL-TTA_LO-6.3.5

> TTA-6.3.5 (K2) 概述支持组件测试和构建（build）流程的工具的目的。

**问题：**

下面哪个选项**最好地**解释了组件测试工具和自动化构建（build）工具之间的关系？

**答案选项：**

- A. 组件测试框架可以简化组件测试的自动化；构建自动化工具允许在组件变更时触发新构建；
- B. JUnit框架可以在Java环境中简化组件测试的自动化；只要当一次构建中的一个组件发生更改，构建自动化工具就会自动触发组件测试；
- C. xUnit框架可用于自动化组件测试；构建自动化工具可以用于执行自动化组件测试；
- D. 组件测试工具可用于多种编程语言；当组件发生更改时，构建自动化工具允许触发新构建。

**解释：**

- A. 正确：这是正确的选项；
- B.不正确：关于组件测试的陈述是正确的；关于构建自动化的陈述是不正确的；
- C.不正确：关于xUnit框架的陈述虽然看起来很像是正确的，但是是不正确的；关于构建自动化的陈述是不正确的。
- D.不正确：关于组件测试的陈述是正确的；关于构建自动化的陈述是不正确的。

分值：1分
