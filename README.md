# 🚀 Instalação Automatizada do Ubuntu para Desenvolvimento com Conda, Mamba e Mais! 🚀
Este projeto oferece um script de instalação automatizada do Ubuntu (versão mais recente) com foco em desenvolvimento, incluindo:

1. 🐍 Conda e Mamba: Gerenciadores de pacotes e ambientes Python para ciência de dados, aprendizado de máquina e muito mais.
2. 💻 Ferramentas Essenciais: Git, Vim, Emacs, Visual Studio Code e outras ferramentas importantes para desenvolvedores.
3. 🐳 Docker e Docker Compose: Para criar e gerenciar contêineres de forma eficiente.
4. ⚙️ Node.js e npm: Para desenvolvimento web e JavaScript.
5. ✨ Personalização: Interface do GNOME ajustada com Gnome Tweaks.
6. ⚠️ Atenção: Este script habilita o usuário root com uma senha padrão (vazia) para facilitar o acesso inicial. É CRUCIAL alterar a senha do root imediatamente após a instalação para garantir a segurança do sistema!

# 📖 Conteúdo
autoinstall.yaml: O script de instalação principal, que define as configurações e pacotes a serem instalados.
README.md: Este arquivo, com instruções e detalhes sobre o projeto.

# 🛠️ Como Usar
1. Crie um pendrive bootável do Ubuntu:
    1. Baixe a imagem ISO mais recente do Ubuntu em https://ubuntu.com/download.
    2. Use uma ferramenta como o Rufus ou Etcher para criar um pendrive bootável com a imagem ISO.
2. Copie o arquivo autoinstall.yaml para o pendrive:
    1. Coloque o arquivo autoinstall.yaml na raiz do pendrive.
3. Inicie o computador a partir do pendrive:
    1. Configure o BIOS/UEFI para iniciar a partir do pendrive.
4. A instalação será automática:
    1. O script autoinstall.yaml configurará e instalará o Ubuntu com todas as ferramentas e pacotes especificados.
5. Altere a senha do root após a instalação:
Execute o comando sudo passwd root e siga as instruções para definir uma senha forte.

# 💻 Especificações Detalhadas
    ## ⚙️ Sistema Operacional
    1. Ubuntu: Versão mais recente (verifique o site oficial para a versão mais atual).
    2. Idioma: Português do Brasil (pt_BR).
    3. Fuso Horário: Configurado de acordo com sua localização (por exemplo, America/Sao_Paulo).

# 🐍 Python e Conda
    1. Miniconda: Instalação do Miniconda, uma distribuição mínima do Conda.
    2. Mamba: Gerenciador de pacotes alternativo ao Conda, mais rápido e eficiente.
    3. Ambiente Conda "dev": Cria um ambiente Conda chamado "dev" com os seguintes pacotes Python:
    4. Python 3.10
    5. NumPy
    6. SciPy
    7. Matplotlib
    8. Pandas
    9. JupyterLab

# 🛠️ Ferramentas de Desenvolvimento
    1. Git: Sistema de controle de versão distribuído.
    2. Vim e Emacs: Editores de texto poderosos e personalizáveis.
    3. Visual Studio Code: Editor de código moderno e popular (instalado via snap).
    4. Docker e Docker Compose: Ferramentas para criar e gerenciar contêineres.
    5. Node.js e npm: Ambiente de execução JavaScript e gerenciador de pacotes.
    6. Gnome Tweaks: Ferramenta para personalizar a interface do GNOME.

# 🔐 Segurança
Usuário Root Habilitado: O usuário root é habilitado por padrão para facilitar o acesso inicial.
Senha Padrão Vazia: A senha do root é inicialmente vazia. ALTERE-A IMEDIATAMENTE após a instalação!

# 🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

---

#📄 Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.