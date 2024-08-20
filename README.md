### python3 run my_introduction.py
```python
class Fourth_yr_CSE_Student:

    def __init__(self):
        self.name = "Pranav Pakalapati"
        self.role = "Py/Ai Dev"
        self.hobbies = ['sleeping','coding','eating']

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")
        
    def my_skills(self):
        my_skills = { 
        'languages': ['Python','C++','C'],
        'Frameworks' : ['Tensorflow','Django','R'],
        'Python Library' : ['numpy', 'opencv', 'pandas', 'glob', 'requests', 'PIL'],
        'Data Visualization' : ['Plotly', 'Seaborn', 'Matplotlib'],
        'Hosting & Cloud' : ['Digital Ocean','Streamlit Cloud'],
        'Other Skills': ['Git', 'Github','Project Management']
    }
       return my_skills
    
me = Fourth_yr_CSE_Student()
me.say_hi()
print(f"Take a Look at my skills {me.my_skills()}")
```

<!-- Social icons section -->
<h1 align="center"> Social Media: </h1>
  <p align="center">
    <a href="https://t.me/sasivatsal">
      <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=black">
    </a>
    <a href="https://sasivatsal.herokuapp.com/">
      <img src="https://img.shields.io/badge/WebPage-7cebf5?&style=for-the-badge&logo=data:image/png;base64,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&logoColor=black">
    </a>
    <a href="https://www.linkedin.com/in/sasi-vatsal-606195215/">
      <img src="https://img.shields.io/badge/linkedin-7cebf5?&style=for-the-badge&logo=linkedin&logoColor=black">
    </a>
    <a href="mailto:sasivatsal7122@gmail.com">
      <img src="https://img.shields.io/badge/SEND%20MAIL-7cebf5?&style=for-the-badge&logo=MAIL.RU&logoColor=black">
    </a>
  </p>
</h1>

<hr>

<!-- Description about me -->
<h2 align="center"> 🤔 About me 👨‍💻 </h2>


Eyyyy!!! <br />
- I am <b>Satya Sasi Vatsal</b> better known as 'Sasi'🕵🏼‍♂️ <br />
  - A Self- motivated, Inquisitive, energetic computer science engineering student skilled in leadership, with a strong foundation in math, logic, and cross-platform coding with proven and tested engineering, management, marketing skills Seeking a challenging role at a reputed organization to utilize my skills that can contribute to the company’s growth as well as enhance my knowledge by exploring new things. <br />
- I am from <strong>India</strong><br />
- I'm a guy who love to develop new things 🖥️ <br />
- So... I am more than a robot coding 🤖, I am a real human trying to learn new things and develop incredible projects with ❤️ meeting incredible people on the way🚀<br />
- If you are interested in a guy with a good vibe who loves the knowledge and the constant learning 📚, <b>⚙️I AM YOUR GUY⚙️</b> <br />
- Contact me for new projects 📨, <sup>I am open to collaborate with you</sup>
<br/><br/> 

### 🧐 More About Me:
<table style="border: none;">
  <tr style="border: none;">
    <td style="border: none;">
      <ul>
        <li>
          🔭 I’m currently studying at **VIIT**
        </li>
        <li>
          🤝 I’m looking to collaborate on Open Source Projects
        </li>
        <li>
          🌱 I’m currently learning Django  
        </li>
        <li> 
          👨🏻‍💻 Most of my projects are available on <a style='text-decoration:none;color:red' target='_blank' href="https://github.com/sasivatsal7122?tab=repositories">GitHub</a>
        </li>
        <li>
          💬 Ask me about anything tech related, I am happy to help (if you have questions with linux you can ask me🐧);
        </li>
        <li>
          📫 Feel free to contact me on <a href="https://www.linkedin.com/in/sasi-vatsal-606195215/">LinkedIn</a>
        </li>
        <li>
          🧠 I'm learning Machine Learning and Data Science
        </li>
        <li>
          📝 Checkout my <a href="https://sasivatsal.herokuapp.com/">Page</a>
        </li>
    </td>
    <td style="border: none;">
      <img align="right" alt="GIF" src="https://media1.giphy.com/media/xThuWu82QD3pj4wvEQ/giphy.gif?cid=790b761184ab84400e1cb4eefabca2bf83649c8520f19a73&rid=giphy.gif&ct=g" width="450vw"/>
    </td>
  </tr>
