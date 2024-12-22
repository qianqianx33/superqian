# superqIAan

1. **上传或下载二进制文件到您的VPS**。您可以使用 `wget` 命令从发布页面下载。例如：
    
    ```bash
    wget https://story-geth-binaries.s3.us-west-1.amazonaws.com/story-public/story-linux-amd64-0.11.0-aac4bfe.tar.gz
    
    # 解压文件
    tar -xvzf story-linux-amd64-0.11.0-aac4bfe.tar.gz
    
    # 查看解压后的文件
    ls
    ```
    
    ```bash
    wget https://github.com/piplabs/story-geth/releases/download/v0.9.4/geth-linux-amd64
    ```
    

1. **授予二进制文件执行权限**：
    
    ```bash
    chmod +x story-geth
    chmod +x story

    ```
