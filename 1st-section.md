# 2018年6-7月研发部工作总结
	成果
		目的 
			计划
### 源码管理平台TFS（互联网随时可访问）

- 代码管理
	- 系统的管理代码并记录所有人对代码的一切操作，做到可追溯、能回退、便于统计、高容错。
	- 对代码进行权限控制，但对开发人员开放公用部分便于提取及复用，同时给予开发人员编写更重要代码的机会。
- 项目管理
	- 建立需求和缺陷、故障提出的规范，在tfs上登记跟踪。
		- 之后全程备忘、监控以及跟踪。
		- 任务来源。
		- 减少不必要的沟通。
		- 能力评估依据。
	- 尝试敏捷（scrum）研发过程，初步普及相关基础概念。（sprint、backlog、task、bug）
	- 新系统的版本发布规范，每两周的固定版本，不定期的紧急版本。（完成第一版发布，后续引入自动编译、发布、通知）
	- 建立验收规范和标准。（需公司内部协作和持续积累）
- 报表服务器
	- 搭建报表服务器，以tfs平台为数据基础提供随时可访问的报表服务（可自定义相关的报表）


### 代码整理
- 把公司现有代码集中保存并添加相应标记说明，便于所有人快速寻找代码，提高工作效率。
- 合并无意义的项目或者工程结构的划分，使项目变得更简洁明了易于维护。（部分完成，持续改进）
- 减少配置文件，降低项目部署难度。（部分完成，持续改进）
- 提取相同、相似功能的代码，便于系统需求的变更和持续维护。（部分完成，持续改进）


### 新病理系统相关
- 迭代一列表
- 未来两周先完善当前系统已发现并登记的问题和续期，同时保证已发布版本的bug及时修复（迭代二）
- 季度目标，构建一个基础功能稳定的通用版产品。


### 服务器
- 代码，统一管理
- 数据库，真实（医院）数据导入，作为测试的环境
- 资产
	- 共享文档
		- 公司文档
		- 项目文档
		- 产品发布目录
	- 共享研发和系统工具安装文件
- 帐号，分配个人帐号提供共享资源的访问同时也是tfs的帐号


### 不足与改进
- 编码能力（速度、质量）
- 对系统的理解（需求层面）和了解（代码层面）
- 设计能力，高效代码的编写（可读、复用、性能、风格等）
- 需求分析和需求沟通能力
- 测试能力
- 协作能力
- 创新能力