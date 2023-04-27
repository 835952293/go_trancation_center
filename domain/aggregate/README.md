### 聚合
聚合是一组具有内聚关系的领域对象（包括实体和值对象）的集合，这里的一组可以是一个或多个实体。每个聚合都会有一个根实体（亦称聚合根），它主要用来和外界交互，即外部对象如果想访问聚合内的实体，必须先访问聚合根，然后聚合根再和内部要访问的实体进行交互。

还是拿“有赞精选内容平台”举例说明，一篇博文中，它包含博文基础信息（内容、标题等）、关联的商品信息、关联的标签信息等，这一组合就是一个聚合，其中，“博文基础信息”可以设置为这个组合的聚合根。