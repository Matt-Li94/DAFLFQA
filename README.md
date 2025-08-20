# DAFLFQA
The repository of article “DAFLFQA：Dual Attention Fusion for Light Field Quality Assessment” 
这个仓库包括了脚本、网络和分割好的数据集。
分别在下面三个链接：
网络：Nets 链接: https://pan.baidu.com/s/1EGj44ylCqNWHqLiXj5_QsA?pwd=3yi2 提取码: 3yi2
数据集：Dataset 链接: https://pan.baidu.com/s/19ST7sunaqZDd1cEaik--pg?pwd=45ra 提取码: 45ra
脚本：Script 链接: https://pan.baidu.com/s/1tds_3v1zA3vvsHKBP9aJqQ?pwd=kezt 提取码: kezt

脚本里面包含了可复现论文中表2的结果 运行就可以得到和论文中一样的结果
由于已经打包好了二进制可执行文件，所以不需要额外配置环境，直接下载运行以下命令就行了

其中脚本里面包含了二进制文件和新编写的脚本，任选其中一个运行就行。
例如：对于二进制可执行文件执行如下命令：
./core_tester your_weights_path your_dataset_path
或者 可以运行编写的脚本
python run_test.py your_weights_path your_dataset_path

