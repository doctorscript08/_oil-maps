# Oil Maps

## Objectivo

Desenvolver um sistema simples e interactivo que permita que os usuários possam partilhar informações sobre os postos de combustível dentro e fora da cidade, cooperando uns com os outros e facilitando assim a aquisição de combustível sem muitos contratempos.

---

## Usuários do sistema

- Super Administradores
- Administradores
- Clientes/Condutores

## Problemas identificados

- Falta de informação sobre o actual estado dos postos de combustível mais próximos
- Demora na procura do combustível
- Perda de tempo
- Urgência para adquirir combustível

---

## Requisitos funcionais

- RF01 - Visualizar postos de combustível num mapa
- RF02 - Obter a localização do usuário
- RF03 - Informar sobre o estado dos postos
- RF04 - Visualizar as métricas baseadas nas informações dadas pelos usuários
- RF05 - Armazenar os dados dos postos de combustível
- RF06 - Actualizar as métricas consoante os dados mais recentes
- RF07 - Cadastrar de administradores
- RF08 - Gerir administradores (criar, editar, excluir)
- RF09 - Realizar login e autenticação

## Requisitos não funcionais

- RNF01 - Segurança
- RNF02 - Performance
- RNF03 - Interface simples e intuitiva
- RNF04 - Responsividade

## Regras de Negócio

- RN01 - O usuário só pode seleccionar uma opção ao fornecer os dados de determinado posto de combustível
- RN02 - Apenas super administradores podem cadastrar e gerenciar outros administradores
- RN03 - Administradores normais apenas gerenciam dados do sistema