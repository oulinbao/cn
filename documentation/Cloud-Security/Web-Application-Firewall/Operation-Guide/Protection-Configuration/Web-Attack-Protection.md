## Web应用攻击防护

Web应用攻击防护可防护SQL注入、XSS跨站等常见Web应用攻击，且提供不同等级的防护策略：正常、宽松、严格。

### 背景信息

将网站接入WAF后，您可以为其开启Web应用攻击防护，并根据实际需求调整相应防护策略。Web应用防护开启后实时生效；如果出现突发事件影响了业务流量，可将选择将其关闭。

**操作步骤**

参照以下步骤，配置 Web应用攻击防护 ：

**说明：** 执行以下操作前，请确保已将网站接入WAF进行防护。具体操作请参考CNAME接入指南

1. 登录[京东云Web应用防火墙控制台](https://cloudwaf-console.jdcloud.com)。

2. 前往**网站配置**页面。

3. 选择要操作的域名，单击其操作列下的**防护配置**。

4. 在**Web应用攻击防护**下，开启防护，并选择防护**模式**： 
         **说明：**使用过程中出现流量异常，可在通过拨动按钮关闭防护。![img](https://github.com/jdcloudcom/cn/blob/edit/image/waf-img/web%E9%98%B2%E6%8A%A4-1.png)

5. - **防护模式**：发现攻击后对攻击请求进行拦截。
   - **预警模式**：发现攻击后仅发送告警信息，不会对请求进行拦截。 

6. 在**防护规则策略等级**下选择合适的防护策略：

7. - 默认使用**正常**模式规则。
   - 当发现存在较多误拦截，或者业务存在较多不可控的用户输入，选择**宽松**模式。       
   - 当您需要更严格地防护路径穿越、SQL注入、命令执行时，建议您选择**严格**模式。

 
