## 作业1 回合制游戏
[Github仓库链接](https://github.com/fufuandfoufou/Hogwarts_work)

## python脚本编写实战（二）
#### 作业一
用类和面向对象的思想，“描述”生活中任意接触到的东西（比如动物、小说里面的人物，不做限制，随意发挥），数量为5个

**解答：** 
- 人是一个类，黄种人是它的子类，小明是人的一个实例。
- 动物是一个类， 灵长类是它的子类， 猴子是人的一个实例。
- 电子产品是一个类， 电脑是它的子类， macbookpro是电子产品的一个实例。
- 食物是一个类， 零食是它的子类， 薯片是食物的一个实例。
- 游戏是一个类， 网游是它的子类， 魔兽世界是游戏的一个实例。

#### 作业二
- 定义一个天山童姥类 ，类名为TongLao，属性有血量，武力值（通过传入的参数得到）。TongLao类里面有2个方法:
    1. see_people方法，需要传入一个name参数，如果传入”WYZ”（无崖子），则打印，“师弟！！！！”，如果传入“李秋水”，打印“呸，贱人”，如果传入“丁春秋”，打印“叛徒！我杀了你”
    1. fight_zms方法（天山折梅手），调用天山折梅手方法会将自己的武力值提升10倍，血量缩减2倍。需要传入敌人的hp，power，进行一回合制对打，打完之后，比较双方血量。血多的一方获胜。
- 定义一个XuZhu类，继承于童姥。虚竹宅心仁厚不想打架。所以虚竹只有一个read（念经）的方法。每次调用都会打印“罪过罪过”
- 加入模块化改造  
[作业地址](https://github.com/fufuandfoufou/Hogwarts_work/tree/master/class_practice)