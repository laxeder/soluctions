# DNS
Algumas operadoras usam DNS que bloqueiam determinados sites. Para desbloquear, é necessário alterar o DNS da rede para um servidor público, como o do Google (`8.8.8.8`) ou Cloudflare (`1.1.1.1`).

## Windows 10
1. Abra o **Painel de Controle** → _Rede e Internet_ → _Central de Rede e Compartilhamento_
2. Clique em **Alterar as configurações do adaptador** (menu lateral esquerdo)
3. Clique com o botão direito na sua conexão (Wi-Fi ou Ethernet) → **Propriedades**
4. Selecione **Protocolo IP Versão 4 (TCP/IPv4)** e clique em **Propriedades**
5. Marque **Usar os seguintes endereços de servidor DNS** e preencha:
    - Servidor DNS preferencial: `8.8.8.8`
    - Servidor DNS alternativo: `8.8.4.4`
6. Clique em **OK** e reconecte à rede

## Windows 11:
1. Abra `Configurações`
2. Vá em `Rede e Internet`
3. Clique em `Wi-Fi`
4. Clique na rede conectada
5. Em `Atribuição de servidor DNS`, clique em `Editar`
6. Troque de `Automático (DHCP)` para `Manual`
7. Ative `IPv4`
8. Preencha:
* DNS preferencial: `8.8.8.8`
* DNS alternativo: `8.8.4.4`
9. Clique em `Salvar`
