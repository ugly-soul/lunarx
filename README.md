# lunarx
用于flutter中获取农历的dart包

## 添加依赖
```javascript
  dependencies:
    lunarx: ^0.0.1
```

## 一个简单的示例
```javascript
  import 'package:lunarx/lunarx.dart';

  var result = lunarx(2023, 2, 5); 
  print(result); // -> {date: 2023-2-5, lunarDate: 2023-1-15, festival: null, lunarFestival: 元宵节, lYear: 2023, lMonth: 1, lDay: 15, Animal: 兔, IMonthCn: 正月, IDayCn: 十五, cYear: 2023, cMonth: 2, cDay: 5, gzYear: 癸卯, gzMonth: 甲寅, gzDay: 癸亥, isToday: false, isLeap: false, nWeek: 7, ncWeek: 星期日, isTerm: false, Term: null, astro: 水瓶座}

```
