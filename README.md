# golang-study

            ______________
            ___________(_)__  /
            ___  /____  /__  / 
            __  /____  / _  /  
            _____/__  /  /_/   
               /___/  2021 day day up
     
    我的 Go 语言学习之路，目的构建清晰知识体系，以及一些简单的demo
## env

- GOBIN

> go install命令安装的目录
    
- GOROOT

> golang的安装路径

- GOPATH 

    > 工作目录 , go命令依赖的一个重要环境变量：$GOPATH

    > 例如：
                                                  
        GOPATH="/Users/zjl/golang_study"
    
    > 当有多个项目的时候可以设置多个
                                                                                                                                                             
        例如：
        GOPATH="/Users/zjl/go_project1;/Users/zjl/go_project2;/Users/zjl/go_project3;"  

    - bin
     
    > golang编译可执行文件存放路径
    
    - pkg
     
    > golang编译包时，生成的.a文件存放路径
    
    - src 
    
    > 源码路径
    
    > 按照golang默认约定，go run，go install等命令的当前工作路径（即在此路径下执行上述命令）

## 引入外部包

- go get
- go module
- vendor目录