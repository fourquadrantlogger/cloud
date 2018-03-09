KVM 是 kernel-based Virtual Machine 的简称，是一个开源的系统虚拟化模块，自Linux 2.6.20之后集成在Linux的各个主要发行版本中。它使用Linux自身的调度器进行管理，所以相对于Xen，其核心源码很少。KVM已成为学术界的主流VMM之一。　KVM的虚拟化需要硬件支持（如Intel VT技术或者AMD V技术)。是基于硬件的完全虚拟化。而Xen早期则是基于软件模拟的Para-Virtualization，新版本则是基于硬件支持的完全虚拟化。但Xen本身有自己到进程调度器，存储管理模块等，所以代码较为庞大。广为流传的商业系统虚拟化软件VMware ESX系列也是基于软件模拟的Para-Virtualization。
KVM (全称是 Kernel-based Virtual Machine) 是 Linux 下 x86 硬件平台上的全功能虚拟化解决方案，包含一个可加载的内核模块 kvm.ko 提供和虚拟化核心架构和处理器规范模块。
使用 KVM ，可允许运行多个虚拟机，包括 Linux 和 Windows操作系统。 每个虚拟机有私有的硬件，包括网卡、磁盘以及图形适配卡等。
