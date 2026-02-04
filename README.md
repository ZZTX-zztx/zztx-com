# zztx-com
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Service Center</title>
    <link rel="icon" href="./zztx.ico" type="image/x-icon">
    <style>
        /* Basic styles */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
            position: relative;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        h1 {
            color: #333;
        }
        .content-section {
            margin-bottom: 30px;
            padding-bottom: 20px;
            border-bottom: 1px solid #f0f0f0;
        }
        .content-section:last-child {
            border-bottom: none;
        }
        .content-section h3 {
            color: #4CAF50;
            margin-top: 0;
        }
        .content-section p {
            margin-bottom: 10px;
        }
        .content-section ul {
            margin-top: 10px;
            padding-left: 20px;
        }
        .content-section li {
            margin-bottom: 5px;
        }
        
        /* Language selector */
        .language-selector {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            z-index: 1000;
        }
        .language-selector h4 {
            margin: 0 0 10px 0;
            font-size: 14px;
            color: #666;
        }
        .language-selector button {
            background: #f8f8f8;
            border: 1px solid #ddd;
            border-radius: 4px;
            padding: 5px 10px;
            margin-right: 5px;
            cursor: pointer;
            font-size: 14px;
        }
        .language-selector button:hover {
            background: #e8e8e8;
        }
        .language-selector button.active {
            background: #4CAF50;
            color: white;
            border-color: #4CAF50;
        }
        
        /* Language content */
        .lang-content {
            display: none;
        }
        .lang-content.active {
            display: block;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="lang-content active" id="en-content">
            <h1>Digital Service Center</h1>
            
            <div class="content-section">
                <h3>Version 1: Professional & Comprehensive</h3>
                <p><em>(Suitable for Store Front, Posters, Google Business Profile)</em></p>
                <p>One-Stop Digital Service Center</p>
                <p>Phone Repairs | Device Sales | Document Printing | Software Solutions</p>
                
                <h4>📱 Mobile Services</h4>
                <p>Professional repair for all smartphone brands (screen/battery replacement, motherboard repair). Brand new & certified pre-owned phones available. Transparent pricing, quick turnaround.</p>
                
                <h4>🖨️ Printing & Copying</h4>
                <p>High-speed printing, copying, scanning, document binding, and ID photo services.</p>
                
                <h4>🎵 Multimedia</h4>
                <p>Lossless music download, video editing, and data transfer to USB drives/memory cards.</p>
                
                <h4>💻 Software & Tools</h4>
                <p>Custom mobile app development. Access a wide range of Windows tools directly via the Web – no installation required! System reinstallation and PC troubleshooting also available.</p>
            </div>
            
            <div class="content-section">
                <h3>Version 2: Concise & Catchy</h3>
                <p><em>(Suitable for Social Media, Business Cards, Short Video Captions)</em></p>
                <p>[Shop Name] Digital Hub</p>
                <p>Your Neighbourhood Tech Concierge!</p>
                <ul>
                    <li>✅ Phone Repair & Sales</li>
                    <li>✅ Printing, Copying & Scanning</li>
                    <li>✅ Music Download & USB Transfer</li>
                    <li>✅ Custom App Development</li>
                    <li>✅ Web-Based Windows Tools</li>
                </ul>
                <p>📍 Address: [Your Address] | 📞 Tel: [Your Number]</p>
            </div>
            
            <div class="content-section">
                <h3>Version 3: Casual & Friendly</h3>
                <p><em>(Suitable for Verbal Introduction, Chat Groups, Customer Service)</em></p>
                <p>Welcome to [Shop Name]! We fix all your digital problems under one roof.</p>
                <p>Got a broken phone? We do repairs and sell both new and second-hand phones.</p>
                <p>Need documents printed? Fast service and great prices.</p>
                <p>Want new songs? We can download lossless music to your phone or USB.</p>
                <p>We even build custom apps! Plus, you can use various Windows tools through our website – no need to install anything complicated.</p>
                <p>Whatever your tech need, we’ve got you covered!</p>
            </div>
        </div>
        
        <div class="lang-content" id="zh-content">
            <h1>数字服务中心</h1>
            
            <div class="content-section">
                <h3>版本1：专业全面</h3>
                <p><em>（适用于店面、海报、谷歌商家资料）</em></p>
                <p>一站式数字服务中心</p>
                <p>手机维修 | 设备销售 | 文档打印 | 软件解决方案</p>
                
                <h4>📱 移动服务</h4>
                <p>专业维修所有智能手机品牌（屏幕/电池更换，主板维修）。提供全新和认证二手手机。价格透明，快速周转。</p>
                
                <h4>🖨️ 打印复印</h4>
                <p>高速打印、复印、扫描、文档装订和身份证照片服务。</p>
                
                <h4>🎵 多媒体</h4>
                <p>无损音乐下载、视频编辑，以及数据传输到U盘/存储卡。</p>
                
                <h4>💻 软件工具</h4>
                <p>定制移动应用开发。直接通过网络访问各种Windows工具 - 无需安装！还提供系统重装和电脑故障排除服务。</p>
            </div>
            
            <div class="content-section">
                <h3>版本2：简洁醒目</h3>
                <p><em>（适用于社交媒体、名片、短视频标题）</em></p>
                <p>[店铺名称] 数字中心</p>
                <p>您的邻里科技管家！</p>
                <ul>
                    <li>✅ 手机维修销售</li>
                    <li>✅ 打印复印扫描</li>
                    <li>✅ 音乐下载U盘传输</li>
                    <li>✅ 定制应用开发</li>
                    <li>✅ 网页版Windows工具</li>
                </ul>
                <p>📍 地址：[您的地址] | 📞 电话：[您的号码]</p>
            </div>
            
            <div class="content-section">
                <h3>版本3：轻松友好</h3>
                <p><em>（适用于口头介绍、聊天群、客户服务）</em></p>
                <p>欢迎来到[店铺名称]！我们一站式解决您所有数字问题。</p>
                <p>手机坏了？我们提供维修服务，同时销售全新和二手手机。</p>
                <p>需要打印文档？快速服务，价格优惠。</p>
                <p>想要新歌曲？我们可以将无损音乐下载到您的手机或U盘。</p>
                <p>我们甚至开发定制应用！此外，您可以通过我们的网站使用各种Windows工具 - 无需安装任何复杂软件。</p>
                <p>无论您有什么科技需求，我们都能满足！</p>
            </div>
        </div>
    </div>

    <!-- Language selector -->
    <div class="language-selector">
        <h4>选择语言：</h4>
        <button class="active" onclick="switchLanguage('en')">English</button>
        <button onclick="switchLanguage('zh')">中文</button>
    </div>

    <script>
        function switchLanguage(lang) {
            // Update active button
            const buttons = document.querySelectorAll('.language-selector button');
            buttons.forEach(btn => btn.classList.remove('active'));
            event.target.classList.add('active');
            
            // Switch content
            document.querySelectorAll('.lang-content').forEach(content => {
                content.classList.remove('active');
            });
            document.getElementById(lang + '-content').classList.add('active');
        }
    </script>
</body>
</html>
