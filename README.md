# SQL

## 软件简介

MySQL是世界上最受欢迎的开源数据库。凭借其经过验证的性能，可靠性和易用性，MySQL已成为基于Web的应用程序的领先数据库选择，覆盖从个人项目和网站，电子商务和信息服务到高端的整个范围网络资源包括Facebook，Twitter，YouTube，Yahoo!等等。

所属类别是编程语言

特点：

1．使用 C和 C++编写，并使用了多种编译器进行测试，保证了源代码的可移植性。

2．支持 AIX、FreeBSD、HP-UX、Linux、Mac OS、NovellNetware、OpenBSD、OS/2 Wrap、Solaris、Windows等多种操作系统。

3．为多种编程语言提供了 API。这些编程语言包括 C、C++、Python、Java、Perl、PHP、Eiffel、Ruby,.NET和 Tcl 等。

4．支持多线程，充分利用 CPU 资源。

5．优化的 SQL查询算法，有效地提高查询速度。

6．既能够作为一个单独的应用程序应用在客户端服务器网络环境中，也能够作为一个库而嵌入到其他的软件中。

7．提供多语言支持，常见的编码如中文的 GB 2312、BIG5，日文的 Shift_JIS等都可以用作数据表名和数据列名。

8．提供 TCP/IP、ODBC 和 JDBC等多种数据库连接途径。

9．提供用于管理、检查、优化数据库操作的管理工具。

10．支持大型的数据库。可以处理拥有上千万条记录的大型数据库。

11．支持多种存储引擎。

12.MySQL 是开源的，所以你不需要支付额外的费用。

13.MySQL 使用标准的 SQL数据语言形式。

14.MySQL 对 PHP 有很好的支持，PHP是目前最流行的 Web 开发语言。

15.MySQL是可以定制的，采用了 GPL协议，你可以修改源码来开发自己的 MySQL 系统。

16.在线 DDL/更改功能，数据架构支持动态应用程序和开发人员灵活性（5.6[4]  新增）

17.复制全局事务标识，可支持自我修复式集群（5.6[4]  新增）

18.复制无崩溃从机，可提高可用性（5.6[4]  新增）

19.复制多线程从机，可提高性能（5.6[4]  新增）

20.3倍更快的性能（5.7[5]  新增）

21.新的优化器（5.7[5]  新增）

22.原生JSON支持（5.7[5]  新增）

23.多源复制（5.7[5]  新增）

24.GIS的空间扩展（5.7[5]  新增）


## 软件官网

https://www.mysql.com/

## Dockerfile 使用方法

启动mysql服务器实例
启动MySQL实例很简单：

$ docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql:tag

... some-mysql您要分配给容器的名称是要为my-secret-pwMySQL root用户设置的密码，是指定tag所需MySQL版本的标签。

## 资源链接

- https://www.mysql.com/
