# XMU'18 OOAD Database Working Group
This repo contains Public Releases and Offical Resources from XMU'18 OOAD Database Working Group

## Resources
 * [sql脚本](https://github.com/Black-W/DatabaseStandard/blob/master/sql/init.sql)
 * [数据字典](https://github.com/Black-W/DatabaseStandard/blob/master/%E6%95%B0%E6%8D%AE%E5%AD%97%E5%85%B8.md)
 * [架构设计图](https://raw.githubusercontent.com/Black-W/DatabaseStandard/master/%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1%E5%9B%BE.bmp)
 * [外键图](https://github.com/Black-W/DatabaseStandard/blob/master/%E5%A4%96%E9%94%AE%E5%9B%BE.png)
 * [策略表说明](https://github.com/Black-W/DatabaseStandard/blob/master/%E7%AD%96%E7%95%A5%E8%A1%A8%E8%AF%B4%E6%98%8E.md)

 ## 支持软件
 * MySQL 5.7

 ## 修订记录
| 版本 | 出版日期 | 修订内容 | 作者 | 
| --- | --- | --- | --- |
| 1.0 | 2018.12.12 | 初稿 (表中暂未插入数据)| 数据库标准组  |
| 2.0 | 2018.12.15 | 新增表：<br>team_and_strategy <br> team_or_strategy <br>course_member_limit_strategy <br> <br>删除表：<br>member_sex_strategy<br> <br>修改表：<br> - student.sex <br> * team team.is_valid -> team.status <br>  * student.email -> 允许为空 <br> * klass_seminar.status 类型改为 tinyint unsigned<br>* 纠正 attendance.report_url 拼写错误<br>* 删除所有表名中的 _table 后缀 <br> * 修改所有 decimal 字段为无符号 <br>* course、team、seminar的name扩展为varchar(30) <br> <br>新增文件：<br>策略表说明 .md <br>外键图.png| 数据库标准组  |