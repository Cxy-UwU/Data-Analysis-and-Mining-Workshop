# 数据挖掘workshop
## 运行环境
运行前使用
```bash
pip install -r requirements.txt
```
安装所需的依赖

建议使用能够运行jupyter notebook的ide比如pycharm或者vscode

## 数据准备
将workshop指定的数据文件放在data目录下，确保其文件名为`anonymized_data_for_workshop.xlsx`

在data目录下预先创建一个sub目录。

## 运行
四个ipynb有严格的依赖关系和运行顺序，建议的顺序如下：
1. overview
2. corr
3. PCA_and_clustering
4. outlier_detect

前一个的所有单元成功运行后，才能运行下一个，否则可能会出现问题。