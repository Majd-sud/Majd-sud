
ea288f35-bdc0-4fa7-80f1-fa8b3bfb9dc3.png

From inside your GitHub profile folder, run:

git init
git add .
git commit -m "Update GitHub profile"
git branch -M main
git remote add origin https://github.com/Majd-sud/Majd-sud.git
git push -u origin main
If the repo is already connected to GitHub, just use:

git add .
git commit -m "Update GitHub profile"
git push
To check status first:

git status
And if you downloaded my README as README-natural-pink.md, rename it first:

ren README-natural-pink.md README.md
Then:

git add .
git commit -m "Update profile README"
git push

it dose not apesr in github profile

Most likely one of these 3 things is wrong:

The repository name must be exactly your GitHub username:

Majd-sud
So the repo should be:

https://github.com/Majd-sud/Majd-sud
The repository must be Public.

The file must be named exactly:

README.md
and it must be in the root of the repository, not inside another folder. GitHub confirms all three are required for a profile README to appear. 

Your repo should look like this:

Majd-sud/
└── README.md
not:

Majd-sud/
└── some-folder/
    └── README.md
Check locally:

git status
git remote -v
Then push again:

git add README.md
git commit -m "Add profile README"
git push
After that, open:

https://github.com/Majd-sud/Majd-sud
and confirm you can see README.md there.

If it exists there and the repo is public, it should automatically appear at the top of your GitHub profile. 

If you send me a screenshot of your Majd-sud repository page, I can tell you immediately what's wrong.


not pink and fun enough 

Yep — this one is more pink and more fun, but still clean and believable. No emoji spam, no corporate-AI wording, no complicated assets folder.

Download the pink fun README

It uses:

soft pink wave header/footer

pink + white tech badges

pink GitHub stats

casual section names like hi, things I've built, stuff I use

simpler wording that sounds more natural

Rename it to:

README.md
then push:

git add README.md
git commit -m "Update profile design"
git push



README-pink-fun.md
مستند


المكتبة
/
README-pink-fun.md


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=FFB6D5&height=190&section=header&text=Majd%20Alsahafi&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Software%20Engineer%20%7C%20I%20like%20building%20things&descAlignY=60&descSize=17" width="100%" />

<br>

<a href="https://my-portfolio-rho-navy.vercel.app/"> <img src="https://img.shields.io/badge/portfolio-FF8FBD?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"> </a> <a href="https://www.linkedin.com/in/majd-alsahafi-/"> <img src="https://img.shields.io/badge/linkedin-FF8FBD?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"> </a> <a href="https://github.com/Majd-sud"> <img src="https://img.shields.io/badge/github-FF8FBD?style=flat-square&logo=github&logoColor=white" alt="GitHub"> </a> <a href="https://drive.google.com/file/d/1HIff9_C9sW1wrHdKjG7zAv_OWp-qT7jz/view?usp=sharing"> <img src="https://img.shields.io/badge/resume-FF8FBD?style=flat-square&logo=googledrive&logoColor=white" alt="Resume"> </a>

</div>

<br>

hi
I'm Majd, a Software Engineering graduate who likes learning by actually building things.

I enjoy trying different parts of software engineering instead of staying in one box — backend, web, AI/ML, testing, APIs, and whatever else looks interesting enough to build.

Right now I'm mainly working on small projects that help me get better at writing cleaner code, designing better systems, and understanding how everything fits together.

things I've built
Hazem
An AI road-safety project built to detect dangerous driving behavior.
Second place in the Absher Challenge 2025.

Rasid
A traffic-violation detection system using YOLOv11, ONNX, Flutter, and Firebase.

Smart Traffic Violation & Risk Prediction System
A C++ traffic-management project with a Python machine-learning model for risk prediction.

SkillsTrade
A full-stack peer skill-exchange platform built with JavaScript, PHP, MySQL, and AJAX.

see all my repositories

stuff I use
<div align="center">

<img src="https://img.shields.io/badge/Python-FFF0F6?style=for-the-badge&logo=python&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/C++-FFF0F6?style=for-the-badge&logo=cplusplus&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/JavaScript-FFF0F6?style=for-the-badge&logo=javascript&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/TypeScript-FFF0F6?style=for-the-badge&logo=typescript&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/Java-FFF0F6?style=for-the-badge&logo=openjdk&logoColor=FF5FA2">

<br>

<img src="https://img.shields.io/badge/Django-FFF0F6?style=for-the-badge&logo=django&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/Node.js-FFF0F6?style=for-the-badge&logo=nodedotjs&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/Express-FFF0F6?style=for-the-badge&logo=express&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/React-FFF0F6?style=for-the-badge&logo=react&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/Flutter-FFF0F6?style=for-the-badge&logo=flutter&logoColor=FF5FA2">

<br>

