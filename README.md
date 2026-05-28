# Astreon

> Sistemas modulares auto-construtores para mineração de Hélio-3 e gases nobres na superfície lunar.

**Astreon** é uma empresa de tecnologia espacial focada em desenvolver hardware autônomo para extração de recursos no regolito lunar. O **Astreon Model I**, nosso primeiro produto, é composto por 20 módulos esféricos inteligentes que pousam, se dispersam, se auto-montam e iniciam operações de mineração sem intervenção humana.

Este repositório contém a landing page institucional da Astreon, publicada via GitHub Pages.

## 🌐 Site no ar

Após ativar o GitHub Pages nas configurações do repositório, o site fica disponível em:

```
https://romuloexavier2.github.io/GlobalSolution2026/
```

## 📂 Estrutura do repositório

```
GlobalSolution2026/
├── index.html              ← Landing page principal
├── astreon-logo.png        ← Logo institucional (usada no hero)
├── 404.html                ← Página de erro customizada com a estética da marca
├── README.md               ← Este arquivo
├── .gitignore              ← Arquivos ignorados pelo Git
└── assets/                 ← (Opcional) Material complementar para download
    ├── pitch-deck.pdf
    └── pitch-deck.pptx
```

## 🚀 Como ativar o GitHub Pages

1. Suba os arquivos para a branch `main`.
2. Vá em **Settings → Pages** no repositório do GitHub.
3. Em **Source**, selecione **Deploy from a branch**.
4. Escolha a branch `main` e a pasta `/ (root)`.
5. Clique em **Save**.
6. Aguarde 1–3 minutos para o GitHub provisionar o site.

## 🧪 Como rodar localmente

O site é um arquivo HTML único e funciona offline. Para visualizar:

- **Opção rápida:** abrir `index.html` diretamente no navegador (Chrome, Edge, Firefox).
- **Opção com servidor local** (recomendado para evitar restrições de CORS em imagens):

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve .
```

Depois acesse `http://localhost:8000`.

## 🛰️ Sobre o Astreon Model I

O **Astreon Model I** é um sistema modular auto-construtor projetado para operar em condições extremas da superfície lunar. Cada módulo é uma esfera de 200 mm com casca ferromagnética selada, locomoção por momento angular interno (sem partes móveis externas) e 12 portas de acoplamento eletromagnético criogênico.

### Inovações combinadas

| Componente | Descrição |
|---|---|
| **Casca esférica selada** | Imune ao regolito eletrostático lunar |
| **Locomoção inercial** | Flywheels internos eliminam juntas expostas |
| **Conector EP criogênico** | Travamento sem consumo de energia, vedação pressórica em −180°C |
| **Resource sharing distribuído** | Resiliência exponencial à falha de módulos |
| **Geometria rombicododecaédrica** | 12 vizinhos por módulo, máxima densidade estrutural |

### Aplicação: Hélio-3

O Hélio-3 (³He) é um isótopo raríssimo na Terra (estoque mundial < 30 kg) que se acumula em abundância no regolito lunar há bilhões de anos. É candidato ideal para fusão nuclear limpa, sem nêutrons e sem resíduos radioativos de longa duração. Mercado atual: ~US$ 40.000 por grama, com projeção de 5–10× nos anos 2030 com o avanço de reatores comerciais de fusão.

## 🎯 Roadmap

| Fase | Período | Investimento | TRL |
|---|---|---|---|
| **01** · Protótipo do conector | 2026–2027 | USD 200K–400K | 3–4 |
| **02** · Módulo completo | 2027–2028 | USD 1M–3M | 4–5 |
| **03** · Qualificação espacial | 2028–2030 | USD 5M–15M | 6–7 |
| **04** · Missão de demo CLPS | 2030–2032 | USD 30M–80M | 8–9 |
| **05** · Produção comercial | 2032+ | Operacional | — |

## 📐 Tecnologias do site

- HTML5 + CSS3 (single file, ~520 KB)
- JavaScript vanilla (sem frameworks ou dependências externas)
- Animações via IntersectionObserver API
- Canvas API para campo estelar procedural no hero
- Imagens reais de espaço/Lua via Pexels CDN (licença livre comercial)
- Logo Astreon embarcada em base64 nas seções nav/footer
- Responsivo (desktop, tablet, mobile)
- Compatível com navegadores modernos (Chrome, Edge, Firefox, Safari)

## 📄 Licença

© 2026 Astreon. Todos os direitos reservados.

O código-fonte deste site é proprietário da Astreon. As imagens de fundo (Lua, Terra, espaço) são licenciadas pelo Pexels para uso comercial.

## ✉️ Contato

- **Email:** contact@astreon.space
- **Imprensa:** press@astreon.space
- **Localização:** São Paulo, Brasil

---

*Built for the next 100 years.*
