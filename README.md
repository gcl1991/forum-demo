这里是教程英文原址:https://code.tutsplus.com/tutorials/how-to-create-a-phpmysql-powered-forum-from-scratch--net-10188<br/>
参照极客时间陈皓在：70|程序员练级攻略：零基础启蒙，中所布置的Blog任务<br/>
已经完成:<br/>
1 用户登录和注册（不需密码找回）。<br/>
2 用户发贴（不需要支持富文本，只需要支持纯文本）。<br/>
3 用户评论（不需要支持富文本，只需要支持纯文本）。<br/>
4 用户登录时的密码不应该保存为明文，应该用 MD5+Salt 来保存（关于这个是什么，希望你能自行 Google）。<br/>
5 用户登录后，对于用户自己的贴子可以有“重新编辑”或 “删除”的功能，但是无权编辑或删除其它用户的贴子。<br/>
6 图片验证码。<br/>
7 上传图片。<br/>
未完成:<br/>
1 阻止用户在发文章或评论时输入带 HTML 或 JavaScript 的内容，https://excess-xss.com/。<br/>
2 防范 SQL 注入,https://www.php.net/manual/zh/security.database.sql-injection.php,https://docs.microsoft.com/zh-cn/previous-versions/sql/sql-server-2008-r2/ms161953(v=sql.105)?redirectedfrom=MSDN。<br/>