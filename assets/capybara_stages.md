# 咕姆 · 五阶段形态 SVG 资产

## 使用铁律

1. 这五个 SVG 是**手写矢量图**，禁止用 emoji、禁止 `<image>`、禁止外链图片、禁止 base64 位图替代。
   只有矢量才能做「沉睡灰调」「进化高亮」的滤镜与形变。
2. 输出时**原样内联**到卡片/HTML 中，**不要改写结构、不要合并 path、不要删注释**。
   只可在外面套一层 `<g filter="...">` 做状态效果。
3. 每个 SVG 自带 `viewBox="0 0 240 200"`，可自由缩放；推荐渲染宽度 200–280px。
4. 配色固定：身体 `#A98258` / 头部 `#B58C60` / 深色部件 `#8E6B47` / 眼鼻 `#332A22` / 腮红 `#E9A38E`。
   改色等于换了一只宠物，不要改。

---

## 阶段 1 · 咕咕蛋（0 – 99 经验）

蛋壳里探出半个脑袋，眼睛已经睁开了。

```svg
<svg viewBox="0 0 240 200" width="240" height="200" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="咕咕蛋">
  <!-- 地面阴影 -->
  <ellipse cx="120" cy="178" rx="50" ry="8" fill="#E8E1D5"/>
  <!-- 蛋壳下半 -->
  <path d="M62 146 Q62 174 120 174 Q178 174 178 146 Z" fill="#FBF6EE" stroke="#DCCDB8" stroke-width="3"/>
  <!-- 蛋壳上半（锯齿裂口） -->
  <path d="M62 146 L82 124 L99 142 L118 116 L137 140 L154 120 L178 146" fill="#FFFDF8" stroke="#DCCDB8" stroke-width="3" stroke-linejoin="round"/>
  <!-- 耳朵（画在头下层，只露上半） -->
  <ellipse cx="90" cy="104" rx="10" ry="9" fill="#8E6B47"/>
  <ellipse cx="150" cy="104" rx="10" ry="9" fill="#8E6B47"/>
  <ellipse cx="90" cy="104" rx="4.5" ry="4" fill="#6B4E37"/>
  <ellipse cx="150" cy="104" rx="4.5" ry="4" fill="#6B4E37"/>
  <!-- 脑袋 -->
  <ellipse cx="120" cy="128" rx="33" ry="29" fill="#A98258"/>
  <!-- 呆毛 -->
  <path d="M120 100 Q126 92 118 87" stroke="#6B4E37" stroke-width="3.5" fill="none" stroke-linecap="round"/>
  <!-- 眼睛 -->
  <ellipse cx="107" cy="126" rx="4.5" ry="5" fill="#332A22"/>
  <ellipse cx="133" cy="126" rx="4.5" ry="5" fill="#332A22"/>
  <circle cx="108.5" cy="124" r="1.6" fill="#FFFFFF"/>
  <circle cx="134.5" cy="124" r="1.6" fill="#FFFFFF"/>
  <!-- 鼻子 -->
  <ellipse cx="120" cy="138" rx="6" ry="4.5" fill="#6B4E37"/>
  <ellipse cx="120" cy="136.5" rx="2" ry="1.4" fill="#332A22"/>
  <!-- 腮红 -->
  <ellipse cx="100" cy="136" rx="6" ry="4" fill="#E9A38E" opacity="0.55"/>
  <ellipse cx="140" cy="136" rx="6" ry="4" fill="#E9A38E" opacity="0.55"/>
</svg>
```

---

## 阶段 2 · 毛球崽（100 – 299 经验）

站起来了，圆滚滚，解锁「错题森林」。

