# dongchedi_spider
用于爬取懂车帝所有车型的口碑评价内容：

'data_dongchedi.csv'文件包含cardid和carname字段，爬取过程中会需要读取carid，可以根据懂车帝对应车型的carid修改或添加’

'data_car_comment.csv'是懂车帝「理想L9」口碑评价的爬取结果

目前代码可以实现：懂车帝所有车型的口碑评价长文本爬取

暂时不能实现：长文本切分成短文本、更详细的车主评价（提车时间、rating、裸车价格、油耗、购买地点等）-- 这些信息还有待爬取
