<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amsterdam Logic Model</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .logic-model {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
            width: 80%;
            max-width: 1000px;
        }
        .logic-model .section {
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background-color: white;
            text-align: center;
        }
        .logic-model .section h2 {
            margin-bottom: 10px;
        }
        .logic-model .arrows {
            text-align: center;
            font-size: 24px;
            color: #555;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <div class="logic-model">
        <div class="section" style="background-color: #e3f2fd;">
            <h2>Inputs</h2>
            <p>Policy support, collaboration, funding, expertise.</p>
        </div>

        <div class="arrows">&#8595;</div>

        <div class="section" style="background-color: #e8f5e9;">
            <h2>Activities</h2>
            <p>Pass policies, expand parks, implement physical education programs, develop curricula, create school gardens.</p>
        </div>

        <div class="arrows">&#8595;</div>

        <div class="section" style="background-color: #fff8e1;">
            <h2>Process Objectives (2022)</h2>
            <ul>
                <li>Eliminate local food advertising to children.</li>
                <li>Increase parks by 10%.</li>
                <li>Implement school physical activity requirements.</li>
                <li>Develop curricula for physical activity and nutrition.</li>
                <li>Expand school gardens from 13 to 21.</li>
            </ul>
        </div>

        <div class="arrows">&#8595;</div>

        <div class="section" style="background-color: #ffecb3;">
            <h2>Short-Term Outcomes (2024)</h2>
            <ul>
                <li>75% of children can name benefits of reducing screen time.</li>
                <li>25% increase in positive attitudes toward physical activity.</li>
                <li>50% increase in positive attitudes toward fruits and vegetables.</li>
            </ul>
        </div>

        <div class="arrows">&#8595;</div>

        <div class="section" style="background-color: #ffcdd2;">
            <h2>Intermediate Outcomes (2025)</h2>
            <ul>
                <li>25% reduction in daily consumption of sugary drinks.</li>
                <li>15% reduction in screen time over 2 hours daily.</li>
                <li>15% increase in recommended fruit/vegetable intake.</li>
                <li>20% increase in daily physical activity of at least 1 hour.</li>
            </ul>
        </div>

        <div class="arrows">&#8595;</div>

        <div class="section" style="background-color: #d1c4e9;">
            <h2>Long-Term Outcomes (2033)</h2>
            <p>Reduction of overweight and obesity rates in children from 21% to 13%.</p>
        </div>
    </div>
</body>
</html>
