---
title: 训练计划与复盘
url: /sport/
summary: Garmin 训练计划与每周复盘
---

<style>
  .sport-dashboard {
    margin-top: 1.5rem;
    line-height: 1.75;
  }

  .sport-dashboard .sport-nav {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 0.7rem;
    margin: 1.5rem auto 2.2rem;
  }

  .sport-dashboard .sport-nav a {
    border: 1px solid var(--border);
    border-radius: 999px;
    padding: 0.42rem 1rem;
    text-decoration: none;
    font-size: 0.92rem;
    background: var(--entry);
    transition: transform 0.15s ease, border-color 0.15s ease, background 0.15s ease;
  }

  .sport-dashboard .sport-nav a:hover {
    transform: translateY(-1px);
    border-color: var(--primary);
    background: var(--code-bg);
  }

  .sport-dashboard .sport-card {
    border: 1px solid var(--border);
    border-radius: calc(var(--radius) + 4px);
    padding: 1.35rem;
    margin: 1.35rem 0;
    background: var(--entry);
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.04);
  }

  .sport-dashboard h2,
  .sport-dashboard h3,
  .sport-dashboard h4,
  .sport-dashboard h5,
  .sport-dashboard h6 {
    margin-top: 1.5em;
    margin-bottom: 0.65em;
  }

  .sport-dashboard #plan > h2:first-child,
  .sport-dashboard #history > h2:first-child {
    margin-top: 0;
  }

  .sport-dashboard .table-wrap {
    overflow-x: auto;
    margin: 1rem 0;
    border: 1px solid var(--border);
    border-radius: var(--radius);
  }

  .sport-dashboard table {
    width: 100%;
    border-collapse: collapse;
    min-width: 720px;
    font-size: 0.95rem;
  }

  .sport-dashboard th,
  .sport-dashboard td {
    border-bottom: 1px solid var(--border);
    padding: 0.7rem 0.8rem;
    text-align: left;
    vertical-align: top;
  }

  .sport-dashboard tr:last-child td {
    border-bottom: 0;
  }

  .sport-dashboard th {
    background: var(--code-bg);
    font-weight: 700;
    white-space: nowrap;
  }

  .sport-dashboard code {
    background: var(--code-bg);
    border-radius: 5px;
    padding: 0.12em 0.38em;
    font-size: 0.92em;
  }

  .sport-dashboard ul {
    padding-left: 1.35rem;
  }

  .sport-dashboard li + li {
    margin-top: 0.25rem;
  }

  .sport-dashboard hr {
    border: 0;
    border-top: 1px solid var(--border);
    margin: 1.25rem 0;
  }

  .sport-dashboard .sport-history-list {
    position: relative;
    margin-top: 0.2rem;
  }

  .sport-dashboard .sport-history-item {
    position: relative;
    border: 0;
    margin-left: 0.85rem;
    padding-left: 1.6rem;
  }

  .sport-dashboard .sport-history-item::before {
    content: "";
    position: absolute;
    left: 0;
    top: 0.2rem;
    bottom: -0.2rem;
    width: 2px;
    background: var(--border);
  }

  .sport-dashboard .sport-history-item:last-child::before {
    bottom: 1.2rem;
  }

  .sport-dashboard .sport-history-item summary {
    position: relative;
    cursor: pointer;
    list-style: none;
    padding: 0.9rem 0 0.9rem 0.2rem;
    font-weight: 700;
    color: var(--primary);
    outline: none;
  }

  .sport-dashboard .sport-history-item summary::-webkit-details-marker {
    display: none;
  }

  .sport-dashboard .sport-history-item summary::before {
    content: "";
    position: absolute;
    left: -1.72rem;
    top: 1.35rem;
    width: 0.72rem;
    height: 0.72rem;
    border-radius: 999px;
    background: var(--entry);
    border: 2px solid var(--primary);
    box-shadow: 0 0 0 4px var(--theme);
  }

  .sport-dashboard .sport-history-item summary::after {
    content: "展开";
    display: inline-block;
    margin-left: 0.65rem;
    color: var(--secondary);
    font-size: 0.78rem;
    font-weight: 500;
    line-height: 1.4;
    border: 1px solid var(--border);
    border-radius: 999px;
    padding: 0.12rem 0.48rem;
    vertical-align: middle;
  }

  .sport-dashboard .sport-history-item[open] summary::after {
    content: "收起";
  }

  .sport-dashboard .sport-history-item[open] summary::before {
    background: var(--primary);
  }

  .sport-dashboard .sport-markdown-body {
    margin: 0.1rem 0 1.2rem;
    padding: 1rem 1.1rem;
    border: 1px solid var(--border);
    border-radius: var(--radius);
    background: var(--theme);
  }

  .sport-dashboard .sport-markdown-body > *:first-child {
    margin-top: 0;
  }

  .sport-dashboard .sport-markdown-body > *:last-child {
    margin-bottom: 0;
  }

  .sport-dashboard .sport-empty {
    margin: 0;
    color: var(--secondary);
  }

  @media (max-width: 720px) {
    .sport-dashboard .sport-hero {
      padding: 1.3rem 1rem;
    }

    .sport-dashboard .sport-card {
      padding: 1rem;
    }

    .sport-dashboard .sport-history-item {
      margin-left: 0.5rem;
      padding-left: 1.25rem;
    }

    .sport-dashboard .sport-history-item summary::before {
      left: -1.37rem;
    }

    .sport-dashboard .sport-markdown-body {
      padding: 0.9rem;
    }
  }
