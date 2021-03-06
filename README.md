# AISC

> Edit smart contract for blockchain without programming

- AISC（AI Smart Contract）是一个图灵完备的智能合约免编程工具，用户通过图形化的编辑方式编制合约，由工具的Ai模块自动产生合约程序代码。AISC开创性的免去了编程，摆脱了只能由程序员才能编写智能合约的桎梏，回归传统合同编制的便利性。
- AISC起源于游戏制作工具的思想，将原本需要代码实现的逻辑进行可视化以及编辑。
- AISC不仅可以为GAME.FUND社区基础建设带来高效工具，而且可以成为区块链世界的通用工具，势必对区块链的发展产生重大影响。
- AISC提供各类模块组件，以及模板，进一步加速智能合约的实现过程。
- AISC立志于加快区块链技术普及的推动者，伴随着行业发展，可视化的智能合约开发工具将会成为一种区块链开发者的常用工具，加速区块链应用的开发与落地。
- AISC作为开源项目获得了NEO的大力支持。可视化编辑框架已经完成DEMO，初始版本将首先支持NEO的智能合约。

- 通过通用中间表达，来解除和具体区块链智能合约语义规范的耦合。通过适配层适配多种区块链，并且易于扩展。智能合约的执行一般来说需要看成类似数据库的事务操作（某些地方不太恰当的比喻为原子操作），要么全部成功，要么完全没有执行。系统至上而下，分为Frontend Creator、IR、Backend Adapter、Blockchain底层等多层结构。Frontend的Creator是创建工具图形化工具，提供符合普通人认知和思维的逻辑可视化编辑方法；IR（Intermediate Representation）是工具智能地所推导输出的中间表达；中间表达输入Backend Adapter，针对不同的Blockchain（区块链）实现有其特定的Adapater，特定Adapater按特定区块链的智能合约虚拟机代码集格式输出智能合约指令文件。

http://github.com/gamefund/aisc
<br>
http://aisc.tech (Under construction)
