# CarPilot 用户手册

> **Language / 语言**: [**English**](user-manual.md) | [**简体中文**](user-manual-zh.md)

---

欢迎使用 **CarPilot**，您的专业车辆性能分析仪和赛道记录助手。本手册将帮助您了解所有功能，充分利用您的驾驶体验。

## 📖 目录
1. [入门指南](#getting-started)
2. [主屏幕概览](#home-screen-overview)
3. [性能测试](#performance-testing)
    - [加速测试](#acceleration-tests)
    - [制动测试](#braking-tests)
    - [自定义测试](#custom-tests)
4. [赛道录制](#track-recording)
    - [自动检测](#automatic-detection)
    - [手动选择](#manual-selection)
    - [创建自定义赛道](#creating-custom-tracks)
5. [分析与报告](#analysis--reports)
    - [性能分析](#performance-analysis)
    - [赛道分析](#track-analysis)
    - [舒适度与噪音分析](#comfort--noise-analysis)
6. [数据管理](#data-management)
    - [导入/导出 (VBO)](#importexport-vbo)
    - [会话库](#session-library)
7. [设置](#settings)

---

## <a id="getting-started"></a>1. 入门指南

### 手机安装
为了获得准确的数据，您的 iPhone 必须牢固地安装在车辆中。
1.  **稳固安装**：使用坚固的手机支架。避免安装在松动的位置。
2.  **方向校准**：确保手机与车辆行驶方向对齐。
    *   进入 **设置 > 手机安装 (Phone Mounting)** 进行校准。
    *   **重要**：如果是垂直安装（屏幕面向驾驶员），请将设备向后倾斜至少 30°，以避免传感器数据异常。

### 权限说明
CarPilot 需要以下权限：
- **位置 (Location)**：选择“始终允许”或“使用 App 期间”（用于高精度 GPS）。
- **运动与健身 (Motion & Fitness)**：用于获取加速度计和陀螺仪数据。
- **麦克风 (Microphone)**（可选）：用于噪音水平分析（仅记录声压级数值，不录制语音）。

---

## <a id="home-screen-overview"></a>2. 主屏幕概览

主屏幕是您的控制中心。

*   **右上角指示器**：
    *   **GPS 状态**：显示当前 GPS 精度（如 5m, 10m）。绿色表示信号良好。
    *   **安装状态**：显示手机方向和校准状态。
*   **主要按钮**：
    *   🟢 **普通录制**：用于日常驾驶或混合测试。自动检测开始和停止。
    *   🟠 **性能测试**：专用于 0-100、100-0 等测试模式。
    *   🔵 **赛道录制**：专用于赛道驾驶，支持圈速计时。
*   **赛道卡片**：如果您在已知赛道附近，会自动显示赛道卡片。

---

## <a id="performance-testing"></a>3. 性能测试

测量车辆的直线加速和制动性能。

### <a id="acceleration-tests"></a>加速测试
*   **0-100 km/h (0-60 mph)**：测量到达指定速度的时间。
*   **0-400m (1/4 英里)**：测量通过指定距离的时间和尾速。
*   **操作步骤**：
    1.  点击 **性能测试**（橙色按钮）。
    2.  选择测试类型。
    3.  完全静止。
    4.  App 提示 "Ready"（准备就绪）。
    5.  起步！当检测到移动时，App 会自动开始计时。

### <a id="braking-tests"></a>制动测试
*   **100-0 km/h (60-0 mph)**：测量刹停距离和时间。
*   **操作步骤**：
    1.  选择 **制动测试**。
    2.  加速到目标速度以上（例如 105 km/h）。
    3.  全力制动直到完全停止。

### <a id="custom-tests"></a>自定义测试
您可以在测试配置菜单中定义自己的速度范围（如 60-120 km/h）或距离。

---

## <a id="track-recording"></a>4. 赛道录制

记录圈速、行车线和分段分析。

### <a id="automatic-detection"></a>自动检测
如果您位于支持的赛道附近，主屏幕会出现 **赛道卡片**。点击 **"使用赛道 (Use Track)"** 即可开始。

### <a id="manual-selection"></a>手动选择
1.  点击 **赛道录制**（蓝色按钮）。
2.  浏览赛道库查找您的赛道。

### <a id="creating-custom-tracks"></a>创建自定义赛道
1.  进入 **数据 (Data) > 赛道 (Tracks)**。
2.  点击 **+ (创建赛道)**。
3.  选择之前的驾驶记录。
4.  在时间轴上找到起跑/终点线的位置。
5.  设置起点线方向。
6.  保存自定义赛道。

---

## <a id="analysis--reports"></a>5. 分析与报告

### <a id="performance-analysis"></a>性能分析
查看加速和制动测试的详细图表。
*   **图表**：速度 vs 时间，G值 vs 时间。
*   **指标**：峰值 G 值，0-60 时间，60英尺时间，坡度信息。

### <a id="track-analysis"></a>赛道分析
对比圈速并分析行车线。
*   **圈速计时器**：查看所有圈速。
*   **轨迹图**：基于速度或 G 值的热力图。
*   **对比分析**：选择两圈进行叠加对比，查看速度差异点。

### <a id="comfort--noise-analysis"></a>舒适度与噪音分析
*   **舒适度**：分析垂直 G 值和震动（乘坐质量）。
*   **噪音**：将车内噪音水平 (dB) 映射到车速。

---

## <a id="data-management"></a>6. 数据管理

### <a id="importexport-vbo"></a>导入/导出
CarPilot 支持行业标准的 **VBO** 格式 (Racelogic VBOX)。
*   **导出**：将任何会话导出为 VBO 文件，以便在 Circuit Tools 等专业软件中分析。
*   **导入**：打开其他设备生成的 `.vbo` 文件并在 CarPilot 中分析。

### <a id="session-library"></a>会话库
在 **数据 (Data)** 标签页下查看历史记录。
*   **筛选**：按日期、赛道或测试类型。
*   **删除**：在任意会话上向左滑动即可删除。

---

## <a id="settings"></a>7. 设置

根据您的需求配置 App。
*   **语言 (Language)**：更改 App 语言。
*   **单位 (Units)**：切换公制 (km/h, m) 和英制 (mph, ft)。
*   **视频 (Video)**：配置分辨率 (1080p/4K) 和摄像头选择。
*   **驾驶员与车辆**：管理不同车辆和驾驶员的配置文件。
*   **屏幕录制**：在测试期间开启同步屏幕录制（支持麦克风音频）。
