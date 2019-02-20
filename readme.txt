
# 1.创建虚拟环境

  mkvirtualenv -p python3 HMHome


# 2.安装依赖库

  pip install -r requirements.txt -i https://pypi.douban.com/simple/


# 3.创建数据库，导入测试数据
  详情见项目概述文件夹
# 4.运行

  gunicorn -c gunicorn.conf.py main:mgr
