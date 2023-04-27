# go_trancation_center

## 业务场景
某天活动，某人在某平台用A价格拍下某商品，市场价格为B元，中间利润为（B-A）元。但某人并没有销售渠道，需要通过渠道商将商品售出，渠道商从中抽层C元。则实际收益为（B-A-C）元

### 四色原型图分析
（1）时刻-时间段原型（Moment-Interval Archetype）

原型简称MI，表述的是某刻或某段时间内发生的一件事，比如：租房合同签署，是在某个时刻签署的，它有发生日期、行为人；租房行为是在一段时间内发生的，它有开始、结束时间和退租行为。这些我们都是可以通过此原型来表达的。在画原型图时，采用粉红色表示。

（2）参与方-地点-物品原型（Part-Place-Thing Archetype）

原型简称PPT，用来表示参与某个活动的人或物，地点则是活动的发生地。比如签署租房合同这个行为，合同、承租人分别对应这里的物、人，中介办公室对应这里的地点。在画原型图时，使用绿色表示。

（3）描述原型（Description Archetype）

原型简称DESC，是对PPT公共属性的描述，拿“签署租房合同”这个场景为例，在合同中会有一些租期、租金、押金、违约条件等约定，这些约定信息便可采用DESC原型来描述。绘制原型图时，采用蓝色表示。

（4）角色原型（Role Archetype）

原型简称Role，这里的角色，就是我们平时所理解的“身份”。以“签署租房合同”这个场景为例，签署行为人有承租人和中介工作人员，这里的角色便是指“承租人”和“中介工作人员”。绘制原型图时，采用黄色表示。


 
## 项目