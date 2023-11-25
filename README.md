<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人网站</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
        }

        header {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
        }

        section {
            margin-top: 20px;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #333;
        }

        p {
            line-height: 1.6;
        }

        .contact-info {
            list-style-type: none;
            padding: 0;
        }

        .contact-info li {
            margin-bottom: 10px;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
        }

        .skills div {
            background-color: #4CAF50;
            color: white;
            padding: 8px;
            margin: 4px;
            border-radius: 4px;
        }
    </style>
</head>
<body>

    <header>
        <h1>你的名字</h1>
        <p>个人网站</p>
    </header>

    <section>
        <h2>个人简介</h2>
        <p>你好，我是你的名字。欢迎访问我的个人网站。我对前端开发和设计有浓厚的兴趣，并致力于不断学习和改进我的技能。</p>
    </section>

    <section>
        <h2>简历</h2>
        <p><strong>教育背景:</strong> 你的学校，学位，专业，毕业时间</p>
        <p><strong>工作经历:</strong> 公司名称，职位，工作内容，起止时间</p>
    </section>

    <section>
        <h2>技能</h2>
        <div class="skills">
            <div>HTML</div>
            <div>CSS</div>
            <div>JavaScript</div>
            <div>React</div>
            <div>Photoshop</div>
        </div>
    </section>

    <section>
        <h2>联系方式</h2>
        <ul class="contact-info">
            <li>Email: your.email@example.com</li>
            <li>电话: +123 456 7890</li>
            <li>地址: 你的地址</li>
        </ul>
    </section>

    <script>
        // 如果需要添加 JavaScript 功能，可以在这里编写代码
    </script>

</body>
</html>
