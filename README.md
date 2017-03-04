# dll_dlopen_dlsym_dlclose
the use of dynamic link library 
两种打开方式RTLD_LAZY和RTLD_NOW：前者在打开共享库的时候，会检查库里面所有的函数是否已经实现；后者只在dlsym的时候，检查使用的函数是否实现
