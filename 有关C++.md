#有关C++

##C++语法


1. 初始化

		|运算符=（assignment），沿袭C语言，仅用于单值赋值；例如int a=10; string s = "hello";
		|构造函数语法（constructor syntax），多值赋值；例如complex<double> p(1.0,2.0);

2. 浮点数

		|单精度float
		|双精度double
		|扩展精度浮点long doule

3. 骤死式评估法


		if(expt1 == true || expt2 == false ), 如果exp1等于true，条件即为真


4. 函数引用参数

		|直接对传入的对象进行修改
		|降低复制对象的负担，提升效率
		|指针参数和引用参数的区别，指针参数可能（也可能不）指向某个实际对象，当我们提领指针时，需要判空；而引用必定指定实际对象，所以不必做检查
	

##STL

##Boost

##资料
###书籍
- Essential C++ 