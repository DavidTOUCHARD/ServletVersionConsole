# ServletVersionConsole

# ServletVersionJSP

Installer TomcatServer 9.0 : http://objis.com/tutoriel-tomcat-n1-installation-tomcat-8/

Generation du fichier WAR :
A la racine du projet, où se trouve le dossier target executer la commande suivante :

$ mvn package

Une fois que l'invite de commande affiche "BUILD SUCCESS", vous pouvez aller dans le dossier "target" et récuperer le fichier WAR.

Déploiement de l'application sur le serveur Tomcat : 

1-Deplacer le fichier TestServletV1.war dans le dossier webapp de Tomcat (Le fichier .war peut etre renomé)

2-Executer startup.bat situé dans le dossier bin de tomcat 

3-Dans l'url du navigateur internet, entrer la commande suivante : http://localhost:8080/TestServletV1/PremierServlet (TestServletV1 étant le nom du fichier WAR déplacé dans le dossier webapp)

Fonctionnalités présentes :

- Session

- Contexte

- Local Port

- Local addr.

- Remote Port

- Protocol

- Remote User

- Server name

- Reader

- AuthType

- Session

Technologies :

Servlet, HTML, JSP, Bootstrap



