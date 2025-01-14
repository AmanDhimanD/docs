---
ms.openlocfilehash: 801b42faa6e9a1bff269c1e4fcb0a5a2330717a4
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/05/2022
ms.locfileid: "145066902"
---
| 优先级 | 说明 | 示例 |
| :---: | --- | --- |
| {% data variables.product.support_ticket_priority_urgent %} | {% data variables.product.prodname_ghe_server %} 在生产环境中出现故障，此故障将直接影响您的业务运营。<br/><br/>{% data reusables.support.priority-urgent-english-only %} | <ul><li>影响所有用户的核心 Git 或 web 应用程序功能的错误或中断</li><li>影响大多数用户的性能严重下降</li><li>用完或快速占用存储空间</li><li>无法安装续订的许可文件</li><li>安全事件</li><li>失去对实例的管理权限，并且没有已知的解决方法</li><li>无法将备份还原到生产环境</li></ul> |
| {% data variables.product.support_ticket_priority_high %} | {% data variables.product.prodname_ghe_server %} 在生产环境中出现故障，但对您的业务影响有限。 | <ul><li>性能下降，影响许多用户的工作效率</li><li>因高可用性 (HA) 或集群节点故障而减少冗余</li><li>无法备份实例</li><li>无法将备份还原到测试或暂存环境，可能影响成功还原到生产环境</li></ul> |
| {% data variables.product.support_ticket_priority_normal %} | 您在 {% data variables.product.prodname_ghe_server %} 方面遇到了有限或普通问题，或者对于实例运行有一般性疑虑或问题。 | <ul><li>测试或暂存环境中的问题</li><li>关于使用 {% ifversion fpt or ghec %}{% data variables.product.prodname_dotcom %}{% else %}{% data variables.product.product_name %}{% endif %} API 和功能的建议，或有关根据实例配置第三方集成的问题</li><li>有关 {% data variables.product.company_short %} 提供的用户数据迁移工具的问题</li><li>升级</li><li>Bug 报告</li><li>功能未按预期工作</li><li>一般安全问题</li></ul> |
| {% data variables.product.support_ticket_priority_low %} | 您对于 {% data variables.product.prodname_ghe_server %} 有问题或建议，但并不紧迫，或者该问题不影响团队的生产力。 | <ul><li>功能请求</li><li>产品反馈</li><li>状态检查请求（目前仅适用于 {% data variables.product.premium_support_plan %} 客户）</li><li>通知 {% data variables.product.company_short %} 对实例进行计划内维护</li></ul> |
