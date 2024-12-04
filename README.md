
# Nome do Projeto

## Descrição

Este projeto visa desenvolver um sistema de <descrever> utilizando a metodologia ágil e práticas de DevOps integradas ao GitHub. A arquitetura do software seguirá o padrão Model-View-Controller (MVC) e incorporará o(s) padrõe(s) de projeto  <descrever> para garantir uma base de código robusta e escalável. O desenvolvimento será feito na linguagem Java.

## Índice

1. [Objetivos do Projeto](#objetivo) 
2. Objetivo Geral:
    • Desenvolver um programa de controle de estoque que permita gerenciar e monitorar os níveis de produtos, garantindo que a empresa tenha informações precisas sobre a disponibilidade de itens, evitando excessos ou faltas de produtos.
    • Objetivos Específicos:
    • Registrar Produtos: Permitir a inclusão, edição e exclusão de produtos no sistema com informações como código, nome, descrição, categoria, preço e quantidade.
    • Controle de Quantidades: Monitorar o estoque de cada produto, com os níveis de estoque (mínimo ou máximo).
    • Relatórios de Estoque: Gerar relatórios simples sobre o status atual do estoque, como lista de produtos com baixo estoque ou com excesso em estoque.
    • Entrada e Saída de Produtos: Facilitar o registro de entradas (compra de novos produtos) e saídas (Solicitações e movimentações).
    • Histórico de Movimentação: Registrar todas as movimentações de estoque,  acompanhamento de entradas e saídas de cada produto.
3. [Definições, Acrônimos e Abreviações](#definição)
4. Definições
    • Produto: Item no estoque que possui atributos como código, nome, descrição, quantidade, categoria e fornecedor.
    • Categoria: Classificação do produto, representada por um conjunto de valores possíveis (enum), com código, nome e descrição.
    • Fornecedor: Entidade ou empresa responsável por fornecer os produtos. Possui atributos como código, nome, contato, telefone e email.
    • Pedido: Registro de um pedido, incluindo o código do pedido, data, status, lista de produtos e suas quantidades.
    • Estoque: Controle do inventário de produtos, incluindo operações como cadastrar, remover e consultar produtos, além de atualizar as quantidades com base em pedidos.
Acrônimos
    • ENUM: Tipo de dado que define um conjunto fixo de valores possíveis (por exemplo, para "Categoria" e "Status do Pedido").
    • SQLite: Sistema de gerenciamento de banco de dados relacional utilizado para armazenar os dados do sistema de estoque.
    • CRUD: Create, Read, Update, Delete — Operações básicas para manipulação de dados no sistema.
    • API: Application Programming Interface — Interface de programação para integração com outros sistemas (caso necessário no futuro).
    • DB: Database (Banco de Dados) — Sistema que armazena os dados do sistema de estoque.
Abreviações
    • SKU: Stock Keeping Unit (Unidade de Manutenção de Estoque) — Código único para identificar produtos no estoque (caso seja adotado no futuro).
    • FIFO: First In, First Out (Primeiro a Entrar, ultimo a Sair) — Método de controle de estoque.
    • LIFO: Last In, First Out (Último a Entrar, Primeiro a Sair) — Outro método de controle de estoque.
    • OOS: Out of Stock (Fora de Estoque) — Indica que o produto não está mais disponível no estoque.
    • UI: User Interface (Interface do Usuário) — Parte do sistema com a qual os usuários interagem diretamente.
    • UX: User Experience (Experiência do Usuário) — Experiência geral do usuário ao utilizar o sistema.
5. [Requisitos](#requisitos)
   1. [Requisitos Funcionais](#rf)
   2. [Requisitos Não Funcionais](#rnf)
6. [Diagramas UML](#uml)
   1. [Diagrama de Casos de Uso](#uc)
   2. [Descrição da imagem](Diagramadecasodeuso-jpg)
   5. [Diagrama de Classe](#classe)
7. [Estrutura do Projeto](#estrutura)
8. [Contribuição](#contribuição)
9. [Licença](#licença)
10. [Contato](#contato)

## Definições, Acrônimos e Abreviações.
< Comentário: listar siglas, termos e abreviações que estão envolvidas com o
sistema e que são utilizadas pelos usuários para indicar áreas internas, documentos,
processos, etc e são relevantes para o projeto. Listar em ordem alfabética.>
Exemplos:
▪ DAC – departamento de adminitracao e controle
▪ Controle de caixa – é o processo onde ....
▪ SCRUM - Metodologia ágil utilizada no desenvolvimento de projetos

## Requisitos ou História de Usuário
< Comentário: Aqui serão descritos os requisitos funcionais e não funcionais do
sistema a ser implementado. Os requisitos, em geral, refletem funções que o usuário
precisa realizar para atingir o objetivo do sistema ou funções de apoio à estratégia
do negócio. Registros, controle de fluxo, consultas e cadastros são requisitos típicos.
Em geral, requisito é algo que o usuário solicita explicitamente (ou requisita)
O grupo pode optar por usar história de usuário.

   ### Requisitos Funcionais
   perceptível do sistema pelos usuários. Telas, informações, relatórios, fluxo de
negócio são requisitos funcionais.>
Exemplos:
ID    Descrição
RF 01 O sistema deverá solicitar ao usuário seu login e senha e verificar se o mesmo possui
permissão de acesso ao sistema

   ### Requisitos Não Funcionais
   <Comentário: Requisito Não Funcional é aquele que define os parâmetros de
funcionamento do sistema, que trarão ao usuário uma melhor experiência no uso do
sistema, porém não são diretamente acionados por ele. Nesta categoria estão os
requisitos de arquitetura, desempenho, usabilidade, tempo de resposta, padrão de
nomenclatura, entre outros. Em geral, os usuários finais do sistema tem uma boa
noção dos requisitos não funcionais desejados, porém, pela própria subjetividade
deles, o usuário não os explicita diretamente. Ou, nos melhores casos, o usuário fala
coisas como: “que o sistema seja rápido”, “fácil de usar”, “atalhos”, “esteja sempre
disponível”, “não dependa de ninguém para usar”.
1. Segurança:<Descreve os requisitos associados à integridade dos dados, privacidade,
como o sistema trata de informação confidencial, liberação de acesso aos usuários do
sistema.>.

## Diagramas UML
   <Comentario
   
   ### Diagrama de Casos de Uso
    <Comentario 
    ID Caso de Uso               Descrição do Objetivo do Caso de Uso
    UC1 Consultar Pedido de Sala Permite consultar os pedidos de sala solicitados.
   
   ### Diagrama de Classe

## Estrutura do Projeto 
<Comentario: faça a adaptação necessária para o seu projeto
- `src/`: Código-fonte do projeto.
- `docs/`: Documentação adicional.

## Tecnologias Utilizadas
- [Linguagem de Programação]
- [Framework/Biblioteca]
- [Outras Tecnologias]

## Instruções de Instalação
1. Clone o repositório:
   ```sh
   git clone https://github.com/sua-organizacao/nome-do-repositorio.git
## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo <LICENSE> para mais detalhes.
## Contato
<Comentario: adicione foto, nome e email dos integrantes do grupo>
