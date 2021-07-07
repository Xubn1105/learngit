git add 文件名 //将文件上传至git中
git commit -m "文件标题"

git reset --hard HEAD^ //版本回滚命令 ^的个数代表回滚的次数
git reset --hard commit_id //版本回滚再滚回来 commit_id 可以通过git log来查看

git reflog  //查看历史命令
