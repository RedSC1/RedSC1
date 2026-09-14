<div align="center">

# Hi, I'm RedSC1 👋

🌙 **闭关中**  
写了挺久，但反馈和合作机会都比较少，暂时没什么继续开发的动力，所以先停止新功能开发。现有项目正常保留。  
有 Bug 请发邮件，**Issue 不一定看得到。**

🪐 兴趣驱动的独立开发者，主要写天文历算、历法、占星与传统术数相关的软件和开源项目。

<p>An interest-driven independent developer building software and open-source projects around astronomical computation, calendars, astrology and traditional Chinese metaphysics.</p>

很多项目都起源于一个很简单的问题：现有工具不够顺手，或者我想知道它底层到底是怎么算的，于是就自己（~~AI~~）写了一套。

💻 <strong>Dart · TypeScript · Python · C++</strong>

<a href="https://www.redsc1.com">个人网站 / Website</a> · <a href="https://github.com/RedSC1?tab=repositories">全部仓库 / Repositories</a>

</div>

## 🔨 现在在做 / Current Projects

<table>
  <tr>
    <td valign="top">
      <h3><a href="https://github.com/RedSC1/opendestiny-web">OpenDestiny Web</a></h3>
      <code>JavaScript / TypeScript</code> <code>React</code> <code>Web App</code> <a href="https://github.com/RedSC1/opendestiny-web/blob/main/LICENSING.md"><code>Mixed licenses</code></a>
      <p>本地优先的在线排盘与历法工具站，支持简体中文与繁體中文。</p>
      <p><em>A local-first web app for Chinese astrology, tarot and calendar tools.</em></p>
      <ul>
        <li>八字与紫微斗数排盘，支持天文年 −6000～10000（约公元前 6000 年至公元 10000 年）</li>
        <li>78 张 Rider–Waite–Smith 塔罗牌、正逆位、多种牌阵和本地抽牌历史</li>
        <li>万年历、农历、干支、节气、黄历与气朔推算</li>
        <li>无需账号，命例与记录保存在浏览器本地，支持 JSON 导入与导出</li>
        <li><strong>下一步：</strong>占星 → 六爻 → 梅花易数 → 大六壬 → 奇门遁甲<br><em>Roadmap: astrology, Liuyao, Meihua Yishu, Da Liu Ren and Qimen Dunjia.</em></li>
        <li><a href="https://tools.redsc1.com"><strong>在线使用 / Live site</strong></a></li>
      </ul>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td valign="top">
      <h3><a href="https://github.com/RedSC1/taiyin-ephemeris">Taiyin Ephemeris</a></h3>
      <code>C++</code> <code>核心引擎</code> <code>MPL-2.0</code>
      <p>可嵌入的高性能天文历算内核。</p>
      <p><em>An embeddable C++ astronomy engine with ephemerides, observations, events, eclipses, calendars and optional BaZi / Ziwei modules.</em></p>
      <ul>
        <li>太阳系天体位置、观测坐标、升落与天文事件<br><em>Solar-system positions, observing coordinates, rise/set calculations and astronomical event searches.</em></li>
        <li>日月食、掩星、固定星、历法与真太阳时<br><em>Solar and lunar eclipses, occultations, fixed stars, calendars and apparent solar time.</em></li>
        <li>可选的八字、干支与紫微斗数扩展<br><em>Optional BaZi, Ganzhi and Ziwei Doushu extensions.</em></li>
        <li>JPL SPK / OPM2 星历，以及供语言绑定使用的 C99 API<br><em>JPL SPK and OPM2 ephemerides with a versioned C99 API designed for embedding and language bindings.</em></li>
        <li>提供 <a href="https://github.com/RedSC1/py-ephemeris">Python</a> 与 <a href="https://github.com/RedSC1/dart-ephemeris">Dart</a> 语言绑定<br><em>Official Python and Dart bindings are available.</em></li>
        <li><strong>支持年份：</strong>全量 DE441 OPM2 压缩星历（约公元前 13,200 年～公元 17,191 年，跨度约 30,370 年）；内置半解析模型与 Lite 版一致，覆盖天文年 −6000～10000 年<br><em>Full-range DE441 OPM2 data (approximately 13,200 BCE to 17,191 CE, spanning about 30,370 years); the built-in semi-analytic models follow the Lite implementation and cover astronomical years −6000 to 10000.</em></li>
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
      <p><em>A zero-dependency astronomy, calendar and Chinese metaphysics toolkit for browsers and Node.js.</em></p>
      <ul>
        <li>太阳、月球和行星的位置与速度，以及恒星表、视位置和地平坐标<br><em>Positions and velocities for the Sun, Moon and planets, plus star catalogs, apparent positions and horizontal coordinates.</em></li>
        <li>升落中天、照明与视直径、合冲、留、入宫、近远点、交点和大距<br><em>Rise, set and transit times; illumination, apparent diameters, conjunctions, oppositions, stations, ingresses, apsides, nodes and elongations.</em></li>
        <li>全球与地方日月食搜索，以及接触时刻和地方可见性<br><em>Global and local solar/lunar eclipse searches with contact times and local visibility.</em></li>
        <li>节气、月相、农历、历史历法、算术回历、干支与真太阳时<br><em>Solar terms, lunar phases, Chinese and arithmetic Hijri calendars, historical calendar rules, Ganzhi and apparent solar time.</em></li>
        <li>包含 BaZi、Ziwei、Huangli 和 Star Catalog 子包<br><em>Also includes BaZi, Ziwei, Huangli and Star Catalog packages.</em></li>
        <li><strong>支持年份：</strong>天文年 −6000～10000 年<br><em>Supported astronomical years: −6000 to 10000; precision varies by body, epoch and API.</em></li>
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
      <p><em>A pure Dart astronomy and calendar library for Dart VM, Flutter and the web.</em></p>
      <ul>
        <li>太阳、月球和行星的位置与速度，以及外部恒星表、视位置和地平坐标<br><em>Positions and velocities for the Sun, Moon and planets, with external star catalogs, apparent positions and horizontal coordinates.</em></li>
        <li>升落中天、照明、合冲、留、入宫、近远点、交点和大距<br><em>Rise, set and transit times; illumination, conjunctions, oppositions, stations, ingresses, apsides, nodes and elongations.</em></li>
        <li>全球与地方日月食搜索，以及接触时刻和地方可见性<br><em>Global and local solar/lunar eclipse searches with contact times and local visibility.</em></li>
        <li>节气、月相、农历、历史历法、算术回历、干支与真太阳时<br><em>Solar terms, lunar phases, Chinese and arithmetic Hijri calendars, historical calendar rules, Ganzhi and apparent solar time.</em></li>
        <li>纯 Dart 实现，支持 Dart VM、Flutter 和 Dart Web<br><em>Pure Dart with support for Dart VM, Flutter and Dart Web.</em></li>
        <li><strong>支持年份：</strong>天文年 −6000～10000 年<br><em>Supported astronomical years: −6000 to 10000; precision varies by body, epoch and API.</em></li>
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
      <p><em>A pure Dart BaZi chart engine built on Ephemeris Lite.</em></p>
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
      <p><em>A configurable Ziwei Doushu chart and timeline engine written in pure Dart.</em></p>
      <p>支持出生盘、运限与流盘、时间线、规则配置、修改盘、无生日起盘和条件反查。</p>
      <p><strong>支持年份：</strong>天文年 −6000～10000 年；无生日起盘不受此范围限制</p>
    </td>
  </tr>
