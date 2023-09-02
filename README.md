# primer-repositori
Primer repositori curs Github
Ens hem clonat el repositori de github a local
O sigui que estem en una carpeta local i fem:
git clone https://github.com/emilicamprubi/primer-repositori.git
Primera prova de commit a veure què passa
git remote (per consultar el origin des de local)
Ocultació de l'email original - sustituim pel que ens dóna github
git config --global user.email (consultem l'actual)
git config --global user.email el-correu-sustitutiu (el nou correu)
INTENTAR ENVIAR a github amb git push
git push origin master
en ppi ens pot donar un error de que no tenim permisos
hem de configurar les claus en github en HTTPS
en el moment de fer commit ens demanarà autenticació
podem utilitzar un token que generem des de github
settings - developer - tokens - classic
hem de guardar el token en un lloc segur
ara hi tornem i quan ens demani el token l'hi afegim
git push origin master
a veure si a github es veu tota aquesta modificació
MODIFICACIÓ !!!
