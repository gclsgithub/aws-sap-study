1.习题1
![xiti1.png](../images/xiti1.png)

> 这里的问题应该是出现了Rate exceeded 错误。错误的原因是没有删除策略。从而使得错误积累再队列中。
> 
> B删除的是Lambda目标，显然不对，删除的应该是消息队列中的消息通知。
> 
> E选项也是同样的道理
> 
> F因为是集群架构，这样单个读取调用API肯定无法满足需求。

2.习题2
![xiti2.png](../images/xiti2.png)

3.习题3
![xiti3.png](../images/xiti3.png)

4.习题4
![xiti4.png](../images/xiti4.png)

4.习题5
![xiti5.png](../images/xiti5.png)