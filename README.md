# ros2_pubsub

このパッケージは、ROS2のPythonノードで簡単なパブリッシャーとサブスクライバーの例を提供します。

## クローン方法

このパッケージはros2ワークスペースのsrc以下に配置してください。

```bash
cd ~/ros2_ws/src
# 下記コマンドでクローン
git clone https://github.com/sige0002/ros2_pubsub.git
```

## 実行方法

1. ROS2ワークスペース（`ros2_ws`）のルートでビルドします。

```bash
cd ~/ros2_ws
colcon build --packages-select ros2_pubsub
source install/setup.bash
```

2. パブリッシャーノードを起動します。

```bash
ros2 run ros2_pubsub publisher_node
```

3. 別のターミナルでサブスクライバーノードを起動します。

```bash
ros2 run ros2_pubsub subscriber_node
```

---

GitHub: https://github.com/sige0002/ros2_pubsub.git
