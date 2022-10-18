# phone_comments  
作者为学生科研项目而爬取的评论数据

数据规模如下：  
<img width="185" alt="phone_comments" src="https://user-images.githubusercontent.com/77054680/196384334-f0fd2d5b-d584-4fec-895a-fb1519e705cd.png">

本文爬取京东商城中华为，苹果，小米，vivo和三星5个品牌的部分手机评论，并将评论分划分为好评和差评两个类别，分别以数字1和0标记。  
爬取了总计有2万多条评论数据，每条长度3至500字符不等。将总数据集其按照7:3随机划分为训练集和测试集，再将测试集按照7:3划分为测试集和校验集。
