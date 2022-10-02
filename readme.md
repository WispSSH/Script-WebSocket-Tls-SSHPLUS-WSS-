SCRIPT WebSocket Tls [WSS]

Add licença 

mkdir /opt/sshplus
echo > /opt/sshplus/sshplus

Baixar o WebSocket e Licença =

cd /etc/SSHPlus/ && wget https://www.dropbox.com/s/muh8otpcjb9qa6d/WebSocket && wget https://www.dropbox.com/s/zv01bftfjj58wt8/pub.key && wget https://www.dropbox.com/s/pj5s9x23boj840q/priv.pem && chmod 777 WebSocket && cd $HOME

Modo de Usar:

× Ativar sem o SSL ×

screen -dmS novoWS /etc/SSHPlus/WebSocket -proxy_port 0.0.0.0:80 -msg=SUA_MENSAGEM_AQUI

× Ativar com SSL ×

screen -dmS novoWS /etc/SSHPlus/WebSocket -tls=true -proxy_port 0.0.0.0:80 -msg=SUA_MENSAGEM_AQUI

Caso queria atualizar ou modificar o certificado, basta alterar no Diretório 

nano /etc/SSHPlus/

BY : @kiritosshxd
