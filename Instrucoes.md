## Curso de Git da ADA Tech
--
https://cursos.ada.tech/curso-digital/ad048bd7-8188-4ba0-bfab-b62c91460b83/modulo/11e3cacf-ad98-4554-b79c-bc18ee5b26e4/topico/8b773d8b-5c16-436e-9dd7-8be743d7f69e


https://i.imgur.com/KLQZRJu.png
# git init
    * Inicia um repositorio do git
# git add 
    * Adiciona arquivos a serem monitorados pelo git
# git status
    * lista os arquivos que foram modificados e como esta em relação ao remoto
# git diff
    * Mostra o que foi removido e adicionado
    pode ter o --staged para mostrar as diferenças nos arquivos preparados (stageds)
# git commit -m "message xxxxxx"
    * faz o commit e salva o "snashot/state" do repositório.
# git log
    * mostra o log de commits
# git restore
    * Volta o repositório ou arquivo a um estado anterior
### REPOS REMOTOS
## git remote add origin https://github.com/Michael1503/git-commands.git
    * Seta o repo remoto a ser usado
## git push -u origin master
    * faz um push (envia as alterações commitadas)
## git pull
    * Vai no repo remoto e traz pro repo local e aplica sem pedir confirmação
    * tomar muito cuidado
## git fetch
    * busca as modificações e não aplica
    * ai usamos o git diff origin/master para mostrar as alterações, caso concordemos, rodamos o git pull
