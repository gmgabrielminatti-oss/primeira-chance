# Primeira Chance — site

**Fonte única de verdade.** Este repositório (`primeira-chance`) é o que está publicado.
O antigo `primeira-chance-preview` está **obsoleto** e não é mais mantido.

- **Site no ar:** https://cursoprimeirachance.com.br
- **Hospedagem:** GitHub Pages, servindo da **raiz** da branch `main` (Enforce HTTPS ativo).
- **Domínio:** definido pelo arquivo `CNAME` — **não remover nem alterar**.

## Estrutura
- `index.html` — landing principal
- `mega-aula/` — landing da mega aula (+ `obrigado.html`)
- `curriculo/` — gerador de currículo
- `checklist/`, `email/`, `vagas/` — ferramentas gratuitas
- `politica-de-privacidade/`, `termos-de-uso/` — páginas legais
- `CNAME` — domínio do Pages (não mexer)

## Fluxo de trabalho
1. Editar no clone local **`primeira-chance-prod`**.
2. Revisar o diff (`git status` / `git diff`).
3. **Commit + push direto pra `main`** — o GitHub Pages publica em ~1 min.

## Reverter, se preciso
Backup do estado anterior à migração do site novo:
- branch `backup-landing-antiga`
- tag `pre-migracao-2026-06-17`

## Analytics
GTM `GTM-NNZXQPTD` em todas as páginas (Consent Mode v2); tags/triggers no painel do GTM.
