# Software Engineering Skills

Conjunto de skills e instruções reutilizáveis para apoiar desenvolvimento com foco em:

- estruturação de User Stories
- implementação com clean code, SOLID e padrões consistentes
- revisão de código
- cobertura e qualidade de testes
- análise de vulnerabilidades e hardening
- preparação de merge requests e code review

Este repositório foi escrito para ser útil em fluxos de trabalho com Codex e também como base de instruções compatíveis com GitHub Copilot, usando arquivos de texto simples e orientações diretas.

## Resumo Executivo

Este pacote organiza o trabalho de engenharia de software em um fluxo confiável, com foco em:

- entendimento claro da demanda antes de codar
- implementação consistente com clean code, SOLID e padrões do projeto
- revisão técnica objetiva com evidências
- testes proporcionais ao risco
- análise de segurança e hardening
- preparação estruturada para merge request

O objetivo é reduzir ambiguidade, evitar suposições e manter o trabalho auditável do início ao fim.

## Objetivo

Ajudar desenvolvedores a trabalhar com mais consistência, previsibilidade e segurança, evitando suposições não verificadas e mantendo foco em entregas auditáveis.

As skills deste repositório priorizam:

- clareza antes de velocidade
- decisão baseada em fatos presentes no código e no contexto fornecido
- mudanças pequenas e rastreáveis
- validação por testes e revisão
- segurança por padrão

## Estrutura

- `agents/openai.yaml` - metadados gerais do pacote
- `skills/software-engineering-core/` - skill principal com princípios gerais e roteamento para as demais
- `skills/user-story-structure/` - apoio para quebrar uma demanda em história, critérios e riscos
- `skills/implementation-quality/` - apoio para desenvolver com padrão, legibilidade e robustez
- `skills/implementation-quality-dotnet/` - .NET
- `skills/implementation-quality-java/` - Java
- `skills/implementation-quality-python/` - Python
- `skills/code-review/` - apoio para revisão técnica objetiva
- `skills/code-review-dotnet/` - .NET
- `skills/code-review-java/` - Java
- `skills/code-review-python/` - Python
- `skills/testing-and-coverage/` - apoio para estratégia, cobertura e confiabilidade de testes
- `skills/testing-and-coverage-dotnet/` - .NET
- `skills/testing-and-coverage-java/` - Java
- `skills/testing-and-coverage-python/` - Python
- `skills/security-review/` - apoio para análise de vulnerabilidades e saneamento
- `skills/security-review-dotnet/` - .NET
- `skills/security-review-java/` - Java
- `skills/security-review-python/` - Python
- `skills/release-readiness/` - apoio para preparar merge request, checklist e validação final
- `.github/copilot-instructions.md` - instruções gerais para uso com GitHub Copilot
- `.github/CODEOWNERS` - define `@hoskengadu` como aprovador obrigatório
- `BRANCH_PROTECTION.md` - instruções para proteger a `master`
- `USAGE.md` - guia rápido de uso por perfil
- `CONTRIBUTING.md` - guia de contribuição e governança

## Skills E Uso

### Fluxo Principal

- `software-engineering-core`: ponto de entrada para orientar o trabalho completo
- `user-story-structure`: transforma a demanda em história, escopo e critérios
- `implementation-quality`: orienta a implementação com foco em qualidade
- `code-review`: orienta a revisão técnica do que foi produzido
- `testing-and-coverage`: orienta estratégia de testes e cobertura
- `security-review`: orienta análise de vulnerabilidades e hardening
- `release-readiness`: orienta a preparação final para merge request e release

### Skills Por Stack

- `.NET`
  - `implementation-quality-dotnet`
  - `code-review-dotnet`
  - `testing-and-coverage-dotnet`
  - `security-review-dotnet`
- `Java`
  - `implementation-quality-java`
  - `code-review-java`
  - `testing-and-coverage-java`
  - `security-review-java`
- `Python`
  - `implementation-quality-python`
  - `code-review-python`
  - `testing-and-coverage-python`
  - `security-review-python`

## Como usar

### No Codex

Copie a pasta `skills/` para o diretório de skills do Codex ou mantenha este repositório como base de referência para instalar os arquivos desejados.

Use a skill principal quando quiser um fluxo completo. Use as skills específicas quando o objetivo for apenas uma etapa.

Se você estiver integrando este repositório como pacote de skills, mantenha a estrutura de pastas como está para facilitar descoberta e manutenção.

Quando a tecnologia alvo não estiver explícita, pergunte se o trabalho deve seguir convenções de `.NET`, `Java` ou `Python` antes de continuar com orientação específica.

### No GitHub Copilot

O arquivo `.github/copilot-instructions.md` fornece uma base de comportamento para os cenários mais comuns:

- entender a demanda antes de codar
- evitar invenções sem evidência
- sugerir mudanças pequenas e seguras
- favorecer testes e revisão
- sinalizar riscos e lacunas

## Princípios de operação

As instruções deste repositório seguem estas regras:

1. Não inventar requisitos, dependências, APIs ou comportamento não comprovado.
2. Sempre diferenciar fato observado de hipótese.
3. Sempre indicar riscos, lacunas e impactos de forma objetiva.
4. Sempre privilegiar soluções simples, testáveis e mantíveis.
5. Sempre buscar cobertura de teste proporcional ao risco.
6. Sempre tratar segurança como requisito, não como adendo.

## Governança

Este repositório foi pensado para funcionar com fluxo de merge request e revisão centralizada.

- alterações devem passar por revisão antes de chegar à branch principal
- a branch principal deve permanecer protegida
- aprovações e merges seguem a política do time ou do repositório de destino

As skills não concedem permissão de commit, merge ou aprovação. Elas apenas orientam o assistente a respeitar a governança já existente.

## Manutenção

Ao evoluir as skills, prefira:

- manter instruções curtas e específicas
- separar regras gerais de casos especializados
- remover redundâncias
- atualizar exemplos e checklists apenas quando realmente ajudam a decisão

## Instalação

1. Clone ou copie este repositório para o ambiente onde as skills serão consumidas.
2. Mantenha a pasta `skills/` com a mesma estrutura de diretórios.
3. Se estiver usando Codex, aponte o repositório como base de skills ou copie as pastas desejadas para o diretório de skills configurado no ambiente.
4. Se estiver usando GitHub Copilot, use o arquivo `.github/copilot-instructions.md` como referência base do projeto.
5. No GitHub, aplique as regras de proteção da branch `master` conforme [BRANCH_PROTECTION.md](./BRANCH_PROTECTION.md).

## Fluxo Recomendado

1. Estruture a demanda com `user-story-structure`.
2. Confirme a tecnologia alvo se ela não estiver explícita.
3. Implemente com `implementation-quality` ou a variante da stack.
4. Revise com `code-review` ou a variante da stack.
5. Ajuste ou adicione testes com `testing-and-coverage` ou a variante da stack.
6. Faça a análise de segurança com `security-review` ou a variante da stack.
7. Prepare o merge request com `release-readiness`.

## Exemplo Prático

Exemplo de uso em um projeto real:

1. Uma solicitação chega sem detalhamento suficiente.
2. A skill `user-story-structure` transforma isso em escopo, critérios de aceitação e riscos.
3. O projeto informa que a stack é `Python`.
4. A implementação segue `implementation-quality-python`.
5. A revisão usa `code-review-python`.
6. Os testes seguem `testing-and-coverage-python`.
7. A análise de risco segue `security-review-python`.
8. O merge request final segue `release-readiness`.

## Versões

Veja o histórico de mudanças em [CHANGELOG.md](./CHANGELOG.md).
