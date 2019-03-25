### powershell 常用命令

#### 1.文件系统类
    #创建文件夹
    mkdir folderName 

    #
    ls

    #
    cd folderPath

    #重定向
    ls > 001.txt  #输出当前路径文件列表到001.txt（若存在001.txt则会覆盖）
    ls >> 001.txt  #与上一条不同点，不会覆盖而是追加

    #


#### 2.类型？
    #输出环境变量
    $env:name     #输出名为name的环境变量，与cmd不同，cmd直接name即可，如$env:path(ps) / path (cmd)

    # 列出系统所有变量
    ls env:


