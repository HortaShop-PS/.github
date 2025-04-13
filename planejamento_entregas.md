# 📦 Planejamento e Relatório das Entregas

<p align="center">
  <img src="/images/logo/hortaShop.png" alt="logo" height="200">
</p>

- Índice
  - [Entregas Iniciais (Pré-Sprint)](#entregas-iniciais-pré-sprint)
  - [Sprint 1 | 07/04 - 05/05](#sprint-1--0704---0505)
  - [Sprint 2 | 06/05 - 19/05](#sprint-2--0605---1905)
  - [Sprint 3 | 20/05 - 02/06](#sprint-3--2005---0206)
  - [Sprint 4 | 03/06 - 16/06](#sprint-4--0306---1606)

[Voltar ao README](https://github.com/HortaShop-PS)

---

## 📌 Entregas Iniciais (Pré-Sprint)

**Objetivo:** Levantamento de requisitos, alinhamento do projeto e definição do produto.

### Atividades e Responsáveis

- **Definição do Problema:**  
  👨‍💻 [@andrebarceloschagas](https://github.com/andrebarceloschagas)  
  🧪 Review: [@thiagogonzagadev](https://github.com/thiagogonzagadev)

- **Modelo Canvas:**  
  👩‍💻 [@HeloCris](https://github.com/HeloCris)  
  🧪 Review: [@andrebarceloschagas](https://github.com/andrebarceloschagas)

- **Validação do Problema com Clientes:**  
  [Validação de Mercado e Usabilidade](/validacao_mercado_usabilidade.md)

- **Definição do MVP:**  
  👨‍💻 [@thiagogonzagadev](https://github.com/thiagogonzagadev)  
  🧪 Review: [@andrebarceloschagas](https://github.com/andrebarceloschagas)

- **Prototipagem no Figma:**  
  👥 Todos  
  [Prototípo no Figma](https://www.figma.com/proto/qBmHxZgLpY7XdVGG2g0Now/HortaShop-Telas?node-id=160-1559&p=f&t=S7wfnOBBJwhbxv5J-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=160%3A1559)  

- **User Stories:**
  - RF01, RF02, RF03  
    👨‍💻 [@thiagogonzagadev](https://github.com/thiagogonzagadev)  
    🧪 Review: [@andrebarceloschagas](https://github.com/andrebarceloschagas)
  - RF04, RF12, RF13  
    👨‍💻 [@andrebarceloschagas](https://github.com/andrebarceloschagas)  
    🧪 Review: [@uGonzaguinha](https://github.com/uGonzaguinha)
  - RF05, RF06, FR07  
    👨‍💻 [@uGonzaguinha](https://github.com/uGonzaguinha)  
    🧪 Review: [@raphaelsales](https://github.com/raphaelsales)
  - RF08, RF09, RF11  
    👨‍💻 [@raphaelsales](https://github.com/raphaelsales)  
    🧪 Review: [@uGonzaguinha](https://github.com/uGonzaguinha)

**Resumo:** Essa etapa foi fundamental para alinhar a visão do produto, definir suas funcionalidades básicas e preparar a equipe para o início do desenvolvimento.

---

## 🔐 Sprint 1 | 07/04 - 05/05

**Valor:** Estabelecer a base de acesso dos usuários, com login, cadastro e gerenciamento de perfil, garantindo segurança e personalização desde o início da experiência.

### Funcionalidades e Distribuição

#### Autenticação (Login e Cadastro)

- **Backend:**
  - Endpoint de Login: [@andrebarceloschagas](https://github.com/andrebarceloschagas)
  - Endpoint de Cadastro: [@HeloCris](https://github.com/HeloCris)

- **Frontend:**
  - Tela de Login  
    👨‍💻 Dev: [@andrebarceloschagas](https://github.com/andrebarceloschagas)  
    🧪 Review: [@thiagogonzagadev](https://github.com/thiagogonzagadev)  
    🔗 PR: *[link]*

  - Tela de Cadastro  
    👩‍💻 Dev: [@HeloCris](https://github.com/HeloCris)  
    🧪 Review: [@uGonzaguinha](https://github.com/uGonzaguinha)  
    🔗 PR: *[link]*

#### Home

- **Backend:**  
  - Endpoint para dados iniciais: [@raphaelsales](https://github.com/raphaelsales)

- **Frontend:**  
  - Tela Home (com mapa)  
    👨‍💻 Dev: [@raphaelsales](https://github.com/raphaelsales)  
    🧪 Review: [@andrebarceloschagas](https://github.com/andrebarceloschagas)  
    🔗 PR: *[link]*

#### Perfil

- **Backend:**
  - Buscar Perfil: [@thiagogonzagadev](https://github.com/thiagogonzagadev)
  - Editar Perfil: [@uGonzaguinha](https://github.com/uGonzaguinha)

- **Frontend:**
  - Tela de Perfil  
    👨‍💻 Dev: [@thiagogonzagadev](https://github.com/thiagogonzagadev)  
    🧪 Review: [@HeloCris](https://github.com/HeloCris)  
    🔗 PR: *[link]*

  - Tela de Editar Perfil  
    👨‍💻 Dev: [@uGonzaguinha](https://github.com/uGonzaguinha)  
    🧪 Review: [@raphaelsales](https://github.com/raphaelsales)  
    🔗 PR: *[link]*

#### Participação Cruzada

| Membro               | Frontend              | Backend                    |
|----------------------|------------------------|-----------------------------|
| @andrebarceloschagas | Tela de Login          | Endpoint de Login           |
| @HeloCris            | Tela de Cadastro       | Endpoint de Cadastro        |
| @raphaelsales        | Tela Home              | Endpoint da Home            |
| @thiagogonzagadev    | Tela de Perfil         | Endpoint de Buscar Perfil   |
| @uGonzaguinha        | Tela de Editar Perfil  | Endpoint de Editar Perfil   |

**Release:** *pendente*

---

## 🛒 Sprint 2 | 06/05 - 19/05

**Valor:** Permitir a navegação e descoberta de produtos com filtros inteligentes, além de iniciar o fluxo logístico com visualização e controle de pedidos disponíveis.

### Funcionalidades
- Tela de Catálogo de Produtos
- Filtros de Busca (tipo de produto, região)
- Detalhes do Produto
- Visualização de Pedidos Disponíveis (próximos)
- Aceitar/Rejeitar Pedido
- Integração com Google Maps (rotas)

**Release:** *pendente*

---

## 🚚 Sprint 3 | 20/05 - 02/06

**Valor:** Implementar o ciclo completo de pedidos, do carrinho ao pagamento e entrega, integrando clientes, produtores e entregadores em uma experiência fluida.

### Funcionalidades
- Carrinho de Compras
- Tela de Checkout
- Opções de Entrega/Retirada
- Integração com Meios de Pagamento (PIX e Cartão)
- Iniciar Entrega
- Atualizar Status da Entrega (coletado, em rota, entregue)
- Chat com Cliente/Produtor

**Release:** *pendente*

---

## 📦 Sprint 4 | 03/06 - 16/06

*(Conteúdo ainda não inserido)*

---
