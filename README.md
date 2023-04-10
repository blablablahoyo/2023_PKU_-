# blablablahoyo.github.io

学号：2200921845
姓名：洪巧芸

## 题目一：
### 题目要求：
词频统计图  选择自己熟悉领域的某一长篇文本进行某一类词的词频分析（也可选科研著作）
将结果可视化，可使用柱状图或词云，也可用课上未讲到的其他图表形式

### 故事背景：
1. 统计毛语录中不同人名出现的次数（步驟2-4）
2. 生成柱状图 （步驟5-6）
3. 生成词云（步驟7）

### 解题思路：
1. 从网上下载毛语录的txt档案
2. 利用flag先进行初步判读，找出可能为人名的字词
3. 手动输入ignore list，将错误的人名塞选进行排除
4. 生成人名与出现次数的统计图表，并储存为csv档
5. 读取步骤4.所生成的csv档案，生成柱状图
   标题为人物词频统计，并以人物为x座标，出现次数为y座标
6. 调整图片大小及标签大小，让图片中的人名标签不会相互重叠影响判读
7. 生成词云

### 程式码：
http://blablablahoyo.github.io/01.py

### 作业连结：
http://blablablahoyo.github.io/毛语录-人物词频.csv
http://blablablahoyo.github.io/毛语录-人物词频.png
http://blablablahoyo.github.io/毛语录-人物词云.html

## 题目二：
### 题目要求：
中国地图、世界地图（自己设定故事背景）

### 故事背景：
1. 中国地图 -> 各个省份录取清北人数
2. 挑选几个城市拉线至清北所在省份
3. 世界地图 -> 台湾人喜欢到哪里去读书
4. 找出前20个国家 标记数量

### 程式码：
http://blablablahoyo.github.io/02.py

### 作业连结：
http://blablablahoyo.github.io/清华北大招生人数.html
http://blablablahoyo.github.io/台湾学生出国留学数据地图_geo.html

### 参考资料：
https://shirley.tw/2021y-study-abroad/
https://new.qq.com/rain/a/20210719A0EBFG00

## 题目三：
### 题目要求：
组合图表（自己设定故事背景）

### 故事背景：
1. 比较去年每个月的花销 (NTD)
2. 分为饮食、交通、总和

### 程式码：
http://blablablahoyo.github.io/03.py
### 作业连结：
http://blablablahoyo.github.io/2022年每月花销.html
