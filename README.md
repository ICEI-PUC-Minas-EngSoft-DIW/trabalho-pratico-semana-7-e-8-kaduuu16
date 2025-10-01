# Trabalho Prático 05 - Semanas 7 e 8

**Páginas de detalhes dinâmicas**

Nessa etapa, vamos evoluir o trabalho anterior, acrescentando a página de detalhes, conforme o  projeto escolhido. Imagine que a página principal (home-page) mostre um visão dos vários itens que existem no seu site. Ao clicar em um item, você é direcionado pra a página de detalhes. A página de detalhe vai mostrar todas as informações sobre o item do seu projeto. seja esse item uma notícia, filme, receita, lugar turístico ou evento.

Leia o enunciado completo no Canvas. 

**IMPORTANTE:** Assim como informado anteriormente, capriche na etapa pois você vai precisar dessa parte para as próximas semanas. 

**IMPORTANTE:** Você deve trabalhar e alterar apenas arquivos dentro da pasta **`public`,** mantendo os arquivos **`index.html`**, **`styles.css`** e **`app.js`** com estes nomes, conforme enunciado. Deixe todos os demais arquivos e pastas desse repositório inalterados. **PRESTE MUITA ATENÇÃO NISSO.**

## Informações Gerais

- Nome: Carlos Eduardo Farias de Oliveira
- Matricula: 1562374
- Proposta de projeto escolhida: Gerenciamento de artista e informações.
- Breve descrição sobre seu projeto: Trazer informações de artistas renomados.

## Print da Home-Page

![Captura de tela_1-10-2025_203413_127 0 0 1](https://github.com/user-attachments/assets/99ea2e48-8b4f-4261-908e-fc885f9b7113)


## Print da página de detalhes do item

![Captura de tela_1-10-2025_20353_127 0 0 1](https://github.com/user-attachments/assets/bfcd1871-cfad-493e-9c0b-1b10ab5f8093)


## Cole aqui abaixo a estrutura JSON utilizada no app.js

```javascript
const artistas = [
  {
    id: 1,
    nome: "Anitta",
    genero: "Pop/Funk",
    imagem: "https://jpimg.com.br/uploads/2025/07/sem-titulo-27-677x450.png",
    bio: "Anitta é uma cantora, compositora, atriz e empresária brasileira, conhecida mundialmente por seus hits de funk e pop.",
    discografia: ["Bang (2015)", "Kisses (2019)", "Versions of Me (2022)"],
    redes: {
      instagram: "https://instagram.com/anitta",
      spotify: "https://open.spotify.com/artist/7FNnA9vBm6EKceENgCGRMb"
    }
  },
  {
    id: 2,
    nome: "Emicida",
    genero: "Rap/Hip-Hop",
    imagem: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTMkGc-WMWit8LX-G-19KbtajEch4pOBzEq-w&s",
    bio: "Emicida é um rapper, cantor e compositor brasileiro, referência no rap nacional e premiado internacionalmente.",
    discografia: ["O Glorioso Retorno de Quem Nunca Esteve Aqui (2013)", "AmarElo (2019)"],
    redes: {
      instagram: "https://instagram.com/emicida",
      spotify: "https://open.spotify.com/artist/5rHbUjpWsdwj7SUSbGua3t"
    }
  },
  {
    id: 3,
    nome: "Ivete Sangalo",
    genero: "Axé/Pop",
    imagem: "https://assets.portalleodias.com/2024/04/ErIuVRnN-Design-sem-nome-3-615x461.png",
    bio: "Ivete Sangalo é uma das maiores cantoras brasileiras, conhecida pelo carisma e energia em seus shows.",
    discografia: ["Festa (2001)", "Real Fantasia (2012)", "Live Experience (2019)"],
    redes: {
      instagram: "https://instagram.com/ivetesangalo",
      spotify: "https://open.spotify.com/artist/7jrmNG2M1n3mZx8twxokHa"
    }
  }
];
```
