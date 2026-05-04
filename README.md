    1  sudo apt update
    2  sudo apt install nano
    3  cd /mnt/c/Users/KKQ/Desktop/Examen\ Docker/MF0223_3_EP_03_JIMENEZ_XAVIER/dev_enviroment
    4  nano frontend/public/index.html
    5  nano frontend/src/App.js
    6  nano frontend/src/styles/main.css
    7  history
    8  ls
    9  ls -la
   10  ls frontend/src/
   11  mkdir backup
   12  cp -r frontend backup/
   13  cp backend/app/server.js backup/server_backup.js
   14  mv frontend/src/styles/main.css frontend/public/
   15  mv frontend/src/App.js frontend/src/app.js
   16  mv backend/config/config.json backend/app/
   17  chmod 744 scripts/deploy.sh
   18  chmod 640 backend/app/server.js
   19  chmod 444 README.md
   20  ls -l scripts backend/app README.md
   21  rm -r frontend/src/components
   22  cp -r backup/frontend/src/components frontend/src/
   23  rm -r temp
   24  rm backup/server_backup.js
   25  tree
   26  ls -R
   27  pwd
   28  history