</table>

## 📦 其他项目 / More Projects

<table>
  <tr>
    <td valign="top">
      <h3>🔌 语言绑定</h3>
      <p>
        <strong><a href="https://github.com/RedSC1/py-ephemeris">Python Ephemeris</a></strong>
        <code>Python</code> <code>Binding</code> <code>MPL-2.0</code><br>
        Taiyin Ephemeris 的 Python 绑定；支持年份随加载的星历数据变化。<br>
        <em>Python bindings for Taiyin Ephemeris.</em>
      </p>
      <p>
        <strong><a href="https://github.com/RedSC1/dart-ephemeris">Dart Ephemeris</a></strong>
        <code>Dart</code> <code>FFI</code> <code>MPL-2.0</code><br>
        Taiyin Ephemeris C API 的 Dart 绑定；支持年份随加载的星历数据变化。<br>
        <em>Dart FFI bindings for Taiyin Ephemeris.</em>
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
        纯 Dart 实现的中国传统黄历库；支持年份待重写后重新确认。<br>
        <em>Traditional Chinese almanac library for Dart. Rewrite planned.</em>
      </p>
      <p>
        <strong><a href="https://github.com/RedSC1/sxwnl_spa_dart">SXWNL SPA Dart</a></strong>
        <code>Dart</code> <code>移植项目</code> <code>MIT</code><br>
        农历、节气、干支与真太阳时计算库；已对拍验证 −2000～5000 年。<br>
        <em>Dart port for Chinese calendars, solar terms, Ganzhi and true solar time.</em>
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
        跨平台排盘应用，目前包含紫微斗数与八字功能；支持公元前 4713 年至公元 9999 年（天文纪年 −4712～9999 年）。<br>
        <em>A cross-platform Flutter app for BaZi and Ziwei Doushu charts, supporting dates from 4713 BCE through 9999 CE (astronomical years −4712 to 9999).</em>
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
        纯 Python 的轻量占星星历实验；支持 −3000～+3000 年。<br>
        <em>An experimental pure-Python astrology ephemeris.</em>
      </p>
      <p>
        <strong><a href="https://github.com/RedSC1/taiyin-ephemeris-semi-analytic">Taiyin Ephemeris — Semi-Analytic</a></strong>
        <code>Python</code> <code>Experiment</code> <code>Apache-2.0</code><br>
        Taiyin Ephemeris 的半解析算法实验；支持 −3000～+3000 年。<br>
        <em>Experimental semi-analytic ephemeris models for Python.</em>
      </p>
    </td>
  </tr>
</table>
