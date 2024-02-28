# PaperNote

## 论文阅读笔记

### 2024/02/26

## Project Purpose

记录论文的阅读笔记的数据库，方便后续查阅

## 主要内容

- 1、论文归类
- 2、论文名称
- 3、论文作者和
- 4、发表单位
- 4、杂志名称
- 5、论文发表时间
- 6、论文摘要Abstract
- 7、论文关键词
- 8、论文引用格式
- 9、doi
- 10、论文链接
- 11、论文阅读笔记
- 12、论文全文pdf版本-路径

### 论文格式 format

数据库：sqlite3

|序号|论文分类|论文名称|论文作者|发表单位|杂志名称|论文发表年份|关键词|论文摘要|引用格式|doi|论文链接|论文阅读笔记|论文全文pdf版本路径|保存时间|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|ID|Cat|Title|Author|Affil|Journal|Year|KeyWord|Abstract|Citation|Doi|Link|Summary|SavePath|Timestamp|
|integer|Text|Text|Text|Text|Text|Date|Text|Text|Text|Text|Text|Text|Text|DateTime|


## 论文信息爬虫开发

- 爬虫名称：PaperNoteSpider
- 爬虫网站：
  - [sciencedirect](https://www.sciencedirect.com)
  - [pubmed](https://pubmed.ncbi.nlm.nih.gov/)
  - [webofscience](https://www.webofscience.com/wos/alldb/advanced-search)
  - [cnki](https://kns.cnki.net/kns8s/)
  - [acs](https://pubs.acs.org/)
- 爬虫目标：获取论文名称、作者、单位、杂志名称、发表时间、摘要、关键词、doi、链接、阅读笔记

## 数据库开发

- 数据库名称：PaperNoteDB
- 数据库版本：MySQL 8.0.30

## UI界面开发

- 界面名称：PaperNoteUI
- 界面语言：Python
- 界面开发工具：Qt6
- 数据库连接通讯
