# Intelectio: building an institutional system

🇧🇷 [Versão em português](intelectio.pt-BR.md)

**Eduardo dos Santos Paim · PHP/Laravel · UNIPAMPA / PROINOVE**

[Product](https://intelectio.com.br/) · [Contact](https://www.linkedin.com/in/eduardo-ds-paim/)

## Context

Intelectio is an intellectual property management system in an institutional pilot. It brings together assets, deadlines, documents, payments and decision history to support the work of people authorized by the institution.

## My role

I worked as an intern in 2026 and have continued on the project as a development fellow since September. I develop and maintain backend and frontend features, integrations, tests, documentation and environment operations. Other people also contribute to the project; this page does not claim sole authorship of the whole solution.

## An engineering case: integrating public data

Integrating data from INPI (the Brazilian Patent and Trademark Office) takes more than importing a file. Data must be normalized, linked to the correct asset and reviewed when there are discrepancies. My work involves ZIP/XML/HTML processing, validation, duplicate control, provenance and queued reprocessing.

The goal is to let the team examine where each piece of information came from and make decisions with a history behind them. Data received from a source does not replace human confirmation when the workflow requires review.

## Other areas I work on

- Business rules and relational persistence with Laravel/Eloquent and MySQL.
- Permissions and per-organization data isolation.
- UI with Blade, Alpine.js and Tailwind CSS.
- Automated tests with PHPUnit and Laravel Dusk.
- Redis queues, scheduled tasks, Docker Compose and maintenance procedures.

## How I present this work in interviews

1. I explain the problem behind an institutional routine.
2. I demonstrate a flow with fictional data, when available in the presentation environment.
3. I show the technical decision, a possible failure and how the behavior is validated.
4. I distinguish what I implemented, what was built collaboratively and what is still being validated.

## Status and limits

Source code and institutional data are private. The public page presents the product; it does not grant access to internal features. This page is an account of my work, not an interactive demo. I do not claim adoption metrics or time savings without documented measurement. Internal screenshots and recordings depend on material authorized for release and on fictional data.
