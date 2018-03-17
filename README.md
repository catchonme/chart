## 使用`canvas`绘制图表

## 使用方法

1. 引入`chart.js`文件

2. 配置参数，曲线图参数配置示例如下
```apple js
var options = {
      el:"#line-chart",
      data: [
        [243,9,564,134,97,139,233,47,88,43,197,245,841,32,775,123,666,235],
        [23,143,56,14,917,19,23,474,418,430,97,245,84,302,75,12,61,500],
      ],
      xAxis:["13:00","14:00","15:00","16:00","17:00","18:00","19:00","20:00","21:00","22:00","23:00","0:00","1:00","2:00","3:00","4:00","5:00","6:00"],
      yAxis:"m/s",
      title:"Line Example"
    }
```

3. 调用函数
```apple js
chart.line(options);
```
