
## �ο�
https://hengyunabc.github.io/github-to-maven-repo/

http://bastengao.com/blog/2013/03/hosting-maven-repository-on-github.html

## ����

### deploy������git�ֿ�
mvn -DaltDeploymentRepository=zhiyin-mvn-repo::default::file:E:/Github/MavenRepository/repository/ -Dmaven.test.skip=true clean source:jar javadoc:jar deploy

### ָ��Profile 
mvn -Dmaven.home=E:\Software\apache-maven-3.2.5 -s E:\Software\apache-maven-3.2.5\conf\setting.xml -Dmaven.repo.local=E:\MavenRepository -DskipTests=true deploy -P rd

mvn -Dmaven.home=E:\Software\apache-maven-3.2.5 -s E:\Software\apache-maven-3.2.5\conf\setting.xml -Dmaven.repo.local=E:\MavenRepository -DskipTests=true clean source:jar javadoc:jar install
