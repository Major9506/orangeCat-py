# orangeCat-py(基于flask的mvc框架)
### 项目启动
1.安装依赖
``` python
pip install -r requirement.txt   
``` 
2.切换环境
``` python
export ops_config=local
```
3.启动项目
``` python
python manager.py runserver
```
### 根据数据表创建model
1.自动生成model的语法如下:
``` python  
flask-sqlacodegen "mysql+pymysql://root:root@127.0.0.1/movie_cat" --tables user --outfile "common/models/user.py"  --flask
``` 

