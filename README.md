# 35届腾飞杯作品网页文档
# 综合能源系统仿真优化平台开发

本地编译markdown文件到html请使用如下命令：
```shell
julia --project=docs/ -e 'using Pkg; Pkg.update(); Pkg.instantiate()'
julia --project=docs/ docs/make.jl
``` 

PS:`./src`中包含了文档中的一些代码与相关资源
