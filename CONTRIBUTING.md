# Guia de Contribuição

## Branches
- Branch principal: `main`
- Crie novas branches a partir da `main` no formato:  
  `feature/nome-da-feature` ou `fix/nome-da-correção`

## Commits
Use o padrão:
<tipo>: <descrição>

markdown
Copiar código
Exemplo:  
`feat: adicionar cálculo automático de saldo`

Tipos: `feat`, `fix`, `docs`, `refactor`, `chore`, `style`

## Issues
- Verifique se já existe uma issue parecida.  
- Descreva o problema, passos para reproduzir e comportamento esperado.

## Pull Requests
- Atualize sua branch antes do PR.  
- Descreva o que mudou e por quê.  
- Não inclua `node_modules`, `dist` ou `.parcel-cache`.

## Revisão e Merge
- Todo PR precisa de **3 aprovações** antes do merge na `main`.
- O merge deve ser feito **via PR**, nunca direto na `main`.