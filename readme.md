🚀 Instalação Automatizada do Ubuntu para Desenvolvimento com Conda, Mamba e Mais! 🚀
Este projeto oferece um script de instalação automatizada do Ubuntu (versão mais recente) com foco em desenvolvimento, incluindo:

🐍 Conda e Mamba: Gerenciadores de pacotes e ambientes Python para ciência de dados, aprendizado de máquina e muito mais.
💻 Ferramentas Essenciais: Git, Vim, Emacs, Visual Studio Code e outras ferramentas importantes para desenvolvedores.
🐳 Docker e Docker Compose: Para criar e gerenciar contêineres de forma eficiente.
⚙️ Node.js e npm: Para desenvolvimento web e JavaScript.
✨ Personalização: Interface do GNOME ajustada com Gnome Tweaks.
⚠️ Atenção: Este script habilita o usuário root com uma senha padrão (vazia) para facilitar o acesso inicial. É CRUCIAL alterar a senha do root imediatamente após a instalação para garantir a segurança do sistema!

📖 Conteúdo
autoinstall.yaml: O script de instalação principal, que define as configurações e pacotes a serem instalados.
README.md: Este arquivo, com instruções e detalhes sobre o projeto.
🛠️ Como Usar
Crie um pendrive bootável do Ubuntu:
Baixe a imagem ISO mais recente do Ubuntu em https://ubuntu.com/download.
Use uma ferramenta como o Rufus ou Etcher para criar um pendrive bootável com a imagem ISO.
Copie o arquivo autoinstall.yaml para o pendrive:
Coloque o arquivo autoinstall.yaml na raiz do pendrive.
Inicie o computador a partir do pendrive:
Configure o BIOS/UEFI para iniciar a partir do pendrive.
A instalação será automática:
O script autoinstall.yaml configurará e instalará o Ubuntu com todas as ferramentas e pacotes especificados.
Altere a senha do root após a instalação:
Execute o comando sudo passwd root e siga as instruções para definir uma senha forte.
💻 Especificações Detalhadas
⚙️ Sistema Operacional
Ubuntu: Versão mais recente (verifique o site oficial para a versão mais atual).
Idioma: Português do Brasil (pt_BR).
Fuso Horário: Configurado de acordo com sua localização (por exemplo, America/Sao_Paulo).
🐍 Python e Conda
Miniconda: Instalação do Miniconda, uma distribuição mínima do Conda.
Mamba: Gerenciador de pacotes alternativo ao Conda, mais rápido e eficiente.
Ambiente Conda "dev": Cria um ambiente Conda chamado "dev" com os seguintes pacotes Python:
Python 3.10
NumPy
SciPy
Matplotlib
Pandas
JupyterLab
🛠️ Ferramentas de Desenvolvimento
Git: Sistema de controle de versão distribuído.
Vim e Emacs: Editores de texto poderosos e personalizáveis.
Visual Studio Code: Editor de código moderno e popular (instalado via snap).
Docker e Docker Compose: Ferramentas para criar e gerenciar contêineres.
Node.js e npm: Ambiente de execução JavaScript e gerenciador de pacotes.
Gnome Tweaks: Ferramenta para personalizar a interface do GNOME.
🔐 Segurança
Usuário Root Habilitado: O usuário root é habilitado por padrão para facilitar o acesso inicial.
Senha Padrão Vazia: A senha do root é inicialmente vazia. ALTERE-A IMEDIATAMENTE após a instalação!
🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

📄 Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
