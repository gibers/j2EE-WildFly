"# j2EE-WildFly" 

<br>
Supprimer les credentials : git config --global -e
<br>
<br>
rajouter le credential wincred : git config --global credential.helper wincred
<br>
<br>
remplir le credential précédemment rajouté : git credential-wincred store 
<br>
<br>
protocol=https <br>
host=bigfont.ca <br>
username=shaun <br>
password=super-strong-password <br>
<br>
Vérifier le crédential : git credential-wincred get <br>
protocol=https <br>
host=bigfont.ca <br>
<br>
Supprimer le credential : 
git credential-wincred erase <br>
protocol=https  <br>
host=bigfont.ca  <br>


 