# 前言

欢迎来到基于SSM的在线考试系统vue版项目。该项目旨在为广大开发者提供一个简洁、易用、高效的在线考试系统。本项目采用Java语言，结合Spring、SpringMVC和MyBatis框架，前端使用Vue、JS和CSS3技术。以下是本项目的详细说明。

## 内容介绍

基于SSM的在线考试系统vue版主要包括以下功能模块：学生管理、教师管理、科目管理、题目管理、考试管理、成绩管理等。系统采用B/S架构，用户通过浏览器即可完成考试、查看成绩等操作。为了提高开发效率和项目质量，本项目遵循MVC设计模式，后端提供RESTful API供前端调用。

## 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是一段关于题目管理的核心代码：

```java
// QuestionMapper.xml
<mapper namespace="com.exam.mapper.QuestionMapper">
    <!-- 查询题目列表 -->
    <select id="listQuestions" resultType="com.exam.entity.Question">
        SELECT * FROM question
        WHERE subject_id = #{subjectId}
        ORDER BY id ASC
    </select>
</mapper>

// QuestionService.java
public List<Question> listQuestions(Integer subjectId) {
    return questionMapper.listQuestions(subjectId);
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/339016/19/6386/121028/68b8851aF6acd621d/b9df0e5d0d95d2c9.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/328148/3/15737/59130/68b884efF56083f45/dcbc0e77ae61a1c0.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/339784/9/6317/27734/68b884f0F801821df/a05cec5ce2d396b0.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/327600/13/15694/34412/68b884f1Fe934868e/40dfbe9a74ad20ae.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/328366/14/15625/40454/68b884f2F6b5a8a9f/b7650949a07c5ddb.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/327006/35/15579/41442/68b884f3F706ecc33/b129566e8f90ff3d.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/337002/18/6301/39041/68b884f5F3f0cbcc9/38f7d428b415662d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/293515/31/13217/55765/68b884f6F926793f3/dc21ce7afbeaa4e4.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/326673/34/15471/32748/68b884f7Fcc091aa3/1473ae8b2ea3b53f.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/323787/21/15739/35574/68b884f9Fb9363277/7a5237ac6c68662a.jpg)
