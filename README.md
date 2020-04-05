# orangeCat-py
基于flask的mvc框架
===
### 根据数据表创建model
1.自动生成model的语法如下:   
flask-sqlacodegen "mysql://root:root@127.0.0.1/movie_cat" --tables user --outfile "common/models/user.py"  --flask

