# Configurar o Git



## Usar o Git

Para usar o Git na linha de comando, você precisará fazer download, instalar e configurar o Git no computador. Você também pode instalar GitHub CLI para usar GitHub a partir da linha de comando. Para obter mais informações, consulte "[Sobre GitHub CLI](https://docs.github.com/pt/github-cli/github-cli/about-github-cli)".

Se quiser trabalhar com o Git, mas não quiser usar a linha de comando, você poderá fazer o download e instalar o cliente do [GitHub Desktop](https://desktop.github.com/). Para obter mais informações, consulte "[Instalar e configurar o GitHub Desktop](https://docs.github.com/pt/desktop/installing-and-configuring-github-desktop)".

Se não precisar trabalhar nos arquivos localmente, o GitHub permite a execução de diversas ações relacionadas ao Git diretamente no navegador, incluindo:

- [Criar um repositório](https://docs.github.com/pt/articles/create-a-repo)
- [Bifurcar um repositório](https://docs.github.com/pt/articles/fork-a-repo)
- [Gerenciar arquivos](https://docs.github.com/pt/repositories/working-with-files/managing-files)
- [Interagir socialmente](https://docs.github.com/pt/articles/be-social)

## Configurar o Git

1. [Faça download e instale a versão mais recente do Git](https://git-scm.com/downloads).

**Observação**: Se você estiver usando um dispositivo do Chrome OS, será necessário configurar adicionalmente:

1. Instale um emulador de terminais como, por exemplo, o Termux da Google Play Store no seu dispositivo Chrome OS.
2. A partir do emulador de terminal que você instalou, instale o Git. Por exemplo, no Termux, insira `apt install git` e, em seguida, digite `y` quando solicitado.

1. [Configure seu nome de usuário no Git](https://docs.github.com/pt/github/getting-started-with-github/setting-your-username-in-git).
2. [Configure seu endereço de e-mail de commit no Git](https://docs.github.com/pt/articles/setting-your-commit-email-address).

## Efetuando a autenticação com GitHub a partir do Git

Quando você se conecta a um repositório do GitHub a partir do Git, precisa fazer a autenticação no GitHub usando HTTPS ou SSH.

**Observação:** Você pode efetuar a autenticação em GitHub usando GitHub CLI, para HTTP ou SSH. Para obter mais informações, consulte [`login gh auth`](https://cli.github.com/manual/gh_auth_login).

### Conexão por HTTPS (recomendada)

Se você fizer a clonagem com HTTPS, você pode armazenar suas credenciais de GitHub no Git usando um auxiliar de credenciais. Para obter mais informações, consulte "[Clonando com URLs de HTTPS](https://docs.github.com/pt/github/getting-started-with-github/about-remote-repositories/#cloning-with-https-urls)" e "[Armazenando as suas credenciais de GitHub no cache do Git](https://docs.github.com/pt/github/getting-started-with-github/caching-your-github-credentials-in-git)".

### Conexão por SSH

Se você fizer a clonagem com SSH, você deverá gerar chaves SSH em cada computador que usar para fazer push ou pull a partir de GitHub. Para obter mais informações, consulte "[Clonando com URLs de SSH](https://docs.github.com/pt/github/getting-started-with-github/about-remote-repositories/#cloning-with-ssh-urls)" e "[Gerando uma nova chave SSH](https://docs.github.com/pt/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)".

## Próximas etapas

Agora você o Git e GitHub estão configurados. Agora você pode optar por criar um repositório onde possa colocar seus projetos. Salvar seu código em um repositório permite que você faça backup do seu código e o compartilhe no mundo todo.

- Creating a repository for your project allows you to store code in GitHub. This provides a backup of your work that you can choose to share with other developers. For more information, see “[Create a repository](https://docs.github.com/pt/get-started/quickstart/create-a-repo).".
- Forking a repository will allow you to make changes to another repository without affecting the original. Para obter mais informações, consulte "[Bifurcar um repositório](https://docs.github.com/pt/get-started/quickstart/fork-a-repo). "
- Cada repositório em GitHub pertence a uma pessoa ou organização. Você pode interagir com as pessoas, repositórios e organizações, conectando-se e seguindo-as em GitHub. For more information, see "[Be social](https://docs.github.com/pt/articles/be-social)."
- GitHub tem uma ótima comunidade de suporte onde você pode pedir ajuda e conversar com pessoas de todo o mundo. Join the conversation on [GitHub Support Community](https://github.community/).