```svg
<svg viewBox="0 0 240 200" width="240" height="200" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="毛球崽">
  <!-- 地面阴影 -->
  <ellipse cx="120" cy="180" rx="56" ry="9" fill="#E8E1D5"/>
  <!-- 尾巴 -->
  <ellipse cx="178" cy="148" rx="10" ry="8" fill="#8E6B47"/>
  <!-- 身体 -->
  <ellipse cx="120" cy="140" rx="47" ry="38" fill="#A98258"/>
  <!-- 后腿 -->
  <rect x="92" y="162" width="18" height="18" rx="9" fill="#8E6B47"/>
  <rect x="130" y="162" width="18" height="18" rx="9" fill="#8E6B47"/>
  <!-- 前爪 -->
  <ellipse cx="97" cy="152" rx="10" ry="7" fill="#8E6B47"/>
  <ellipse cx="143" cy="152" rx="10" ry="7" fill="#8E6B47"/>
  <!-- 耳朵 -->
  <ellipse cx="86" cy="66" rx="11" ry="10" fill="#8E6B47"/>
  <ellipse cx="154" cy="66" rx="11" ry="10" fill="#8E6B47"/>
  <ellipse cx="86" cy="66" rx="5" ry="4.5" fill="#6B4E37"/>
  <ellipse cx="154" cy="66" rx="5" ry="4.5" fill="#6B4E37"/>
  <!-- 头 -->
  <ellipse cx="120" cy="92" rx="40" ry="34" fill="#B58C60"/>
  <!-- 眼睛 -->
  <ellipse cx="105" cy="90" rx="5" ry="5.5" fill="#332A22"/>
  <ellipse cx="135" cy="90" rx="5" ry="5.5" fill="#332A22"/>
  <circle cx="107" cy="88" r="1.8" fill="#FFFFFF"/>
  <circle cx="137" cy="88" r="1.8" fill="#FFFFFF"/>
  <!-- 鼻子与嘴 -->
  <ellipse cx="120" cy="105" rx="8" ry="6" fill="#6B4E37"/>
  <circle cx="116" cy="105" r="1.8" fill="#332A22"/>
  <circle cx="124" cy="105" r="1.8" fill="#332A22"/>
  <path d="M113 114 Q120 120 127 114" stroke="#6B4E37" stroke-width="2.5" fill="none" stroke-linecap="round"/>
  <!-- 腮红 -->
  <ellipse cx="94" cy="104" rx="7" ry="4.5" fill="#E9A38E" opacity="0.5"/>
  <ellipse cx="146" cy="104" rx="7" ry="4.5" fill="#E9A38E" opacity="0.5"/>
</svg>
```

---

## 阶段 3 · 泡澡少年（300 – 699 经验）

学会了泡温泉，头顶小毛巾，解锁「周末挑战」。

```svg
<svg viewBox="0 0 240 200" width="240" height="200" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="泡澡少年">
  <defs>
    <clipPath id="gumu-stage3-water">
      <rect x="0" y="0" width="240" height="138"/>
    </clipPath>
  </defs>
  <!-- 蒸汽 -->
  <path d="M74 62 Q66 50 76 40 Q86 30 78 20" stroke="#BFD8E6" stroke-width="4" fill="none" stroke-linecap="round" opacity="0.85"/>
  <path d="M166 60 Q158 48 168 38 Q178 28 170 18" stroke="#BFD8E6" stroke-width="4" fill="none" stroke-linecap="round" opacity="0.85"/>
  <!-- 木桶 -->
  <path d="M56 136 H184 L174 176 A12 12 0 0 1 162 186 H78 A12 12 0 0 1 66 176 Z" fill="#C98F5C" stroke="#A5713F" stroke-width="3"/>
  <path d="M50 130 H190 V142 H50 Z" fill="#B87F4E" stroke="#A5713F" stroke-width="3"/>
  <path d="M62 152 H178" stroke="#A5713F" stroke-width="3" opacity="0.6"/>
  <path d="M66 168 H174" stroke="#A5713F" stroke-width="3" opacity="0.6"/>
  <!-- 身体（裁到水面以上，像泡在桶里） -->
  <g clip-path="url(#gumu-stage3-water)">
    <ellipse cx="120" cy="130" rx="43" ry="34" fill="#A98258"/>
  </g>
  <!-- 耳朵 -->
  <ellipse cx="86" cy="62" rx="11" ry="10" fill="#8E6B47"/>
  <ellipse cx="154" cy="62" rx="11" ry="10" fill="#8E6B47"/>
  <ellipse cx="86" cy="62" rx="5" ry="4.5" fill="#6B4E37"/>
  <ellipse cx="154" cy="62" rx="5" ry="4.5" fill="#6B4E37"/>
  <!-- 头 -->
  <ellipse cx="120" cy="88" rx="39" ry="33" fill="#B58C60"/>
  <!-- 头顶小毛巾 -->
  <path d="M92 62 Q120 48 148 62 L148 56 Q120 42 92 56 Z" fill="#FFFFFF" stroke="#DCE6EC" stroke-width="2"/>
  <path d="M104 52 L104 46" stroke="#6FB3D9" stroke-width="3" stroke-linecap="round"/>
  <path d="M136 52 L136 46" stroke="#6FB3D9" stroke-width="3" stroke-linecap="round"/>
  <!-- 眯眼（享受） -->
  <path d="M97 88 Q105 82 113 88" stroke="#332A22" stroke-width="3" fill="none" stroke-linecap="round"/>
  <path d="M127 88 Q135 82 143 88" stroke="#332A22" stroke-width="3" fill="none" stroke-linecap="round"/>
  <!-- 鼻子与嘴 -->
  <ellipse cx="120" cy="102" rx="8" ry="6" fill="#6B4E37"/>
  <circle cx="116" cy="102" r="1.8" fill="#332A22"/>
  <circle cx="124" cy="102" r="1.8" fill="#332A22"/>
  <path d="M113 111 Q120 117 127 111" stroke="#6B4E37" stroke-width="2.5" fill="none" stroke-linecap="round"/>
  <!-- 腮红（泡热了） -->
  <ellipse cx="95" cy="100" rx="8" ry="5" fill="#E9A38E" opacity="0.7"/>
  <ellipse cx="145" cy="100" rx="8" ry="5" fill="#E9A38E" opacity="0.7"/>
  <!-- 爪子搭在桶沿 -->
  <ellipse cx="70" cy="134" rx="13" ry="8" fill="#8E6B47"/>
  <ellipse cx="170" cy="134" rx="13" ry="8" fill="#8E6B47"/>
  <!-- 水面波纹 -->
  <path d="M60 132 Q70 126 80 132 Q90 138 100 132" stroke="#EAF3F9" stroke-width="3" fill="none" stroke-linecap="round" opacity="0.9"/>
  <path d="M140 132 Q150 126 160 132 Q170 138 180 132" stroke="#EAF3F9" stroke-width="3" fill="none" stroke-linecap="round" opacity="0.9"/>
</svg>
```

