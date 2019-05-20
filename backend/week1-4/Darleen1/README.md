# 代码重构任务
## 总体情况
* 还是可以实现的吧，代码没做什么大的改动。主要把代码分成不同包，实现同不功能。
* 学习主要就学了一个反射机制来调用不同类中的私有化方法。但是代码中没用到。
* 对了，还学了好多英语单词，都是报错看不懂，去查学的。
* 最近有点懒，本来双周下午基本都没课，都给我午睡睡过去了，什么事也没干。
## 遇到的坑
* 记得那次看林的代码很简洁，很有条理，分成不同包，实现不同功能。到我自己做就不是那样了，我才新建一个类，
就都是红色的，错误。一开始用的是import 包名.类名；但是还是提示错误，说好像里面的成员是私有化的不能被调用。
后来啊，我根据idea的提示点了红色灯泡的第一个就好了，但是还有好多错误。
* 不知道明明可以调用booklist了，但是常量好像不能调用，我就一个个给复制过去了，好像有点冗杂了。这个就先这样吧。
* 在addbook中，getid，getname报错。还未解决，我先提交，不想拖，后面会继续改
* 在changebook，deletebook，findbook中都是一个错误，method called expected，应为方法调用。我按照小红灯的提示new 了那个方法，又出现错误，说我的id，number不能被调用，然后再method的类里添加了对number的声明，就是public findid（int number）{}。这样之后id又报错"operate "<" cannot be applied to int"，还是没解决。
## 后期要改进的地方
1. 下午不能荒废了，午休要订闹钟，不然时间真的浪费很多很多。
2. 多学点知识，我都是遇到什么问题就去找这个问题的知识点，要是我知道一点这个方面的话，就可以再深入学习，理解透彻。
3. 最重要的以后任务不要拖延！！！