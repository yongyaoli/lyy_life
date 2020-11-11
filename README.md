# lyy_life
lyy_life


---
- pypi 注册账号密码
[pypi网址](https://pypi.org/)
- 安装twine
```
pip install twine
```
- 编译
```
python setup.py sdist
```
- 上传 (需要输入pypi注册的账号密码)
```
twine upload dist/*
``