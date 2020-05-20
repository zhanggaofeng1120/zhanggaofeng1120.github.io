---
title: 大数据可视化
date: 2018-09-30 17:25:30
type: "categories"
layout: "categories"
---
#第一书记可视化呈现


<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Awesome-pyecharts</title>
            <script type="text/javascript" src="https://assets.pyecharts.org/assets/echarts.min.js"></script>

</head>
<body>
    <div id="9491357b49884194a9d1ddeee1617617" class="chart-container" style="width:900px; height:500px;"></div>
    <script>
        var chart_9491357b49884194a9d1ddeee1617617 = echarts.init(
            document.getElementById('9491357b49884194a9d1ddeee1617617'), 'light', {renderer: 'canvas'});
        var option_9491357b49884194a9d1ddeee1617617 = {
    "animation": true,
    "animationThreshold": 2000,
    "animationDuration": 1000,
    "animationEasing": "cubicOut",
    "animationDelay": 0,
    "animationDurationUpdate": 300,
    "animationEasingUpdate": "cubicOut",
    "animationDelayUpdate": 0,
    "series": [
        {
            "type": "bar",
            "name": "product1",
            "data": [
                {
                    "value": 12,
                    "percent": 0.8
                },
                {
                    "value": 23,
                    "percent": 0.5227272727272727
                },
                {
                    "value": 33,
                    "percent": 0.868421052631579
                },
                {
                    "value": 3,
                    "percent": 0.05454545454545454
                },
                {
                    "value": 33,
                    "percent": 0.4342105263157895
                }
            ],
            "stack": "stack1",
            "barCategoryGap": "50%",
            "label": {
                "show": true,
                "position": "right",
                "margin": 8,
                "formatter": function(x){return Number(x.data.percent * 100).toFixed() + '%';}
            },
            "rippleEffect": {
                "show": true,
                "brushType": "stroke",
                "scale": 2.5,
                "period": 4
            }
        },
        {
            "type": "bar",
            "name": "product2",
            "data": [
                {
                    "value": 3,
                    "percent": 0.2
                },
                {
                    "value": 21,
                    "percent": 0.4772727272727273
                },
                {
                    "value": 5,
                    "percent": 0.13157894736842105
                },
                {
                    "value": 52,
                    "percent": 0.9454545454545454
                },
                {
                    "value": 43,
                    "percent": 0.5657894736842105
                }
            ],
            "stack": "stack1",
            "barCategoryGap": "50%",
            "label": {
                "show": true,
                "position": "right",
                "margin": 8,
                "formatter": function(x){return Number(x.data.percent * 100).toFixed() + '%';}
            },
            "rippleEffect": {
                "show": true,
                "brushType": "stroke",
                "scale": 2.5,
                "period": 4
            }
        }
    ],
    "legend": [
        {
            "data": [
                "product1",
                "product2"
            ],
            "selected": {
                "product1": true,
                "product2": true
            }
        }
    ],
    "tooltip": {
        "show": true,
        "trigger": "item",
        "triggerOn": "mousemove|click",
        "axisPointer": {
            "type": "line"
        },
        "textStyle": {
            "fontSize": 14
        },
        "borderWidth": 0
    },
    "xAxis": [
        {
            "show": true,
            "scale": false,
            "nameLocation": "end",
            "nameGap": 15,
            "gridIndex": 0,
            "inverse": false,
            "offset": 0,
            "splitNumber": 5,
            "minInterval": 0,
            "splitLine": {
                "show": false,
                "lineStyle": {
                    "show": true,
                    "width": 1,
                    "opacity": 1,
                    "curveness": 0,
                    "type": "solid"
                }
            },
            "data": [
                1,
                2,
                3,
                4,
                5
            ]
        }
    ],
    "yAxis": [
        {
            "show": true,
            "scale": false,
            "nameLocation": "end",
            "nameGap": 15,
            "gridIndex": 0,
            "inverse": false,
            "offset": 0,
            "splitNumber": 5,
            "minInterval": 0,
            "splitLine": {
                "show": false,
                "lineStyle": {
                    "show": true,
                    "width": 1,
                    "opacity": 1,
                    "curveness": 0,
                    "type": "solid"
                }
            }
        }
    ]
};
        chart_9491357b49884194a9d1ddeee1617617.setOption(option_9491357b49884194a9d1ddeee1617617);
    </script>
</body>
</html>


<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Awesome-pyecharts</title>
            <script type="text/javascript" src="https://assets.pyecharts.org/assets/echarts.min.js"></script>
        <script type="text/javascript" src="https://assets.pyecharts.org/assets/maps/china.js"></script>