---

## 阶段 4 · 顶橘大叔（700 – 1499 经验）

完整形态，头顶一颗橘子，永远淡定，解锁「教我做一题」。

```svg
<svg viewBox="0 0 240 200" width="240" height="200" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="顶橘大叔">
  <!-- 地面阴影 -->
  <ellipse cx="120" cy="182" rx="60" ry="10" fill="#E8E1D5"/>
  <!-- 尾巴 -->
  <ellipse cx="182" cy="150" rx="11" ry="9" fill="#8E6B47"/>
  <!-- 身体 -->
  <ellipse cx="120" cy="142" rx="50" ry="40" fill="#A98258"/>
  <ellipse cx="120" cy="150" rx="34" ry="28" fill="#B58C60" opacity="0.5"/>
  <!-- 后腿 -->
  <rect x="90" y="164" width="20" height="18" rx="9" fill="#8E6B47"/>
  <rect x="130" y="164" width="20" height="18" rx="9" fill="#8E6B47"/>
  <!-- 前爪 -->
  <ellipse cx="94" cy="154" rx="11" ry="7.5" fill="#8E6B47"/>
  <ellipse cx="146" cy="154" rx="11" ry="7.5" fill="#8E6B47"/>
  <!-- 耳朵 -->
  <ellipse cx="84" cy="64" rx="12" ry="11" fill="#8E6B47"/>
  <ellipse cx="156" cy="64" rx="12" ry="11" fill="#8E6B47"/>
  <ellipse cx="84" cy="64" rx="5.5" ry="5" fill="#6B4E37"/>
  <ellipse cx="156" cy="64" rx="5.5" ry="5" fill="#6B4E37"/>
  <!-- 头 -->
  <ellipse cx="120" cy="92" rx="42" ry="35" fill="#B58C60"/>
  <!-- 橘子 -->
  <circle cx="120" cy="46" r="16" fill="#F5A33C" stroke="#D9862A" stroke-width="2"/>
  <circle cx="114" cy="40" r="4" fill="#FFD79A" opacity="0.75"/>
  <path d="M120 30 Q128 22 136 26 Q130 34 120 32 Z" fill="#5C9E58"/>
  <!-- 眯眼（淡定） -->
  <path d="M98 92 Q106 87 114 92" stroke="#332A22" stroke-width="3.2" fill="none" stroke-linecap="round"/>
  <path d="M126 92 Q134 87 142 92" stroke="#332A22" stroke-width="3.2" fill="none" stroke-linecap="round"/>
  <!-- 鼻子与嘴 -->
  <ellipse cx="120" cy="106" rx="9" ry="6.5" fill="#6B4E37"/>
  <circle cx="115.5" cy="106" r="1.9" fill="#332A22"/>
  <circle cx="124.5" cy="106" r="1.9" fill="#332A22"/>
  <path d="M112 116 Q120 122 128 116" stroke="#6B4E37" stroke-width="2.5" fill="none" stroke-linecap="round"/>
  <!-- 腮红 -->
  <ellipse cx="92" cy="104" rx="8" ry="5" fill="#E9A38E" opacity="0.5"/>
  <ellipse cx="148" cy="104" rx="8" ry="5" fill="#E9A38E" opacity="0.5"/>
</svg>
```

