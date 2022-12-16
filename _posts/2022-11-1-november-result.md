---
title: "November Result"
categories: [ShifuFX]
tags: [ShifuFX]
excerpt: "Based on November"
---

|  NO | DATE  | ENTRY   | OPEN PRICE  | CLOSE PRICE | PIP  | TP| SL|
|---|---|---|---|---|---|---|---|
| 1  |1-Nov-22   |   |   |   |  |  | | 
| 2  | 2-Nov-22  |   |   |   |  |  | | 
| 3  |3-Nov-22   |   |    |   |  |  | | 
| 4  |  4-Nov-22 |   |   |   |  |  | | 
| 5  | 5-Nov-22  | :heavy_minus_sign:  | :heavy_minus_sign:  |  :heavy_minus_sign: |  :heavy_minus_sign: |  :heavy_minus_sign: |  :heavy_minus_sign: |
| 6  | 6-Nov-22  |:heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   | :heavy_minus_sign:   |:heavy_minus_sign:  | :heavy_minus_sign:  |
| 7  | 7-Nov-22  |    |    |    |    |   |   |
| 8 | 8-Nov-22  |   |   |   |  |   |   |
| 9 | 9-Nov-22  |   |   |   | |   |   |
| 10  | 10-Nov-22  |   |   |   |  |  | | 
| 11  | 11-Nov-22  |   |   |   |  |  | |
| 12  | 12-Nov-22  | :heavy_minus_sign:   | :heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   | :heavy_minus_sign:  | :heavy_minus_sign:  |
| 13  | 13-Nov-22  | :heavy_minus_sign:   | :heavy_minus_sign:   |:heavy_minus_sign:   | :heavy_minus_sign:   | :heavy_minus_sign:  | :heavy_minus_sign:  |
| 14  |14-Nov-22   |  |  |     | |   |   |
| 15  | 15-Nov-22  |   |   |   | |   |   |
| 16  | 16-Nov-22  |   |   |   |  |  | | 
| 17  | 17-Nov-22  |   |   |   |  |  | | 
| 18 | 18-Nov-22  |   |   |   |  |  | | 
| 19  | 19-Nov-22  | :heavy_minus_sign:   | :heavy_minus_sign:   | :heavy_minus_sign:  | :heavy_minus_sign:   |   |:heavy_minus_sign:   |
| 20  | 20-Nov-22  |:heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   |:heavy_minus_sign:   |   :heavy_minus_sign:  |
| 21  | 21-Nov-22  |   |   |   |   |   |   |
| 22 | 22-Nov-22  |   |   |   |   |   |   |
| 23  | 23-Nov-22  |   | |   |    |   |   |
| 24  | 24-Nov-22  |   |   |   |  |  | | 
| 25 | 25-Nov-22  |   |   |   |  |  | | 
| 26  |  26-Nov-22 | :heavy_minus_sign:  | :heavy_minus_sign:  | :heavy_minus_sign:  |  :heavy_minus_sign: | :heavy_minus_sign:  |:heavy_minus_sign:|
| 27 | 27-Nov-22  | :heavy_minus_sign:  |  :heavy_minus_sign: |  :heavy_minus_sign: |  :heavy_minus_sign: |  :heavy_minus_sign: |:heavy_minus_sign:ww|
| 28  | 28-Nov-22  |   |   |   |  |   |   |
| 29  | 29-Nov-22  |   |   |   |   |   |   |
| 30  |  30-Nov-22 |   |   |   |   |   |   |

|    |   |    | TOTAL TRADE  |  | | | |

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
                data: [0],
                lineWidth: 3,
                color: '#07ed16'
            }, {
                name: 'Stop Loss',
                data: [0],
                lineWidth: 3,
                color: '#ed1307'
            }, {
                name: 'OFF',
                data: [0],
                lineWidth: 3,
            }
            ],
        });
    });
</script>