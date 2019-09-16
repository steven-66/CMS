## JavaWeb CMS(customer management system)

### function:

- add customer:add customer's info including name, age, gender, email
- 查询客户:查询数据库中所有的客户，查询结果将客户信息以列表的形式给出，可以对列表中的客户信息进行编辑及删除
- 高级搜索:多条件组合在数据库中进行客户信息的查询，搜索结果以列表的形式给出，可以对列表中的客户信息进行编辑及删除
- 新增分页功能，逻辑很强。
 
### technique

- database query
- c3p0 database connection pool
- using dbutil.jar encapsulating form into java bean
- using dbutils.jar to simplify database query
- JavaWeb MVC three layer
- servlet redirection encapsulation
- reflection

## prepared work
1.import third-party package and c3p0 property file

- c3p0.jar
- mchange-commons.java.jar
- commons-beanutils.jar
- commons-dbutils.jar
- commons-logging.jar
- self-implemented itcast-tools.jar
- jstl.jar
- mysql-connector-java.jar

2.build package

- dao
- service
- servlet
- domain

## build environment
eclipse + MySQL

