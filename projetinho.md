o projeto é esse mesmo

para adicionar, modificar ou qualquer outra coisa os comandos sao os seguintes:

junior@DESKTOP-U4LI8CF MINGW64 /c/gitRafaela (main)
$ git add .    <---------<---------<---------<---------<---------<---------<--------- olhe o ponto, nao precisa citar os arquivos
junior@DESKTOP-U4LI8CF MINGW64 /c/gitRafaela (main)
$ git status   <---------<---------<---------<---------<---------<---------<---------
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   projetinho.md
        modified:   readme.md


junior@DESKTOP-U4LI8CF MINGW64 /c/gitRafaela (main)
$ git commit -m "criacao"  <---------<---------<---------<---------<---------<---------<---------
[main bf0b245] criacao
 2 files changed, 44 insertions(+)
 create mode 100644 projetinho.md

junior@DESKTOP-U4LI8CF MINGW64 /c/gitRafaela (main)
$ git push origin main <---------<---------<--------- nao precisa mais do remote, so dá o push e nem do  -u 
<---------<---------<---------<---------<---------
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 891 bytes | 891.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/JoseJuniordaSilva/gitRafaela.git<---------<---------<---------ele ja vai pro git
   8f080da..bf0b245  main -> main

junior@DESKTOP-U4LI8CF MINGW64 /c/gitRafaela (main)
$
OBS ==============
se eu quiser ver e alterar meus dados
junior@DESKTOP-U4LI8CF MINGW64 /c/gitRafaela (main)
$ git config user.name   <------<------<------<------<------<------<------
Jose Junior da Silva

junior@DESKTOP-U4LI8CF MINGW64 /c/gitRafaela (main)
$ git config user.email  <------<------<------<------<------<------<------<------
98925549+JoseJuniordaSilva@users.noreply.github.com

junior@DESKTOP-U4LI8CF MINGW64 /c/gitRafaela (main)
$ git config user.email croatajunior@gmail.com <------<------ MUDAR O EMAIL

junior@DESKTOP-U4LI8CF MINGW64 /c/gitRafaela (main)
$ git config user.email  <------<------<------<------<------<------
croatajunior@gmail.com

junior@DESKTOP-U4LI8CF MINGW64 /c/gitRafaela (main)
$
VI ISSO EM https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Configura%C3%A7%C3%A3o-Inicial-do-Git



