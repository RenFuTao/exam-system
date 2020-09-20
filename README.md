# exam-system 
#### 南京晓庄学院自动组卷系统--遗传算法生成试卷

###  项目梗概
   模拟生成试卷所需的种种情况，在确保题目数量及知识点覆盖率的情况下，生成合适的试卷；也可以选择自行选择题目，生成试卷，最后实现试卷的导出成word并下载
###  主要模块
#### 1.个人以及用户信息管理
   * 本系统的人员有三种级别，权限由低到高分别是试题录入人员、教师、管理员。
   * 管理员有权限对试题录入人员、教师的信息进行管理，以及对自己密码管理，除此之外，管理员有权新添试题录入人员以及教师；
   * 教师有权添加录入人员，以及对录入人员进行管理；
   * 试题录入人员只有权对自己的密码进行修改；
#### 2.题库管理
   * 试题录入人员只能进行试题录入和对试题的管理，包括对试题的删除、修改、查看、搜索；
   * 教师除了试题录入人员的功能外，还可以在书籍分类的基础上打印题库；对知识点进行管理，包括对知识点的增加、删除、修改、查看、搜索；
   * 管理员在教师的基础上，增加了题型管理，包括对题目类型的增加、删除、修改、查看；科目管理，包括对科目的增加、删除、修改、查看；对书籍的管理，包括对科目下的书籍信息进行增删改查的操作；
   * 导出题库；
 #### 3.试卷生成模块
   * 试卷录入人员没有权限操作此模块；
   * 教师和管理员在此模块下有两种操作：分别是生成试卷和提取现有试卷，生成试卷有自动和手动两部分，前端主要靠jQuery来提高用户体验，自动生成试卷采用自动组卷算法；
 #### 4.系统管理模块
   * 该模块仅供管理员发布一些系统消息使用；
   * 其中有系统设置模块，包括查看系统设置信息和设置系统设置信息；公告管理，包括查看公告信息和 设置公告信息。当然，公告信息是任何人都可以看到的；
   * 数据库管理，包括备份数据库功能。
 ##### 5.开发关键字：
 win10 eclipse mysql Tomcat SSM Maven Hibernate validation log4j CKEditor4 Freemarker 遗传算法
 ### 6.项目中文件说明
* 其余目录结构均为eclipse生成maven项目的目录结构
* spring配置文件地址：根目录/WEB-INF/config/spring
* 其余配置文件地址：src/main/resources/
#### 7.系统架构
![系统功能架构](https://github.com/cppcpp/exam-system/blob/master/src/main/webapp/files/%E5%8A%9F%E8%83%BD%E6%9E%B6%E6%9E%84.png)
#### 8.代码架构
![代码架构](https://github.com/cppcpp/exam-system/blob/master/src/main/webapp/files/%E4%BB%A3%E7%A0%81%E6%9E%B6%E6%9E%84.png)
#### 9.遗传算法流程图
![遗传算法](https://github.com/cppcpp/exam-system/blob/master/src/main/webapp/files/%E9%81%97%E4%BC%A0%E7%AE%97%E6%B3%95%E6%B5%81%E7%A8%8B%E5%9B%BE.png)
###  部分页面展示
![登录页面](https://github.com/cppcpp/exam-system/raw/master/src/main/webapp/public/images/1.png)
![自动生成试卷页面](https://github.com/cppcpp/exam-system/raw/master/src/main/webapp/public/images/2.png)
![操作试卷页面](https://github.com/cppcpp/exam-system/raw/master/src/main/webapp/public/images/3.png)


#### 欢迎大家交流学习-_-
 
