<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>برنامج أولياء الأمور</title>
    <style>
        * {
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #f0f2f5;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 700px;
            margin: 0 auto;
            background: #ffffff;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
            padding: 25px;
        }
        .header {
            text-align: center;
            border-bottom: 2px solid #eef0f3;
            padding-bottom: 15px;
            margin-bottom: 20px;
        }
        .header h1 {
            margin: 0;
            color: #1e293b;
            font-size: 24px;
        }
        .student-info {
            background: #f8fafc;
            border-right: 4px solid #2563eb;
            padding: 12px 16px;
            border-radius: 6px;
            margin-bottom: 20px;
        }
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
            gap: 15px;
            margin-bottom: 25px;
        }
        .stat-card {
            background: #eff6ff;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
        }
        .stat-card .value {
            font-size: 22px;
            font-weight: bold;
            color: #2563eb;
        }
        .stat-card .label {
            font-size: 13px;
            color: #64748b;
            margin-top: 5px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }
        th, td {
            padding: 12px;
            text-align: right;
            border-bottom: 1px solid #e2e8f0;
        }
        th {
            background-color: #f8fafc;
            color: #475569;
            font-size: 14px;
        }
        .status-absent {
            color: #dc2626;
            font-weight: bold;
        }
        .status-present {
            color: #16a34a;
            font-weight: bold;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="header">
        <h1>لوحة متابعة ولي الأمر</h1>
    </div>

    <div class="student-info">
        <strong>اسم الطالب:</strong> أحمد محمد علي <br>
        <strong>الصف:</strong> الرابع الابتدائي
    </div>

    <div class="stats-grid">
        <div class="stat-card">
            <div class="value">94%</div>
            <div class="label">المعدل العام</div>
        </div>
        <div class="stat-card">
            <div class="value">2</div>
            <div class="label">أيام الغياب</div>
        </div>
        <div class="stat-card">
            <div class="value">ممتاز</div>
            <div class="label">السلوك والمواظبة</div>
        </div>
    </div>

    <h3>سجل الدرجات والتقييمات</h3>
    <table>
        <thead>
            <tr>
                <th>المادة</th>
                <th>درجة الشهر الأول</th>
                <th>درجة الشهر الثاني</th>
                <th>الحالة</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>التربية الإسلامية</td>
                <td>98</td>
                <td>95</td>
                <td><span class="status-present">ممتاز</span></td>
            </tr>
            <tr>
                <td>اللغة العربية</td>
                <td>90</td>
                <td>92</td>
                <td><span class="status-present">جيد جداً</span></td>
            </tr>
            <tr>
                <td>الرياضيات</td>
                <td>88</td>
                <td>95</td>
                <td><span class="status-present">ممتاز</span></td>
            </tr>
            <tr>
                <td>العلوم</td>
                <td>95</td>
                <td>96</td>
                <td><span class="status-present">ممتاز</span></td>
            </tr>
        </tbody>
    </table>
</div>

</body>
</html>