---

## 阶段 5 · π 帽智者（1500 经验起）

学士帽 + 圆眼镜 + π 徽章，解锁「出题给爸妈」。

```svg
<svg viewBox="0 0 240 200" width="240" height="200" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="π 帽智者">
  <!-- 地面阴影 -->
  <ellipse cx="120" cy="182" rx="60" ry="10" fill="#E8E1D5"/>
  <!-- 尾巴 -->
  <ellipse cx="182" cy="150" rx="11" ry="9" fill="#8E6B47"/>
  <!-- 身体 -->
  <ellipse cx="120" cy="142" rx="50" ry="40" fill="#A98258"/>
  <ellipse cx="120" cy="150" rx="34" ry="28" fill="#B58C60" opacity="0.5"/>
  <!-- π 徽章 -->
  <circle cx="120" cy="150" r="17" fill="#FFFFFF" stroke="#3B4C7A" stroke-width="2.5"/>
  <path d="M110 143 H131" stroke="#3B4C7A" stroke-width="3.4" stroke-linecap="round"/>
  <path d="M113 143 V159" stroke="#3B4C7A" stroke-width="3.4" stroke-linecap="round"/>
  <path d="M128 143 V152 Q128 159 121 159" stroke="#3B4C7A" stroke-width="3.4" fill="none" stroke-linecap="round"/>
  <!-- 后腿 -->
  <rect x="90" y="164" width="20" height="18" rx="9" fill="#8E6B47"/>
  <rect x="130" y="164" width="20" height="18" rx="9" fill="#8E6B47"/>
  <!-- 前爪 -->
  <ellipse cx="94" cy="154" rx="11" ry="7.5" fill="#8E6B47"/>
  <ellipse cx="146" cy="154" rx="11" ry="7.5" fill="#8E6B47"/>
  <!-- 耳朵 -->
  <ellipse cx="84" cy="66" rx="12" ry="11" fill="#8E6B47"/>
  <ellipse cx="156" cy="66" rx="12" ry="11" fill="#8E6B47"/>
  <ellipse cx="84" cy="66" rx="5.5" ry="5" fill="#6B4E37"/>
  <ellipse cx="156" cy="66" rx="5.5" ry="5" fill="#6B4E37"/>
  <!-- 头 -->
  <ellipse cx="120" cy="94" rx="42" ry="35" fill="#B58C60"/>
  <!-- 学士帽 -->
  <rect x="100" y="52" width="40" height="12" rx="3" fill="#3B4C7A"/>
  <path d="M120 14 L188 40 L120 66 L52 40 Z" fill="#2F3A56" stroke="#212A40" stroke-width="2"/>
  <circle cx="120" cy="40" r="6" fill="#F5C542"/>
  <path d="M186 42 Q196 50 190 66" stroke="#F5C542" stroke-width="3.5" fill="none" stroke-linecap="round"/>
  <circle cx="190" cy="68" r="4.5" fill="#F5C542"/>
  <!-- 圆眼镜 -->
  <circle cx="104" cy="94" r="14" fill="#FFFFFF" fill-opacity="0.25" stroke="#332A22" stroke-width="3"/>
  <circle cx="136" cy="94" r="14" fill="#FFFFFF" fill-opacity="0.25" stroke="#332A22" stroke-width="3"/>
  <path d="M118 94 H122" stroke="#332A22" stroke-width="3"/>
  <path d="M90 92 L80 96" stroke="#332A22" stroke-width="3" stroke-linecap="round"/>
  <path d="M150 92 L160 96" stroke="#332A22" stroke-width="3" stroke-linecap="round"/>
  <!-- 眼睛 -->
  <ellipse cx="104" cy="94" rx="4.5" ry="5" fill="#332A22"/>
  <ellipse cx="136" cy="94" rx="4.5" ry="5" fill="#332A22"/>
  <circle cx="105.5" cy="92" r="1.6" fill="#FFFFFF"/>
  <circle cx="137.5" cy="92" r="1.6" fill="#FFFFFF"/>
  <!-- 鼻子与嘴 -->
  <ellipse cx="120" cy="112" rx="9" ry="6.5" fill="#6B4E37"/>
  <circle cx="115.5" cy="112" r="1.9" fill="#332A22"/>
  <circle cx="124.5" cy="112" r="1.9" fill="#332A22"/>
  <path d="M112 122 Q120 128 128 122" stroke="#6B4E37" stroke-width="2.5" fill="none" stroke-linecap="round"/>
  <!-- 腮红 -->
  <ellipse cx="88" cy="112" rx="7" ry="4.5" fill="#E9A38E" opacity="0.45"/>
  <ellipse cx="152" cy="112" rx="7" ry="4.5" fill="#E9A38E" opacity="0.45"/>
</svg>
```

