## 第十章 计算机操作系统——舞台幕后的工作者

错误：

| 页码 | 具体位置               | 原内容 | 修改后的内容 | 贡献者 |
| ---- | ---------------------- | ------ | ------------ | ------ |
|P1090|10.1.6.5标题上方3行|“KB”|KB||
|P1104|图10-42|图左侧排版有缺失|图左侧排版有缺失||
|P1118|左下|除非线程主动退出或者执行了系统调用|除非线程主动退出、执行了系统调用或者发生了内部异常中断或者外部设备中断||
|P1201|右侧第9行|.轰|呃轰||
|P1224|左上||亲和性（Affinity）加粗处理||
|P1273|右上角|One-Shot的O没有标蓝色|O标蓝色||
|P1298|图10-243|图片出现了镜像|||
| 脑图   | 中部 | 靠中断向量表调用门中断门中给出的权限 | 靠中断向量表、调用门、中断门中给出的权限 | -      |

建议：

| 页码 | 具体位置               | 原内容 | 修改后的内容 | 贡献者 |
| ---- | ---------------------- | ------ | ------------ | ------ |
| P1087   | 右侧提示框 | 目前主流的处理器中都会有iTLB（Instruction TLB）和dTLB（Data TLB），分别与iCache和 dCache对应。 | 目前主流的处理器中都会有iTLB（Instruction TLB）和dTLB（Data TLB），分别与iCache和 dCache对应。另外，切换进程后如果将整个TLB都清除，很不划算，目前主流CPU内部都实现了ASID（Address Space ID）机制，只要为TLB中的每个条目记录一列ASID，就可以避免动辄全清了。 | -      |

