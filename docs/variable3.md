# 变量进阶：探索字符串中的更多用途

我们假设一个字符串中拥有一些你不想现实的空格。你现在希望删除他们。`Trim`、`TrimStart`和`TrimEnd`将会完成这些工作。

尝试运行以下代码：

```C#
string spase = "     Hello World     ";
Console.WriteLine($"[{spase}]");

string nostartspase = spase.trimstart();
Console.WriteLine($"[{nostartspase}]");

string noendspase = spase.trimend();
Console.WriteLine($"[{noendspase}]");

string nospase = spase.trim();
Console.WriteLine($"[{nospase}]");
```

!> `trim`似乎不是用于消除空间，而是用于消除空格。

?> 在教程中使用双关梗是要扣钱的....等等，这个教程不正经，那就不扣钱了吧。

在运行以上代码后，我们就应该理解`Trim`、`Trimstart`和`Trimend`的用途了。

我们可以发现，所有对`Trim`的调用返回的都是新字符串，而不是原始字符串。

如果我们需要搜索并替换一些字符串，`RePlace`可以完成这些操作。

```C#
string Hello = "Hello World"
Console.WriteLine(sayHello);
Hello = Hello.Replace("Hello", "Hey");
Console.WriteLine(Hello);
```
?> 注意：本文档似乎不完善，你可以前往本教程所在的Github存储库进行编辑。