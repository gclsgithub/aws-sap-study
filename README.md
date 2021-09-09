## 1.考试指南中的重要点整理

建议掌握的 AWS 知识

目标考生应具备以下知识：

	⇒ 解释并应用 AWS Well-Architected Framework 的五大支柱
	
	⇒ 将业务目标与应用程序/构架要求一一对应
	
	⇒ 使用关键 AWS 技术设计混合构架
	
	⇒ 构建持续集成/持续交付（CI/CD）流程

主要设计的领域和占比：

领域 1： 针对组织复杂性的设计 12.5%

		1.1 确定复杂组织的跨账户身份验证和访问策略。
			● 分析组织结构
			● 评估当前的身份验证基础设施		
			● 在账户级别分析 AWS 资源
			● 确定身份验证和访问的审计策略
		1.2 确定如何为复杂的组织设计网络。
			● 概述 VPC 的 IP 寻址策略
			● 确定 DNS 策略
			● 对网络流量和安全进行分类
			● 确定混合环境的连接需求
			● 确定审计网络流量的方法
		1.3 确定如何为复杂组织设计多账户 AWS 环境。
			● 确定如何使用 AWS Organizations
			● 实施最合适的账户结构，以实现适当的成本分配、敏捷性和安全性
			● 推荐集中审计和事件通知策略
			● 确定访问策略
			
领域 2： 新解决方案设计 31%

		2.1 在设计和实施解决方案时确定安全要求和控制。
			● 实施基础设施即代码
			● 确定大型 Web 应用程序的预防控制
			● 确定应用程序的角色和责任
			● 确定用于管理解决方案/应用程序的凭证的安全方法
			● 为大型应用程序启用检测控制和安全服务
			● 强制实施主机和网络安全边界
			● 启用传输中加密和静态加密
		2.2 确定解决方案设计和实施策略以满足可靠性要求。
			● 设计高可用性应用程序环境
			● 确定用于检测故障和服务可恢复性的高级技术
			● 确定流程和组件，以便通过区域性故障转移监控区域性服务中断并从中恢复
		2.3 确定解决方案设计以确保业务连续性。
			● 构建一个自动化、经济高效的备份解决方案，用于支持跨多个 AWS 区域的业务连续性
			● 确定在服务中断时提供应用程序和基础设施可用性的构架
		2.4 确定解决方案设计以实现性能目标。
			● 设计互联网规模的应用程序构架
			● 根据业务目标设计性能构架
			● 通过缓存、缓冲和副本，应用设计模式以实现业务目标
		2.5 在设计和实施解决方案时，确定部署策略以满足业务需求。
			● 确定资源调配策略以实现业务目标
			● 确定迁移过程以更改服务版本
			● 确定服务以满足部署策略
			● 确定补丁管理策略
			
领域 3： 迁移规划 15%

		3.1 选择可能迁移到云中的现有工作负载和流程。
			● 完成应用程序迁移评估
			● 根据六个 R（重新托管、更换平台、重新购买、重构、停用和保留）对应用程序进行分类
		3.2 以丰富的 AWS 知识为基础，选择适用于新解决方案和迁移的解决方案的迁移工具和/或服务。
			● 选择适当的数据库传输机制
			● 选择适当的数据传输服务
			● 选择适当的数据传输目标
			● 选择适当的服务器迁移机制
			● 对迁移工具应用适当的安全方法
		3.3 为现有解决方案确定新的云构架。
			● 评估业务应用程序并确定目标云构架
			● 将应用程序的功能分解为服务
			● 确定目标数据库平台
		3.4 确定将现有本地工作负载迁移到云的策略。
			● 确定组织所需的优先级排序策略
			● 分析数据量和变化率以确定数据传输策略
			● 评估切换策略
			● 评估成功迁移的内部和外部合规性要求
			
