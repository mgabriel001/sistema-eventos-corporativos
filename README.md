# Sistema de Cadastro para Eventos Corporativos

Sistema simples para o setor de RH gerenciar participantes de eventos corporativos.

## Funcionalidades

- Autenticação de usuários
- Cadastro e gestão de participantes
- Filtros por setor e cidade
- Painel administrativo
- Controle de check-in

## Tecnologias Utilizadas

- PHP
- MySQL
- HTML, CSS
- Bootstrap

## Como Instalar

### Pré-requisitos
- XAMPP (Apache e MySQL)
- PHP 7.4+

### Instalação
1. Coloque os arquivos na pasta htdocs do XAMPP
2. Crie um banco de dados chamado "eventos_corporativos"
3. Importe o arquivo database.sql (se disponível)
4. Configure as credenciais no arquivo config/database.php
5. Inicie o Apache e MySQL no XAMPP
6. Acesse: http://localhost/nome-da-pasta/admin/login.php

### Credenciais de Teste
Administrador:
- Email: maria@empresa.com
- Senha: 123456

## Estrutura de Arquivos
```
eventos-corporativos/
├── admin/          # Painel administrativo
├── config/         # Configurações
├── participantes/  # Gestão de participantes
├── assets/         # CSS e JS
├── index.php       # Página inicial
└── README.md       # Documentação
```

## Licença
Licença MIT - veja o arquivo LICENSE para detalhes.

Desenvolvido por Marcos Gabriel Nobre de Paiva - mgabrielnp.2606@gmail.com
