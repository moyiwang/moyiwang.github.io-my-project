<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>0909期数据可视化</title>
    <script src=" https://cdn.jsdelivr.net/npm/chart.js "></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f5f5f5;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            gap: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .chart-container {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            padding: 15px;
            flex: 1;
            min-width: 300px;
        }
        h2 {
            text-align: center;
            color: #333;
            font-size: 18px;
            margin-top: 0;
        }
        canvas {
            width: 100% !important;
            height: auto !important;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="chart-container">
            <h2>0909期线索占比</h2>
            <canvas id="pieChart"></canvas>
        </div>
        <div class="chart-container">
            <h2>0909期转化率</h2>
            <canvas id="barChart1"></canvas>
        </div>
        <div class="chart-container">
            <h2>0909期ROI</h2>
            <canvas id="barChart2"></canvas>
        </div>
    </div>

    <script>
        // 饼图数据 - 0909期线索占比
        const pieData = {
            labels: ["王莹莹", "李珊珊", "杨若晴", "孟琪云", "魏莱"],
            datasets: [{
                data: [745, 508, 195, 341, 12],
                backgroundColor: [
                    '#FF6384',
                    '#36A2EB',
                    '#FFCE56',
                    '#4BC0C0',
                    '#9966FF'
                ],
                borderWidth: 1
            }]
        };

        // 柱状图1数据 - 0909期转化率
        const barData1 = {
            labels: ["王莹莹", "李珊珊", "杨若晴", "梦琪云", "魏莱"],
            datasets: [{
                label: '转化率 (%)',
                data: [3.89, 0.79, 1.54, 1.47, 0],
                backgroundColor: '#FF6384',
                borderWidth: 1
            }]
        };

        // 柱状图2数据 - 0909期ROI
        const barData2 = {
            labels: ["王莹莹", "李珊珊", "杨若晴", "梦琪云", "魏莱"],
            datasets: [{
                label: 'ROI',
                data: [2.48, 0.47, 0.86, 0.86, 0],
                backgroundColor: '#36A2EB',
                borderWidth: 1
            }]
        };

        // 创建饼图
        const pieCtx = document.getElementById('pieChart').getContext('2d');
        new Chart(pieCtx, {
            type: 'pie',
            data: pieData,
            options: {
                responsive: true,
                plugins: {
                    tooltip: {
                        callbacks: {
                            label: function(context) {
                                const label = context.label || '';
                                const value = context.raw || 0;
                                const total = context.dataset.data.reduce((a, b) => a + b, 0);
                                const percentage = Math.round((value / total) * 100);
                                return `${label}: ${value} (${percentage}%)`;
                            }
                        }
                    },
                    legend: {
                        position: 'bottom',
                    }
                }
            }
        });

        // 创建第一个柱状图 (转化率)
        const barCtx1 = document.getElementById('barChart1').getContext('2d');
        new Chart(barCtx1, {
            type: 'bar',
            data: barData1,
            options: {
                responsive: true,
                scales: {
                    y: {
                        beginAtZero: true,
                        title: {
                            display: true,
                            text: '百分比 (%)'
                        }
                    }
                },
                plugins: {
                    tooltip: {
                        callbacks: {
                            label: function(context) {
                                return `${context.dataset.label}: ${context.raw}%`;
                            }
                        }
                    }
                }
            }
        });

        // 创建第二个柱状图 (ROI)
        const barCtx2 = document.getElementById('barChart2').getContext('2d');
        new Chart(barCtx2, {
            type: 'bar',
            data: barData2,
            options: {
                responsive: true,
                scales: {
                    y: {
                        beginAtZero: true,
                        title: {
                            display: true,
                            text: 'ROI值'
                        }
                    }
                },
                plugins: {
                    tooltip: {
                        callbacks: {
                            label: function(context) {
                                return `${context.dataset.label}: ${context.raw}`;
                            }
                        }
                    }
                }
            }
        });
    </script>
</body>
</html>
