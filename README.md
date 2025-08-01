# Day 0: Start!
| 任务       | 具体动作                        | 交付物                 |
| -------- | --------------------------- | ------------------- |
| ① 安装环境   | Ubuntu 22.04 LTS 虚拟机 / 物理机  | `lsb_release -a` 截图 |
![图片描述]([https://raw.githubusercontent.com/你的用户名/你的仓库名/main/my-photo.png](https://github.com/missage999/smart-robot-90d/blob/main/images/ubuntu%E5%AE%89%E8%A3%85%E5%AE%8C%E6%88%90.png?raw=true))
| ② 装 ROS2 | 跟官网 Humble 二进制安装脚本          | `ros2 --version` 截图 |
| ③ 配置开发   | VS Code + ROS 插件 + Git      | 能 `code .` 打开仓库     |
| ④ 建仓库    | GitHub 新建 `smart-robot-90d` | README 写 “Day 0 ✅”  |
| 周   | 任务         | 资料 / 命令                                 | 交付物                        |
| --- | ---------- | --------------------------------------- | -------------------------- |
| 1-1 | C++ 语法速通   | 《C++ Primer》1-8 章 + LeetCode 50 题       | 每题 push 到 `/cpp_basic` 文件夹 |
| 1-2 | Linux 常用命令 | `man`, `grep`, `awk`, `gdb`, `valgrind` | 做一张命令速查表 md                |
| 1-3 | Git 工作流    | `git add/commit/push`, PR 模板            | README 里放 badge            |
| 1-4 | CMake 入门   | 写一个最小 `CMakeLists.txt` 编译可执行文件          | `/hello_cmake` 目录          |
| 周   | 任务           | 示例命令                         | 交付物                         |
| --- | ------------ | ---------------------------- | --------------------------- |
| 3-1 | 跑 turtlesim  | `ros2 run turtlesim_node`    | GIF 录屏                      |
| 3-2 | 话题发布/订阅      | 写 `cmd_vel_publisher`        | `/ros2_tutorial/pub_sub`    |
| 3-3 | 服务 & 参数      | 写 `spawn_turtle_client`      | `/ros2_tutorial/srv_param`  |
| 3-4 | launch & bag | 写 `turtlesim.launch.py` + 录包 | `/ros2_tutorial/launch_bag` |
| 周   | 任务      | 硬件/指令                          | 交付物              |
| --- | ------- | ------------------------------ | ---------------- |
| 5-1 | 组装 & 烧录 | TurtleBot3 Burger 官方教程         | 拍照 3 张 + 视频 30 秒 |
| 5-2 | 键盘控制    | `teleop_twist_keyboard` → 正圆轨迹 | 录屏 1 分钟          |
| 5-3 | 里程计测试   | 画 1 m × 1 m 正方形并返回原点           | 轨迹图 + 误差数据       |
| 5-4 | 传感器     | 读取激光雷达 `scan` 话题并可视化           | RViz 截图          |
| 周   | 任务               | 工具                                         | 交付物                   |
| --- | ---------------- | ------------------------------------------ | --------------------- |
| 7-1 | 安装 slam\_toolbox | `sudo apt install ros-humble-slam-toolbox` | `/slam/map.launch.py` |
| 7-2 | 手动建图             | 手推小车绕 10×10 m 场地 3 圈                       | `map.pgm + map.yaml`  |
| 7-3 | 保存地图             | `ros2 run nav2_map_server map_saver_cli`   | 地图文件 push             |
| 7-4 | 误差评估             | 对比真值 vs 建图误差 < 5 cm                        | Excel + md 报告         |
| 周   | 任务      | 工具                               | 交付物        |
| --- | ------- | -------------------------------- | ---------- |
| 9-1 | 启动 Nav2 | `nav2_bringup` + AMCL            | launch 文件  |
| 9-2 | 设定目标点   | 在 RViz 里点 3 个目标，小车依次到达           | GIF 录屏     |
| 9-3 | 自动送货    | 写 `pick_and_place_action_server` | 源码 + 演示视频  |
| 9-4 | 避障测试    | 在路径上加纸箱，观察重规划                    | 视频 + 分析 md |
| 周    | 任务          | 模板/渠道                  | 交付物                       |
| ---- | ----------- | ---------------------- | ------------------------- |
| 11-1 | 整理项目 README | 中英双语 + GIF             | README.md                 |
| 11-2 | LeetCode 刷题 | 50 题（链表/DFS/BFS）       | 题解放仓库                     |
| 11-3 | 简历一页        | Markdown → PDF         | `cv_zh.pdf` & `cv_en.pdf` |
| 11-4 | 内推/投递       | Boss 直聘关键词：机器人 C++ ROS | 每天 5 家，面试邀约≥3             |
