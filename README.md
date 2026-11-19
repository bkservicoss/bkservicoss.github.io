<p align="center"><img src="assets/logo_bk_completo.png" alt="BK Serviços, Produção &amp; Comunicação" width="360"></p>

<p align="center"><b>Site oficial da BK Serviços, Produção &amp; Comunicação: audiovisual, eventos, jornalismo e tecnologia desde 2009.</b><br>
Página única em HTML, CSS e JavaScript puros, publicada no GitHub Pages.</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-no%20ar-E47800" alt="Status: no ar">
  <img src="https://img.shields.io/badge/plataforma-GitHub%20Pages-1A1A1A" alt="Plataforma: GitHub Pages">
  <img src="https://img.shields.io/badge/linguagem-HTML%20%7C%20CSS%20%7C%20JS-A85400" alt="Linguagem: HTML, CSS e JS">
  <img src="https://img.shields.io/badge/uso-privado-F0A83C" alt="Uso privado">
</p>

---

## Sumário

1. [Visão geral](#visão-geral)
2. [Estado do projeto](#estado-do-projeto)
3. [Seções do site](#seções-do-site)
4. [Identidade visual](#identidade-visual)
5. [Como atualizar o conteúdo](#como-atualizar-o-conteúdo)
6. [Publicação](#publicação)
7. [Estrutura do repositório](#estrutura-do-repositório)
8. [Segurança](#segurança)
9. [Pendências](#pendências)

## Visão geral

| Item | Definição |
|---|---|
| Endereço | https://bkservicoss.github.io |
| Objetivo | Apresentar a BK, seus serviços, aplicativos, eventos e trajetória, e levar o visitante ao WhatsApp |
| Inspiração | Site do Moenda Café: montagem na rolagem, faixa em loop, contadores e chamadas constantes |
| Tecnologia | Um único `index.html`, sem dependências nem etapa de compilação |
| Contato principal | WhatsApp (27) 99807-5772, com mensagem pronta |

## Estado do projeto

| Parte | Estado |
|---|---|
| Página completa (hero até rodapé) | Pronta |
| Versão para celular | Pronta |
| Publicação no GitHub Pages | Automática a cada envio na `main` |
| Domínio próprio `.com.br` | Não configurado |

## Seções do site

| Seção | Conteúdo |
|---|---|
| Hero | "Sua história, bem contada." e um vídeo que se monta com a rolagem: roteiro, captação, edição e ao vivo |
| Faixa | Veículos e marcos em loop: Record News ES, BandNews FM ES, RedeTV ES, TV Faesa, Prêmio 2014 |
| De Biko a BK | História do nome e do fundador |
| Quatro frentes | Audiovisual, eventos e ao vivo, comunicação e jornalismo, tecnologia e ensino |
| Como funciona | Processo em quatro passos |
| Tecnologia | iLerta, dFAST, BK Storyworks e o app premiado da Semana de C&T |
| Números | Contadores animados |
| Eventos | Headscon XP 2026, Pokémon Arena 2026, Anime Dark e Semanas de C&T |
| Trajetória | Experiências e formação |
| Como contratar | Por etapa, projeto completo, aulas e treinamentos (sem preços) |
| Contato e rodapé | WhatsApp, e-mail, Instagram, LinkedIn e portfólio de vídeos |

## Identidade visual

Segue o **Manual e Análise de Marca da BK**.

| Elemento | Valor |
|---|---|
| Laranja BK | `#E47800`, destaques, botões e títulos grandes |
| Laranja Profundo | `#A85400`, títulos sobre fundo claro e hover |
| Âmbar | `#F0A83C`, realces sobre fundo escuro |
| Dourado BK | `#B09060`, detalhes finos |
| Grafite | `#1A1A1A`, textos e fundos escuros |
| Areia | `#F5F1EB`, fundo claro |
| Títulos | Montserrat ExtraBold Itálico (Google Fonts) |
| Textos | Inter (Google Fonts) |
| Logotipo | Símbolo no cabeçalho; logo completo no rodapé, com 300 px ou mais |

## Como atualizar o conteúdo

Tudo é editado pelo navegador, sem instalar nada:

1. Abra o repositório no GitHub e clique em `index.html`.
2. Clique no lápis (**Edit this file**).
3. Faça a mudança e clique em **Commit changes**. O site atualiza em 1 ou 2 minutos.

| O que mudar | Onde fica no `index.html` |
|---|---|
| Aplicativos | Lista `const apps = [...]` no fim do arquivo |
| Eventos | Lista `const eventos = [...]` |
| Trajetória | Lista `const traj = [...]` |
| Número e mensagem do WhatsApp | Linha `const zap = ...` |
| Textos das seções | No HTML de cada seção (`id="sobre"`, `id="servicos"`, etc.) |

## Publicação

- O GitHub Pages publica a branch `main`, pasta raiz.
- Para conferir: **Settings → Pages**. Em *Build and deployment*, a origem deve ser **Deploy from a branch**, com `main` e `/ (root)`.
- O arquivo `.nojekyll` faz o GitHub publicar os arquivos como estão.

## Estrutura do repositório

```
bkservicoss.github.io/
├── index.html                  Site completo (HTML, CSS e JS)
├── assets/
│   ├── logo_bk_completo.webp   Logo completo usado no rodapé
│   ├── logo_bk_completo.png    Logo usado neste README
│   └── simbolo_bk.webp         Símbolo BK do cabeçalho e ícone da aba
├── .nojekyll                   Publica sem processamento do Jekyll
├── .gitignore
├── CLAUDE.md                   Regras do projeto para o Claude
└── README.md
```

## Segurança

| Regra | Como é aplicada |
|---|---|
| Sem segredos no repositório | O site não usa chaves, tokens nem senhas |
| Dados pessoais | Só contatos profissionais; o endereço residencial não aparece |
| Links externos | Abrem em nova aba com `rel="noopener"` |

## Pendências

- [ ] Fichas dos trabalhos em vídeo (título, cliente, ano, link) para uma seção de vídeos
- [ ] Depoimentos reais de clientes
- [ ] Domínio próprio `.com.br` e e-mail com domínio
- [ ] Logotipo vetorial para a versão chapada do símbolo
- [ ] Incluir a BK nos cartazes dos próximos eventos com a Prisma Arena

---

<p align="center"><sub>Projeto privado · BK Serviços, Produção &amp; Comunicação</sub></p>
