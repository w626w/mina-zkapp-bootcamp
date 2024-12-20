## task1：创建 auro wallet 账户，完成水龙头领水

### 1. 概述 Mina 所采用的证明系统(包括名称、特点)

Mina 采用的是 Recursive zkSNARK（递归零知识证明）系统，它具有以下特点：

- 递归性：可以证明其他 SNARK 的有效性；支持证明的链式组合；能够压缩多个证明为单个证明。

- 可组合性：多个证明可以组合成一个证明；支持增量式验证；允许并行处理。

- 固定大小：无论计算量多大，证明大小保持不变；验证时间恒定；存储效率高。

### 2. 概述递归零知识证明在 Mina 共识过程中的应用

Mina 通过递归零知识证明：

- 每个新区块的证明都建立在前一个证明之上，而不需要增加证明的大小（仅有 22kb），可以节省了大量时间和能源。

- 验证过程非常迅速和高效，任何设备，包括计算能力较弱的设备，都能轻松同步和验证 Mina 网络。

- 保护用户隐私，用户分享的不是数据本身，而是关于这些数据的证明，这样区块链只需要验证这些数据符合一定的要求即可。

### 3. 领水 tx hash

5Juq63jyFXGnCK6nbcfULYdGTrAnbCczHac9ULWKvMJ1cq7qZvWk
