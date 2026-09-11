# MediCare - Versão HTML/CSS

Versão em HTML puro (sem build, sem dependências além de um CDN de ícones) do mesmo design: `index.html` (tela inicial) e `appointment.html` (detalhe do agendamento). Abra `index.html` direto no navegador para ver funcionando.

## Estrutura

```
healthapp-html/
├── index.html         # Tela inicial
├── appointment.html   # Tela de agendamento
└── style.css          # Todo o estilo (cores, cards, nav)
```

## Publicando no GitHub Pages (fica no ar de graça)

1. Crie um repositório novo no GitHub e suba os arquivos:
   ```bash
   cd healthapp-html
   git init
   git add .
   git commit -m "MediCare - versão HTML"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/medicare-html.git
   git push -u origin main
   ```
2. No GitHub, vá em **Settings → Pages**.
3. Em "Build and deployment", escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`.
4. Salve. Em 1-2 minutos seu site estará em:
   ```
   https://SEU_USUARIO.github.io/medicare-html/
   ```

Pronto, sem precisar de servidor nem build — é só HTML/CSS estático.
