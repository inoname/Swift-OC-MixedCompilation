# Swift-OC-MixedCompilation
Swift与OC混合编译
##SWift调用OC
 * 新建swift文件
   此时系统自动生成 <#项目名称#>-Bridging-Header.h 文件
   并且 TARGETS-> Build Settings->Objective-C Bridging Header(搜索bridg) 选项中会自动填入以上头文件的路径
 * 在 <#项目名称#>-Bridging-Header.h 中#import要调用的OC对象头文件

##OC调用Swift
* 在OC文件中 #import "<#项目名称#>-Swift.h"

![image](https://github.com/kouliang/Swift-OC-MixedCompilation/blob/master/image/1.png)
