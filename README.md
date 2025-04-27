🐾 VetClinic Open Source

Sistema de gestão completo para clínicas veterinárias, open source, multi-tenant e com integração para emissão de NF-e e NFC-e.
✨ Funcionalidades Iniciais

    📋 Cadastro de clientes e pets

    📅 Agendamento de consultas e procedimentos

    💉 Controle de vacinas e tratamentos

    💰 Gestão de orçamentos e faturamento

    🏥 Multi-clínicas (Multi-tenant)

    📄 Integração para emissão de Nota Fiscal Eletrônica (NF-e) e NFC-e

    🌎 100% Open Source, comunidade livre para usar e colaborar

🚀 Tecnologias Utilizadas

    Backend: Laravel 11

    Frontend: Blade (inicialmente, depois podemos usar Livewire ou Vue.js)

    Banco de Dados: MySQL 8.0

    Ambiente de Desenvolvimento: GitHub Codespaces + Docker

🔥 Como Rodar o Projeto Localmente

    Clone o repositório:

git clone https://github.com/seu-usuario/vetclinic-open-source.git

Acesse a pasta:

cd vetclinic-open-source

Suba os containers:

docker compose up -d

Acesse o container app:

docker compose exec app bash

Dentro do container, crie o projeto Laravel:

    composer create-project --prefer-dist laravel/laravel vetclinic

    Ajuste o .env do Laravel para conectar no MySQL (dados padrão do docker-compose).

📈 Roadmap Inicial

Ambiente com Laravel + Docker

Sistema Multi-tenant (separação de clínicas)

Cadastro de clientes e pets

Agendamento de consultas

Controle de estoque de medicamentos

Emissão de NFC-e / NF-e integrada

Módulo de doações para manter o projeto

    Versão SaaS gratuita no futuro

❤️ Contribua!

Quer ajudar? Envie PRs, abra issues, participe!
Este projeto é para ser da comunidade, e para a comunidade veterinária!
📜 Licença

Este projeto está sob a licença MIT — sinta-se livre para usar e modificar como quiser!
🎯 Foco do Projeto

Criar um sistema profissional de forma 100% livre e de qualidade para atender clínicas veterinárias no Brasil 🇧🇷, democratizando a tecnologia no setor.
🐳 VetClinic Open Source

"Tecnologia feita com amor para quem cuida da vida dos nossos melhores amigos!" 🐶🐱🐰
E mais: 🌟

Se você quiser, já posso montar também:

    Um exemplo de .env para o Laravel pronto para o Docker.

    A primeira versão da organização de pastas e módulos pensando no sistema multi-tenant!