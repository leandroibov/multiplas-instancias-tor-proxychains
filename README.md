

#################################################################################################


O que faz cada script!

proxychains-comandos #Mostra comandos de exemplo com proxychains e tor daemons em diferentes instâncias

checkbridges #checa se a bridge está conectada

proxychains_3tors #Cria arquivos de configuração proxychains4.conf relacionado a um circuito distinto criado no tor service

tor-daemon2 #Cria uma instância de tor service com uma SocksPort 9060 e sem bridge

tor-daemon2.2-bridger #Cria uma instância de tor service com uma SocksPort 9060 e com 2 bridges

tor-daemon2-bridger #Cria uma instância de tor service com uma SocksPort 9060 e 1 bridge

tor-daemon3 #Cria uma instância de tor service com uma SocksPort 9062 e sem bridge

tor-daemon3.2-bridger #Cria uma instância de tor service com uma SocksPort 9062 e 2 bridges

tor-daemon3-bridger #Cria uma instância de tor service com uma SocksPort 9062 e 1 bridge

tor-daemon4 #Cria uma instância de tor service com uma SocksPort 9064 e sem bridge

tor-daemon4.2-bridger #Cria uma instância de tor service com uma SocksPort 9064 e 2 bridges

tor-daemon4-bridger #Cria uma instância de tor service com uma SocksPort 9064 e 1 bridge

#################################################################################################

***Executar e Liberar execução

chmod +x  proxychains-comandos

chmod +x  proxychains_3tors

chmod +x  tor-daemon2

chmod +x  tor-daemon2.2-bridger

chmod +x  tor-daemon2-bridger

chmod +x  tor-daemon3

chmod +x  tor-daemon3.2-bridger

chmod +x  tor-daemon3-bridger

chmod +x  tor-daemon4

chmod +x  tor-daemon4.2-bridger

chmod +x  tor-daemon4-bridger

chmod +x checkbridges


***Executando

./proxychains-comandos

./proxychains_3tors

./tor-daemon2

./tor-daemon2.2-bridger

./tor-daemon2-bridger

./tor-daemon3

./tor-daemon3.2-bridger

./tor-daemon3-bridger

./tor-daemon4

./tor-daemon4.2-bridger

./tor-daemon4-bridger

./checkbridges


***Executando, opção 2

#Depois de copiar para /bin, basta digitar o nome de qualquer lugar do terminal linux.

cp -r proxychains-comandos /bin 

cp -r proxychains_3tors /bin 

cp -r tor-daemon2 /bin 

cp -r tor-daemon2.2-bridger /bin 

cp -r tor-daemon2-bridger /bin 

cp -r tor-daemon3 /bin 

cp -r tor-daemon3.2-bridger /bin 

cp -r tor-daemon3-bridger /bin 

cp -r tor-daemon4 /bin 

cp -r tor-daemon4.2-bridger /bin 

cp -r tor-daemon4-bridger /bin 

cp -r checkbridges /bin

##############################################################################################

Como Funciona e Exemplos de Aplicações

Os arquivos gravados em ~/Downloads do seu usuário contêm as configurações de IP e porta a serem utilizadas para a instância desejada do Tor daemon:

proxychains4.2.conf # 127.0.0.1:9060

proxychains4.3.conf # 127.0.0.1:9062

proxychains4.4.conf # 127.0.0.1:9064

***Ao utilizar o proxychains4 -f com os arquivos de configuração correspondentes, podemos rotear o tráfego da instância do Tor para aplicações específicas, isolando esse circuito dos outros circuitos de diferentes instâncias. Veja alguns exemplos:

proxychains4 firefox

proxychains4 -f ~/Downloads/proxychains4.2.conf ~/Downloads/Cake_nano_wallet/cake_wallet/cake_wallet

proxychains4 -f ~/Downloads/proxychains4.3.conf ~/Telegram/Telegram

proxychains4 -f ~/Downloads/proxychains4.4.conf ~/Downloads/Electrum/electrum-4.5.5-x86_64.AppImage





##############################################################################################

Doe monero para nos ajudar:

87JGuuwXzoMGwQAcSD7cvS7D7iacPpN2f5bVqETbUvCgdEmrPZa12gh5DSiKKRgdU7c5n5x1UvZLj8PQ7AAJSso5CQxgjak

Página oficial de segurança digital:

https://traderprofissional.com.br/seguranca-digital.aspx

Vídeo tutorial youtube: 

https://www.youtube.com/watch?v=SxXoQgYH7J4&t=19s





