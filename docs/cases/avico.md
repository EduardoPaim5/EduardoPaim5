# AVICO Gestão ONG: TCC em Engenharia de Software

**Eduardo dos Santos Paim · Laravel · PostgreSQL · Docker**

[Contato](https://www.linkedin.com/in/eduardo-ds-paim/) · [Perfil](https://github.com/EduardoPaim5)

## Problema e escopo

Sistema web desenvolvido como TCC para apoiar gestão de associados, contribuições, doações e transparência de uma ONG. A proposta conecta rotinas administrativas, rastreabilidade financeira e organização dos dados.

## Minha atuação

Desenvolvimento das funcionalidades, modelagem e persistência, importação de dados legados, perfis e permissões, auditoria, relatórios, testes e documentação. O ambiente reproduzível usa Docker Compose.

## Fluxo escolhido para avaliação

Importação de dados fictícios → cadastro do associado → contribuição → registro de pagamento → relatório.

Esse recorte permite discutir validação de dados, tratamento de duplicidade, autorização, consistência financeira e rastreabilidade, sem apresentar informações pessoais de associados.

## Decisões de implementação

- Laravel organiza validações, autorização e regras de negócio.
- PostgreSQL mantém os dados relacionais; registros financeiros possuem caminhos de auditoria e controle de repetição.
- A importação deve informar problemas de dados e preservar contexto para conferência.
- Testes e documentação apoiam a preparação dos fluxos para avaliação com usuários.

## Estado atual

Projeto em desenvolvimento e preparação de fluxos para avaliação. Não afirmo adoção operacional, aceite final ou resultado de produtividade sem registro correspondente. O código é privado; o antigo link público não deve ser usado como acesso ao repositório. Uma demonstração, quando preparada, utiliza dados fictícios.
