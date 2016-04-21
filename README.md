cfexam
======

试题练习系统

1. 将试题数据库导入MySQL中。[数据库脚本参考](https://github.com/cforth/cfexam/tree/master/tools/create_table.sql)。

2. 根据需要修改源代码中数据库名称和用户密码。

3. 打开网页，注册新的用户或登录。


试题导入方法

1. 将原试题文档根据试题类型分类，分别存入dxt.txt（单选题）， duo.txt（多选题）， pdt.txt（判断题）。

2. 通过tools\txt2sql\txt2sql.sh ，转为试题为数据库导入格式，自行修改文件首尾，使之成为数据库导入格式，并以.sql后缀保存。

3. 打开MySQL，通过命令导入试题数据库文件。