</table>
<br><br><br>

<!-- languajes and skills section -->

<h1 align="center"> Languages/Frameworks I'm good at: </h1>
<p align="center">
  <code><a href="https://www.python.org/"><img alt="Python" title="Python" src="./assets/python.png" height="42"></a></code>
  <code><a href="https://devdocs.io/c/"><img alt="C" title="C" src="./assets/c.png" height="42"></a></code>
  <code><a href="https://devdocs.io/cpp/"><img alt="C++" title="C++" src="./assets/cpp.png" height="42"></a></code>
  <code><a href="https://dev.java/learn/"><img alt="Java" title="Java" src="./assets/java.png" height="42"></a></code>
  <code><a href="https://en.wikipedia.org/wiki/HTML"><img alt="HTML 5" title="HTML 5" src="./assets/html.png" height="42"></a></code>
  <code><a href="https://www.w3.org/Style/CSS/Overview.en.html"><img alt="CSS 3" title="CSS 3" src="./assets/css.png" height="42"></a></code>
  <code><a href="https://www.djangoproject.com/"><img alt="Django" title="Django" src="./assets/Django-Logo.png" height="42"></a></code>
  <code><a href="https://www.djangoproject.com/"><img alt="Seaborn" title="Seaborn" src="./assets/seaborn.png" height="42"></a></code>
  <code><a href="https://fastapi.tiangolo.com/"><img alt="FastAPI" title="FastAPI" src="./assets/fast-api.svg" height="42"></a></code>
  <code><a href="https://www.gnu.org/software/bash"><img alt="Bash" title="Bash" src="./assets/bash.png" height="42"></a></code>
  <code><a href="https://github.com/features/actions"><img alt="GitHub Actions" title="GitHub Actions" src="./assets/actions.png" height="42"></a></code>
  <code><a href="https://daringfireball.net/projects/markdown"><img alt="Markdown" title="Markdown" src="./assets/markdown.png" height="42"></a></code>
</p>
<br>

<h1 align="center"> Languages/Frameworks I'm learning: </h1>
<p align="center">
  <code><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img alt="JavaScript" title="JavaScript" src="./assets/js.png" height="42"></a></code>
  <code><a href="https://www.java.com/en/"><img alt="Keras" title="Keras" src="./assets/keras.png" height="42"></a></code>
  <code><a href="https://www.java.com/en/"><img alt="Tensorflow" title="Tensorflow" src="./assets/Tensorflowpng.png" height="42"></a></code>
  <code><a href="https://www.java.com/en/"><img alt="Sklearn" title="Sklearn" src="./assets/sklearnpng.png" height="42"></a></code>
</p>
<br>

<h1 align="center"> Environments I work with: </h1>
<p align="center">
  <code><a href="https://www.archlinux.org/"><img alt="Ubuntu" title="Ubuntu" src="./assets/ubuntu.png" height="42"></a></code>
  <code><a href="https://github.com/"><img alt="GitHub" title="GitHub" src="./assets/github.png" height="42"></a></code>
  <code><a href="https://www.npmjs.com"><img alt="Heroku" title="Heroku" src="./assets/heroku.png" height="42"></a></code>
  <code><a href="https://www.npmjs.com"><img alt="FireBase" title="FireBase" src="./assets/firebase.png" height="42"></a></code>
  <code><a href="https://code.visualstudio.com/"><img alt="Vs code" title="Vs code" src="./assets/vscode.png" height="42"></a></code>
  <code><a href="https://code.visualstudio.com/"><img alt="Sublime Text" title="Sublime Text" src="./assets/sublime.png" height="42"></a></code>
