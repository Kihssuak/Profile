<h1 align="center">Hey there, I'm Kausshik<img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="40px"></h1>
<h3 align="center">AI Enthusiast and a Multipotentialite</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=kaushikt07&label=Profile%20views&color=0e75b6&style=flat" alt="kaushikt07" /> </p>


- 🔭 I’m currently working on **Data Analytics**

- 🌱 I’m currently learning **Machine Learning**

- 👯 I’m looking to collaborate on **Open Source Project**

- 💬 Ask me about **Python, MySQL, Data Visualization**

- 📫 How to reach me **mailkausshik@gmail.com**

- 📄 Know about my experiences [https://cutt.ly/VFPU70p](https://cutt.ly/VFPU70p)

- ⚡ Fun fact **I Think I am Funny!**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/kaushikt07" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="kaushikt07" height="30" width="40" /></a>
<a href="https://kaggle.com/https://www.kaggle.com/iamkausshik" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg" alt="https://www.kaggle.com/iamkausshik" height="30" width="40" /></a>
<a href="https://instagram.com/https://www.instagram.com/iamkausshik/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="https://www.instagram.com/iamkausshik/" height="30" width="40" /></a>
</p>


<h3 align="left">Languages and Tools:</h3>
<p align='center'>
<img src="https://media.giphy.com/media/TEnXkcsHrP4YedChhA/giphy.gif" width="200" height="200" frameBorder="0" class="giphy-embed" allowFullScreen></img></p>

<p align="left">
<a href="https://www.cprogramming.com/" target="_blank"> <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="c"/> </a>
<a href="https://isocpp.org/std/the-standard" target="_blank"> <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++"/> </a>
<a href="https://www.java.com" target="_blank"> <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java"/> </a>
<a href="https://www.mysql.com/" target="_blank"> <img src="https://img.shields.io/badge/MySQL-%234479A1?style=for-the-badge&logo=mysql" alt="MySQL"/> </a>
<a href="https://www.python.org" target="_blank"> <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen" alt="Python"/> </a>
<a href="https://www.jetbrains.com/pycharm/" target="_blank"> <img src="https://img.shields.io/badge/PyCharm-000000.svg?&style=for-the-badge&logo=PyCharm&logoColor=white" alt="Pycharm"/></a>
<a href="https://git-scm.com/" target="_blank"> <img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white" alt="Git"/> </a>
<a href="https://github.com/" target="_blank"> <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
<a href="https://www.linux.org/" target="_blank"> <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="linux"/> </a>
<a href="https://colab.research.google.com/notebooks/" target="_blank"> <img src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252" alt="Google Colab"/> </a>
<a href="https://jupyter.org/" target="_blank"> <img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter"/> </a>
<a href="https://numpy.org/" target="_blank"> <img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" alt="Numpy"/></a>
<a href="https://pandas.pydata.org/" target="_blank"> <img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/></a>
<a href="https://opencv.org/" target="_blank"> <img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white" alt="OpenCV"/></a>
<a href="https://pytorch.org/" target="_blank"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white" alt="Pytorch"/> </a>
<a href="https://scikit-learn.org/" target="_blank"> <img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit_learn"/> </a>

 
<h3 align="left">GitHub Stats🎯:</h3>
<img src ="https://github-readme-stats.vercel.app/api?username=Kihssuak&&show_icons=true&title_color=#black&icon_color=bb2acf&text_color=daf7dc&bg_color=151515">
<br><br>

  
<h3 align="left">Just a Snake 🐍 Eating away my Contribution...😭</h3>

![snake gif](name: generate animation

on:
  # run automatically every 24 hours
  schedule:
    - cron: "0 */12 * * *" 
  
  # allows to manually run the job at any time
  workflow_dispatch:
  
  # run on every push on the main branch
  push:
    branches:
    - main
    
  

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10
    
    steps:
      # generates a snake game from a github user (<github_user_name>) contributions graph, output a svg animation at <svg_out_path>
      - name: generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          
          
      # push the content of <build_dir> to a branch
      # the content will be available at https://raw.githubusercontent.com/<github_user>/<repository>/<target_branch>/<file> , or as github page
      - name: push github-contribution-grid-snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }})

<br><br>
<h2 align='center'>Support Me By Starring ⭐ Some Of My Repositories</h2>
<br>
<p align='center'>
<img src="https://media.giphy.com/media/O51MQ3DduOcGW6ofR3/giphy.gif" width="200" height="200" frameBorder="0" class="giphy-embed" allowFullScreen></img></p>
<br>




