
# Configurando placa de rede no Windows 3.11
Inserir o disquete **win311-pcnet-network.img** no drive A e dar duplo clique no ícone 'Windows Setup'.

![](imagens/win311-network-adapter-01.png)

Selecionar o menu Options > Change Network Settings...

![](imagens/win311-network-adapter-02.png)

Clicar no botão 'Networks...'

![](imagens/win311-network-adapter-03.png)

Selecionar a opção 'Install Microsoft Windows Network'

![](imagens/win311-network-adapter-04.png)

Clicar no botão 'Ok'

![](imagens/win311-network-adapter-05.png)

Clicar no botão 'Drivers'

![](imagens/win311-network-adapter-06.png)

Clicar no botão 'Add Adapter...'

![](imagens/win311-network-adapter-07.png)

Manter o item 'Unlisted or Updated Network Adapter' selecionado e clicar no botão 'Ok'

![](imagens/win311-network-adapter-08.png)

Clicar no botão 'Browse...'

![](imagens/win311-network-adapter-09.png)


Selecionar o drive A e o diretório 'wfw311' e clicar no botão 'Ok'

![](imagens/win311-network-adapter-10.png)
![](imagens/win311-network-adapter-11.png)
![](imagens/win311-network-adapter-12.png)


Clicar no botão OK

![](imagens/win311-network-adapter-13.png)

Clicar no botão 'Close'

![](imagens/win311-network-adapter-14.png)

Clicar no botão 'OK'

![](imagens/win311-network-adapter-15.png)

Se necessário, alterar o nome do usuário e o nome do grupo de trabalho e clicar no botão 'Ok'

![](imagens/win311-network-adapter-16.png)

Aguardar o término da configuração do adaptador de rede.

![](imagens/win311-network-adapter-17.png)

Clicar no botão 'OK'

![](imagens/win311-network-adapter-18.png)

Clicar no botão 'OK'

![](imagens/win311-network-adapter-19.png)

Clicar no botão 'Restart Computer'

![](imagens/win311-network-adapter-20.png)

Quando o Windows reiniciar, provavelmente será exibida a mensagem abaixo.

![](imagens/win311-network-adapter-21.png)

Para corrigir o problema acima, será necessário incluir a linha abaixo no arquivo CONFIG.SYS que esta na raíz do sistema operacional MS-DOS.

```
DEVICE=<path-windows>\IFSHLP.SYS
```

Salvar o arquivo CONFIG.SYS, reiniciar a máquina virtual, carregar o Windows 3.11, será exibida a tela abaixo. Informar uma senha e clicar no botão 'OK'.

![](imagens/win311-network-adapter-22.png)

Clicar no botão 'Yes' para con rmar que o arquivo de senhas deve ser criado.

![](imagens/win311-network-adapter-23.png)

Repetir a senha e clicar no botão 'OK'

![](imagens/win311-network-adapter-24.png)

**Pronto!!!** O adaptador de rede está configurado no Windows 3.11 for Workgroups.

![](imagens/win311-network-adapter-25.png)