领域 4： 成本控制 12.5%

		4.1 为解决方案选择经济高效的定价模型。
			● 根据使用需求购买资源
			● 确定何时使用不同的存储层
		4.2 确定设计和实施哪些控制措施以确保成本优化。
			● 确定 AWS 生成的成本分配标签策略，该策略允许将成本映射到业务单位
			● 确定用于监控何时存在未充分利用的资源的机制
			● 确定用于管理通常部署的资源以实现监管的方法
			● 定义计划不超过预算金额的成本的方法
		4.3 确定在现有构架中降低成本的机会。
			● 识别使用 AWS Managed Services 的机会
			● 确定哪些服务在实现业务目标方面最经济高效
			
领域 5： 持续改进 29%

		5.1 对解决方案构架进行故障排除。
			● 评估现有应用程序构架的缺陷
			● 分析应用程序和基础设施日志
			● 在非生产环境中测试可能的解决方案
		5.2 确定改进现有解决方案以实现卓越运营的策略。
			● 确定最合适的日志记录和监控策略
			● 推荐适当的 AWS 产品以实现配置管理自动化
		5.3 确定提高现有解决方案可靠性的策略。
			● 评估现有构架以确定不够可靠的区域
			● 修复单点故障
			● 启用数据复制、自我修复以及弹性功能和服务
			● 测试新解决方案的可靠性
		5.4 确定提高现有解决方案性能的策略。
			● 协调当前的性能指标与性能目标
			● 识别并检查性能瓶颈
			● 推荐和测试潜在的修复解决方案
		5.5 确定提高现有解决方案安全性的策略。
			● 评估 AWS Secrets Manager 策略
			● 审计环境中的安全漏洞
			● 启用对漏洞检测的手动和/或自动响应
		5.6 确定如何改进现有解决方案的部署。
			● 评估适当的工具以启用基础设施即代码
			● 评估当前的部署流程以获得改进机会
			● 测试自动部署和回滚策略

## 2.AWS组件功能

### 2.1 AWS Auto Scaling [自动缩放]

#### 2.1.1 定义

> AWS Auto Scaling 是一种新型 AWS 服务，它能够轻松、安全地扩展多种 AWS 资源，帮助您在优化应用程序性能的同时实现基础设施成本节约。该产品简化了扩展体验，让您只需单击几次即可扩展用于支持应用程序的相关资源集合。AWS Auto Scaling 可以帮助您跨支持应用程序的完整基础设施堆栈配置一致、协调的扩展策略。AWS Auto Scaling 将遵循您选定的扩展策略根据需要自动扩展资源，以便您保持性能并仅为实际需要的资源付费。

#### 2.1.2 优势

a. 快速设置扩展

> 可以通过画面了解利用率，以及设置拓展

b. 制定明智的扩展决策

> 借助 AWS Auto Scaling，您能够自动确定不同资源组如何响应需求变化。易于理解的扩展策略让您可以选择优化可用性和成本，或者平衡可用性与成本。AWS Auto Scaling 可以根据您的偏好自动创建所有扩展策略并设置目标。

c. 自动维持性能

> 自动监控应用资源，出现需求高峰时候自动增加受限制资源

d. 预计成本并避免超支

> AWS Auto Scaling 可以帮助您优化使用 AWS 产品时的利用率和成本效率，因此您只需为实际需要的资源付费。当需求下降时，AWS Auto Scaling 将自动删除任何多余的资源容量，避免您超支。

### 2.1.3 拓展策略

a. 预测式扩展

> 利用机器学习模型对未来将要发生得流量进行预测并拓展。
> 预测式拓展只能够为EC2实例生成计划
> 与测试拓展至少需要2周得数据才可以正常执行，可以每隔24小时预测48小时得流量


#### 2.1.4 其他拓展得对比

![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png)

![AWSAutoScalling,Amazon EC2 Auto Scaling Auto Scaling对比](../../images/AWSAutoScalling,Amazon EC2 Auto Scaling Auto Scaling对比.png)