</style>

<div class="sport-dashboard">

  <nav class="sport-nav">
    <a href="#plan">本周计划</a>
    <a href="#history">历史复盘</a>
  </nav>

  <section id="plan" class="sport-card">
    <h2>未来七日训练计划</h2>
<p>计划周期：2026-06-05 至 2026-06-11</p>
<h3>本周重点</h3>
<ul>
<li>今天恢复优先：当前 HRV 趋势下降、身体电量偏低，不安排正式训练。</li>
<li>保持每周约 3 次力量或核心训练，增加背部拉练与下肢动作，改善推拉平衡和体态。</li>
<li>有氧以低至中等强度为主；训练后应感觉精神尚可，而不是被完全耗尽。</li>
<li>RPE 为 1-10 的主观用力程度；所有动作保留约 2-3 次余力。</li>
</ul>
<h3>每日计划</h3>
<div class="table-wrap"><table><thead><tr>
<th>日期</th>
<th>场地</th>
<th>训练</th>
<th>具体内容</th>
<th>强度</th>
<th>状态</th>
</tr></thead><tbody>
<tr>
<td>6月5日 周五</td>
<td>户外/居家</td>
<td>主动恢复</td>
<td>轻松步行20-30分钟；肩颈、胸椎和髋部舒展各5分钟</td>
<td>RPE 2-3</td>
<td>休息</td>
</tr>
<tr>
<td>6月6日 周六</td>
<td>泳池</td>
<td>轻松游泳</td>
<td>已预约游泳；轻松连续游或分段游20-30分钟，不追求速度，呼吸保持从容</td>
<td>RPE 3-4</td>
<td>计划</td>
</tr>
<tr>
<td>6月7日 周日</td>
<td>居家</td>
<td>居家力量+核心</td>
<td>2.5 kg哑铃卧推3×10-15；2.5 kg哑铃肩上推举2×10-12；徒手深蹲3×12；前臂平板支撑3×30-45秒；屈膝卷腹触膝2×12-15</td>
<td>RPE 5-6</td>
<td>计划</td>
</tr>
<tr>
<td>6月8日 周一</td>
<td>户外/居家</td>
<td>恢复</td>
<td>轻松步行20-30分钟；胸椎、肩部和髋部舒展5-10分钟</td>
<td>RPE 2-3</td>
<td>休息</td>
</tr>
<tr>
<td>6月9日 周二</td>
<td>户外/居家</td>
<td>恢复</td>
<td>轻松步行20-30分钟，或完全休息；避免高强度核心和推举</td>
<td>RPE 2-3</td>
<td>休息</td>
</tr>
<tr>
<td>6月10日 周三</td>
<td>健身房</td>
<td>拉练+爬坡</td>
<td>宽握高位下拉4×8-12；划船机12-15分钟；跑步机坡度走20分钟；哑铃卧推2×10作为维持</td>
<td>RPE 5-6</td>
<td>计划</td>
</tr>
<tr>
<td>6月11日 周四</td>
<td>居家</td>
<td>轻量全身+核心</td>
<td>徒手深蹲3×12；哑铃肩上推举2×8-10；仰卧空中蹬车3×30秒；前臂平板支撑3×30-45秒；舒展5分钟</td>
<td>RPE 5</td>
<td>计划</td>
</tr>
</tbody></table></div>
<h3>调整规则</h3>
<ul>
<li>若晨起身体电量明显偏低、HRV继续下降或乏力加重，当天改为20分钟轻松步行或完全休息。</li>
<li>若出现关节疼痛、胸痛、异常气促、头晕或明显心悸，停止训练并按情况就医。</li>
<li>健身房或泳池时间不合适时，使用 <code>$garmin-plan-edit</code> 调换日期，不连续安排两个中等以上强度力量日。</li>
</ul>
<h3>调整记录</h3>
<ul>
<li>2026-06-05：根据5月29日至6月4日训练与恢复数据创建首份七日计划；因当日恢复偏弱，将首日设为主动恢复。</li>
<li>2026-06-05 16:33：周六已有游泳预约，改为游泳；因健身房周日不开门，将周日改为2.5 kg哑铃居家力量，并将周一改为恢复。</li>
</ul>
  </section>

  <section id="history" class="sport-card">
    <h2>历史复盘</h2>
    <div class="sport-history-list">
      <details class="sport-history-item"><summary>2026-06-05 周复盘</summary><div class="sport-markdown-body"><h2>七日训练复盘</h2>
