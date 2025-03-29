# Produto Mínimo Viável HortaShop

![logo](https://github.com/user-attachments/assets/hortashop/logo.png)

- Índice
  - [Descrição do produto](#descrição-do-produto)
  - [Time](#time)
  - [Definindo o Problema](#definindo-o-problema)
  - [Business Model Canvas](#business-model-canvas)
  - [Mapeamento e Estudo dos Concorrentes: iFood e Aiqfome](#mapeamento-e-estudo-dos-concorrentes-ifood-e-aiqfome)
  - [MVP no HortaShop](#mvp-no-hortashop)
  - [Por que um MVP para o HortaShop?](#por-que-um-mvp-para-o-hortashop)
  - [Visão Geral das Sprints](#visão-geral-das-sprints)
    - [Critérios de Aceitação](#critérios-de-aceitação)
  - [Próximos Passos](#próximos-passos)

---

## Descrição do produto

HortaShop é uma plataforma online que conecta consumidores que buscam alimentos saudáveis e frescos diretamente com produtores rurais de hortifrúti. O objetivo é eliminar intermediários, promover a sustentabilidade e fortalecer a economia regional, facilitando o acesso a produtos de qualidade.

---

## Time

### Antonio André Barcelos Chagas - [@andrebarceloschagas](https://github.com/andrebarceloschagas)

### Gustavo Gonzaga dos Santos - [@uGonzaguinha ](https://github.com/uGonzaguinha)

### Helorrayne Cristine  - [@HeloCris](https://github.com/HeloCris)

### Raphael Sales - [@raphaelsales ](https://github.com/raphaelsales )

### Thiago Gonzaga dos Santos - [@thiagogonzagadev](https://github.com/thiagogonzagadev)



---

## Definindo o Problema

O HortaShop visa solucionar os seguintes problemas:

- **Desperdício alimentar:** Cerca de 30% da produção agrícola se perde na cadeia logística tradicional.
- **Margens reduzidas:** Intermediários absorvem até 60% do preço final ao consumidor.
- **Acesso limitado:** Pequenos agricultores frequentemente têm dificuldade em acessar mercados diretos.
- **Sustentabilidade:** Longas cadeias de distribuição aumentam o impacto ambiental.

---

## Business Model Canvas


---

## Mapeamento e Estudo dos Concorrentes: iFood e Aiqfome

### Objetivos da Análise:
- Compreender o mercado local brasileiro para venda direta entre produtores e consumidores.
- Identificar oportunidades para diferenciar o HortaShop.
- Desenvolver estratégias para superar os concorrentes.

#### Análise Comparativa:

| Aspecto | iFood | Aiqfome | HortaShop (Potencial) |
|---|---|---|---|
| **Modelo de negócio** | Marketplace para entrega de refeições prontas | Plataforma regional focada em delivery local | Conexão direta entre produtores rurais e consumidores |
| **Funcionalidades** | Busca por restaurantes, entrega rápida | Interface simples com foco em cidades menores | Catálogo agrícola com filtros, listas de produtos sazonais, selos de qualidade (orgânico, agroecológico), receitas com os produtos disponíveis, alerta de novos produtos dos produtores favoritos |
| **Comunidade** | Base ampla em grandes cidades | Forte presença em cidades pequenas e médias | Engajamento com consumidores locais e pequenos agricultores |
| **Marketing e comunicação** | Campanhas nacionais com grandes marcas | Foco em divulgação regionalizada | Redes sociais (Instagram, Facebook) com conteúdo educativo e informativo, parcerias com influenciadores locais e blogs de culinária saudável |
| **Vantagens competitivas** | Grande variedade de opções gastronômicas | Atendimento personalizado em regiões específicas | Sustentabilidade e apoio à agricultura familiar |

---

## MVP no HortaShop

No desenvolvimento do HortaShop, o Produto Mínimo Viável (MVP) será uma versão básica da plataforma que permitirá validar a ideia com os usuários iniciais (produtores rurais e consumidores). 

### Funcionalidades Essenciais:
1. Cadastro dual (produtor/consumidor) com verificação documental.
2. Catálogo de produtos agrícolas com filtros por tipo de cultivo e localização.
3. Sistema de pedidos integrado com opções de retirada ou entrega.
4. Pagamento via PIX ou cartão.

---

## Por que um MVP para o HortaShop?

- **Validar a ideia:** Testar a aceitação da plataforma no mercado.
- **Coletar feedback:** Identificar melhorias necessárias nas funcionalidades.
- **Reduzir custos:** Evitar desenvolvimento desnecessário antes da validação.
- **Acelerar o lançamento:** Priorizar as funcionalidades mais importantes.

---

## Visão Geral das Sprints

### Cronograma:

| Sprint | Período | Foco | Funcionalidades Principais (Clientes/Produtores) | Funcionalidades Principais (Entregadores) | Entregas |
|---|---|---|---|---|---|
| 1 | 07/04 - 04/05 | Core da Plataforma e Cadastro | Tela de Login, Tela de Cadastro (produtor e consumidor), Tela Home (inicial), Tela de Perfil (produtor e consumidor), Tela de Editar Perfil (produtor e consumidor). | Tela de Login, Tela de Cadastro, Tela Home (com mapa), Tela de Perfil, Tela de Editar Perfil. | Release 1: Funcionalidades básicas de autenticação e perfis de usuário para ambos os aplicativos. |
| 2 | 05/05 - 19/05 | Catálogo, Busca e Geolocalização | Tela de Catálogo de Produtos, Filtros de Busca (por tipo de produto, região), Detalhes do Produto. | Visualização de Pedidos Disponíveis (próximos), Aceitar/Rejeitar Pedido, Integração com Google Maps (para rotas). | Release 2: Catálogo de produtos pesquisável, visualização de entregas próximas e sistema de aceitação/rejeição de pedidos. |
| 3 | 20/05 - 02/06 | Sistema de Pedidos e Rastreamento | Carrinho de Compras, Tela de Checkout, Opções de Entrega/Retirada, Integração com Meios de Pagamento (PIX e cartão). | Iniciar Entrega, Atualizar Status da Entrega (coletado, em rota, entregue), Chat com o Cliente/Produtor. | Release 3: Fluxo completo de pedidos para clientes/produtores e sistema de gerenciamento de entregas para entregadores. |
| 4 | 03/06 - 16/06 | Avaliação, Refinamento e Histórico | Sistema de Avaliação de Produtores, Histórico de Pedidos (Clientes/Produtores), Refinamento da Interface e Correção de Bugs. | Histórico de Entregas, Avaliação do Cliente/Produtor, Refinamento da Interface e Correção de Bugs. | Release 4: Funcionalidades de avaliação, histórico e melhorias gerais na plataforma para ambos os aplicativos. |


---

### Critérios de Aceitação

- **Usuário:** O consumidor consegue visualizar produtos disponíveis na sua região.
- **Sistema:** Os dados dos produtores são armazenados com segurança no banco de dados.
- **Usabilidade:** A interface é intuitiva e fácil de navegar.

---

## Próximos Passos

1. Finalizar o design das telas principais no Figma.
2. Iniciar desenvolvimento das funcionalidades da Sprint 1.
3. Realizar testes unitários para garantir qualidade do código.


*O MVP será ajustado conforme feedback dos primeiros usuários.*
