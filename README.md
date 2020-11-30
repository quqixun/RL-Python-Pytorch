# RL-Python-Pytorch

<br/>

《强化学习-原理与Python实现》原书使用```Numpy```、```Keras```和```Tensorflow```实现强化学习方法，见[rl-book](https://github.com/ZhiqingXiao/rl-book)。  

这里使用```Pytorch```将原书中深度强化学习方法实现一遍。

- [x] 1 - 初识强化学习
- [x] 2 - Markov决策过程
- [x] 3 - 有模型数值迭代
- [x] 4 - 回合更新价值迭代
- [x] 5 - 时序差分价值迭代
- [x] 6 - 函数近似方法
- [ ] 7 - 回合更新策略梯度方法
- [ ] 8 - 执行者/评论者方法
- [ ] 9 - 连续动作空间的确定性策略
- [ ] 10 - 综合案例：电动游戏
- [ ] 11 - 综合案例：棋盘游戏
- [ ] 12 - 综合案例：自动驾驶

<br/>

---

<br/>

## 环境配置

| Package    | Version | Installation                                                 |
| ---------- | ------- | ------------------------------------------------------------ |
| python     | 3.8.6   | conda create --name rl python=3.8.6                          |
| numpy      | 1.19.4  | pip install numpy==1.19.4                                    |
| scipy      | 1.5.4   | pip install scipy==1.5.4                                     |
| pandas     | 1.1.4   | pip install pandas==1.1.4                                    |
| sympy      | 1.7     | pip install sympy==1.7                                       |
| gym        | 0.17.3  | pip install gym==0.17.3                                      |
| tqdm       | 4.54.0  | pip install tqdm==4.54.0                                     |
| matplotlib | 3.3.3   | pip install matplotlib==3.3.3                                |
| notebook   | 6.1.5   | pip install notebook==6.1.5                                  |
| pytorch    | 1.7.0   | cpu：conda install pytorch\==1.7.0 cpuonly -c pytorch<br/>gpu：conda install pytorch\==1.7.0 cudatoolkit=10.2 -c pytorch |

