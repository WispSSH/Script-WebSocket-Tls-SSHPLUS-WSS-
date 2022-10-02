SCRIPT WebSocket Tls [WSS]

Add licença 

mkdir /opt/sshplus
echo > /opt/sshplus/sshplus

Baixar o WebSocket e Licença =

cd /etc/SSHPlus/ && wget https://github.com/WispSSH/Script-WebSocket-Tls-SSHPLUS-WSS-/raw/main/WebSocket && wget https://github.com/WispSSH/Script-WebSocket-Tls-SSHPLUS-WSS-/raw/main/pub.key && wget https://github.com/WispSSH/Script-WebSocket-Tls-SSHPLUS-WSS-/raw/main/priv.pem && chmod 777 WebSocket && cd $HOME

Modo de Usar:

× Ativar sem o SSL ×

screen -dmS novoWS /etc/SSHPlus/WebSocket -proxy_port 0.0.0.0:80 -msg=SUA_MENSAGEM_AQUI

× Ativar com SSL ×

screen -dmS novoWS /etc/SSHPlus/WebSocket -tls=true -proxy_port 0.0.0.0:80 -msg=SUA_MENSAGEM_AQUI

Caso queria atualizar ou modificar o certificado, basta alterar no Diretório 

nano /etc/SSHPlus/

BY : @kiritosshxd
