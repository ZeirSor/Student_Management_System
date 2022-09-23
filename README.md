# Java实现的简单学生管理系统

**`Java`平时作业**

使用`HashMap`来实现, 键是学生学号, 值是学生对象

## 1. 作业要求
- 使用`HashMap`编写一个本科生管理程序，包括增加、删除、修改、查找学生等功能。
- 提示，因为本科生对象无法进行值比对，可以借助键值来完成。

## 2. 学生类对象
见[Undergraduate.java](https://github.com/ZeirSor/Undergraduate_Management_Program/blob/master/Undergraduate.java)

## 3. 管理系统对象
见[UndergraduateSystem.java](https://github.com/ZeirSor/Undergraduate_Management_Program/blob/master/UndergraduateSystem.java)

## 4. 主函数运行
见[MainRun.java](https://github.com/ZeirSor/Undergraduate_Management_Program/blob/master/MainRun.java)

## 5. 运行结果
见[runResult.txt](https://github.com/ZeirSor/Undergraduate_Management_Program/blob/master/out/runResult.txt)
```
----------Welcome to Undergraduate Management System----------
1. Add Students Information
2. Remove Student Information
3. Modify Student Information
4. Query Student Information
5. Print All Students' Information
6. EXIT
--------------------------------------------------------------
--------------------------------------------------------------
please enter your option:
1
Add Students Information
Please enter student's name
zhangsan
Please enter student's ID
1234
Please enter student's age
18
Please enter student's gender(m/w)
Man
please check the information:(y/n)
Undergraduate{name = zhangsan, age = 18, gender = MAN, id = 1234}
y
--------------------------------------------------------------
1. Add Students Information
2. Remove Student Information
3. Modify Student Information
4. Query Student Information
5. Print All Students' Information
6. EXIT
--------------------------------------------------------------
please enter your option:
1
Add Students Information
Please enter student's name
lisi
Please enter student's ID
1234
This student ID already exists, please re-enter
2345
Please enter student's age
20
Please enter student's gender(m/w)
w
please check the information:(y/n)
Undergraduate{name = lisi, age = 20, gender = WOMEN, id = 2345}
y
--------------------------------------------------------------
1. Add Students Information
2. Remove Student Information
3. Modify Student Information
4. Query Student Information
5. Print All Students' Information
6. EXIT
--------------------------------------------------------------
please enter your option:
1
Add Students Information
Please enter student's name
wangwu
Please enter student's ID
3456
Please enter student's age
19
Please enter student's gender(m/w)
woman
please check the information:(y/n)
Undergraduate{name = wangwu, age = 19, gender = WOMEN, id = 3456}
y
--------------------------------------------------------------
1. Add Students Information
2. Remove Student Information
3. Modify Student Information
4. Query Student Information
5. Print All Students' Information
6. EXIT
--------------------------------------------------------------
please enter your option:
4
Query Student Information
Please enter the student's id you want to query:(enter "exit" to exit current option)
2345
The student's informations are as follows.
Undergraduate{name = lisi, age = 20, gender = WOMEN, id = 2345}
--------------------------------------------------------------
1. Add Students Information
2. Remove Student Information
3. Modify Student Information
4. Query Student Information
5. Print All Students' Information
6. EXIT
--------------------------------------------------------------
please enter your option:
4
Query Student Information
Please enter the student's id you want to query:(enter "exit" to exit current option)
4567
The student does not exist!
--------------------------------------------------------------
1. Add Students Information
2. Remove Student Information
3. Modify Student Information
4. Query Student Information
5. Print All Students' Information
6. EXIT
--------------------------------------------------------------
please enter your option:
3
Modify Student Information
Please enter the student's id you want to modify:
5467
The student does not exist!
--------------------------------------------------------------
1. Add Students Information
2. Remove Student Information
3. Modify Student Information
4. Query Student Information
5. Print All Students' Information
6. EXIT
--------------------------------------------------------------
please enter your option:
3
Modify Student Information
Please enter the student's id you want to modify:
1234
The student's informations are as follows.
Undergraduate{name = zhangsan, age = 18, gender = MAN, id = 1234}
please enter the infortion you want to modify:(name/id/age/gender/all)
id
Please enter student's ID
6789
Information is modified successfully!
--------------------------------------------------------------
1. Add Students Information
2. Remove Student Information
3. Modify Student Information
4. Query Student Information
5. Print All Students' Information
6. EXIT
--------------------------------------------------------------
please enter your option:
5
Print All Students' Information
id		name		gender		age
2345	lisi	WOMEN			20
3456	wangwu	WOMEN			19
6789	zhangsan	MAN			18
--------------------------------------------------------------
1. Add Students Information
2. Remove Student Information
3. Modify Student Information
4. Query Student Information
5. Print All Students' Information
6. EXIT
--------------------------------------------------------------
please enter your option:
3
Modify Student Information
Please enter the student's id you want to modify:
3456
The student's informations are as follows.
Undergraduate{name = wangwu, age = 19, gender = WOMEN, id = 3456}
please enter the infortion you want to modify:(name/id/age/gender/all)
gender
Information is modified successfully!
--------------------------------------------------------------
1. Add Students Information
2. Remove Student Information
3. Modify Student Information
4. Query Student Information
5. Print All Students' Information
6. EXIT
--------------------------------------------------------------
please enter your option:
5
Print All Students' Information
id		name		gender		age
2345	lisi	WOMEN			20
3456	wangwu	MAN			19
6789	zhangsan	MAN			18
--------------------------------------------------------------
1. Add Students Information
2. Remove Student Information
3. Modify Student Information
4. Query Student Information
5. Print All Students' Information
6. EXIT
--------------------------------------------------------------
please enter your option:
2
Remove Student Information
Please enter the student's id you want to remove:
2345
--------------------------------------------------------------
1. Add Students Information
2. Remove Student Information
3. Modify Student Information
4. Query Student Information
5. Print All Students' Information
6. EXIT
--------------------------------------------------------------
please enter your option:
5
Print All Students' Information
id		name		gender		age
3456	wangwu	MAN			19
6789	zhangsan	MAN			18
--------------------------------------------------------------
1. Add Students Information
2. Remove Student Information
3. Modify Student Information
4. Query Student Information
5. Print All Students' Information
6. EXIT
--------------------------------------------------------------
please enter your option:
6
exit!

Process finished with exit code 0

```