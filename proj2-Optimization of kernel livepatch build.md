# proj2-Optimization of kernel livepatch build
### 项目名称
Linux内核热补丁构建流程优化

### 项目描述与背景

当前Linux内核热补丁构建是基于 [kpatch](https://github.com/dynup/kpatch) 来进行，用户提供一个patch文本文件，调用 kpatch-build 命令行工具即可完成内核热补丁的构建，对于开发者来说，快速构建、调试（试错）是一个强需求，社区的kpatch-build工具搭配主流Linux版本，在构建效率上有提高空间，可对整个构建流程进行优化，做到更高效，并尝试贡献开源社区

### 功能描述

#### 基础功能：
热补丁制作过程，大量时间耗费在第一次内核的编译上，可以考虑缓存起内核的二进制编译产物，这样就只需要做第二次增量的内核编译。

#### 扩展功能：
二进制差异提取工具create-diff-object 性能优化
学生可发挥自主创新，识别其他潜在的优化点并实现

### 所属赛道

2022全国大学生操作系统比赛的“OS功能设计”赛道



### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2022年春季学期或之后本科毕业的大一~大四的学生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求



### 项目导师





### 难度

低


### 参考资料

项目相关参考资料

[kpatch](https://github.com/dynup/kpatch)   
[kpatch-build](https://github.com/dynup/kpatch/blob/master/kpatch-build/kpatch-build)  

### License

* [GPL-2.0](https://opensource.org/licenses/GPL-2.0)



## 预期目标

完成基础和扩展功能的开发，扩展功能部分若无法实现需提出想法和建议，并输出说明文档一篇。

**注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标**

参考任务描述部分。