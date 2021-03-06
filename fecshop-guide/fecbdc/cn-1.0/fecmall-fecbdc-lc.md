FecMall Fecbdc 多商户分销流程
=============




### 基本流程


> 分销系统的流程步骤

1.`分销平台`上线正式运营，发布信息，吸引`分销商`和`经销商`入驻

2.`经销商`招募后，分销平台给`经销商开账户`，`经销商`可以进入`经销商平台`，发布产品，查看订单等一系列的操作

3.`经销商`编辑发布产品后，在前端商城可以显示，终端用户可以进行购买下单，下单后，`经销商销售价格`和`经销商成本价格`的差值，
就是平台的`利润`

4.`分销商`,首先注册商城用户，然后申请成为`分销商`，通过后，正式成为`分销商`，
分销商在申请的时候可以填写`推荐人`，填写后，该`推荐人`成为其`父级分销商`，
当子分销商获取`分成利润`的时候，父级分销商也会获得一定的`分成利润`

> 注意：Fecbdc的分销体系，是有`分销级别`的（后面的章节会详细阐述），如果父级分销商的级别比子分销商级别低（或者相等），
那么子分销商获取利润后，父级分销商是获取不到利润的，
因此，父级分销商在拉人头的同时，还得提高自己的销量，晋升更高的等级，才会获取到子分销商的分成,对于分销商各个`等级`如何分成，
下一章节会详细阐述

5.分销商进行产品价格的自定义，以及首页产品的编辑

分销商可以在`分类`，`产品详细页面`查看产品，产品默认显示的，是分销商默认分销价格，
分销商可以对任何一个产品进行`分销价格自定义`，以及，将这个产品加入`分销商首页`。


6.分销商成本价格

`分销商成本价格`,可以理解成分销商的拿货价格，
系统以 经销商成本价格，平台附加价，分销商等级比率，通过公式，计算出来分销商的`分销商成本价格`

7.分销商分销价格

系统通过公式，在`分销商成本价格`的基础上，通过分销商默认利润比率，计算出来`分销商默认分销价格`
,分销商如果想调价格，可以进行  `分销商自定义分销价格`

通过分销商入口进来的用户，看到的就是`分销商分销价格`


8.终端用户如果经过分销商的`推广入口`进入，那么`用户下单`后，系统脚本会对该订单进行计算，算出来平台的`利润`，各个分销商的`利润`，分销商可以在
分销账户中心看到自己的业绩

9.如果终端用户将支付的订单，进行`订单取消`，`订单退货`等操作，那么分销商的提成将会`关闭`

10.平台对`分销商`，`经销商`的结算，将会以`月结`的方式进行结算，
三方都可以得到相应的利润，三方共赢。



**总结**：本部分只是对流程进行大致的介绍，详细的逻辑请在下面具体的章节中查看介绍。





















