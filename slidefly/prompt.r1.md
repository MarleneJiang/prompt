# 封底

<原文>
---
类型: 封底
版式: 总分
---
# 寻找平衡之道
在青春激情与商业理性之间  
构建包容而有序的旅游生态  
</原文>

<最佳实践>
---
layout: center
---
<div class="my-auto">
  
# 寻找平衡之道，推动经济发展{.!text-6xl .text-center}

在青春激情与商业理性之间{.text-center}

构建包容而有序的旅游生态{.text-center}

</div>
</最佳实践>

# 封面

<原文>
---
类型: 封面
版式: 总分
---
# 特种兵式旅游现象透视
## 从海底捞睡满人事件看青年旅游新趋势
> 社会现象分析报告
</原文>
<最佳实践>
---
layout: intro
---
<div class="my-auto">
  
# 特种兵式旅游现象透视
## 从海底捞睡满人事件看青年旅游新趋势
> 社会现象分析报告

</div>
</最佳实践>

# 过渡

<原文>
---
类型: 过渡
版式: 递进
---
## 现象溯源
"凌晨4点的海底捞为何变身青年旅社？"  
五一假期供需失衡的典型案例
</原文>
<最佳实践>
---
layout: intro
---
<div class="my-auto text-center">

# 现象溯源
"凌晨4点的海底捞为何变身青年旅社？"  
五一假期供需失衡的典型案例

</div>
</最佳实践>

# 目录

<原文>
## 内容框架
1. 现象背景：海底捞事件始末  
2. 深层动因：旅游热潮背后的推手  
3. 专家视角：行业观察与风险警示  
4. 社会讨论：权益平衡与发展机遇
</原文>
<最佳实践>
---
layout: cover
---
<div class="my-auto">
  <h1>内容框架</h1>
  <div grid="~ gap-3" class="cols-2">
    <div v-for="(title, index) in ['现象背景：海底捞事件始末', '深层动因：旅游热潮背后的推手', '专家视角：行业观察与风险警示', '社会讨论：权益平衡与发展机遇']" :key="index" p5 rounded bg-indigo:15 text-indigo1 overflow-hidden>
      <div flex gap-5 items-center>
        <div class="text-5xl text-indigo:30 font-italic font-900 font-sans h-full">
          {{ index + 1 }}
        </div>
        <div text-2xl tracking-wider>
          {{ title }}
        </div>
      </div>
    </div>
  </div>
</div>
</最佳实践>


# 内容页（带项目符号和图片的标题）

<原文>
---
类型: 内容
版式: 并列
---
# 存在的问题

- 模板的高度依赖: 需要人工预置大量模板
- 展示效果不佳: 无法通过AI更精细化调整样式
- 用户自定义空间有限: 无法自定义模板和样式

![腾讯文档生成的演示文稿示例](example.jpg)
</原文>
<最佳实践>
---
layout: default
---

# 存在的问题

<div grid="~ cols-3 gap-4" h="80%">
  <div grid="~ rows-3 gap-2" py4>
    <div v-for="(item, index) in [{ title: '模板的高度依赖', desc: '需要人工预置大量模板' }, { title: '展示效果不佳', desc: '无法通过AI更精细化调整样式' }, { title: '用户自定义空间有限', desc: '无法自定义模板和样式' }]" :key="index" flex="~ col gap-1" p4 rounded bg-indigo:15 text-indigo1>
      <div flex gap-2>
        <div text-2xl i-ph-thumbs-down-duotone text-indigo mb2 /><div text-xl>
          {{ item.title }}
        </div>
      </div>
      <div text-sm op60>
        {{ item.desc }}
      </div>
    </div>
  </div>
  <div col-span-2 flex justify-end flex-col items-end>
    <img src="example.jpg" rounded-lg shadow border="~ main">
    <span op60 mt-3>腾讯文档生成的演示文稿示例</span>
  </div>
</div>
</最佳实践>

# 内容页（大符号列表）

<原文>
---
类型: 内容
版式: 并列
---
# 算法步骤
1. 主题风格提取与应用
  - 识别用户所提供的演示主题和预期风格
  - 确定“目的”、“受众”和“场景”
2. 文本信息提取与处理
  - 从输入文本中提取关键信息
  - 压缩和调整优化
  - 保留必要的核心信息
3. 生成伪代码样式
  - 采用增强的 Markdown 语法
  - 支持预设模板
4. 代码实时渲染执行
  - 将 MDC 代码转换为 Web 渲染可用的格式
  - 静态编译
  - 动态渲染
</原文>
<最佳实践>
---
layout: default
---

# 算法步骤

<div grid="~ cols-2 gap-8" pt6>

<div bg-lime:10 border="~ lime/50 rounded-lg" class="view-transition-step1">
  <div flex="~ items-center gap-2" bg-lime:10 px4 py2 rounded ><div i-ph:number-circle-one text-xl />主题风格提取与应用</div>

  <div ml2 p2 text-lime1>

  - 识别用户所提供的演示主题和预期风格
  - 确定“目的”、“受众”和“场景”
  </div>
