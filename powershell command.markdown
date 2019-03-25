### powershell 常用命令

#### 1.文件系统类
    #创建文件夹
    mkdir folderName 

    #
    ls

    #
    cd folderPath

    #打开文件
    ./001.txt  #需要以带路径的形式打开，若不带路径则报错

    #重定向 （>、>>、<）
    ls > 001.txt  #输出当前路径文件列表到001.txt（若存在001.txt则会覆盖）
    ls >> 001.txt  #与上一条不同点，不会覆盖而是追加
    python spam.py < 001.txt  #将001.txt的内容作为输入源给spam.py使用

    #管道 （|）
    ls | sort -Descending Name  #将前一个操作的结果作为输入源给到下一个操作


#### 2.类型？
    #输出环境变量
    $env:name     #输出名为name的环境变量，与cmd不同，cmd直接name即可，如$env:path(ps) / path (cmd)

    # 列出系统所有变量
    ls env:


