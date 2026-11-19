# CLAUDE.md: site da BK Serviços

Site oficial da BK Serviços, Produção & Comunicação, publicado em https://bkservicoss.github.io pelo GitHub Pages (branch `main`, pasta raiz).

## Como o dono trabalha
- **Não instala nada no computador.** Edições pelo navegador no GitHub ou por aqui; o Pages publica sozinho.
- Fala português do Brasil. Textos do site, README e commits em português.
- Dono: Paulo Victor Leite, jornalista e analista de sistemas.

## Mapa
- `index.html`: o site inteiro (HTML, CSS e JS num arquivo só, sem dependências nem build).
- `assets/simbolo_bk.webp`: símbolo do cabeçalho e ícone da aba.
- `assets/logo_bk_completo.webp`: logo completo do rodapé; `.png` só para o README.
- `.nojekyll`: publica os arquivos como estão.

## Conteúdo editável (no fim do `index.html`)
- `const apps`: aplicativos da seção Tecnologia.
- `const eventos`: eventos organizados (o item com `prox:true` fica em destaque).
- `const zap`: número e mensagem pronta do WhatsApp (27) 99807-5772.

## Marca (Manual e Análise de Marca da BK)
- Cores: Laranja BK `#E47800`, Laranja Profundo `#A85400`, Âmbar `#F0A83C`, Dourado `#B09060`, Grafite `#1A1A1A`, Areia `#F5F1EB`, Branco. Proporção aproximada 60% claros, 25% grafite, 15% laranja.
- Laranja BK como texto só em títulos grandes (24 px ou mais); sobre fundo claro use Laranja Profundo. Dourado nunca em texto pequeno.
- Fontes: Montserrat ExtraBold Itálico nos títulos, Inter no texto.
- Logotipo: não esticar, não recolorir, não colocar o nome escrito em outra fonte ao lado do símbolo. Logo completo com 300 px ou mais.
- Nome sempre na ordem "BK Serviços, Produção & Comunicação".
- Tom de voz: de bom repórter, direto e próximo, "a gente" e "você", sem excesso de exclamação ou emoji. Mensagens-chave: "Sua história, bem contada.", "Do roteiro à edição, um só responsável.", "Padrão de TV, velocidade de rede social."

## Regras
- Inspiração de layout: site do Moenda Café (montagem na rolagem, faixa em loop, contadores, chamadas constantes para o WhatsApp).
- Tom institucional e profissional: sem história pessoal, trajetória individual, LinkedIn pessoal ou endereço. Atendimento: "Grande Vitória/ES, presencial e remoto".
- Não inventar depoimentos, clientes ou números. Fatos vêm do manual, do currículo e do portfólio do dono.
- Nunca guardar segredos, tokens ou senhas no repositório.
- Respeitar `prefers-reduced-motion` e testar em 390 px de largura.

## README
- Manter o padrão BK (logo, selos, Sumário, tabelas, estrutura, pendências, rodapé) e atualizar a cada mudança no site.

## Repositórios novos
- Sempre que o dono criar um repositório novo, perguntar se ele quer criar o `CLAUDE.md` e se os sites do projeto entram no BK Serviços HUB.
