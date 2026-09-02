世界上最简单的搭建个人博客的方案。只需要一个Github账号，十几秒后就能拥有一个个人的博客。
## 搭建个人博客  
首先去官网获取模版创建仓库
> https://github.com/Meekdai/Gmeek         
<img width="1338" height="453" alt="Image" src="https://github.com/user-attachments/assets/f7e7dd6c-dd3a-409e-b984-18a73f0cfdf8" />
记住需要带.github.io作为后缀，前面的随意
<img width="1164" height="935" alt="Image" src="https://github.com/user-attachments/assets/e6a008dd-74ea-40ec-8c6c-63c5ee9adce9" />
创建完成后先去 Settings 中的 Pages，将其中的 Source 设置为 GitHub Actions
<img width="1911" height="981" alt="Image" src="https://github.com/user-attachments/assets/ae024be9-edc9-4a1a-8e4c-4676aad11780" />
配置成功后就可以开始写作了。点击Issues，点击New Issues，就可以开始直接写作了。
<img width="2022" height="1044" alt="Image" src="https://github.com/user-attachments/assets/cdfa5a3c-5171-4f74-a73a-bd0a5c852ba3" />
标题内容随意，但必须在右侧的 labels 选择 label 给这个 issue
<img width="1998" height="1127" alt="Image" src="https://github.com/user-attachments/assets/042f2e29-fe14-4976-aebd-81ae2ac80a53" />
完成后点击 create 即可，之后就可以在 Actions 看到构建已经开始了
<img width="2024" height="1023" alt="Image" src="https://github.com/user-attachments/assets/870ab3a8-b332-4cb3-b9fe-be32b7861e22" />
等待构建结束后，返回主页可以看到Github为我们分配的一个域名
<img width="1974" height="1035" alt="Image" src="https://github.com/user-attachments/assets/03c49410-c521-4c5e-aaaa-a74b72a44df8" />
点击域名进去看看就是个人的一个博客
<img width="1446" height="972" alt="Image" src="https://github.com/user-attachments/assets/62c5ea3c-d5e1-49b6-b572-09a9542ddba5" />    
  
## 修改配置
进入主页点击 config.json 就能看到标题这些，点击修改根据属性进行个人喜好的设置
<img width="1911" height="819" alt="Image" src="https://github.com/user-attachments/assets/235de528-86f0-4292-bf95-2d153487c699" />
然后点击右上方的 Commit changes...
完成后，回到 Actions 点击 build Gmeek，点击Run workflow，然后点击Run workflow，重新构建
<img width="2367" height="903" alt="Image" src="https://github.com/user-attachments/assets/376eaf31-21d3-41f9-a1f0-70f23464893d" />
等待构建完成后，回到刚才的那个网站，就可以看到修改的内容
<img width="1397" height="528" alt="Image" src="https://github.com/user-attachments/assets/8698453a-ec0b-4dd4-9bfe-d730ba475a5f" />
$\color{red}{\text{若需要删除文章，也必须重新构建之后才会在博客上删除内容}}$