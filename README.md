# GitHub-Handbook
我与GitHub的恩怨情仇

## 一些值得参考的文章：
1. [GitHub上传以及常见问题](https://blog.csdn.net/qq_39208536/article/details/116275201)    

  PS. 文章漏掉的一个指令：  
  > git commit -m "first commit"
2. [GitHub上传以及后续修改上传](https://blog.csdn.net/weixin_43632918/article/details/116400953)  
 
 
以下代码可用于回退commit版本
> git reflog  
git reset -- hard 5380189  
push origin -f

**【Attention!!】** 此代码会强制覆盖当前分支，请注意备份
> git push -u origin main -f  

