# qtdist
Qt5 distribution

压缩: tar zcvf qt5.9.8_xx.tar.gz ./qt5.9.8_xx/
解压: tar -C ./qt5 -zxvf ./qt5.9.8_xx.tar.gz

```
Q1: git push 出现如下错误
    ERROR: Authentication error: Authentication required: You must have push access to verify locks
    error: failed to push some refs to 'https://programs@github.com/programs/qtdist.git'
    解决方法
    rm .git/hooks/pre-push
    git push
```