# 📦 Planejamento e Relatório das Entregas

<p align="center">
  <img src="/images/logo/hortaShop.png" alt="logo" height="200">
</p>

## Índice
- [Entregas Iniciais (Pré-Sprint)](#entregas-iniciais-pré-sprint)
- [Sprint 1 | 07/04 - 28/04](#sprint-1--0704---2804)
- [Sprint 2 | 28/04 - 12/05](#sprint-2--2804---1205)
- [Sprint 3 | 12/05 - 26/05](#sprint-3--1205---2605)
- [Sprint 4 | 26/05 - 09/06](#sprint-4--2605---0906)

[Voltar ao README](https://github.com/HortaShop-PS)

---

## Entregas Iniciais (Pré-Sprint)

**Objetivo:** Levantamento de requisitos, alinhamento do projeto e definição do produto.

### Atividades e Responsáveis

#### Definição do Problema
- **Desenvolvido por:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)
- **Revisado por:** [@thiagogonzagadev](https://github.com/thiagogonzagadev)

#### Modelo Canvas
- **Desenvolvido por:** [@HeloCris](https://github.com/HeloCris)
- **Revisado por:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)

#### Validação do Problema com Clientes
- **Documento:** [Validação de Mercado e Usabilidade](/validacao_mercado_usabilidade.md)

#### Definição do MVP
- **Desenvolvido por:** [@thiagogonzagadev](https://github.com/thiagogonzagadev)
- **Revisado por:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)

#### Prototipagem no Figma
- **Desenvolvido por:** Toda a equipe
- **Link:** [Protótipo no Figma](https://www.figma.com/proto/qBmHxZgLpY7XdVGG2g0Now/HortaShop-Telas?node-id=160-1559&p=f&t=S7wfnOBBJwhbxv5J-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=160%3A1559)

#### User Stories
- **RF01, RF02, RF03**
  - **Desenvolvido por:** [@thiagogonzagadev](https://github.com/thiagogonzagadev)
  - **Revisado por:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)
- **RF04, RF12, RF13**
  - **Desenvolvido por:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)
  - **Revisado por:** [@uGonzaguinha](https://github.com/uGonzaguinha)
- **RF05, RF06, RF07**
  - **Desenvolvido por:** [@uGonzaguinha](https://github.com/uGonzaguinha)
  - **Revisado por:** [@raphaelsales](https://github.com/raphaelsales)
- **RF08, RF09, RF11**
  - **Desenvolvido por:** [@raphaelsales](https://github.com/raphaelsales)
  - **Revisado por:** [@uGonzaguinha](https://github.com/uGonzaguinha)

**Resumo:** Essa etapa foi fundamental para alinhar a visão do produto, definir suas funcionalidades básicas e preparar a equipe para o início do desenvolvimento.

---

## Sprint 1 | 07/04 - 28/04

**Valor:** Estabelecer a base de acesso dos usuários, com login, cadastro e gerenciamento de perfil, garantindo segurança e personalização desde o início da experiência.

### Funcionalidades e Distribuição

#### 1. Autenticação (Login e Cadastro)
- **Backend:**
  - Endpoint de Login
    - **Responsável:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)
    - **PR:** [Link](https://github.com/HortaShop-PS/BackEnd/pull/4)
  - Endpoint de Cadastro
    - **Responsável:** [@HeloCris](https://github.com/HeloCris)
    - **PR:** [Link](https://github.com/HortaShop-PS/BackEnd/pull/8)

- **Frontend:**
  - Tela de Login
    - **Responsável:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)
    - **Revisado por:** [@thiagogonzagadev](https://github.com/thiagogonzagadev)
    - **PR:** [Link](https://github.com/HortaShop-PS/FrontEnd/pull/9)
  - Tela de Cadastro
    - **Responsável:** [@HeloCris](https://github.com/HeloCris)
    - **Revisado por:** [@uGonzaguinha](https://github.com/uGonzaguinha)
    - **PR:** [Link](https://github.com/HortaShop-PS/FrontEnd/pull/15)

#### 2. Home
- **Backend:**
  - Endpoint para dados da tela inicial
    - **Responsável:** [@raphaelsales](https://github.com/raphaelsales)
    - **PR:** [Link](https://github.com/HortaShop-PS/BackEnd/pull/3)

- **Frontend:**
  - Tela Home
    - **Responsável:** [@raphaelsales](https://github.com/raphaelsales)
    - **Revisado por:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)
    - **PR:** [Link](https://github.com/HortaShop-PS/FrontEnd/pull/8)

#### 3. Perfil
- **Backend:**
  - Buscar Perfil
    - **Responsável:** [@thiagogonzagadev](https://github.com/thiagogonzagadev)
    - **PR:** [Link](https://github.com/HortaShop-PS/BackEnd/pull/1)
  - Editar Perfil
    - **Responsável:** [@uGonzaguinha](https://github.com/uGonzaguinha)
    - **PR:** [Link](https://github.com/HortaShop-PS/BackEnd/pull/9)

- **Frontend:**
  - Tela de Perfil
    - **Responsável:** [@thiagogonzagadev](https://github.com/thiagogonzagadev)
    - **Revisado por:** [@HeloCris](https://github.com/HeloCris)
    - **PR:** [Link](https://github.com/HortaShop-PS/FrontEnd/pull/14)
  - Tela de Editar Perfil
    - **Responsável:** [@uGonzaguinha](https://github.com/uGonzaguinha)
    - **Revisado por:** [@raphaelsales](https://github.com/raphaelsales)
    - **PR:** [Link](https://github.com/HortaShop-PS/FrontEnd/pull/16)

### Participação Cruzada Sprint 1

| Membro               | Frontend              | Backend                    |
|----------------------|------------------------|-----------------------------|
| @andrebarceloschagas | Tela de Login          | Endpoint de Login           |
| @HeloCris            | Tela de Cadastro       | Endpoint de Cadastro        |
| @raphaelsales        | Tela Home              | Endpoint da Home            |
| @thiagogonzagadev    | Tela de Perfil         | Endpoint de Buscar Perfil   |
| @uGonzaguinha        | Tela de Editar Perfil  | Endpoint de Editar Perfil   |

### Resumo das Entregas Sprint 1

- Funcionalidades de Login e Cadastro implementadas (Frontend e Backend)
- Tela Home funcional com dados básicos do backend
- Gerenciamento de Perfil (Visualizar e Editar) implementado (Frontend e Backend)

**Release:** [v0.1.0](https://github.com/HortaShop-PS/FrontEnd/releases/tag/v0.1.0)

---

## Sprint 2 | 28/04 - 12/05

**Valor:** Implementar gestão completa de produtores, catálogo personalizado com sistema de busca integrado e funcionalidades de favoritos.

### Funcionalidades e Distribuição

#### 1. Cadastro de Produtores
- **Backend:**
  - Endpoint de Cadastro de Produtor
    - **Responsável:** [@HeloCris](https://github.com/HeloCris)
    - **Revisado por:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)

- **Frontend:**
  - Tela de Cadastro de Produtor
    - **Responsável:** [@uGonzaguinha](https://github.com/uGonzaguinha)
    - **Revisado por:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)

#### 2. Gestão de Catálogo
- **Backend:**
  - Endpoint de Registro de Produtos
    - **Responsável:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)
    - **Revisado por:** [@thiagogonzagadev](https://github.com/thiagogonzagadev)

- **Frontend:**
  - Tela de Cadastro de Produtos
    - **Responsável:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)
    - **Revisado por:** [@uGonzaguinha](https://github.com/uGonzaguinha)

#### 3. Favoritos
- **Backend:**
  - Endpoint de Favoritos
    - **Responsável:** [@thiagogonzagadev](https://github.com/thiagogonzagadev)
    - **Revisado por:** [@raphaelsales](https://github.com/raphaelsales)

- **Frontend:**
  - Tela de Favoritos
    - **Responsável:** [@thiagogonzagadev](https://github.com/thiagogonzagadev)
    - **Revisado por:** [@raphaelsales](https://github.com/raphaelsales)

#### 4. Detalhes do Produto
- **Backend:**
  - Endpoint de Detalhes do Produto
    - **Responsável:** [@thiagogonzagadev](https://github.com/thiagogonzagadev)
    - **Revisado por:** [@HeloCris](https://github.com/HeloCris)

- **Frontend:**
  - Tela de Detalhes do Produto
    - **Responsável:** [@thiagogonzagadev](https://github.com/thiagogonzagadev)
    - **Revisado por:** [@HeloCris](https://github.com/HeloCris)

#### 5. Busca e Filtros
- **Backend:**
  - Endpoint de Busca Avançada
    - **Responsável:** [@raphaelsales](https://github.com/raphaelsales)
    - **Revisado por:** [@uGonzaguinha](https://github.com/uGonzaguinha)

- **Frontend:**
  - Componente de Busca com Filtros
    - **Responsável:** [@uGonzaguinha](https://github.com/uGonzaguinha)
    - **Revisado por:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)

### Participação Cruzada Sprint 2

| Membro               | Frontend                        | Backend                         |
|----------------------|---------------------------------|----------------------------------|
| @andrebarceloschagas | Registro de Produtos            | Registro de Produtos            |
| @HeloCris            | -                               | Cadastro de Produtor            |
| @raphaelsales        | -                               | Busca Avançada                  |
| @thiagogonzagadev    | Favoritos + Detalhes do Produto | Favoritos + Detalhes do Produto |
| @uGonzaguinha        | Cadastro de Produtor + Busca    | -                               |

### Resumo das Entregas Sprint 2

- Cadastro de Produtores implementado (Backend e Frontend)
- Gestão de Catálogo com funcionalidade de Registro de Produtos (Backend e Frontend)
- Funcionalidade de Favoritos implementada (Backend e Frontend)
- Tela de Detalhes do Produto funcional (Backend e Frontend)
- Sistema de Busca e Filtros implementado (Backend e Frontend)

**Release:** [v0.2.0](https://github.com/HortaShop-PS/BackEnd/releases/tag/v0.2.0)

---

## Sprint 3 | 12/05 - 26/05

**Valor:** Implementar o ciclo completo de pedidos, do carrinho ao pagamento e entrega, integrando clientes, produtores e entregadores em uma experiência fluida. Esta sprint garante o fluxo completo do cliente e produtor, alinhando-se ao MVP, e adiciona funcionalidades de avaliação e cupons para enriquecer a plataforma, além de melhorias na experiência do usuário.

### Funcionalidades e Distribuição

#### 1. Carrinho de Compras
- **Backend:**
  - Endpoint para adicionar/remover itens ao carrinho
  - Endpoint para listar itens do carrinho do usuário
  - Endpoint para limpar carrinho
- **Frontend:**
  - Tela/Componente de Carrinho de Compras (visualização, remoção, alteração de quantidade, limpar carrinho)
- **Responsável:** [@thiagogonzagadev](https://github.com/thiagogonzagadev) (Frontend + Backend)
- **Revisor:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)

#### 2. Integração com Meios de Pagamento (PIX e Cartão)
- **Backend:**
  - Endpoint para processar pagamento via PIX
  - Endpoint para processar pagamento via cartão (mock/simulação)
  - Endpoint para registrar status do pagamento
- **Frontend:**
  - Tela/Componente de Pagamento (seleção do método, exibição de QR Code PIX, formulário de cartão, feedback de sucesso/erro)
- **Responsável:** [@andrebarceloschagas](https://github.com/andrebarceloschagas) (Frontend + Backend)
- **Revisor:** [@HeloCris](https://github.com/HeloCris)

#### 3. Tela de Checkout com Opção de Entrega/Retirada
- **Backend:**
  - Endpoint para iniciar pedido a partir do carrinho
  - Endpoint para calcular valor total (incluindo frete/taxa)
  - Endpoint para selecionar endereço e método de entrega/retirada
- **Frontend:**
  - Tela de Checkout (resumo do pedido, seleção de endereço, escolha de entrega/retirada, confirmação)
  - Feedback Visual do Processo de Compra (indicador de progresso durante o checkout)
- **Responsável:** [@raphaelsales](https://github.com/raphaelsales) (Frontend + Backend)
- **Revisor:** [@uGonzaguinha](https://github.com/uGonzaguinha)

#### 4. Histórico e Detalhes de Pedidos (Cliente e Produtor)
- **Backend:**
  - Endpoint para listar pedidos do cliente
  - Endpoint para listar pedidos do produtor
  - Endpoint para detalhes do pedido
- **Frontend:**
  - Tela de histórico de pedidos do cliente
  - Tela de histórico de pedidos do produtor
  - Tela/modal de detalhes do pedido (produtos, status, valores, etc)
  - Feedback Visual do Processo de Compra (confirmação visual e mensagem de sucesso após finalização da compra)
- **Responsável:** [@uGonzaguinha](https://github.com/uGonzaguinha) (Frontend + Backend)
- **Revisor:** [@raphaelsales](https://github.com/raphaelsales)

#### 5. Gestão Completa de Produtos (Produtor)
- **Backend:**
  - Endpoint para criar, editar, remover e listar produtos do produtor
- **Frontend:**
  - Tela de gerenciamento de produtos (CRUD completo para o produtor)
- **Responsável:** [@HeloCris](https://github.com/HeloCris) (Frontend + Backend)
- **Revisor:** [@thiagogonzagadev](https://github.com/thiagogonzagadev)

#### 6. Avaliação de Produtos (Cliente)
- **Backend:**
  - Endpoint para cliente submeter avaliação (nota + comentário) para um produto de um pedido concluído
  - Endpoint para listar avaliações de um produto
- **Frontend:**
  - Componente/Seção para o cliente avaliar produtos após a compra
  - Exibição das avaliações na tela de "Detalhes do Produto"
- **Responsável:** [@thiagogonzagadev](https://github.com/thiagogonzagadev) (Frontend + Backend)
- **Revisor:** [@andrebarceloschagas](https://github.com/andrebarceloschagas) e [@uGonzaguinha](https://github.com/uGonzaguinha)

#### 7. Sistema de Cupons de Desconto
- **Backend:**
  - Endpoints para CRUD de cupons (código, tipo, valor, validade, etc.)
  - Endpoint para validar e aplicar cupom no carrinho/checkout
- **Frontend:**
  - Campo para inserir código do cupom na tela do Carrinho ou Checkout
  - Exibição do desconto aplicado no resumo do pedido
- **Responsável:** [@andrebarceloschagas](https://github.com/andrebarceloschagas) (Frontend + Backend)
- **Revisor:** [@raphaelsales](https://github.com/raphaelsales)

### Participação Cruzada Sprint 3

| Membro               | Frontend                                                          | Backend                                                           |
|----------------------|-------------------------------------------------------------------|-------------------------------------------------------------------|
| @thiagogonzagadev    | Carrinho de Compras + Avaliação Produtos                          | Carrinho de Compras + Avaliação Produtos                          |
| @andrebarceloschagas | Pagamento + Sistema de Cupons                                     | Pagamento + Sistema de Cupons                                     |
| @HeloCris            | Gestão de Produtos                                                | Gestão de Produtos                                                |
| @raphaelsales        | Checkout                                                          | Checkout                                                          |
| @uGonzaguinha        | Histórico/Detalhes de Pedidos (Cliente/Prod.)                     | Histórico/Detalhes de Pedidos (Cliente/Prod.)                     |

### Resumo das Entregas Sprint 3

- Carrinho de Compras funcional (adicionar, remover, listar, limpar)
- Checkout completo (resumo, endereço, entrega/retirada)
- Pagamento integrado (PIX e cartão, simulação)
- Histórico e detalhes de pedidos (cliente e produtor)
- Gestão completa de produtos para o produtor (CRUD)
- Sistema de avaliação de produtos pelos clientes
- Sistema de cupons de desconto aplicáveis no checkout
- Feedback visual do processo de compra (indicadores de progresso e confirmação)

**Release:** [v0.3.0](https://github.com/HortaShop-PS/BackEnd/releases/tag/v0.3.0)

---

## Sprint 4 | 26/05 - 09/06

**Valor:** Capacitar os entregadores com um aplicativo dedicado para gerenciar suas entregas de forma eficiente, implementar integrações essenciais de pagamento e geolocalização, estabelecer controles de validação para produtores e criar um sistema completo de rastreamento e notificações para uma experiência transparente entre todos os usuários.

### Funcionalidades e Distribuição

#### 1. Integração com API de Pagamentos (PIX e Cartão de Crédito)
- **Backend:**
  - Integração com gateway de pagamento real (ex: Stripe, PagSeguro, Mercado Pago)
  - Endpoint para processar pagamento via PIX com QR Code dinâmico
  - Endpoint para processar pagamento via cartão de crédito com validação
  - Webhook para receber confirmações de pagamento
  - Sistema de logs e auditoria de transações
- **Frontend:**
  - Interface melhorada de pagamento com integração real
  - Exibição de QR Code PIX dinâmico
  - Formulário de cartão com validações em tempo real
  - Feedback visual de status do pagamento (processando, aprovado, rejeitado)
- **Responsável:** [@thiagogonzagadev](https://github.com/thiagogonzagadev) (Frontend + Backend)
- **Revisor:** [@uGonzaguinha](https://github.com/uGonzaguinha)

#### 2. Integração com Google Maps API e Cadastro de Endereços
- **Backend:**
  - Integração com Google Maps API para validação e geocoding de endereços
  - Endpoints CRUD para endereços de consumidores e produtores
  - Validação de CEP e autocompletar endereços
  - Cálculo de distância entre endereços para frete
- **Frontend:**
  - Componente de cadastro de endereço com autocompletar do Google Maps
  - Tela de gerenciamento de endereços para consumidores (múltiplos endereços)
  - Tela de cadastro/edição de endereço para produtores (endereço principal)
  - Seleção de endereço no checkout com visualização no mapa
- **Responsável:** [@raphaelsales](https://github.com/raphaelsales) (Frontend + Backend)
- **Revisor:** [@uGonzaguinha](https://github.com/uGonzaguinha)

#### 3. Validação e Controle de Perfil Completo do Produtor
- **Backend:**
  - Endpoint para verificar completude do perfil do produtor
  - Validação obrigatória de: CNPJ, endereço completo, dados bancários, foto de perfil, descrição da empresa
  - Middleware para bloquear ações do produtor (cadastrar produtos, receber pedidos) se perfil incompleto
- **Frontend:**
  - Dashboard do produtor com indicador de completude do perfil
  - Mensagens de orientação e bloqueio para ações restritas
- **Responsável:** [@HeloCris](https://github.com/HeloCris) (Frontend + Backend)
- **Revisor:** [@andrebarceloschagas](https://github.com/andrebarceloschagas)

#### 4. Sistema de Atualização de Status pelo Produtor
- **Backend:**
  - Endpoints para produtor atualizar status do pedido ("Preparando", "Pronto para Coleta", "Aguardando Entregador")
  - Lógica de transição de estados válidos
  - Notificações automáticas para entregador e cliente
  - Logs de histórico de mudanças de status
- **Frontend:**
  - Interface do produtor para gerenciar pedidos e atualizar status
  - Timeline visual do status do pedido
  - Notificações em tempo real para o produtor sobre novos pedidos
- **Responsável:** [@uGonzaguinha](https://github.com/uGonzaguinha) (Frontend + Backend)
- **Revisor:** [@raphaelsales](https://github.com/raphaelsales)

#### 5. Sistema de Autenticação e Gestão de Pedidos do Entregador
- **Backend:**
  - Endpoint de autenticação específica para entregadores
  - Endpoints para listagem, aceitação e detalhes de pedidos
- **Frontend (App Mobile Entregador):**
  - Telas de login e perfil do entregador
  - Listagem de pedidos disponíveis com filtros por distância
  - Interface para aceitar/recusar pedidos
- **Responsável:** [@andrebarceloschagas](https://github.com/andrebarceloschagas) (Frontend + Backend)
- **Revisor:** [@HeloCris](https://github.com/HeloCris)

#### 6. Sistema de Entregas e Rotas do Entregador
- **Backend:**
  - Sistema de atualização de status de entrega pelo entregador
  - Cálculo de rotas e distâncias para entregas
- **Frontend (App Mobile Entregador):**
  - Atualização de status com integração ao Google Maps
  - Histórico de entregas e ganhos
- **Responsável:** [@raphaelsales](https://github.com/raphaelsales) (Frontend + Backend)
- **Revisor:** [@HeloCris](https://github.com/HeloCris)

#### 7. Sistema de Notificações Push Completo
- **Backend:**
  - Integração com Firebase Cloud Messaging (FCM)
  - Endpoints para gerenciar tokens de dispositivos
  - Sistema de templates de notificações personalizadas
  - Notificações automáticas para:
    - Consumidor: confirmação de pedido, atualizações de status, pedido entregue
    - Produtor: novo pedido, pedido coletado
    - Entregador: novos pedidos disponíveis, pedidos atribuídos
- **Frontend (App Entregador e HortaShop):**
  - Configuração de permissões de notificação
  - Exibição de notificações in-app
  - Centro de notificações com histórico
  - Configurações de preferências de notificação
- **Responsável:** [@thiagogonzagadev](https://github.com/thiagogonzagadev) (Frontend + Backend)
- **Revisor:** [@uGonzaguinha](https://github.com/uGonzaguinha)

#### 8. Rastreamento em Tempo Real e Transparência
- **Backend:**
  - Websockets para atualizações em tempo real
  - API para rastreamento completo do pedido
  - Integração com geolocalização do entregador (opcional/MVP futuro)
- **Frontend:**
  - Página de rastreamento em tempo real para consumidores
  - Dashboard do produtor com status de todos os pedidos
  - Notificações visuais de mudança de status
  - Estimativa de tempo de entrega baseada na localização
- **Responsável:** [@uGonzaguinha](https://github.com/uGonzaguinha) (Frontend + Backend)
- **Revisor:** [@thiagogonzagadev](https://github.com/thiagogonzagadev)

### Participação Cruzada Sprint 4

| Membro               | Frontend                                                                                          | Backend                                                                                               |
|----------------------|---------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| @andrebarceloschagas | App Entregador (Auth/Pedidos)                                                                     | App Entregador (Auth/Pedidos)                                                                         |
| @raphaelsales        | Google Maps + Cadastro Endereços + App Entregador (Entregas/Rotas)                              | Google Maps API + Endereços + App Entregador (Entregas/Rotas)                                        |
| @HeloCris            | Validação Perfil Produtor + Wizard Completude                                                    | Controle Perfil Produtor + Middleware Validação                                                      |
| @thiagogonzagadev    | Integração de Pagamentos + Notificações Push (Plataforma Web + App)                             | API de Pagamentos Real + Sistema de Notificações FCM                                                 |
| @uGonzaguinha        | Status Produtor + Dashboard Pedidos + Rastreamento Tempo Real                                    | Status pelo Produtor + Rastreamento APIs + WebSockets                                                |

### Resumo das Entregas Sprint 4

- **Pagamentos:** Integração real com gateway de pagamentos para PIX e cartão de crédito
- **Geolocalização:** Google Maps API integrada para cadastro e validação de endereços
- **Controle de Qualidade:** Sistema de validação obrigatória do perfil completo do produtor
- **Gestão de Pedidos:** Produtores podem atualizar status dos pedidos em tempo real
- **App Entregador:** Aplicativo mobile completo para gestão de entregas
- **Notificações:** Sistema push completo para todos os usuários com atualizações de status
- **Rastreamento:** Monitoramento em tempo real do status dos pedidos para transparência total
- **Experiência:** Interface aprimorada com feedback visual e atualizações em tempo real

**Release:** [v1.0.0](https://github.com/HortaShop-PS/BackEnd/releases/tag/v1.0.0) - *Release de