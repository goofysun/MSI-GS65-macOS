# MSI-GS65-macOS

gs65 当前驱动状态

显卡：	uhd630能驱动，但是内屏黑屏，可通过type-c接显示器接外屏，
	gtx1070可驱动，可通过minidp或者hdmi接外屏显示

声卡： 试过所有applealc的layoutid，都无法识别声音设备，使用vodoohda完美驱动，但是声音偏小

网卡：有线网卡通过e2200 驱动，无线拆机换 bcm94352z ，目前wifi完美，蓝牙可连接部分设备

电池：使用 rehaman的电池驱动，不需要修改dsdt完美

键盘&触摸板，使用 smarttouchpad   4.7 beta5 勉强驱动，不好用

usb：通过 遮盖起器，所有端口可用

睡眠唤醒，睡眠变关机，不影响使用
