# YUChineseSorting

一.导入头文件#import "ChineseString.h"

二.使用示例

    NSArray *stringsToSort=[NSArray arrayWithObjects:
                            @"￥hhh, .$",@" ￥Chin ese ",@"开源中国 ",@"www.oschina.net",
                            @"开源技术",@"社区",@"开发者",@"传播",
                            @"2014",@"a1",@"100",@"中国",@"暑假作业",
                            @"键盘", @"鼠标",@"hello",@"world",@"b1",
                            nil];
    
    self.indexArray = [ChineseString IndexArray:stringsToSort];
    self.letterResultArr = [ChineseString LetterSortArray:stringsToSort];
    
  
  ![log](http://static.oschina.net/uploads/space/2015/1110/095952_dh2k_868062.png)

  ![效果图](http://static.oschina.net/uploads/space/2014/0304/163611_Wclh_868062.png)
