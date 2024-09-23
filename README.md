git study 

### 1. 基本命令

```ssh
git remote -v     # 查看本地仓库和远程仓库的名字
git diff          # 默认是比较本地未添加 和本地缓存
git ls-files      # 查看本地仓库内的文件

git log --oneline  #查看提交日志
git reflog         #查看历史提交记录
git reset  --soft   # 软重置   本地，缓存 都保留
git reset  --hard   # 应重置    本地，缓存 都不要
git reset  --mixed   # 不加参数为默认   本地保留， 缓存清理掉    使用场景， 多次add  commit  多次记录， 可以reset --mixed  版本号， 保留本地，清理掉多次缓存的，然后提交本地内容到仓库
```
