

1.   页签显示组件：

2.   页签修改组件：

3.   healthBoard 组件

     *   product 、 productBranch 过滤

     *   数据图表组件 （key 为 titile 标识符）

4.   看板数据展示组件

     

### 看板主页

*   create
    1.   获取station，
    2.   get product from station    (product resource, include product branch )
    3.   get  healthBoard from   station , product  and product branch
*   mount：
     	1.  delivery healthPage   to 看板页签
     	2. healthPage --> initialize  stage object  -->       healthBoards  --> 不同的数据图表组件  （default   is not sorted  ）
*   method:





**排序做成一个接口 ，都是后端资源获取的接口，将 health_board 看作一种资源，传递product ,product_branch 的名字，做到父组件，增删该查都做到父组件 ，采用vue中的监视属性去监视 增删改查，排序这四种操作。 ** 

### healthBoard 组件

*   method :

### 看板页签 组件

 * 展示数据即可

**页签展示组件**
