# Hospedagem

## Acessando o Web Server

Cada aluno possui direito a 512 MB de hospedagem web gratuita nos servidores do CIn, e fica disponível em https://cin.ufpe.br/~LOGIN. O servidor possui suporte a PHP 5, que já vem habilitado por padrão, necessitando apenas o upload dos arquivos PHP. Para fazer o upload dos arquivos para o servidor, você deve estar em algum dos computadores dos laboratórios de graduação ou estar conectado à VPN do CIn.

#### macOS
1. Com o _Finder_ aberto, pressione `⌘ K`
2. Em Server Address digite: `smb://webserver.cin.ufpe.br/LOGIN`
3. Entre com suas credenciais do CIn (lembrando que o usuário é `cin\seulogin`), e o drive será montado

#### Ubuntu
1. Com o _Nautilus_ aberto, no menu _File_, selecione _Connect to Server…_
2. Em _Server Address_ digite: `smb://webserver.cin.ufpe.br/LOGIN`
3. Entre com suas credenciais do CIn (lembrando que o domínio é `CIN`), e o drive será montado

#### Windows
1. Com o _File Explorer_ (_Explorador de Arquivos_) aberto, em _This PC_ (_Este Computador_), no menu _Computer_ (_Computador_), selecione _Map network drive_ (_Mapear unidade de rede)_
2. Em Folder (_Pasta_) digite: `\\webserver.cin.ufpe.br\LOGIN`
3. Entre com suas credenciais do CIn (lembrando que o usuário é `cin\seulogin`), e o drive será montado

!> Caso não consiga, acesse a página de [Áreas Privadas da Infraestrutura](https://sites.google.com/cin.ufpe.br/coordenacao-de-infraestrutura/servicos/areas-privadas). Talvez existam informações mais atualizadas por lá.

Todos os arquivos dentro da pasta `public_html` serão públicos através da sua URL. Por padrão o servidor irá listar todos os arquivos presentes no diretório, a menos que haja lá algum arquivo `index.html` ou `index.php`. Neste caso, ele será provido no lugar da listagem de diretório.

## Acessando o Virtual Disk

Cada aluno possui direito a 256 MB de hospedagem de arquivos gratuita nos servidores do CIn. Para fazer o upload dos arquivos para o servidor, você deve estar em algum dos computadores dos laboratórios de graduação ou estar conectado à VPN do CIn.

#### macOS
1. Com o _Finder_ aberto, pressione `⌘ K`
2. Em Server Address digite: `smb://virtualdisk.cin.ufpe.br/LOGIN`
3. Entre com suas credenciais do CIn (lembrando que o usuário é `cin\seulogin`), e o drive será montado

#### Ubuntu
1. Com o _Nautilus_ aberto, no menu _File_, selecione _Connect to Server…_
2. Em _Server Address_ digite: `smb://virtualdisk.cin.ufpe.br/LOGIN`
3. Entre com suas credenciais do CIn (lembrando que o domínio é `CIN`), e o drive será montado

#### Windows
1. Com o _File Explorer_ (_Explorador de Arquivos_) aberto, em _This PC_ (_Este Computador_), no menu _Computer_ (_Computador_), selecione _Map network drive_ (_Mapear unidade de rede)_
2. Em Folder (_Pasta_) digite: `\\virtualdisk.cin.ufpe.br\LOGIN`
3. Entre com suas credenciais do CIn (lembrando que o usuário é `cin\seulogin`), e o drive será montado

## Acessando o Servidor Git

O CIn oferece gratuitamente aos alunos o acesso a um servidor Git, com criação de repositórios privados. O GitLab é utilizado como gerenciador de repositórios no servidor. O servidor está disponível em [gitlab.cin.ufpe.br](https://gitlab.cin.ufpe.br), e o acesso é feito por meio das suas credenciais do CIn (utilize a opção _LDAP_ para fazer login).
