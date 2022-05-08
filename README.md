# Roger-Maven-Servlet3
=============
### 說明：這是一個使用intelliJ的 servlet3 + tomcat的專案 ###

# 如何啟動
1. 使用外部 tomcat:
   1. 在intelliJ中配置好外部tomcat，將專案war deploy
2. 使用內部 tomcat:
   1. 記得更新 pom.xml 中的 tomcat7 plugin版號為2.2，避免Unable to compile class for JSP
   2. 執行 mvn:tomcat7:run 即可使用內部tomcat將專案帶起
3. 測試URL
   1. http://localhost:8080/Roger-Maven-Servlet3/hello
   2. http://localhost:8080/Roger-Maven-Servlet3/index.jsp


# 參考資料
| #   | 說明                                                                                        | 網址                                                                                    |
|-----|:------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------|
| 1   | mvn servlet3 archetype                                                                    | https://github.com/maciejwalkowiak/servlet3-maven-archetype                           |
| 2   | 使用外部tomcat                                                                                | https://blog.judysocute.com/2020/02/23/%E7%AC%AC-3-%E9%80%B1-tomcat-servlet-intellij/ |
| 3   | Maven中使用tomcat:run出現錯誤org.eclipse.jdt.internal.compiler.classfmt.ClassFormatException     | https://www.796t.com/content/1544727247.html                                          |
| 4   | 使用idea測試maven項目環境 出現錯誤：org.apache.jasper.JasperException: Unable to compile class for JSP | https://www.twblogs.net/a/5c6146c0bd9eee06ee227fb7                                    | 