
#### ENOSPC Error


```
npm dedupe
# If not work, TRY
# This will increase the limit for the number of files you can watch
echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
```


#### Clean && Delete

*  delete blog file in source/_post/xxx.md xxx.html xxx/_
*  delete db.json file directly
*  hexo clean

## 图片链接失效

[修复hexo-admin图片无法正确链接问题](https://www.hjliao.cn/2019/04/04/hexo-admin%E5%9B%BE%E7%89%87%E6%97%A0%E6%B3%95%E6%AD%A3%E7%A1%AE%E9%93%BE%E6%8E%A5%E9%97%AE%E9%A2%98/)  
[hexo引用本地图片无法显示](https://850552586.github.io/2018/11/15/hexo%E5%BC%95%E7%94%A8%E6%9C%AC%E5%9C%B0%E5%9B%BE%E7%89%87%E6%97%A0%E6%B3%95%E6%98%BE%E7%A4%BA/)  
