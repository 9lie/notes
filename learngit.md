# git学习笔记

## 配置git

```
git config --global user.name <用户名>

git config --global user.email <邮箱>
```

## 生成sshkey

```
ssh -keygen
```

一直回车就可以

在 https://github.com/settings/keys 中添加 id_rsa.pub中的内容

```
ssh -T git@github.com
```

用于测试是否成功连接服务器
第一次要打 **yes**

## 基本命令

```
git clone <仓库地址>

git add <文件>

git status

git commit -m '提交信息'

git commit -am '提交信息'

git push origin master
```
