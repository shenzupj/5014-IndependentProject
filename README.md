# 5014-IndependentProject
本项目为msbd5014的IP项目，题目为:'Alternative Financial Data Mining and Multi-modal Stock Prediction'。\
StockCrawler和ReportCrawler为爬虫代码，前者可以爬取股票价格，后者目前设置为爬取宏观研报。更改URL后可爬取个股或者行业研报。\
DataPreprocess为数据预处理代码。包括数据清洗，情感分析，数据合并等。应用‘个股研报’标题部分即可完成对个股研报的清洗和情感分析。\
StockPrediction为股价预测代码，应用论文中所给出的数据结构可直接于模型中进行学习及预测，可以将情感分数全部设置为0或1进行无情感分数模型的训练及预测。\
Data文件夹中为之前整理的部分研报信息（report中），以及部分股价信息和处理后数据（stock中）。\
以上代码均运行在JupyterNotebook中。
