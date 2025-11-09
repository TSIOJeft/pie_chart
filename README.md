# Pie Chart Plus

edit from apgapg/pie_chart because author already not accept any pullrequest 2 years. So I fork the package and add some feature.

[pie_chart](https://pub.dev/packages/pie_chart)

![shoot](https://github.com/TSIOJeft/pie_chart/tree/master/screen_shots/shoot.jpeg)



## 😄 Add Features

1. Add show value label on chart.
2. Avoid value overlay.
3. Add value line if show value outside.

## 🤔 Use

```dart
PieChart(
        dataMap: pieChartDataMap.value,
        animationDuration: const Duration(milliseconds: 800),
        chartLegendSpacing: 32,
        chartRadius: MediaQuery.of(context).size.width / 3.2,
        colorList: colorList,
        initialAngleInDegree: 0,
        chartType: ChartType.ring,
        ringStrokeWidth: 32,
        legendOptions: const LegendOptions(
          showLegendsInRow: false,
          legendPosition: LegendPosition.right,
          showLegends: false,
          legendShape: BoxShape.circle,
          legendTextStyle: TextStyle(
            fontWeight: FontWeight.bold,
          ),
        ),
        // show line to value text
        showValueLine: true,
        // show label to value text
      showTitleWithValues: true,
        centerText: "cost_text".tr,
        chartValuesOptions: const ChartValuesOptions(
          showChartValueBackground: false,
          showChartValues: true,
          showChartValuesInPercentage: true,
          showChartValuesOutside: true,
          decimalPlaces: 2,
          
        ),
        // gradientList: ---To add gradient colors---
        // emptyColorGradient: ---Empty Color gradient---
      );
```


## 👍 Contribution
1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -m 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request
