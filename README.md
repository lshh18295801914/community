## 吕尚昊社区

## 资料
[Spring文档](https://spring.io/guides)  
[spring的web文档](https://spring.io/guides/gs/serving-web-content/)  
[Github OAuth ](https://developer.github.com/apps/)  
[Github deploy key](https://developer.github.com/v3/guides/managing-deploy-keys/#deploy-keys)

## 工具
[Git](https://git-scm.com/)

## 脚本
```sql
create table USER
(
    ID           int   auto_increment,
    NAME         VARCHAR(50),
    ACCOUNT_ID   VARCHAR(100),
    TOKEN        CHAR(36),
    GMT_CREATE   BIGINT,
    GMT_MODIFIED BIGINT,
    constraint USER_PK
        primary key (ID)
);
```