---
title: "November Result"
categories: [ShifuFX]
tags: [ShifuFX]
excerpt: "Based on November"
---

|  NO | DATE  | ENTRY   | OPEN PRICE  | CLOSE PRICE | PIP  | TP| SL|
|---|---|---|---|---|---|---|---|
| 1  |1-Nov-22   | SELL  | 1637  | 1646  | 9  |  | :x: | 
| |  | BUY  | 1649  | 1646  | 3  |  | :x: | 
| 2  | 2-Nov-22  |  SELL | 1654  | 1658  | 4  |  | :x: |
| |  | SELL  | 1658  | 1647  | 11  | :heavy_check_mark: |  | 
| 3  |3-Nov-22   |  SELL | 1642   | 1633  | 9 | :heavy_check_mark: | | 
| |  | SELL  | 1627  | 1634  | 7  |  | :x: | 
| 4  |  4-Nov-22 |  SELL | 1655  | 1660  |  5|  |:x: | 
| 5  | 5-Nov-22  | :heavy_minus_sign:  | :heavy_minus_sign:  |  :heavy_minus_sign: |  :heavy_minus_sign: |  :heavy_minus_sign: |  :heavy_minus_sign: |
| 6  | 6-Nov-22  |:heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   | :heavy_minus_sign:   |:heavy_minus_sign:  | :heavy_minus_sign:  |
| 7  | 7-Nov-22  |:heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   | :heavy_minus_sign:   |:heavy_minus_sign:  | :heavy_minus_sign:  |
| 8 | 8-Nov-22  | BUY  | 1671   | 1673   | 2 |  :heavy_check_mark: |   |
| 9  | 9-Nov-22  |:heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   | :heavy_minus_sign:   |:heavy_minus_sign:  | :heavy_minus_sign:  |
| 10  | 10-Nov-22  | BUY  | 1702  | 1711  | 9 | :heavy_check_mark: | | 
| 11  | 11-Nov-22  | :heavy_minus_sign:   | :heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   | :heavy_minus_sign:  | :heavy_minus_sign:  |
| 12  | 12-Nov-22  | :heavy_minus_sign:   | :heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   | :heavy_minus_sign:  | :heavy_minus_sign:  |
| 13  | 13-Nov-22  | :heavy_minus_sign:   | :heavy_minus_sign:   |:heavy_minus_sign:   | :heavy_minus_sign:   | :heavy_minus_sign:  | :heavy_minus_sign:  |
| 14  | 14-Nov-22  | :heavy_minus_sign:   | :heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   | :heavy_minus_sign:  | :heavy_minus_sign:  |
| 15  | 15-Nov-22  | :heavy_minus_sign:   | :heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   | :heavy_minus_sign:  | :heavy_minus_sign:  |
| 16  | 16-Nov-22  | :heavy_minus_sign:   | :heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   | :heavy_minus_sign:  | :heavy_minus_sign:  |
| 17  | 17-Nov-22  | :heavy_minus_sign:   | :heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   | :heavy_minus_sign:  | :heavy_minus_sign:  |
| 18 | 18-Nov-22  |  SELL | 1762   | 1757  | 5 | :heavy_check_mark: | | 
| 19  | 19-Nov-22  | :heavy_minus_sign:   | :heavy_minus_sign:   | :heavy_minus_sign:  | :heavy_minus_sign:   |   |:heavy_minus_sign:   |
| 20  | 20-Nov-22  |:heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   |   :heavy_minus_sign:  |
| 21  | 21-Nov-22  |  SELL | 1749   | 1741   |8   |:heavy_check_mark:   |   |
| 22 | 22-Nov-22  | SELL  | 1747   | 1738   | 9  | :heavy_check_mark:   |   |
| 23  | 23-Nov-22  | SELL  | 1740 | 1743  | 3   |   |:x:   |
| 24  | 24-Nov-22  |  BUY | 1748  | 1760  | 12  | :heavy_check_mark: | | 
| 25  |  25-Nov-22 | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_minus_sign:  |  :heavy_minus_sign: | :heavy_minus_sign:  |:heavy_minus_sign:|
| 26  |  26-Nov-22 | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_minus_sign:  |  :heavy_minus_sign: | :heavy_minus_sign:  |:heavy_minus_sign:|
| 27 | 27-Nov-22  | :heavy_minus_sign:  |  :heavy_minus_sign: |  :heavy_minus_sign: |  :heavy_minus_sign: |  :heavy_minus_sign: |:heavy_minus_sign:|
| 28  | 28-Nov-22  |  SELL | 1755   | 1760   | 5  |   |:x:   |
| 29  | 29-Nov-22  | SELL  | 1754   | 1758   | 4   |   |:x:   |
| 30  |  30-Nov-22 |  SELL | 1760   | 1742   | 18   |  :heavy_check_mark: |   |

|    |   |    | TOTAL TRADE  |  | | 84| 40 |

## Total Trade

<div id="container" style="width:100%; height:400px;"></div>

<script> 

document.addEventListener('DOMContentLoaded', function () {
        const chart = Highcharts.chart('container', {
            chart: {
                type: 'line'
            },
            title: {
                text: 'November Trade With Shifu FX'
            },
            xAxis: {
                title: {
                    text: 'Week'
                },
                categories: [],
            },
            yAxis: {
                title: {
                    text: 'PIP'
                }
            },
             tooltip: {
                valueSuffix: 'pip'
            },
            series: [{
                name: 'Take Profit',
                data: [0,13,70,84],
                lineWidth: 3,
                color: '#07ed16'
            }, {
                name: 'Stop Loss',
                data: [0,16, 30, 40],
                lineWidth: 3,
                color: '#ed1307'
            }, {
                name: 'OFF',
                data: [0,1,4,7],
                lineWidth: 3,
            }
            ],
        });
    });
</script>

## Trade Result Monthly

<div>
  <canvas id="myChart"></canvas>
</div>

<script> 
    var ctx = document.getElementById('myChart').getContext('2d'); 
    var myChart = new Chart(ctx, { 
        type: 'line', 
        data: {
            labels: [' ','Sep', 'Oct', 'Nov', 'Des'],
            datasets: [
                {
                    label: 'Take Profit',
                    data: [0, 144, 183, 267],
                    fill: false,
                    borderWith: 5,
                    backgroundColor: '#2a9df4',
                    borderColor: '#2a9df4',
                },

                {
                    label: 'Stop Loss',
                    data: [0, 64, 95, 135],
                    fill: false,
                    borderWith: 5,
                    backgroundColor: '#F65A83',
                    borderColor: '#F65A83',

                }
                
                ], 
                },

            options: 
                {
                    scales:
                    { yAxes: [{
                        ticks: {beginAtZero: true}
                    }]}
                }
}); 
</script>