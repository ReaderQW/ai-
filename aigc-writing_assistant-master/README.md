## 环境配置：

```
conda create -n <name> python=3.13
conda activate <name>
pip install -r requirements.txt
```

或者直接：

```
conda <name> create -f  myenv.yml
conda activate <name>
```

## 数据库配置：

```
python init_db.py
```

### 管理员登录：

用户名：admin
密码：123

## 运行后端：

python app.py

## 访问前端：

http://127.0.0.1:5000/

## 文件结构：

```
WritingAssistant
├─ env.yml
├─ poetry.lock
├─ pyproject.toml
├─ README.md
├─ test
│  ├─ classicalChinese.txt
│  └─ poem.txt
├─ uploads
│  └─ 夏蝉.json
└─ writing_assistant
   ├─ app.py
   ├─ blueprints
   │  ├─ auth.py
   │  ├─ classicalChinese.py
   │  ├─ home.py
   │  ├─ material.py
   │  ├─ paint.py
   │  └─ poem.py
   ├─ db
   │  ├─ init_db.py
   │  └─ users.db
   ├─ static
   │  ├─ css
   │  │  ├─ classicalChinese.css
   │  │  ├─ footer.css
   │  │  ├─ header.css
   │  │  ├─ index.css
   │  │  ├─ material.css
   │  │  ├─ overall.css
   │  │  ├─ paint.css
   │  │  └─ poem.css
   │  ├─ images
   │  │  ├─ calendar1.png
   │  │  ├─ calendar2.png
   │  │  ├─ pic.png
   │  │  └─ spring.jpg
   │  └─ js
   │     ├─ classicalChinese.js
   │     ├─ index.js
   │     ├─ material.js
   │     ├─ overall.js
   │     ├─ paint.js
   │     └─ poem.js
   └─ templates
      ├─ classicalChinese.html
      ├─ index.html
      ├─ login.html
      ├─ material.html
      ├─ paint.html
      ├─ poem.html
      └─ register.html

```
