直视范围感知任务 (Direct Gaze Perception Task)

这是一个基于 Web 的心理学实验程序，用于测量个体的直视锥 (Cone of Direct Gaze, CoDG)。

🧠 实验背景

在社会认知心理学中，“直视锥”是指个体感知到被他人注视的空间范围。焦虑水平、社交恐惧或自闭症特质等因素可能会影响这一范围的宽窄。

🛠️ 技术特点

纯前端实现：使用 HTML5、CSS3 和 JavaScript (ES6+)。

Canvas 绘图：刺激材料（人脸及眼球运动）通过 Canvas 实时绘制，无需加载外部图片资源，确保了毫秒级的加载速度和精确的控制。

自适应设计：使用 Tailwind CSS，适配桌面端和移动端设备。

数据可视化：实验结束后自动使用 Chart.js 生成结果折线图，并计算直视锥宽度。

🚀 如何运行

在线体验

访问本项目的 GitHub Pages 链接：

https://jhdfghertrtyuxxx-afk.github.io/Direct-vision-range-perception-task-CoDG-/
本地运行

克隆或下载本项目。

直接使用浏览器（推荐 Chrome, Edge, Firefox）打开 index.html 文件即可。

📊 实验参数配置

在代码中的 experiment.config 对象中可以修改实验参数：

config: {
    angles: [-8, -7, ... 7, 8], // 注视角度范围
    repetitions: 2,             // 每个角度的重复次数
    fixationDuration: 500,      // 注视点呈现时间 (ms)
    interTrialInterval: 300     // 试次间隔 (ms)
}


📝 交互方式

键盘：

J 键：是 (Yes)

F 键：否 (No)

触屏/鼠标：

点击屏幕下方的对应按钮。

📄 许可证

MIT License