---

## 状态滤镜（套在形态外层，不改内部结构）

### 沉睡态（断签 ≥2 天）

```svg
<filter id="gumu-sleep" x="-10%" y="-10%" width="120%" height="120%">
  <feColorMatrix type="saturate" values="0.12"/>
  <feComponentTransfer>
    <feFuncR type="linear" slope="0.88" intercept="0.06"/>
    <feFuncG type="linear" slope="0.88" intercept="0.06"/>
    <feFuncB type="linear" slope="0.92" intercept="0.08"/>
  </feComponentTransfer>
</filter>
```

用法：`<g filter="url(#gumu-sleep)"><!-- 贴入当前阶段 SVG 的内部内容 --></g>`
配套文案：**咕姆在水里等你。**

### 进化高亮（跨阶段当天）

```svg
<filter id="gumu-evolve" x="-20%" y="-20%" width="140%" height="140%">
  <feGaussianBlur stdDeviation="6" result="blur"/>
  <feFlood flood-color="#F5C542" flood-opacity="0.85" result="glow"/>
  <feComposite in="glow" in2="blur" operator="in" result="ring"/>
  <feMerge>
    <feMergeNode in="ring"/>
    <feMergeNode in="SourceGraphic"/>
  </feMerge>
</filter>
```

用法同上，配套文案：**进化！** + 新阶段名。

---

## 附：经验进度条（日报卡片用）

把 `{filled}` 换成 `当前经验 ÷ 下一阶段门槛 × 340` 的整数值，`{exp}` / `{next}` 换成数字。

```svg
<svg viewBox="0 0 400 52" width="400" height="52" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="经验进度条">
  <rect x="10" y="18" width="340" height="16" rx="8" fill="#EAE4DA"/>
  <rect x="10" y="18" width="{filled}" height="16" rx="8" fill="#7FB069"/>
  <circle cx="{knobX}" cy="26" r="11" fill="#FFFFFF" stroke="#7FB069" stroke-width="3"/>
  <text x="10" y="12" font-family="system-ui, -apple-system, PingFang SC, Microsoft YaHei, sans-serif" font-size="12" fill="#8A8172">咕姆的经验</text>
  <text x="360" y="12" text-anchor="end" font-family="system-ui, -apple-system, PingFang SC, Microsoft YaHei, sans-serif" font-size="12" fill="#6B6357">{exp} / {next}</text>
</svg>
```

---

## 附：错题森林小树（阶段 2 解锁，订正一棵亮一棵）

`dim` = 未订正（灰），`lit` = 已订正（亮）。复制 N 棵横向排列即可。

```svg
<svg viewBox="0 0 40 52" width="40" height="52" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="错题树">
  <rect x="17" y="34" width="6" height="14" rx="2" fill="#8E6B47"/>
  <circle cx="20" cy="24" r="15" fill="#7FB069"/>
  <circle cx="11" cy="30" r="9" fill="#6FA55E"/>
  <circle cx="29" cy="30" r="9" fill="#6FA55E"/>
  <circle cx="20" cy="14" r="6" fill="#9CCB85"/>
</svg>
```

未订正版：把三个绿色换成 `#C9C3B8` / `#BDB7AC` / `#D5D0C6`，并在树干下加一条横线表示"还没扎根"。
