# eaternity-cloud-ide

**setup with on git repo for code and one repo for ide settings**

Please clone everything in ~/git/
Different directory structure could lead to problems.

- close Intellij
- cd ~/git
- git clone git@github.com:Eaternity/eaternity-cloud.git
- git clone git@github.com:Eaternity/eaternity-cloud-ide.git
- move directory ~/git/eaternity-cloud-ide to ~/git/eaternity-cloud-ide-repo
- start Intellij
- File -> New Project -> next
- select Java or Node.js -> next 
- select nothing-> next
- - Project name: eaternity-cloud
- - Project location: ~/git/eaternity-cloud-ide
- - Content root: ~/git/eaternity-cloud
- - Module file location: ~/git/eaternity-cloud-ide
- - finish
- close Intellij
- copy everything (including .git/ and .idea/) from  ~/git/eaternity-cloud-ide-repo to ~/git/eaternity-cloud-ide

- start intellij
- check if maven is enabled, if not
- - View -> Tool Windows -> Maven Projects
- - click + and select eaternity-cloud/pom.xml

