# Proteção da Branch `master`

Para garantir que somente `@hoskengadu` possa aprovar pull requests para `master`, configure as regras de proteção da branch no GitHub com estes ajustes:

## Configurações obrigatórias

- Proteger branches correspondentes: `master`
- Exigir pull request antes do merge
- Exigir aprovações: pelo menos `1`
- Exigir revisão de Code Owners: habilitado
- Descartar aprovações antigas quando novos commits forem enviados: habilitado
- Restringir quem pode fazer push para as branches correspondentes: habilitado
- Permitir force push: desabilitado
- Permitir exclusões: desabilitado

## Efeito esperado

- Qualquer pull request que altere arquivos cobertos por `.github/CODEOWNERS` exigirá aprovação de `@hoskengadu`.
- Push direto para `master` será bloqueado para todos, exceto usuários explicitamente permitidos pela regra da branch.
- Novos commits enviados para um pull request já aprovado invalidarão aprovações antigas.

## Observação importante

`CODEOWNERS` sozinho não impõe proteção de branch. As configurações do repositório no GitHub também precisam ser aplicadas.