</p>
<br>

<!-- GitHub stats section -->

## 📊 Github stats

<!-- Bassed on: https://github.com/anuraghazra/github-readme-stats -->
<p align="center">
  <br/>
  <a href="https://github.com/anuraghazra/github-readme-stats"><img alt="SasiVatsal's Github Stats" src="https://github-readme-stats.vercel.app/api/?username=sasivatsal7122&show_icons=true&count_private=true&theme=react&bg_color=1F222E&title_color=7cebf5&icon_color=2d7de4&show_icons=true&border_color=7cebf5&border_radius=10" height="192px"/></a>
  <a href="https://github.com/anuraghazra/github-readme-stats"><img alt="SasiVatsal's Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sasivatsal7122&langs_count=8&layout=compact&theme=react&bg_color=1F222E&title_color=7cebf5&icon_color=2d7de4&show_icons=true&border_color=7cebf5&border_radius=10" height="192px"/></a>
  <br/>
  <b>Note:</b> Top languages is only a metric of the languages my public code consists of and doesn't reflect experience or skill level.
</p>

<!-- Projects section -->

## 📘 My top projects

<!-- Bassed on: Repo info cards - https://github.com/anuraghazra/github-readme-stats -->
<p align="center">
  <p style="widht: 100%;" align="center">
    <a href="https://github.com/sasivatsal7122/Go_Screen-CineMatrix-ML-MODEL"><img align="left" width="45%" height="150px" src="https://github-readme-stats.vercel.app/api/pin/?username=sasivatsal7122&repo=Go_Screen-CineMatrix-ML-MODEL&bg_color=1F222E&title_color=7cebf5&icon_color=2d7de4&theme=react&border_color=7cebf5&border_radius=10&show_icons=true" alt="readme-typing-svg"></a>
    <a href="https://github.com/sasivatsal7122/Student-Marks-yonolesees-VIIT"><img align="right" width="45%" height="150px" src="https://github-readme-stats.vercel.app/api/pin/?username=sasivatsal7122&repo=Student-Marks-yonolesees-VIIT&bg_color=1F222E&title_color=7cebf5&icon_color=2d7de4&theme=react&border_color=7cebf5&border_radius=10&show_icons=true" alt="readme-typing-svg"></a>
  </p>
  <p align="center">&#8192;</p>
  <p style="widht: 100%;" align="center">
    <a href="https://github.com/sasivatsal7122/HandGesture-Recognition-and-Live-Translator"><img align="left" width="45%" height="150px" src="https://github-readme-stats.vercel.app/api/pin/?username=sasivatsal7122&repo=HandGesture-Recognition-and-Live-Translator&bg_color=1F222E&title_color=7cebf5&icon_color=2d7de4&theme=react&border_color=7cebf5&border_radius=10&show_icons=true" alt="readme-typing-svg"></a>
    <a href="https://github.com/sasivatsal7122/OpenCheatSheet-Heroku"><img align="right" width="45%" height="150px" src="https://github-readme-stats.vercel.app/api/pin?username=sasivatsal7122&repo=OpenCheatSheet-Heroku&theme=react&border_color=7cebf5&border_radius=10&bg_color=1F222E&title_color=7cebf5&icon_color=2d7de4&show_icons=true" alt="custom-icon-badges"></a>
  </p>
</p>

<p align="center">&#8192;</p>
<p align="center">&#8192;</p>

<p align="left">
  <a href="https://github.com/sasivatsal7122?tab=repositories"><img alt="All Repositories" title="All Repositories" src="https://custom-icon-badges.herokuapp.com/badge/-All%20Repos-2962FF?style=for-the-badge&logoColor=white&logo=repo"/></a>
</p>
