# Functions
## https://youtu.be/WB4hJJkfhLU

### You��re already familiar with the print(), input(), and len() functions from the previous chapters. 
Python provides several builtin functions like these, but you can also write your own functions. 
A function is like a mini-program within a program.

### ��ǰ����½����Ѿ���Ϥ��print()��input()��LEN()������
Python�ṩ��һЩ�������ڽ���������Ҳ���Ա�д�Լ��ĺ�����
��������һ�������е�һ��С����

### To better understand how functions work, let��s create one. Type this program into the file editor and save it as helloFunc.py:

### ��⺯���Ĺ���ԭ�����÷��������Ǵ���һ�����ԡ����ļ��༭������������δ��뵽������ΪhelloFunc.py��

def hello():
	print('Howdy!')
	print('Howdy!!!')
	print('Hello there.')
hello()
hello()
hello()

### The first line is a def statement [1], which defines a function named hello().
The code in the block that follows the def statement[2]�� is the body of the function. 
This code is executed when the function is called, not when the function is first defined.

### ��һ�е�def���ǳ�Ϊ����������䡣defΪ���������ؼ��ʡ����ǽ�����������ƶ���Ϊhello.
�����ź����������Ĵ�������ǳ�Ϊ�����塣
�����������õ�ʱ�����Ĵ���Ż�ִ�У����������״ζ��庯����ʱ��ִ�иô��롣

### The hello() lines after the function are function calls. In code,  a function call is  just the  function��s name 
followed by  parentheses, possibly with some number of arguments in between the parentheses.  When the  program execution
reaches these  calls, it  will jump  to the  top line  in the function and begin executing the code there. When it reaches the end 
of the function, the execution eturns to the line  that called the function  and continues moving through  the code as before. 
Since  this program calls hello()  three times, the code  in the hello() function is executed three times. When you run this program, 
the  output looks like this:

#### Howdy!
#### Howdy!!!
#### Hello there.
#### Howdy!
#### Howdy!!!
#### Hello there.
#### Howdy!
#### Howdy!!!
#### Hello there.

### ������е�hello()���ǳ�֮Ϊ�������á��������ý�����Ҫ�������ͽ����ŵ����ţ�����������������������������Ĳ�����������ִ�е�
�������õ�ʱ����Զ���ת���������������λ�ò���ʼִ�к������롣���������ܵĽ���ʱ��ִ�з��ص����ú���λ�ã�������ִ������Ĵ��롣
��Ϊ��δ������������hello()��������hello()������ִ�������Ρ�����������δ���ʱ���������£�
#### Howdy!
#### Howdy!!!
#### Hello there.
#### Howdy!
#### Howdy!!!
#### Hello there.
#### Howdy!
#### Howdy!!!
#### Hello there.