<p>复盘范围：2026-05-29 至 2026-06-04<br>计划范围：2026-06-05 至 2026-06-11</p>
<h3>训练摘要</h3>
<ul>
<li>共3个实际训练日、6条活动记录；同日连续记录已合并理解。</li>
<li>总记录时长约89分钟，消耗约423千卡。</li>
<li>力量训练约56分钟；有氧约33分钟，包括室内有氧和椭圆机。</li>
<li>5月30日：力量训练约19分钟，随后椭圆机约7分钟。</li>
<li>6月1日：室内有氧约27分钟；另有约1分钟力量记录，视为零碎或误触记录。</li>
<li>6月3日：两段连续力量训练合计约36分钟。</li>
<li>动作结构仍以上肢推为主；背部拉练和下肢训练相对不足。此前没有有效七日计划，因此无法判断计划完成率。</li>
</ul>
<h3>恢复摘要</h3>
<ul>
<li>有记录的5晚平均睡眠约6小时43分，平均睡眠评分约75；5月30日和31日睡眠摘要缺失。</li>
<li>HRV七日均值在复盘期由47 ms降至45 ms；2026-06-05进一步降至43 ms并被标记为不平衡。</li>
<li>复盘期平均静息心率约58次/分；2026-06-05为62次/分，高于近7日平均59次/分。</li>
<li>6月3日和4日压力被标记为偏高；部分日期日末身体电量较低。</li>
<li>2026-06-05睡眠约7小时3分、评分77，但起床身体电量58，整体恢复仍偏弱。</li>
</ul>
<h3>判断</h3>
<p>训练量本身偏低至适中，并无明显过量；当前更值得关注的是睡眠不足或波动、近期压力及恢复趋势下降。下一周期不宜突然增加高强度，而应通过规律的中等训练、更多拉练和下肢动作，以及明确恢复日来改善结构。</p>
<h3>下周期安排依据</h3>
<ul>
<li>首日采用主动恢复。</li>
<li>安排2次健身房训练，重点补充宽握高位下拉、划船和下肢动作。</li>
<li>安排1次轻松游泳、1次居家核心与体态训练、1次居家轻量全身训练。</li>
<li>中等力量日之间保留恢复空间，所有力量动作保留2-3次余力。</li>
</ul>
<h3>数据缺口</h3>
<ul>
<li>5月30日和31日缺少睡眠摘要，相关恢复判断不能覆盖完整七晚。</li>
<li>Garmin未记录可靠的哑铃重量，计划使用RPE和重复次数，不推测负重。</li>
<li>自动动作识别存在误差，动作判断以用户在 <code>memory.md</code> 中确认的项目为准。</li>
</ul></div></details>
    </div>
  </section>
</div>
