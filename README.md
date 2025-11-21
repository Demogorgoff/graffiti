```
graffiti - Programa para deixar mensagens entre usuários de um mesmo sistema linux. 
Autor: Demogorgon
Inspirado por ou fork do mural.sh de slackjeff: slackjeff@riseup.net

##### Changelog:
03/04/2024 - Correção ortográfica - devnull (The POSIX Way Samurai)
13/11/2025 - Banner ASCII, novo menu, renomear programa - Demogorgon
13/11/2025 - Proteção contra injeção de comandos / escape codes - Demogorgon

Use: graffiti | less para exibir as mensagens linha por linha.
Use: graffiti | more para exibir as mensagens com paginação.

Requisitos sugeridos (Executar como root ou superusuário):
# Copiar o programa shellscript graffiti para todos os usuários utilizarem
# cp graffiti /usr/local/bin/
# chmod +x /usr/local/bin/graffiti
# Como root, cria o arquivo de mensagens e adiciona um "enter" antes do primeiro registro, para uma leitura padronizada.
# touch /var/log/graffiti_wall.log && printf '\n' > /var/log/graffiti_wall.log 
# chmod 666 /var/log/graffiti_wall.log
# Opcional:
# chattr +a /var/log/graffiti_wall.log (modo append-only)
# Para editar: chattr -a /var/log/graffiti_wall.log

Opcional:
# chattr +a /var/log/graffiti_wall.log (modo append-only)
# Para editar: chattr -a /var/log/graffiti_wall.log
```
