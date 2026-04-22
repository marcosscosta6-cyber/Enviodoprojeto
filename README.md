# Enviodoprojeto

Coin Gecko API

Descrição
Uma aplicação front-end focada na busca de criptomoedas e seus respectivos valores, desenvolvida a partir dos dados da Coin Gecko API, estruturado com duas páginas, validação de estado da interface e automação de testes E2E

 Tecnologias Utilizadas
HTML5
CSS3
JavaScript 
Cypress

Funcionalidades
Home: Primeira página e campo de busca com API pública.
Estado de Carregamento: Botão de busca fica desabilitado (.disabled) enquanto aguarda a localização da moeda na API.
Detalhes Page: Exibição de informações detalhadas do item selecionado.
Navegação:  Botões funcionais entre Home e Detalhes.

 Pré-requisitos de execução dos testes
Antes de começar, deve se garantir de ter instalado:
[Node.js](https://nodejs.org) (versão LTS)
npm ou yarn   

Documentação BDD (Gherkin)
(Os cenários de teste também podem ser encontrados no arquivo specs.md na raiz do projeto) 

Cenário 1: Buscar criptomoeda
Dado que estou na página inicial
Quando clico no botão buscar
Então devo ver uma lista de criptomoedas

Cenário 2: Navegar para detalhes
Dado que estou na página inicial
Quando clico em uma criptomoeda
Então devo ser redirecionado para a página de detalhes

Cenário 3: Ver detalhes
Dado que estou na página de detalhes
Então devo ver informações da criptomoeda selecionada 

Relatório de Grupo

Marcos Saulo: Fez a primeira e segunda página e a conexão API

Monique: Fez a parte HTML e os testes cypress

Alessandra: Fez e elaborou os slides 

André Luiz: apresentou

Gabriel Melo: apresentou

Hugo Harley: apresentou
