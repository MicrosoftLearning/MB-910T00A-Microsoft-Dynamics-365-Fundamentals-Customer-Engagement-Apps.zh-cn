---
lab:
    title: '实验室 4.3： Dynamics 365 现场服务巅峰课程实验室'
    module: '模块 4： 学习 Dynamics 365 Field Service 的基础知识'
---

模块 4： 学习 Dynamics 365 Field Service 的基础知识
========================

## 实践实验室 4.3 - Dynamics 365 现场服务巅峰课程实验室

## 实验室场景

ABC 公司专注于安全设备的制造、销售、安装和维修。该公司的产品包括室内和室外安全摄像头、湿度和火灾传感器、监视服务等。 

ABC 公司使用 Dynamics 365 应用程序跨组织的各个领域（从销售到服务）与所有客户互动。 

**销售和营销**

ABC 公司直接通过针对性的营销活动对住宅客户展开营销。基于客户所在城市和其他因素将客户设置为目标。营销材料通过电子邮件发送，并基于客户与电子邮件的互动相应地进行引导。 

虽然一些小型产品是通过零售商销售的，但大多数产品通过内部销售人员直接销售给消费者。

从内部看，他们侧重于两个关键领域： 

- **住宅客户：** 住宅客户通常需要单独的部件或希望购买整个家庭解决方案。此类销售周期通常较短，且来自于社交媒体、网站、推荐者或意向客户的直接联系人。由于住宅客户通常较关注特定产品或较小的安装，因此其销售周期通常持续几天或几周。 

- **企业客户：** 企业销售人员侧重于需要较专业化的定制业务解决方案的客户。企业销售人员通常覆盖多个地点，具有关联的通信，通常需要使用多种资源才能完成项目。此类销售周期通常较长且具有更多的灵活部分。 

ABC 公司的销售人员需要具有必要的工具、资源和指导（无论他们在对客户进行推销时侧重于什么方面），这一点非常重要。 

**系统安装：**

已购买的安全设备的安装过程因购买设备的客户的类型而异。 

- **住宅客户：** 由于住宅安装所需时间通常不超过一天，因此由内部员工完成。完成销售后，系统会创建工作订单、确定一名合格的技师并安排安装。 

- **企业客户：** 企业部署可能需要几个月，并需要一名项目经理监督日常操作。这包括创建项目计划、定义项目团队和计划资源。 

**服务和支持：**

系统安装后，ABC 公司提供售后支持。如果客户有问题，可以联系客户支持。代理将尝试与客户远程协作，解决问题。如果问题无法通过远程方式解决，支持代理会将问题上报给工作订单，一名合格的现场技师会对此工作订单进行安排并予以处理。 

## 目标

通常，ABC 公司会派遣现场技术员到现场处理以下三种场景的客户项。 

- 客户购买了新的安全系统并需要安装该系统。

- 技术支持代理无法通过远程方式解决客户问题。

- 客户直接联系请求现场服务。 

最近一个公司客户 Active Transport, Inc 就他们的安全系统上的摄像头的问题联系了支持人员。技术支持人员无法通过远程方式解决他们的问题，因此需要派遣现场技术员。在此场景中，你将执行以下操作：

- 将案例记录转换为工作订单

- 计划工作订单

- 使用移动应用解决工作订单。 

## 实验室设置

  - **预计用时：** 45 分钟

## 说明

## 练习 1：创建案例并上报到工作订单 

### 任务 1：创建案例记录

1. 如果尚未打开，请打开 **Dynamics 365 Field Service** 应用程序。 

2. 使用屏幕左侧的导航，选择 **“案例”**。 

3. 在 **“命令栏”** 上，选择 **“新建”** 按钮，创建新的案例记录。

4. 按如下所示完成新的案例记录：

	- **案例标题：** 摄像头故障

	- **客户**： Best For You Organics Company

	- **来源：** 电话

	保存记录。

5. 选择 **“现场服务”** 选项卡

