# Hi, I'm RedSC1 👋

🪐 我是一名兴趣驱动的独立开发者，主要写天文历算、历法计算、占星与传统术数相关的软件和开源项目。

很多项目都起源于一个很简单的问题：现有工具不够顺手，或者我想知道它底层到底是怎么算的，于是就自己（~~AI~~）写了一套。

💻 目前主要使用 **Dart / TypeScript / Python / C++**。从天文星历、历法核心，到八字、紫微引擎和 Flutter 应用都有涉及。

🧭 这里按用途整理了目前公开的项目，也算是这些年兴趣路线的一张地图。

[个人网站](https://www.redsc1.com) · [全部仓库](https://github.com/RedSC1?tab=repositories)

## 🔨 现在在做

<table>
  <tr>
    <td valign="top">
      <h3><a href="https://github.com/RedSC1/taiyin-ephemeris">Taiyin Ephemeris</a></h3>
      <code>C++</code> <code>核心引擎</code> <code>MPL-2.0</code>
      <p>可嵌入的高性能天文历算内核。</p>
      <ul>
        <li>太阳系天体位置、观测坐标、升落与天文事件</li>
        <li>日月食、掩星、固定星、历法与真太阳时</li>
        <li>可选的八字、干支与紫微斗数扩展</li>
        <li>JPL SPK / OPM2 星历，以及供语言绑定使用的 C99 API</li>
        <li>提供 <a href="https://github.com/RedSC1/py-ephemeris">Python</a> 与 <a href="https://github.com/RedSC1/dart-ephemeris">Dart</a> 语言绑定</li>
        <li><strong>支持年份：</strong>内置半解析模型约为 −3000～+3000 年；配套 OPM2 压缩星历可加载全量 DE441 数据，覆盖约 30,370 年</li>
      </ul>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td valign="top">
      <h3><a href="https://github.com/RedSC1/js-ephemeris-lite">JS Ephemeris Lite</a></h3>
      <code>JavaScript / TypeScript</code> <code>工具集</code> <code>MPL-2.0</code>
      <p>用于浏览器和 Node.js 的天文、历法与传统术数工具集，无运行时依赖。</p>
      <ul>
        <li>太阳、月球和行星的位置与速度，以及恒星表、视位置和地平坐标</li>
        <li>升落中天、照明与视直径、合冲、留、入宫、近远点、交点和大距</li>
        <li>全球与地方日月食搜索，以及接触时刻和地方可见性</li>
        <li>节气、月相、农历、历史历法、算术回历、干支与真太阳时</li>
        <li>包含 BaZi、Ziwei、Huangli 和 Star Catalog 子包</li>
        <li><strong>支持年份：</strong>天文年 −6000～10000 年</li>
      </ul>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td valign="top">
      <h3><a href="https://github.com/RedSC1/dart-ephemeris-lite">Dart Ephemeris Lite</a></h3>
      <code>Dart</code> <code>轻量库</code> <code>MPL-2.0</code>
      <p>JS Ephemeris Lite 的纯 Dart 实现，支持 Dart VM 和 Web，无运行时依赖。</p>
      <ul>
        <li>太阳、月球和行星的位置与速度，以及外部恒星表、视位置和地平坐标</li>
        <li>升落中天、照明、合冲、留、入宫、近远点、交点和大距</li>
        <li>全球与地方日月食搜索，以及接触时刻和地方可见性</li>
        <li>节气、月相、农历、历史历法、算术回历、干支与真太阳时</li>
        <li>纯 Dart 实现，支持 Dart VM、Flutter 和 Dart Web</li>
        <li><strong>支持年份：</strong>天文年 −6000～10000 年</li>
      </ul>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td valign="top">
      <h3><a href="https://github.com/RedSC1/bazi_core">BaZi Core</a></h3>
      <code>Dart</code> <code>Library</code> <code>MPL-2.0</code>
      <p>基于 Ephemeris Lite 的纯 Dart 八字排盘库。</p>
      <p>支持四柱、十神、藏干、长生、纳音、神煞、刑冲合害、起运、大运与出生时间反查。</p>
      <p><strong>支持年份：</strong>天文年 −6000～10000 年</p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td valign="top">
      <h3><a href="https://github.com/RedSC1/ziwei_core">Ziwei Core</a></h3>
      <code>Dart</code> <code>Library</code> <code>MPL-2.0</code>
      <p>纯 Dart 的紫微斗数排盘核心。</p>
      <p>支持出生盘、运限与流盘、时间线、规则配置、修改盘、无生日起盘和条件反查。</p>
      <p><strong>支持年份：</strong>天文年 −6000～10000 年；无生日起盘不受此范围限制</p>
    </td>
  </tr>
</table>

## 其他项目

<table>
  <tr>
    <td valign="top">
      <h3>🔌 语言绑定</h3>
      <p>
        <strong><a href="https://github.com/RedSC1/py-ephemeris">Python Ephemeris</a></strong>
        <code>Python</code> <code>Binding</code> <code>MPL-2.0</code><br>
        Taiyin Ephemeris 的 Python 绑定；支持年份随加载的星历数据变化。
      </p>
      <p>
        <strong><a href="https://github.com/RedSC1/dart-ephemeris">Dart Ephemeris</a></strong>
        <code>Dart</code> <code>FFI</code> <code>MPL-2.0</code><br>
        Taiyin Ephemeris C API 的 Dart 绑定；支持年份随加载的星历数据变化。
      </p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td valign="top">
      <h3>🧭 Dart / Flutter 工具</h3>
      <p>
        <strong><a href="https://github.com/RedSC1/chinese_lunar_almanac">Chinese Lunar Almanac</a></strong>
        <code>Dart</code> <code>Library</code> <code>MIT</code> <code>待重写</code><br>
        纯 Dart 实现的中国传统黄历库；支持年份待重写后重新确认。
      </p>
      <p>
        <strong><a href="https://github.com/RedSC1/sxwnl_spa_dart">SXWNL SPA Dart</a></strong>
        <code>Dart</code> <code>移植项目</code> <code>MIT</code><br>
        农历、节气、干支与真太阳时计算库；已对拍验证 −2000～5000 年。
      </p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td valign="top">
      <h3>📱 应用</h3>
      <p>
        <strong><a href="https://github.com/RedSC1/opendestiny-flutter">OpenDestiny Flutter</a></strong>
        <code>Flutter</code> <code>App</code> <code>MIT</code><br>
        跨平台排盘应用，目前包含紫微斗数与八字功能；支持公元前 1000 年至公元 9999 年。
      </p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td valign="top">
      <h3>🧪 实验项目</h3>
      <p>
        <strong><a href="https://github.com/RedSC1/lunaeph">LunaEph</a></strong>
        <code>Python</code> <code>Experiment</code> <code>Apache-2.0</code><br>
        纯 Python 的轻量占星星历实验；支持 −3000～+3000 年。
      </p>
      <p>
        <strong><a href="https://github.com/RedSC1/taiyin-ephemeris-semi-analytic">Taiyin Ephemeris — Semi-Analytic</a></strong>
        <code>Python</code> <code>Experiment</code> <code>Apache-2.0</code><br>
        Taiyin Ephemeris 的半解析算法实验；支持 −3000～+3000 年。
      </p>
    </td>
  </tr>
</table>
