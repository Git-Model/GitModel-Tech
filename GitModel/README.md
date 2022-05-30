<h1 align="left">GitModel-Tech</h1>

<p align='center'>
    <a href='https://www.python.org/'>
        <img src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="Python" height="40"/>
    </a>
    <a href='https://jupyter.org/'>
        <img src="https://www.vectorlogo.zone/logos/jupyter/jupyter-icon.svg" alt="Jupyter" height="40"/> 
    </a>
    <a href='https://numpy.org/'>
        <img src="https://www.vectorlogo.zone/logos/numpy/numpy-icon.svg" alt="Numpy" height="40"/>
    </a>
    <a href='https://git-scm.com/'>
        <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" height="40"/>
    </a>
</p>

<h2 align='left'><b>算法大纲</b></h2>

<div align="center">

|算法目录|文件名称|注意事项|
|--|--|--|
|线性规划|linear.py|文件夹`programming/`下，依赖`numpy`与`sympy`|
|整数规划|integer.py|文件夹`programming/`下，依赖`numpy`与`sympy`|
|非线性规划|nonlinear.py|文件夹`programming/`下，依赖`numpy`与`sympy`|
|目标规划|goal.py|文件夹`programming/`下，依赖`numpy`与`sympy`|
|图与网络模型及方法|多个文件|文件夹`graph/`下|
|插值与拟合|多个文件|文件夹`fit/`下|
|微分方程建模|多个文件|文件夹`DE/`下|
|数理统计|多个文件|文件夹`statistics/`下|
|时间序列|多个文件|文件夹`time_series/`下|
|分类器|多个文件|文件夹`classifier/`下|
|多元分析|多个文件|文件夹`multivariate/`下|
|偏最小二乘回归分析|plsregress.py|文件夹`plsregress/`下|
|现代优化算法|多个文件|文件夹`optimization/`下|
|数字图像处理|多个文件|文件夹`image/`下|
|综合评价与决策方法|多个文件|文件夹`evaluation/`下|
|预测方法|多个文件|文件夹`predict/`下|

</div>

*多个文件*：主要指的是一般可以从书中子目录得到的算法大纲，可能要根据个人体会自己作出改动。

<h2 align='left'><b>项目结构（初版）</b></h2>

```textile
|- optimtool
    |-- programming
        |-- __init__.py
        |-- linear.py
        |-- integer.py
        |-- nonlinear.py
        |-- goal.py
    |-- graph
        |-- __init__.py
    |-- fit
        |-- __init__.py
    |-- DE
        |-- __init__.py
    |-- statistics
        |-- __init__.py
    |-- time_series
        |-- __init__.py
    |-- classifier
        |-- __init__.py
    |-- multivariate
        |-- __init__.py
    |-- plsregress
        |-- __init__.py
    |-- optimization
        |-- __init__.py
    |-- image
        |-- __init__.py
    |-- evaluation
        |-- __init__.py
    |-- predict
        |-- __init__.py
    |-- __init__.py 
```

<h2 align='left'><b>参考书籍</b></h2>

* 数学建模算法与应用（第2版）