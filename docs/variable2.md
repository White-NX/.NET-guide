# 变量进阶：探索更多功能

上次编辑是对`string`的初步探索，接下来，我们将进入到更深层....

```C#
string lang = "C#";
string ithink = "I love it.";
Console.WriteLine($"I'm learning {lang} and {ithink}");
```

当我们对变量的用途进行更深♂层次探索时，你可以发现它不仅仅能输出字符串组合，还可以输出变量中的字符数：
```C#
Console.WriteLine($"I'm learning {lang}.{ithink} have {ithink.Length} letters in total.");
```


?> 这是自行探索的良机！试试看在变量后键入`.`。我们就可以看到可以使用的属性和使用方法。

?> 注意：本文档似乎不完善，你可以前往本教程所在的Github存储库进行编辑。