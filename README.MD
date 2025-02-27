<!DOCTYPE html>
<html lang="zh-cn">
<head>
  <meta charset="UTF-8">
  <title>五连杆机构写字刷题批卷机器人</title>
  <style>
    body { font-family: "微软雅黑", Arial, sans-serif; background: #f5f5f5; margin: 0; padding: 20px; }
    .container { max-width: 800px; margin: auto; background: #fff; padding: 30px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); }
    h1, h2 { color: #333; }
    p { line-height: 1.6; color: #555; }
    .section { margin-bottom: 30px; }
    /* 新增任务列表样式 */
    .task-list { list-style: none; padding: 0; }
    .task-item { margin: 10px 0; padding: 10px; border-radius: 5px; }
    .task-item.completed { background: #e0f7e9; border: 1px solid #66bb6a; }
    .task-item.pending { background: #fff3e0; border: 1px solid #ffb74d; }
    .task-item input[type="checkbox"] { margin-right: 10px; transform: scale(1.2); }
  </style>
</head>
<body>
  <div class="container">
    <h1>五连杆机构写字刷题批卷机器人</h1>
    <div class="section">
      <h2>项目简介</h2>
      <p>
        本项目为TJUT Robotics课程中的 #10 小组作业，涉及一个五连杆机构的写字刷题批卷机器人，旨在通过先进的机械设计与编程实践，打造一个高效的写字及批卷系统。
      </p>
    </div>
    <div class="section">
      <h2>机械臂的SW模型</h2>
      <p>
        我们已经完成了机械臂的软件模型设计，详细模拟了各个操作部件的行为，确保控件精准、高效。
      </p>
    </div>
    <div class="section">
      <h2>嵌入式代码</h2>
      <p>
        嵌入式部分的代码已更新至代码库，便于在硬件部分实现控制及数据采集。
      </p>
    </div>
    <div class="section">
      <h2>未来规划</h2>
      <p>
        未来我们将完成具身智能系统、详细的数学建模以及相关技术文档的编写，为整个项目提供理论和技术支持。
      </p>
    </div>
    <div class="section">
      <h2>任务进度</h2>
      <ul class="task-list">
        <li class="task-item completed">
          <input type="checkbox" checked disabled> 机械臂的SW模型 ✅
        </li>
        <li class="task-item completed">
          <input type="checkbox" checked disabled> 嵌入式代码 ✅
        </li>
        <li class="task-item pending">
          <input type="checkbox" disabled> 未来规划 🚧
        </li>
      </ul>
    </div>
  </div>
</body>
</html>
