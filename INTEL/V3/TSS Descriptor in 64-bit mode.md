# TSS Descriptor in 64-bit mode [64位下的TSS选择器]
在64位模式下，不支持任务切换，但TSS描述符仍然存在。一个64位的TSS的格式在7.7节中描述。
在64位模式中，TSS描述扩展为16个字节（见图7-4）。这种扩展也适用于在64位模式中的LDT描述符。表3-2提供了段类型字段的编码信息。

![](../../img/TSS-LDT-DESCRIPTOR.png)