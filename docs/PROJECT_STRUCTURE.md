# Estrutura recomendada do projeto

Este guia descreve pastas e arquivos que funcionam bem para projetos agnósticos.

## Diretórios principais

- `src/`
  - Código-fonte principal do projeto.
  - Pode conter front-end, back-end, scripts ou exemplos de algoritmo.
- `tests/`
  - Testes unitários, de integração e verificações simples.
  - Ideal para manter qualidade em projetos de estudo e portfólio.
- `public/`
  - Arquivos estáticos, demos, protótipos ou deploys estáticos.
- `assets/`
  - Imagens, ícones, diagramas e mídia do projeto.
- `docs/`
  - Documentos auxiliares, notas de arquitetura e guias de uso.

## Arquivos de apoio

- `README.md` - descrição, instruções de execução e exemplos.
- `CONTRIBUTING.md` - normas de colaboração.
- `CHANGELOG.md` - histórico de alterações.
- `ROADMAP.md` - planejamento e prioridades.
- `.editorconfig` - estilo básico cross-platform.
- `.gitignore` - exclusões de arquivos temporários.

## Como adaptar para diferentes contextos

### Hackathon

- Use `src/` para o MVP.
- Deixe `docs/` leve e focada no que foi construído.
- Priorize velocidade de entrega.

### Estudo

- Comente mais o código.
- Adicione etapas de aprendizado em `docs/`.
- Use `tests/` para validar conceitos.

### Portfólio

- Crie uma narrativa clara no `README.md`.
- Adicione capturas em `assets/`.
- Documente escopo, desafios e resultados.

## Boas práticas

- Prefira convenções simples.
- Evite dependências desnecessárias.
- Centralize as instruções em `README.md`.
- Mantenha a estrutura minimalista, mas extensível.
