
# Configurando Protocolo TCP/IP no Windows 3.11
Inserir o CD **win311-tcp.iso** no drive de CD-ROM e dar duplo clique no ícone 'Windows Setup'.

![](imagens/windows311-network-tcp-01.png)

Selecionar o menu Options > Change Network Settings...

![](imagens/windows311-network-tcp-02.png)

Clicar no botão 'Drivers...'

![](imagens/windows311-network-tcp-03.png)

Clicar no botão 'Add Protocol...'

![](imagens/windows311-network-tcp-04.png)

Manter o item 'Unlisted or Updated Protocol' selecionado e clicar no botão 'OK'

![](imagens/windows311-network-tcp-05.png)

Selecionar o drive D e clicar no botão 'Ok'

![](imagens/windows311-network-tcp-07.png)

Clicar no botão 'OK'

![](imagens/windows311-network-tcp-08.png)

Selecionar o item 'Microsoft TCP/IP-32 3.11b'

![](imagens/windows311-network-tcp-09.png)

Clicar no botão 'Set As Default Protocol'

![](imagens/windows311-network-tcp-10.png)

Selecionar o item 'Microsoft TCP/IP-32 3.11b' e clicar no botão 'Setup...'

![](imagens/windows311-network-tcp-11.png)

Marcar a opção 'Enable Automatic DHCP Configuration'

![](imagens/windows311-network-tcp-12.png)

Clicar no botão 'Yes' para habilitar o DHCP.

![](imagens/windows311-network-tcp-13.png)

Preencher o campo 'Default Gateway' com o gateway padrão da sua rede.

**Obs:** O modo de rede padrão utilizado pelo VirtualBox é o modo bridge. Portanto, a máquina virtual que você esta criando, terá um IP fornecido pelo roteador da sua rede.

![](imagens/windows311-network-tcp-14.png)

Clicar no botão 'Close'

![](imagens/windows311-network-tcp-15.png)

Clicar no botão 'OK'

![](imagens/windows311-network-tcp-16.png)

Clicar no botão 'OK'

![](imagens/windows311-network-tcp-17.png)

Clicar no botão 'OK'

![](imagens/windows311-network-tcp-18.png)

Clicar no botão 'Restart Computer'

![](imagens/windows311-network-tcp-19.png)

Ao reinciar o computador e carregar o Windows 3.11 novamente será exibido um novo grupo de aplicativos.

![](imagens/windows311-network-tcp-20.png)

Para verificar se a configuração do protocolo TCP deu certo e ver qual endereço IP a máquina virtual recebeu, clicar no icone 'Ms-DOS Prompt'

![](imagens/windows311-network-tcp-20.png)

Digitar o comando 'ipconfig' na linha de comando do Ms-DOS.

![](imagens/windows311-network-tcp-21.png)

O resultado do comando 'ipconfig' será o IP atribuído a sua máquina virtual pelo servidor DHCP que está no seu roteador.

![](imagens/windows311-network-tcp-22.png)

**Pronto!!!** O protocolo TCP esta con gurado no Windows 3.11 for Workgroups.

