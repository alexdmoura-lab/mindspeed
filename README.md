# MINDSPEED — Performance Mental para Pilotos

Landing page institucional de uma página para a MINDSPEED — mentoria de performance mental voltada para pilotos de automobilismo e kart.

## Stack

- HTML único (`index.html`) com CSS e JS inline
- Sem build step, sem dependências externas (apenas Google Fonts)
- Imagens locais em `assets/`
- Mobile-first, totalmente responsivo

## Estrutura

```
.
├── index.html                          # Página única
├── assets/
│   ├── hero-pilot.jpg                  # Hero — piloto na pit lane
│   ├── pillar-01-mindfulness.jpg       # Pilar 01 — Mindfulness
│   ├── pillar-02-breathwork.jpg        # Pilar 02 — Breathwork
│   ├── pillar-03-mentalidade.jpg       # Pilar 03 — Mentalidade
│   └── wandler.jpg                     # Foto do mentor
└── README.md
```

## Rodar localmente

Não precisa de build. Basta abrir o `index.html` no navegador ou servir com qualquer servidor estático:

```bash
# opção 1: abrir direto
open index.html

# opção 2: servidor local (Python)
python3 -m http.server 8000

# opção 3: servidor local (Node)
npx serve .
```

## Deploy no Vercel

1. Conecte este repositório ao Vercel (`vercel.com/new`).
2. Vercel detecta automaticamente como site estático — **nenhuma configuração necessária**.
3. Build Command: *(vazio)*
4. Output Directory: *(vazio — usa a raiz)*
5. Deploy.

Cada push para `main` redeploya automaticamente.

## Contato

- WhatsApp: [(11) 95239-4256](https://wa.me/5511952394256)
- Instagram: [@mindspeedbr](https://instagram.com/mindspeedbr)

---

© 2026 MINDSPEED · Performance mental para pilotos
