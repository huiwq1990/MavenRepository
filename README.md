
## �ο�
https://hengyunabc.github.io/github-to-maven-repo/

http://bastengao.com/blog/2013/03/hosting-maven-repository-on-github.html

## ���𵽱���

mvn -DaltDeploymentRepository=zhiyin-mvn-repo::default::file:E:/Github/MavenRepository/repository/ -Dmaven.test.skip=true clean source:jar javadoc:jar deploy
