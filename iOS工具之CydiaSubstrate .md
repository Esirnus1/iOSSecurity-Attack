### CydiaSubstrate 

CydiaSubstrate 是绝大部分teek正常工作的基础

##### 一、MobileHook
	
1.mobile的作用是替换系统函数(即hook)
	
	// 作用于OC函数,可直接替换掉方法    
	void MSHookMessageEx(Class class, SEL selector, IMP replacement, IMP *result);
	// 作用于C , C++	直接汇编插入,实现hook
	void MSHookFunction(void* function, void* replacement, void** original);
##### 二、MobileLoader
##### 三、Safe mode
