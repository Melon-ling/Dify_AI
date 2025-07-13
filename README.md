* `Dify_AI.yml`文件为包含本项目服务的yaml源文件，基于Docker搭建本地Dify的详细教程可参考以下网址：https://blog.csdn.net/zhishi0000/article/details/147992745

* 搭建成功后，可以直接导入yml文件（即DSL）来进行调用

* ##### 运行步骤：

  * 将导出的` .yml` 文件放在适当目录（可选项目根目录）

  * 进入包含`.yml`文件的目录下（若在根目录下，在根目录下进行下面操作即可）

  * 启动`Dify`服务:  

    ```bash
    `docker-compose up -d`
    ```