<img src="https://img.shields.io/badge/PostgreSQL-FFF0F6?style=for-the-badge&logo=postgresql&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/MySQL-FFF0F6?style=for-the-badge&logo=mysql&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/Firebase-FFF0F6?style=for-the-badge&logo=firebase&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/Docker-FFF0F6?style=for-the-badge&logo=docker&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/Git-FFF0F6?style=for-the-badge&logo=git&logoColor=FF5FA2">

</div>

currently
learning     backend + systems + ML
building     C++ and Node.js projects
practicing   APIs, testing, clean architecture
goal         become a better engineer one project at a time
github
<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Majd-sud&show_icons=true&hide_border=true&title_color=FF5FA2&icon_color=FF8FBD&text_color=6B5A63&bg_color=FFF9FC" width="49%" alt="GitHub stats" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Majd-sud&layout=compact&hide_border=true&title_color=FF5FA2&text_color=6B5A63&bg_color=FFF9FC" width="49%" alt="Top languages" />

</div>

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=FFB6D5&height=100&section=footer" width="100%" />

</div>

المكتبة
/
README-pink-fun.md


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=FFB6D5&height=190&section=header&text=Majd%20Alsahafi&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Software%20Engineer%20%7C%20I%20like%20building%20things&descAlignY=60&descSize=17" width="100%" />

<br>

<a href="https://my-portfolio-rho-navy.vercel.app/"> <img src="https://img.shields.io/badge/portfolio-FF8FBD?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"> </a> <a href="https://www.linkedin.com/in/majd-alsahafi-/"> <img src="https://img.shields.io/badge/linkedin-FF8FBD?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"> </a> <a href="https://github.com/Majd-sud"> <img src="https://img.shields.io/badge/github-FF8FBD?style=flat-square&logo=github&logoColor=white" alt="GitHub"> </a> <a href="https://drive.google.com/file/d/1HIff9_C9sW1wrHdKjG7zAv_OWp-qT7jz/view?usp=sharing"> <img src="https://img.shields.io/badge/resume-FF8FBD?style=flat-square&logo=googledrive&logoColor=white" alt="Resume"> </a>

</div>

<br>

hi
I'm Majd, a Software Engineering graduate who likes learning by actually building things.

I enjoy trying different parts of software engineering instead of staying in one box — backend, web, AI/ML, testing, APIs, and whatever else looks interesting enough to build.

Right now I'm mainly working on small projects that help me get better at writing cleaner code, designing better systems, and understanding how everything fits together.

things I've built
Hazem
An AI road-safety project built to detect dangerous driving behavior.
Second place in the Absher Challenge 2025.

Rasid
A traffic-violation detection system using YOLOv11, ONNX, Flutter, and Firebase.

Smart Traffic Violation & Risk Prediction System
A C++ traffic-management project with a Python machine-learning model for risk prediction.

SkillsTrade
A full-stack peer skill-exchange platform built with JavaScript, PHP, MySQL, and AJAX.

see all my repositories

stuff I use
<div align="center">

<img src="https://img.shields.io/badge/Python-FFF0F6?style=for-the-badge&logo=python&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/C++-FFF0F6?style=for-the-badge&logo=cplusplus&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/JavaScript-FFF0F6?style=for-the-badge&logo=javascript&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/TypeScript-FFF0F6?style=for-the-badge&logo=typescript&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/Java-FFF0F6?style=for-the-badge&logo=openjdk&logoColor=FF5FA2">

<br>

<img src="https://img.shields.io/badge/Django-FFF0F6?style=for-the-badge&logo=django&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/Node.js-FFF0F6?style=for-the-badge&logo=nodedotjs&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/Express-FFF0F6?style=for-the-badge&logo=express&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/React-FFF0F6?style=for-the-badge&logo=react&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/Flutter-FFF0F6?style=for-the-badge&logo=flutter&logoColor=FF5FA2">

<br>

<img src="https://img.shields.io/badge/PostgreSQL-FFF0F6?style=for-the-badge&logo=postgresql&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/MySQL-FFF0F6?style=for-the-badge&logo=mysql&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/Firebase-FFF0F6?style=for-the-badge&logo=firebase&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/Docker-FFF0F6?style=for-the-badge&logo=docker&logoColor=FF5FA2"> <img src="https://img.shields.io/badge/Git-FFF0F6?style=for-the-badge&logo=git&logoColor=FF5FA2">

</div>

currently
learning     backend + systems + ML
building     C++ and Node.js projects
practicing   APIs, testing, clean architecture
goal         become a better engineer one project at a time
github
<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Majd-sud&show_icons=true&hide_border=true&title_color=FF5FA2&icon_color=FF8FBD&text_color=6B5A63&bg_color=FFF9FC" width="49%" alt="GitHub stats" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Majd-sud&layout=compact&hide_border=true&title_color=FF5FA2&text_color=6B5A63&bg_color=FFF9FC" width="49%" alt="Top languages" />

</div>

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=FFB6D5&height=100&section=footer" width="100%" />

</div>

