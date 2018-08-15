# imooc-webSecurity

## web前后端漏洞分析与防御技巧

* xss：跨站脚本攻击

    存储型，反射型

    * 防御：

        * 浏览器自身过滤
        * 黑白名单过滤（xss的库）
        * csp: 内容安全策略

* csrf:跨站请求伪造

    * 不访问目标网站的前端
    * referer为B网站

* 点击劫持：目标网站作为iframe嵌入到攻击者网站中，opacity为0
    
    * js禁止内嵌
    * http头：X-FRAME-OPTIONS禁止内嵌 DENY
    * 其他辅助手段（验证码：增加操作的门槛）