# ms_maxwellnet
# 昇腾AI创新大赛2023-昇思赛道-算法创新赛题
# 基于mindspore复现ms_maxwellnet, mindspore=1.10
# 目录结构
```shell
├── ms_maxwellnet                              # 官方支持模型
│     ├── README.md                           # 模型说明文档
│     ├── requirements.txt                    # 依赖说明文件
│     ├── configs                             # 模型配置和数据集
│     │   ├──spheric_te                     # te数据
│     │   │   ├──model           			# 模型参数
│     │   │   │     ├──250000_te_fourth.ckpt           # 模型参数
│     │   │   │     ├──latest.ckpt				# 模型参数
│     │   │   ├──specs_maxwell.json             # 模型配置文件
│     │   │   ├──train.npz                     # 训练数据
│     │   │   ├──sample.npz                     # 测试数据
│     │   │   ├──maxwellnet_2023-05-17 01-59-34.log   # 训练日志
│     │   │   ├──te_result.png            # 测试可视化图片
│     │   ├──spheric_tm                     # tm数据
│     │   │   ├──model           			# 模型参数
│     │   │   │     ├──250000_tm_fourth.ckpt           # 模型参数
│     │   │   │     ├──latest.ckpt				# 模型参数
│     │   │   ├──specs_maxwell.json             # 模型配置文件
│     │   │   ├──train.npz                     # 训练数据
│     │   │   ├──sample.npz                     # 测试数据
│     │   │   ├──maxwellnet_2023-05-17 02-00-48.log   # 训练日志
│     │   │   ├──tm_result.png            # 测试可视化图片
```
# 训练
```shell
bash ./scripts/run_standalone_train.sh
```
# 验证
```shell
bash ./scripts/run_eval.sh
```