6. 将 **“事件类型”** 字段设置为 **“摄像头故障”**。（新建）

7. 在 **“命令栏”** 上，选择 **“保存并关闭”** 按钮，保存并关闭案例记录。 

 

### 任务 2：手动创建工作订单

我们稍后将返回你已创建的案例记录。接下来，让我们看看如何手动创建工作订单记录。 

 

1. 使用左侧导航栏，选择 **“工作订单”**。

2. 在 **“命令栏”** 上，选择 **“新建”** 按钮，创建新的工作订单。

3. 按如下所示完成工作订单详细信息：

	- **服务帐户：** Margie's Travel

	- **价目表：** Office 365 美国版（示例）

	- **工作订单类型：** 服务

	- **应纳税：** 否

	保存记录并分配主要事件类型

	- **主要事件类型：** 扇出（新建）

4. 记录工作订单编号，确保稍后处理的是正确的工作订单。 

5. 选择 **“设置”** 选项卡。

6. 将 **“服务区域”** 字段设置为 **“华盛顿州”**。

7. 在 **“首选项”** 下，按如下所示配置时间首选项：

	- **承诺的起始时间：** 今天上午 9:00

	- **承诺截止时间：** 今天上午 11:00

8. 选择 **“保存并关闭”**，保存更改，退出新的工作订单。

 

### 任务 3：从案例生成工作订单

生成工作订单的另一种方式是上报案例记录。在此示例中，我们将上报之前创建的“摄像头故障”案例记录。 

 

1. 使用左侧导航栏，选择 **“案例”**。 

2. 打开之前创建的 **“摄像头故障”** 案例。

3. 在 **“命令栏”** 上，选择 **“转换为工作订单”** 按钮。 

4. 完成工作订单创建后，选择弹出屏幕上的 **“确定”** 按钮，查看工作订单详细信息。 

 

已准备好计划两个新创建的工作订单。 

## 练习 2：使用 Dynamics 365 Field Service 计划项  

### 任务 1：从工作订单直接计划

1. 使用左侧导航栏，选择 **“计划板”**。

2. 在屏幕的右上角，将 **“新建计划板”** 体验设置为 **“启用”**。 

3. 在“搜索资源”查找字段中，输入 **“Aidan Knaggs”**。 

4. 在“需求”面板的屏幕底部，选择 **“未计划的工作订单”**。 （如果未显示“需求”面板，请选择屏幕底部的箭头将其展开。） 

5. 找到基于案例记录创建的 **“Munson's Pickles”** 工作订单。（记住工作订单编号）。 

6. 拖动 **“Munson's Pickles”** 记录，将其放置在 Aiden 联系人记录的空闲时段上。 

7. 通常需要根据技术员冲突或其他项重新计划工作订单。调度员通过利用计划板可以轻松解决此问题。 

 

### 任务 2：使用计划板进行计划

1. 使用左侧导航栏，选择 **“计划板”**。

2. 使用 **“搜索资源”** 查找字段，输入你的用户帐户名称。 （应该显示你的资源记录。）

3. 在“需求”面板的屏幕底部，选择 **“未计划的工作订单”**。 （如果未显示“需求”面板，请选择屏幕底部的箭头将其展开。） 

4. 找到从案例记录创建的 **“活动传输”** 工作订单。（记住工作订单编号）。 

5. 拖动 **“活动传输”** 记录，将其放置在你的用户记录的打开槽位中。如果时间段与客户的首选时间段匹配，则文本显示为绿色。

6. 通常需要根据技术员冲突或其他项重新计划工作订单。调度员通过利用计划板可以轻松解决此问题。 

7. 在计划板上，选择“资源名称”列正上方的“搜索资源”框，输入 **“Brady”**，找到安排给 **Brady Hannon** 的今天稍后时间的工作订单。 

8. **右键** 单击计划的项。在显示的菜单中，选择 **“替换资源”**。选择“选择/搜索”框，选择你的资源记录，选择 **“重新分配”**