</head>
<body>
    <div id="696b66053ddb485094a76bf445352e1b" class="chart-container" style="width:900px; height:500px;"></div>
    <script>
        var chart_696b66053ddb485094a76bf445352e1b = echarts.init(
            document.getElementById('696b66053ddb485094a76bf445352e1b'), 'white', {renderer: 'canvas'});
        var option_696b66053ddb485094a76bf445352e1b = {
    "animation": true,
    "animationThreshold": 2000,
    "animationDuration": 1000,
    "animationEasing": "cubicOut",
    "animationDelay": 0,
    "animationDurationUpdate": 300,
    "animationEasingUpdate": "cubicOut",
    "animationDelayUpdate": 0,
    "color": [
        "white",
        "#c23531",
        "#2f4554",
        "#61a0a8",
        "#d48265",
        "#749f83",
        "#ca8622",
        "#bda29a",
        "#6e7074",
        "#546570",
        "#c4ccd3",
        "#f05b72",
        "#ef5b9c",
        "#f47920",
        "#905a3d",
        "#fab27b",
        "#2a5caa",
        "#444693",
        "#726930",
        "#b2d235",
        "#6d8346",
        "#ac6767",
        "#1d953f",
        "#6950a1",
        "#918597"
    ],
    "series": [
        {
            "type": "effectScatter",
            "coordinateSystem": "geo",
            "showEffectOn": "render",
            "rippleEffect": {
                "show": true,
                "brushType": "stroke",
                "scale": 2.5,
                "period": 4
            },
            "symbolSize": 12,
            "data": [
                {
                    "name": "\u5e7f\u5dde",
                    "value": [
                        113.23,
                        23.16,
                        55
                    ]
                },
                {
                    "name": "\u5317\u4eac",
                    "value": [
                        116.407526,
                        39.90403,
                        66
                    ]
                },
                {
                    "name": "\u676d\u5dde",
                    "value": [
                        120.19,
                        30.26,
                        77
                    ]
                },
                {
                    "name": "\u91cd\u5e86",
                    "value": [
                        106.551556,
                        29.563009,
                        88
                    ]
                }
            ],
            "label": {
                "show": false,
                "position": "top",
                "margin": 8
            }
        },
        {
            "type": "lines",
            "name": "geo",
            "coordinateSystem": "geo",
            "zlevel": 3,
            "progressive": 400,
            "progressiveThreshold": 3000,
            "effect": {
                "show": true,
                "brushType": "stroke",
                "scale": 2.5,
                "period": 4,
                "color": "blue",
                "symbol": "arrow",
                "symbolSize": 6
            },
            "symbol": [
                "none",
                "arrow"
            ],
            "polyline": false,
            "large": false,
            "largeThreshold": 2000,
            "symbolSize": 12,
            "data": [
                {
                    "name": "\u5e7f\u5dde->\u4e0a\u6d77",
                    "coords": [
                        [
                            113.23,
                            23.16
                        ],
                        [
                            121.473701,
                            31.230416
                        ]
                    ]
                },
                {
                    "name": "\u5e7f\u5dde->\u5317\u4eac",
                    "coords": [
                        [
                            113.23,
                            23.16
                        ],
                        [
                            116.407526,
                            39.90403
                        ]
                    ]
                },
                {
                    "name": "\u5e7f\u5dde->\u676d\u5dde",
                    "coords": [
                        [
                            113.23,
                            23.16
                        ],
                        [
                            120.19,
                            30.26
                        ]
                    ]
                },
                {
                    "name": "\u5e7f\u5dde->\u91cd\u5e86",
                    "coords": [
                        [
                            113.23,
                            23.16
                        ],
                        [
                            106.551556,
                            29.563009
                        ]
                    ]
                }
            ],
            "lineStyle": {
                "show": true,
                "width": 1,
                "opacity": 1,
                "curveness": 0.2,
                "type": "solid"
            },
            "label": {
                "show": false,
                "position": "top",
                "margin": 8
            },
            "rippleEffect": {
                "show": true,
                "brushType": "stroke",
                "scale": 2.5,
                "period": 4
            }
        }
    ],
    "legend": [
        {
            "data": [
                "",
                "geo"
            ],
            "selected": {
                "": true,
                "geo": true
            },
            "show": true,
            "padding": 5,
            "itemGap": 10,
            "itemWidth": 25,
            "itemHeight": 14
        }
    ],
    "tooltip": {
        "show": true,
        "trigger": "item",
        "triggerOn": "mousemove|click",
        "axisPointer": {
            "type": "line"
        },
        "formatter": function (params) {        return params.name + ' : ' + params.value[2];    },
        "textStyle": {
            "fontSize": 14
        },
        "borderWidth": 0
    },
    "title": [
        {
            "text": "Geo-Lines-background",
            "padding": 5,
            "itemGap": 10
        }
    ],
    "geo": {
        "map": "china",
        "roam": true,
        "itemStyle": {
            "color": "#323c48",
            "borderColor": "#111"
        },
        "emphasis": {}
    }
};
        chart_696b66053ddb485094a76bf445352e1b.setOption(option_696b66053ddb485094a76bf445352e1b);
    </script>
</body>
</html>

