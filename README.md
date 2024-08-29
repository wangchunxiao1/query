<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的账户</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        .header {
            background-color: #fff;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .header h1 {
            margin: 0;
        }
        .header .options {
            display: flex;
            align-items: center;
        }
        .header .options img {
            width: 20px;
            height: 20px;
            margin-left: 10px;
        }
        .card {
            background-color: #fff;
            border-radius: 10px;
            padding: 20px;
            margin: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .card h2 {
            margin: 0;
            font-size: 24px;
            color: #333;
        }
        .card .card-info {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 20px;
        }
        .card .card-info .card-number {
            display: flex;
            align-items: center;
        }
        .card .card-info .card-number img {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            margin-right: 10px;
        }
        .card .card-info .card-number span {
            font-size: 24px;
            color: #333;
        }
        .card .card-info .card-number button {
            background-color: #38d9a9;
            color: #fff;
            border: none;
            padding: 5px 10px;
            border-radius: 5px;
            margin-left: 10px;
        }
        .card .card-balance {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 20px;
        }
        .card .card-balance .balance {
            font-size: 24px;
            color: #333;
        }
        .card .card-balance .details {
            background-color: #e0f2f1;
            color: #38d9a9;
            padding: 10px 20px;
            border-radius: 10px;
            font-size: 18px;
            text-align: center;
        }
        .card .card-actions {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .card .card-actions button {
            background-color: #fff;
            color: #333;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
        }
        .card .card-actions button:hover {
            background-color: #e0e0e0;
        }
        .credit-card {
            margin: 20px;
        }
        .credit-card img {
            width: 100%;
            height: auto;
        }
        .open-account {
            background-color: #fff;
            border: 2px dashed #f5a623;
            border-radius: 10px;
            padding: 20px;
            margin: 20px;
            text-align: center;
        }
        .open-account button {
            background-color: #f5a623;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            font-size: 24px;
            cursor: pointer;
        }
        .open-account button:hover {
            background-color: #f1c40f;
        }
        .footer {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            margin: 20px;
            text-align: center;
            font-size: 20px;
            color: #333;
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="https://via.placeholder.com/20" alt="Back">
        <h1>我的账户</h1>
        <div class="options">
            <img src="https://via.placeholder.com/20" alt="Option 1">
            <img src="https://via.placeholder.com/20" alt="Option 2">
            <img src="https://via.placeholder.com/20" alt="Option 3">
        </div>
    </div>
    <div class="card">
        <h2>借记卡</h2>
        <div class="card-info">
            <div class="card-number">
                <img src="https://via.placeholder.com/40" alt="Card Icon">
                <span>6228 **** 9073</span>
                <button>查看</button>
            </div>
            <div>
                <span>设置别名</span>
                <input type="checkbox" checked>
            </div>
        </div>
        <div class="card-balance">
            <div class="balance">人民币可用余额：762.23</div>
            <div class="details">详情</div>
        </div>
        <div class="card-actions">
            <button>查询明细</button>
            <button>我要转账</button>
            <button>我要理财</button>
        </div>
    </div>
    <div class="credit-card">
        <img src="https://via.placeholder.com/300" alt="Credit Card">
    </div>
    <div class="open-account">
        <button>开通电子账户</button>
    </div>

</body>
</html>
