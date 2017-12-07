# scrapbox-alfred-workflow
scrapbox alfred workflow

depend on [scrapbox go cli](https://github.com/ohtomi/scrapbox)

![workflow screencast](https://i.gyazo.com/6a5b23660e0d2964f65b7ed29a0d33bb.gif)

# Installation
1. install [scrapbox go cli](https://github.com/ohtomi/scrapbox)
2. install [workflow package](https://github.com/dotimpact/scrapbox-alfred-workflow/releases) into alfred
3. specify environment variable
  - *gohome* : your go home path
  - *site* : your scrapbox project name
  - *token* : your scrapbox auth token(in scrapbox.io cookie "connect.sid" value)
  - ![variable setting dialog button](https://i.gyazo.com/7ac0a1fc941104c4df077cf1042a9191.png)
  - ![setting value](https://i.gyazo.com/e6aaabae4e0d97dea6059be9913eef35.png)
  
# Usage
- keyword "sb" : search scrapbox pages
  - enter: open selected scrapbox page
- keyword "sb:new" : create new page
  - arg: new page title
  - enter: open new scrapbox page with title
  
  
