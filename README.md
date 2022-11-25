# GoLearn-Cobra

`Cobra命令交互工具学习使用。[Github地址: https://github.com/DivenZhong/GoLearn-Cobra.git)

用于diven zhong个人学习实践,转载请说明


#Cobra的核心概念
   CoBra 命令行交互工具：
     命令（Command）：就是需要执行的操作；
     参数（Arg）：命令的参数，即要操作的对象；
     选项（Flag）：命令选项可以调整命令的行为。
	
#接口	
   cobra 提供了非常丰富的特性和定制化接口，例如：
         设置钩子函数，在命令执行前、后执行某些操作；	
	
#脚手架Scaffold示例
   CoBra 生成Scaffold示例：
          github路径下的生成的main.exe，实现这样一个功能，根据传入的年、月，打印这个月的日历。如果没有传入选项，使用当前的年、月
		  用法：main.exe date --year 2019 --month 12