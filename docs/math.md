# 入土：探索整数数学运算

创建一个名为`math-start`的目录，将`Powershell`或`cmd`设为当前目录并运行以下命令：

```shell
dotnet new console -n NumbersInCSharp -o .
```
在常用编辑器中，将行`Console.WriteLine("Hello World!");`替换成以下代码：
```C#
int a = 1;
int b = 18;
int c = a+b;
Console.WriteLine(c);
```

?>注意：接下来的教程极其容易导致放弃，但是，请坚持下去!

我们刚刚看到是的一种基本的数学运算，`int`表示整数。使用`+`来进行加法运算。其他常见的证书运算包括：

 - `-`减法运算
 - `/`除法运算
 - `*`乘法运算

首先，我们需要探索这些不同类型的运算。在输出c值的行之后添加如下行：

```C#
// 减法
c = a - b;
Console.WriteLine(c);
// 除法
c = a / b;
Console.WriteLine(c);
// 乘法
c = a * b;
Console.WriteLine(c);
```

随后，在命令窗口中输入`dotnet run`运行此代码