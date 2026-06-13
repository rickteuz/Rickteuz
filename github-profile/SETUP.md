# 🚀 Como instalar o novo perfil

## 1. Repositório especial
O README de perfil precisa estar no repositório com o **mesmo nome do seu usuário**: `Rickteuz/Rickteuz` (público, com o README na raiz da branch principal).

## 2. Suba estes arquivos
Copie para a raiz do repositório `Rickteuz/Rickteuz`:

```
README.md
assets/header.svg
assets/terminal.svg
assets/divider.svg
.github/workflows/snake.yml
```

## 3. Ative a Snake Animation (1x apenas)
1. No repositório, vá em **Settings → Actions → General** e confirme que Actions estão habilitadas com permissão **Read and write** em "Workflow permissions".
2. Vá na aba **Actions** → workflow **"🐍 Generate Snake Animation"** → botão **Run workflow**.
3. Isso cria a branch `output` com os SVGs da cobrinha. Depois disso ela se atualiza sozinha a cada 12h.
4. Enquanto o workflow não rodar, a seção da snake aparece quebrada — é esperado.

## 4. Personalize os links de contato
No `README.md`, troque os placeholders:
- `SEU-LINKEDIN-AQUI` → seu usuário do LinkedIn
- `SEU-INSTAGRAM-AQUI` → seu usuário do Instagram

## 5. Dicas
- As animações dos SVGs (`header`, `terminal`, `divider`) rodam direto no GitHub — sem nenhuma dependência externa.
- Os cards de stats (`github-readme-stats`, `streak-stats`, `activity-graph`, `trophy`) são serviços públicos; se algum demorar a carregar, é cache deles, normaliza sozinho.
- `count_private=true` nos stats só funciona plenamente se você fizer deploy próprio do github-readme-stats; com o serviço público ele mostra o que é visível publicamente.
