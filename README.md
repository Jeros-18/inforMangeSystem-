# inforMangeSystem-
高校人员信息管理系统
对高校人员信息的增删改查，登录，菜单，文件

高校人员信息管理系统设计
1、问题描述
某高校有四类员工：教师、实验员、行政人员，教师兼行政人员；共有的信息包括：编号、姓名、性别、年龄等。其中，教师还包含的信息有：所在系部、专业、职称；实验员还包含的信息由：所在实验室、职务；行政人员还包含的信息有：政治面貌、职称等。
2、功能要求
（1）添加功能：程序能够任意添加上述四类人员的记录，可提供选择界面供用户选择所要添加的人员类别，要求员工的编号要唯一，如果添加了重复编号的记录时，则提示数据添加重复并取消添加。（2）查询功能：可根据编号、姓名等信息对已添加的记录进行查询，如果未找到，给出相应的提示信息，如果找到，则显示相应的记录信息。（3）显示功能：可显示当前系统中所有记录，每条记录占据一行。（4）编辑功能：可根据查询结果对相应的记录进行修改，修改时注意编号的唯一性。（5）删除功能：主要实现对已添加的人员记录进行删除。如果当前系统中没有相应的人员记录，则提示“记录为空！”并返回操作；否则，输入要删除的人员的编号或姓名，根据所输入的信息删除该人员记录，如果没有找到该人员信息，则提示相应的记录不存。
（6）统计功能：能根据多种参数进行人员的统计。能统计四类人员数量以及总数，统计男、女员工的数量。
（7）保存功能：可将当前系统中各类人员记录存入文件中，存入方式任意。
（8）读取功能：可将保存在文件中的人员信息读入到当前系统中，供用户进行使用。
3、问题的解决方案
根据系统功能要求，可以将问题解决分为以下步骤：
（1）应用系统分析，建立该系统的功能模块框图以及界面的组织和设计；
（2）分析系统中的各个实体及它们之间的关系；
（3）根据问题描述，设计系统的类层次；
（4）完成类层次中各个类的描述；
（5）完成类中各个成员函数的定义；
（6）完成系统的应用模块；
（7）功能调试；
（8）完成系统总结报告。
