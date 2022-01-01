# linux5.10.58-analysis
linux源码分析
* alloc_pages：流程图及部分中文注释
* free_pages:流程图及部分中文注释
* 缺页中断：5.10.58这个版本的源码在x86结构下已经找不到__do_page_fault，入口是：DEFINE_IDTENTRY_RAW_ERRORCODE (exc_page_fault)，暂时只有一些零散中文注释

 
> 中文注释不是很完整，一部分在自己笔记中，一部分在源码中，没有系统性整理。除了两幅流程图，其它内容暂时只适合个人使用（比如task_struct进程描述符 mm_struct内存描述符 虚拟内存区域vm_area_struct等都并未在源码中有详细中文注释）
