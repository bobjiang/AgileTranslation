# 敏捷翻译社
由一群热爱敏捷的翻译小伙伴自发组织的社群，致力于把优秀的英文敏捷文章带给更多的中国读者

## 目录说明
articles/ - 翻译后文章目录，文件名为<issue_name>.md  
docs/ - 博客目录， hosted by github page  
xxx/ - xxx是独立的一本电子书

## 加入我们
请先联系BoB Jiang（微信：bob_jiang_xinbao）  
备注：敏捷翻译社

## 我可以做什么
* 选题（帮忙寻找优秀英文资源）
* 翻译
* 校对（审校）
* 发布（编辑）


## 工作分工

### 寻找优质英文素材
1. 寻找优质英文素材
2. 与作者联系是否可以翻译成中文
3. 取得授权后，每一篇文章新建一个issue
4. 在issue内注明原文链接，同时可以复制原文文本到issue内

### 翻译
1. 到issue中找到自己感兴趣的文章
2. 下面留言领取本篇文章
3. fork [敏捷翻译社仓库](https://github.com/bobjiang/AgileTranslation/)
   1. 本地仓库新建分支，分支名字如`translating/issue-name.md`，
   2. 在articles目录内新建issue-name.md文件。文件名以issue的名字一致。例如\<issue_name\>.md
   3. 在上述文件内进行翻译，翻译完成后，提交到本地仓库分支
   4. 发起一个pull request, 从刚才新建的分支（translating/issue-name.md）merge到敏捷翻译社仓库的translating分支
   5. 至此，翻译结束。如果审校完需要修改的地方，会再次修改后重新提交。  
4. branch (不熟练fork的小伙伴，看这里)
   1. clone bobjiang/AgileTranslation [敏捷翻译社仓库](https://github.com/bobjiang/AgileTranslation/) 到本地；
   2. 按目录要求，在合适的目录，新建issue-name.md文件。文件名以issue的名字一致。例如\<issue_name\>.md；
   3. 在上述文件内翻译，完成后，提交到translating分支；
   4. issue状态更新到“审核中”，审核完有需要修改的地方，修改后再次提交到translating分支；
   5. 管理员会对不同branch分支，根据需要设置权限和Pull Request要求；

### 审校
1. 到pull request打开open状态的pull request
2. 仔细审校翻译的文章，并填写相对应行的审校意见
3. 提出审校意见（同意或需要修改）
4. 如果同意，等待merge到translating分支
