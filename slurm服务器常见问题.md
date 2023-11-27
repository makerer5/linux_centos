1）无法启动conda环境
在slurm系统的服务器上，我们必须提交作业到计算节点，任务才能运行
如果我们写的.sh中conda环境无法正常进入，PS：conda activate spades
则换另一种方式进入conda环境
sources /home/data/miniconda3/envs/spades/bin/activate
但我们经常在"miniconda3/envs/spades/bin/"目录下无法找到"activate"文件
我们只需要复制一份"actvate"文件到该目录系统下，就可以正常启动了
