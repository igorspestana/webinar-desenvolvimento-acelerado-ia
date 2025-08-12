# Webinar: Desenvolvimento Acelerado com Agentes de IA

> **Repositório de Material de Apoio** - Este repositório serve como material de apoio para o webinar **"Desenvolvimento Acelerado com Agentes de IA"**, fornecendo documentação estruturada e regras para criação automatizada de boilerplates de APIs Node.js.

## Sobre Este Projeto

Este projeto tem como objetivo demonstrar como utilizar agentes de IA para acelerar o desenvolvimento de software, fornecendo um conjunto completo de documentação e regras que permitem a criação automatizada de boilerplates de APIs Node.js com TypeScript, autenticação Supabase, rate limiting e outras funcionalidades essenciais.

## Estrutura do Projeto

### 📄 `desenvolvimento-acelerado-com-agentes-de-ia.pdf`
Slides da apresentação do webinar "Desenvolvimento Acelerado com Agentes de IA".

### 📁 `docs/` - Arquivos de Documentação
Contém arquivos `.mdc` (Markdown Cursor) que servem como base de conhecimento:

- **`architecture.mdc`** - Visão geral da arquitetura do sistema
- **`auth.mdc`** - Estratégia de autenticação e controle de acesso
- **`deployment.mdc`** - Estratégias de deploy, configuração de ambientes e CI/CD
- **`endpoints.mdc`** - Padrões e exemplos de rotas REST
- **`entities.mdc`** - Estruturas das entidades do banco de dados
- **`guardrails.mdc`** - Regras de segurança, proteções contra operações destrutivas e configuração de CORS
- **`env.example`** - Template de variáveis de ambiente
- **`package.json.example`** - Template de dependências
- **`adr/`** - Registros de Decisões de Arquitetura

### 📁 `.cursor/` - Regras para Agentes de IA
Configurações específicas para o Cursor IDE:
- **`rules/`** - Regras de desenvolvimento e padrões de código
- **`mcp.json`** - Configurações do MCP (Model Context Protocol)

### 📁 `prompts/` - Prompts Iniciais
- **`initial-prompt.md`** - Prompt principal para iniciar a criação do boilerplate

## Agentes de IA de Desenvolvimento Suportados

Este repositório foi projetado para funcionar com múltiplos agentes de desenvolvimento de software:

- **🎯 Cursor** (Principal) - Configuração completa na pasta `.cursor/`
- **🌊 Windsurf** - Compatível com a estrutura de documentação
- **🤖 Claude Code** - Funciona com formato de documentação .mdc
- **💎 Gemini CLI** - Suporta abordagem de documentação estruturada

### Modelo Recomendado
**Claude Sonnet 4** é recomendado para melhores resultados na geração do boilerplate.

## Projeto Desenvolvido

### 🚀 API Boilerplate com Autenticação Supabase
O projeto [api-boilerplate-auth-supabase](https://github.com/igorspestana/api-boilerplate-auth-supabase) foi desenvolvido utilizando os recursos e documentação deste repositório, demonstrando na prática como os agentes de IA podem acelerar o desenvolvimento de APIs Node.js com TypeScript e autenticação Supabase.

## Como Usar

### 1. Escolha Sua Ferramenta de IA para Desenvolvimento
Selecione um dos agentes de IA suportados (Cursor, Windsurf, Claude Code, ou Gemini CLI).

### 2. Carregue o Prompt Inicial
Copie o conteúdo do arquivo `prompts/initial-prompt.md` e cole no chat do seu agente de IA escolhido:

```markdown
Utilize os arquivos em @node-rules.mdc e @docs/ como contexto e inicie o desenvolvimento do projeto seguindo os critérios informados.
```

### 3. Documentação de Referência
O agente utilizará automaticamente os arquivos de documentação em `docs/` e as regras em `.cursor/` como contexto para gerar o boilerplate completo.

### 4. Funcionalidades do Boilerplate Gerado
O boilerplate gerado incluirá:
- ✅ Configuração Node.js + TypeScript
- ✅ Integração de autenticação Supabase
- ✅ Implementação de rate limiting
- ✅ Estrutura de API RESTful
- ✅ Gerenciamento de entidades do banco de dados
- ✅ Proteções de segurança
- ✅ Configuração de ambiente
- ✅ Estrutura pronta para deploy

## Início Rápido para Desenvolvimento

### 1. Clone o Repositório
```bash
git clone https://github.com/igorspestana/webinar-desenvolvimento-acelerado-com-agentes-de-ia.git
cd webinar-desenvolvimento-acelerado-com-agentes-de-ia
```

### 2. Configure Seu Agente de IA
Configure sua ferramenta de desenvolvimento com IA escolhida para referenciar a documentação e regras neste repositório.

### 3. Inicialize a Criação do Boilerplate
Use o prompt inicial para começar o processo de geração automatizada do boilerplate.