</div>

<div bg-gray:10 border="~ gray/50 rounded-lg">
  <div flex="~ items-center gap-2" bg-gray:10 px4 py2 rounded><div i-ph:number-circle-two text-xl />文本信息提取与处理</div>

  <div ml2 p2 text-gray1>

  - 从输入文本中提取关键信息
  - 压缩和调整优化
  - 保留必要的核心信息

  </div>
</div>

<div bg-orange:10 border="~ orange/50 rounded-lg">
  <div flex="~ items-center gap-2" bg-orange:10 px4 py2 rounded><div i-ph:number-circle-three hue-rotate-180 text-xl />生成伪代码样式</div>

  <div ml2 p2 text-orange1>

  - 采用增强的 Markdown 语法
  - 支持预设模板

  </div>
</div>

<div bg-pink:10 border="~ pink/50 rounded-lg">
  <div flex="~ items-center gap-2" bg-pink:10 px4 py2 rounded><div i-ph:number-circle-four text-xl />代码实时渲染执行</div>

  <div ml2 p2 text-pink2>

  - 将 MDC 代码转换为 Web 渲染可用的格式
  - 静态编译
  - 动态渲染

  </div>
</div>

</div>
</最佳实践>


# 测试

```md
---
类型: 封面
版式: 总分
---
# 特种兵式旅游现象透视
## 从海底捞睡满人事件看青年旅游新趋势
> 社会现象分析报告

---
类型: 目录
版式: 并列
---
## 内容框架
1. 现象背景：海底捞事件始末  
2. 深层动因：旅游热潮背后的推手  
3. 专家视角：行业观察与风险警示  
4. 社会讨论：权益平衡与发展机遇

---
类型: 过渡
版式: 递进
---
## 现象溯源
"凌晨4点的海底捞为何变身青年旅社？"  
五一假期供需失衡的典型案例

---
类型: 内容
版式: 总分
---
### 事件背景：供需矛盾的爆发
- **核心冲突**：南京海底捞因大学生留宿影响正常经营
- **消费者质疑**："餐饮场所是否应承担住宿功能？"
- **门店回应**：
  - 演唱会叠加假期形成极端客流
  - 承诺保障用餐区域优先
  - 临时调整留宿政策

---
类型: 内容
版式: 并列
---
### 现象发酵轨迹
| 发展阶段 | 特征表现 |
|---------|---------|
| 偶发个案 | 网友分享应急留宿体验 |
| 攻略传播 | 社交媒体出现系统教程 |
| 规模效应 | 五一期间集中爆发冲突 |
| 舆论分化 | 理解包容VS质疑批评 |

---
类型: 过渡
版式: 递进
---
## 动因解码
"青春没有售价"背后的经济账本

---
类型: 内容
版式: 递进
---
### 三大驱动要素
1. **心理补偿机制**  
   - 疫情三年压抑的出行需求集中释放
   - "活在当下"价值观的年轻化表达

2. **经济现实考量**  
   - 酒店价格同比上涨200%-300%
   - 大学生月均生活费与旅游预算对比失衡

3. **社交传播推动**  
   - 短视频平台旅游话题播放量超50亿次
   - 打卡文化催生新型旅行叙事方式

---
类型: 内容
版式: 总分
---
### 行业专家观察
**吴丽云教授**（旅游新业态研究）：
- 特定阶段的过渡性消费形态
- 开发轻量化旅游产品的商业启示

**邓静副教授**（文旅管理）：
- 需警惕的三大风险：
  1. 景区超负荷运营
  2. 旅行安全保障缺口
  3. 跟风行为潜在隐患

---
类型: 过渡
版式: 递进
---
## 多维视角下的社会讨论

---
类型: 内容
版式: 并列
---
### 舆论场域的交锋
**支持方观点**  
- 商家自主经营权应受尊重  
- 青年探索精神值得呵护  
- 促进旅游市场全面复苏  

**反对方担忧**  
- 公共资源挤占风险  
- 服务边界模糊化隐忧  
- 不可持续的旅行方式  

---
类型: 内容
版式: 递进
---
### 可持续解决方案
1. **商家层面**  
   - 建立清晰的留宿规则公示制度
   - 设置非消费时段应急服务专区

2. **行业层面**  
   - 开发青年旅社与民宿联动产品
   - 搭建景区实时客流预警系统

3. **社会层面**  
   - 推动旅游保险产品创新
   - 完善公共交通夜间接驳

---
类型: 封底
版式: 总分
---
# 寻找平衡之道
在青春激情与商业理性之间  
构建包容而有序的旅游生态  

> 旅游新业态发展需要：  
> 企业智慧 + 青年自觉 + 社会支持
```
