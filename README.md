<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clever - 智能搜索</title>
    
    <script async src="https://cse.google.com/cse.js?cx=15d6b6bdc24554f1e"></script>
    
    <style>
        body {
            font-family: "PingFang SC", "Microsoft YaHei", -apple-system, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            background-color: #ffffff;
            padding-top: clamp(60px, 15vh, 200px);
        }
        .container {
            width: 90%;
            max-width: 650px;
            text-align: center;
        }
        h1 {
            font-size: clamp(3rem, 10vw, 4.5rem);
            margin-bottom: 20px;
            color: #4285f4; 
            letter-spacing: -2px;
            font-weight: 700;
            user-select: none;
        }
        h1 span { color: #ea4335; }
        
        .gcse-search {
            margin-top: 20px;
            width: 100%;
            min-height: 50px;
        }

        /* 强制覆盖 Google 的一些默认样式，让它更美观 */
        .gsc-control-cse {
            background-color: transparent !important;
            border: none !important;
            padding: 0 !important;
        }
        .gsc-search-button-v2 {
            border-radius: 8px !important;
            padding: 10px 20px !important;
        }
        .gsc-input-box {
            border-radius: 24px !important;
            padding: 5px 15px !important;
            border: 1px solid #dfe1e5 !important;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Cle<span>ver</span></h1>
        
        <div class="gcse-search"></div>
    </div>

</body>
</html>
