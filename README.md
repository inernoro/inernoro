<!-- Profile README for github.com/inernoro. Visual assets are stored in this repository. -->
<p align="center">
  <img src="./assets/hero.png" width="100%" alt="InerNoro — From idea to system. AI products. Thoughtful engineering." />
</p>

<p align="center">
  <strong>把想法做成产品，把复杂留给工程。</strong><br />
  <sub>AI 产品 · 全栈应用 · 开发者工具</sub>
</p>

<p align="center">
  <a href="#selected-work">精选项目</a> &nbsp; / &nbsp;
  <a href="#engineering">工程方法</a> &nbsp; / &nbsp;
  <a href="#toolbox">技术工具箱</a> &nbsp; / &nbsp;
  <a href="https://github.com/inernoro?tab=repositories">全部仓库 ↗</a>
</p>

我是 **InerNoro**。这里记录我在 AI 产品、全栈应用与工程工具上的实践：从产品知识与 Agent 工作流，到模型路由、品牌视觉生成和部署预览。喜欢把一条链路做通，也关心系统运行之后，如何观察、核验与改进。

<a id="selected-work"></a>
## Selected work

<table>
  <tr>
    <td width="50%" valign="top"><a href="https://github.com/inernoro/prd_agent"><img src="./assets/prd-agent.svg" width="100%" alt="PRD Agent：AI 产品工作台，包含知识、Agent 工作流、模型路由与分支预览。技术：.NET 8、React、Tauri。" /></a></td>
    <td width="50%" valign="top"><a href="https://github.com/inernoro/openvisual"><img src="./assets/openvisual.svg" width="100%" alt="OpenVisual：品牌视觉 AI 图片生成工作台，P0 阶段。技术：Next.js、FastAPI、PostgreSQL。" /></a></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="https://github.com/inernoro/vlm_price"><img src="./assets/ai-price-board.svg" width="100%" alt="AI Price Board：AI 服务公开价格、统一口径、来源证据与每日目录更新。" /></a></td>
    <td width="50%" valign="top"><a href="https://github.com/inernoro/redis_monitor"><img src="./assets/redis-monitor.svg" width="100%" alt="Redis Monitor：用 Go 将 Redis MONITOR 输出转换为周期性活动排行榜，支持 Docker。" /></a></td>
  </tr>
</table>

<p align="center"><a href="https://inernoro.github.io/vlm_price/">打开 AI Price Board 在线看板 ↗</a></p>

<a id="engineering"></a>
## How I approach engineering

<p><img src="./assets/engineering-loop.svg" width="100%" alt="工程循环：构建可用产品，观察系统行为，根据证据持续改进。" /></p>

| 关注点 | 项目中的实践 |
| :--- | :--- |
| **完整链路** | PRD Agent 将知识工作台、Agent 工作流、模型网关与分支预览纳入同一工程体系。 |
| **明确边界** | OpenVisual 用共享契约描述数据与接口，通过 Provider 适配层组织 AI 服务。 |
| **可核验证据** | AI Price Board 分开记录目录预算与实验实付，保留来源、公式与核验时间。 |
| **可观察行为** | Redis Monitor 把命令流整理为数据库、命令、Key 与客户端等维度的活动排行。 |

<a id="toolbox"></a>
## Toolbox

公开项目中使用的技术：

**应用与交互** &nbsp; `TypeScript` · `React` · `Next.js` · `Tauri`  
**服务与工具** &nbsp; `C# / .NET` · `Python / FastAPI` · `Go`  
**数据与交付** &nbsp; `MongoDB` · `PostgreSQL` · `Redis` · `Docker` · `GitHub Actions`

<details>
<summary>还有一点有趣的东西</summary>

除了工程，也给桌面做了一只圆滚滚的熊猫：**[Panda Bun](https://github.com/inernoro/panda-bun-pet)**，一只带动画精灵图的 Codex 宠物。

</details>

<br />
<p align="center"><img src="./assets/footer.svg" width="100%" alt="InerNoro — Build with intent. Improve with evidence." /></p>
