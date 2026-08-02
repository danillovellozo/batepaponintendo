# Bate-Papo Nintendo

Site institucional/portal de links do canal de YouTube **Bate-Papo Nintendo**, hospedado gratuitamente no GitHub Pages com domínio próprio `batepaponintendo.com.br`.

Site estático: HTML5 + CSS puro + um pouquinho de JavaScript vanilla. Sem frameworks, sem build, sem backend.

## Estrutura

```
/
├── index.html              # Página inicial: links do canal (YouTube, X, Instagram) e card do NintenDrops
├── nintendrops/
│   └── index.html          # Página do NintenDrops: acesso ao Telegram e WhatsApp
├── assets/
│   ├── css/
│   │   └── style.css       # Estilos e variáveis de cor (:root) — troque a paleta aqui
│   ├── img/                # Logos e imagens (a preencher)
│   └── js/
│       └── main.js         # JS mínimo (ano do rodapé)
├── CNAME                   # Domínio customizado do GitHub Pages
└── README.md
```

## Personalização

- **Cores**: edite as variáveis em `assets/css/style.css`, no bloco `:root` (`--cor-primaria`, etc.).
- **Logos**: substitua o placeholder (`.logo-placeholder`) por `<img>` apontando para arquivos em `assets/img/` quando as artes finais estiverem prontas.

## Publicação (GitHub Pages)

1. Repositório público, branch `main`, Pages configurado para publicar da raiz (`/`).
2. Arquivo `CNAME` já aponta para `batepaponintendo.com.br`.
3. Configurar no DNS (registro.br) os registros apontando para o GitHub Pages.
