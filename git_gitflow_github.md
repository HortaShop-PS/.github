# Guia de Uso: Git, GitFlow e GitHub

![logo](/logo/hortaShop.png)

- Índice
  - [Git](#git)
    - [Configuração Inicial](#configuração-inicial)
    - [Clonar repositorios da HortaShop](#clonar-os-repositórios-da-hortashop)
    - [Atualizar o Repositório Local](#atualizar-o-repositório-local)
  - [GitFlow](#gitflow)
    - [Inicializar o GitFlow](#inicializar-o-gitflow)
    - [Criar uma Nova Feature](#criar-uma-nova-feature)
    - [Criar um Hotfix](#criar-um-hotfix)
  - [GitHub](#github)
    - [Criar um Pull Request](#criar-um-pull-request)

[Voltar ao README](https://github.com/HortaShop-PS)

Este documento fornece instruções básicas para o uso do Git, GitFlow e GitHub, visando auxiliar no gerenciamento eficiente do projeto.

## Git

O Git é um sistema de controle de versão distribuído que permite o rastreamento de alterações em arquivos e coordenação do trabalho entre desenvolvedores.

### Configuração Inicial

Antes de começar a usar o Git, configure seu nome de usuário e e-mail:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```

### Clonar os repositórios da HortaShop

Para clonar um repositório remoto:

```bash
git clone <URL-do-repositório>
```

### Atualizar o Repositório Local

Para atualizar seu repositório local com as alterações do remoto:

```bash
git pull origin <nome-da-branch>
```

## GitFlow

O GitFlow é um modelo de branching para o Git que define um fluxo de trabalho específico para o gerenciamento de branches em projetos.

### Inicializar o GitFlow

Dentro do seu repositório Git, inicialize o GitFlow (depois que clonar o repositório):

```bash
git flow init
```

Siga as instruções interativas para configurar as branches principais e de suporte.

### Criar uma Nova Feature

Para iniciar o desenvolvimento de uma nova funcionalidade:

```bash
git flow feature start <nome-da-feature>
```

Após concluir o desenvolvimento:

```bash
git flow feature finish <nome-da-feature>
```

### Criar um Hotfix

Para corrigir um problema crítico em produção:

```bash
git flow hotfix start <nome-do-hotfix>
```

Após implementar a correção:

```bash
git flow hotfix finish <nome-do-hotfix>
```

## GitHub

O GitHub é uma plataforma de hospedagem de código-fonte que utiliza o Git para controle de versão.

### Criar um Pull Request

1. Faça push das suas alterações para uma branch no GitHub.
2. No GitHub, vá até a página do repositório e clique em "New pull request".
3. Selecione as branches apropriadas e crie o pull request.

[Subir](#guia-de-uso-git-gitflow-e-github)
