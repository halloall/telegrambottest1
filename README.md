# telegrambottest1     
 实例 @zaihuatest1bot     
 这是为telegram在花群做的bot,目前还在开发,开发结束以后应该别人就用不了了 https://t.me/zaihuachat    
 部署很容易,先像@BotFather 申请机器人,再开一个cloudflare worker免费账户,将bot.js 复制过去,最后像下面那样即可     
    
实例部署在cloudflare上, 设置boot的webhook许多文章都没写清楚, 我这里尽可能写清楚一点, 用浏览器访问(curl也可以,但哪个简单不用我说了把)    
https://api.telegram.org/bot   
然后直接加你获得的tooken   
/setwebhook?url=    
以cloudflare为例,就是cloudflare给你分配的url,或者你你可执行文件所在的位置     
     
最后连起来   
应该像      
https://api.telegram.org/bot123456:uibewuibci/setwebhook?url=https://site.username.cloudflare.com     

致谢:
https://github.com/my-telegram-bots/hitokoto_bot    开始的动力和教程,最早的源代码也是从start.js复制过来的
