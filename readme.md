#微信公众号批量抓取工具
##文件介绍
1. prepare_request.py这个文件.
2. new_crawl_wechet.py这个是最新的，主要就是将fiddler4获取到mp.weixin.qq.com的request和response获取到的txt解析然后
获取其中内容并放置到mysql中.
3. test.py 这个是方便自己调试函数的，没什么卵用，可以删除掉.

##技术含量
1. 恩，爬取微信除了让我比较难受以外没什么卵技术含量.

##其他
我是直接将fiddler截获文章列表然后通过requests获取文章头之类的信息，当然，你也可以就获取key然后每十几分钟再换一下。
至于如何批量获取key 我用按键精灵，如果嫌慢可以自己写脚本 也稳定.