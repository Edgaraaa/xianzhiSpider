### 基于python3 将先知的文章通过关键字爬取到本地转为markdown格式，并建立本地图床
```
git clone https://github.com/Kit4y/xianzhiSpider
cd xianzhiSpider
pip install -r requirements.txt
python xianzhiSpider.py -s CTF -c 10 -p 1
```
生成的内容放于同目录output文件夹下
参数说明

- -s 需要查找的关键字，空代表按时间顺序爬取
- -c 需要文章的数目，默认30
- -p 是否需要建立本地图床，默认0 0代表不需要 1代表需要

![](1.png)

仅供学习，禁止商用行为