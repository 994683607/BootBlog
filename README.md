**Ľ����ʵս�γ���Ŀ-����Spring boot���͵Ĵ�̳�**
**����ջ**
 * ��ˣ� SpringBoot+ElasticSearch+SpringSecurity

 * ǰ�ˣ� Thymeleaf/Bootstrap/jQuery
 * ���ݿ⣺MySQL/MongoDB/H2
 * �������� jdk 1.8
 * ����ƽ̨ Idea 2018 +win10
 ------
��Ŀ��飺

[Ľ������Ƶ���](https://coding.imooc.com/class/125.html)
��ĿԴ�룺

[github�ֿ�Դ������](https://github.com/994683607/BootBlog)

Ŀ¼���£�
![���������ͼƬ����](https://img-blog.csdnimg.cn/20181120195552456.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1MTgwOTcz,size_16,color_FFFFFF,t_70)

�ֿ����

```
|--MyBlog-auth: ������֤
|--MyBlog-blog: 
|--MyBlog-catalog  ������๦��
|--MyBlog-comment  �������۹���
|--MyBlog-prototype  ����
|--MyBlog-search       ������������
|--MyBlog-tag            �����ǩ����
|--MyBlog-user        �����û�����
|--MyBlog-vote:        ������޹���
|--MyBlog-index:        ������Ŀ
elaseticsearch: ES�ͻ���
springbootEs������ES�Ĺ�����Ŀ
���ͽ�ѧԴ�룺Ľ����Դ�루�ο����еľ�̬��Դ��
```
ע�� ���������ǵ������������Ǿۺ���Ŀ�����ʼ�Ļ�����Ŀ��������Ŀ�ټ����¹������ǩ�����ޣ����۵Ⱥ�������

-----
**�Ѿ���ɵĹ��ܣ�**
1.��ҳ����      
2.�������
3.�û�����      
4.���۹���
5.��ɫ����      
6.���޹���
7.Ȩ�޹���     
8.��ǩ����
9.���͹���     

-------
#  ������Ŀ
1.[����Դ��(https://github.com/994683607/BootBlog)������ѹ��
2.������Ŀ��ΪMyblog-index��Ŀ��idea������pom.xml���ɣ��������¡�

![���������ͼƬ����](https://img-blog.csdnimg.cn/20181120200709371.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1MTgwOTcz,size_16,color_FFFFFF,t_70)
![���������ͼƬ����](https://img-blog.csdnimg.cn/20181120200728967.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1MTgwOTcz,size_16,color_FFFFFF,t_70)
3.����mysql������Ҫ������������������в鿴mysql�����Ƿ�������ͨ�����ݿ���ӻ������½����ݿ�db_testboot(��application.properties�������ݿ���)ע��
����Ҫ��������Ŀ���Զ�����������application.properties�С�

![���������ͼƬ����](https://img-blog.csdnimg.cn/20181120201023662.png)

�ر�ע����Ҫ����ͼ����ط���Ϊ����
![���������ͼƬ����](https://img-blog.csdnimg.cn/20181120201119423.png)
�����Զ��������á�
4.����ES������github�����ص�ѹ����������elasticsearch.bat��
![���������ͼƬ����](https://img-blog.csdnimg.cn/20181120201219767.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1MTgwOTcz,size_16,color_FFFFFF,t_70)
5.�����ļ�����������Mongodb-file-server������Ҳ��git��ѹ������
![���������ͼƬ����](https://img-blog.csdnimg.cn/20181120201319813.png)
------
6.�����ļ���������MyBlog-index��springboot�������FileApplication.java��8081�˿ڣ���
MyBlogApplication.java��8080�˿ڣ�
7.���ԣ�
*����127.0.0.1:8081�����ļ���������ַ��
![���������ͼƬ����](https://img-blog.csdnimg.cn/20181120201823452.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1MTgwOTcz,size_16,color_FFFFFF,t_70)
����127.0.0.1:8080/index��
![���������ͼƬ����](https://img-blog.csdnimg.cn/201811202028369.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1MTgwOTcz,size_16,color_FFFFFF,t_70)
API���Թ��ߣ�[swagger���](https://blog.csdn.net/qq_35180973/article/details/84191759)��
�����ַ[http://localhost:8080/swagger-ui.html#!/admin-controller/listUsersUsingGET](http://localhost:8080/swagger-ui.html#!/admin-controller/listUsersUsingGET)
![���������ͼƬ����](https://img-blog.csdnimg.cn/20181120203048824.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1MTgwOTcz,size_16,color_FFFFFF,t_70)


-----
# Ľ������ҳԤ��              
![���������ͼƬ����](https://img-blog.csdnimg.cn/20181120200138673.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM1MTgwOTcz,size_16,color_FFFFFF,t_70)