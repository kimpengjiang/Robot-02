# Robot-02   
爬取今日头条摄影集   
    
01版本：只能爬取单页面   
bug：暂无
     
02版本：可指定爬取多少次    
bug：无法获取完整“相关推荐”的链接    
    
03版本：修复了02版本的问题    
bug：出现”ConnectionResetError: [WinError 10054] 远程主机强迫关闭了一个现有的连接“问题；爬取过程中cpu负载高    
     
04版本：加入socket超时设定，貌似解决了03的问题，但又出现了个新问题--“相关推荐”里的照片并不能无限循环下去，当我在爬取到30-35次时，“相关推荐”里出现的全是已经爬取过的内容……    
   
环境：python3.7
