# 點以下連結測試程式


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/maloyang/lstm_test/)

----

- 查版本 `conda -V`

- 查看有幾個虛擬環境 `conda env list`

- 建立新環境： `conda create --name py37lstm python=3.7.1`

- 啟用虛擬環境： `conda activate py37lstm`

- 直接安裝： `pip install tensorflow==2.3.0 pandas==1.3.5 statsmodels==0.12.2 matplotlib jupyter`
或是用使用requirements.txt安裝： `pip install -r requirements.txt`
- 使用requirements.txt安裝時需要先建立以下檔案
```
tensorflow==2.3.0
pandas==1.3.5
statsmodels==0.12.2
matplotlib
jupyter
```

- 安裝完成後，再啟用jupyter，下指令: `jupyter-notebook`

- 這時教材都放到個人資料夾中的Documents（文件）中，我們就可以直接使用jupyter開啟程式

----
- 未來開啟程式都需要執行：
```
conda activate py37lstm
jupyter-notebook
```
