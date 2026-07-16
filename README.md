# agilean-b2c-pages

Páginas custom do Azure AD B2C (login + reset) da Plataforma Agilean — hospedagem de TESTE via GitHub Pages.

**DÉBITO:** migrar pra blob storage/CDN gerenciado pelo devops. Fonte canônica dos arquivos:
`agilean-core-frontend/public/b2c/` (worktree). Este repo é só o host estável enquanto se testa.

- `unified.html` — página de sign-in (page layout "Unified sign up or sign in")
- `selfasserted.html` — páginas SelfAsserted (reset de senha: verificação de email, nova senha)
