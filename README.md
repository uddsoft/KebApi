# KebApi
API 文档简介
此Api接口是给Keb新零售移动终端扫码购物使用的数据接口。
接口总数：2
接口请求地址：http://kebapi.101222.com/api/v1/
1、getGoodsSort
   参数：无参
   功能：获取KebErp商品分类数据
2、getGoods
   参数：sortCode[string] pageIndex[int]
   功能：输入商品分类参数，和页面获取商品数据。
   备注：Id[数据库Id] BarCode[国际条码] GoodsName[商品名称] Price[价格] Brands[品牌]  Norm[规格] SortCode[分类编码]  Unit[单位]
   
