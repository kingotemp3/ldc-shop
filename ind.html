<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>获取文本示例</title>
</head>
<body>
    <!-- 你的页面其他内容 -->
    <h1>这是页面主要内容</h1>
    <p>页面加载后，下方会通过接口获取并添加一段文本。</p>

    <script>
        // 定义一个异步函数来获取文本
        async function fetchTextAndAppend() {
            const apiUrl = 'https://api.lolimi.cn/API/shangg/api?type=text';
            
            try {
                // 1. 发起网络请求
                const response = await fetch(apiUrl);
                
                // 2. 检查请求是否成功 (状态码为200-299)
                if (!response.ok) {
                    throw new Error(`网络请求失败，状态码: ${response.status}`);
                }
                
                // 3. 获取响应的纯文本
                const resultText = await response.text();
                
                // 4. 创建一个新的元素来放置文本
                const newDiv = document.createElement('div');
                newDiv.id = 'api-result'; // 可以添加一个ID方便后续查找
                newDiv.textContent = resultText; // 设置文本内容
                
                // 5. 添加一些样式（可选，使其在移动端显示更友好）
                newDiv.style.cssText = 'margin-top: 20px; padding: 15px; border-top: 1px solid #eee; color: #666;';
                
                // 6. 将新元素插入到HTML文档的<body>标签最底部
                document.body.appendChild(newDiv);
                
            } catch (error) {
                // 捕获并处理请求过程中可能发生的任何错误
                console.error('获取数据时出错:', error);
                
                // 即使在出错的情况下，也在页面底部显示一个友好的错误提示
                const errorDiv = document.createElement('div');
                errorDiv.id = 'api-error';
                errorDiv.textContent = '抱歉，暂时无法加载内容。请稍后再试。';
                errorDiv.style.cssText = 'margin-top: 20px; padding: 15px; background-color: #fff0f0; color: #d00;';
                document.body.appendChild(errorDiv);
            }
        }

        // 当页面初始的HTML文档完全加载和解析完毕后，执行我们的函数
        document.addEventListener('DOMContentLoaded', fetchTextAndAppend);
    </script>
</body>
</html>
