# 🟢 A PERVIE — Ecossistema Cultural Soberano

> **Plataforma decolonial, independente e tática de conexão, autonomia e circulação artística brasileira.**

---

## 📌 Visão Geral & Manifesto

A **Pervie** é uma plataforma e ecossistema digital *mobile-first* e *audio-first* projetada para libertar a produção cultural brasileira da dependência de redes centralizadas de Big Tech, algoritmos de engajamento forçado e extrativismo de dados.

Inspirada na lógica comunitária e na rede de confiança de plataformas históricas (como o Orkut), a Pervie prioriza a **reputação validada por pares**, a **comunicação direta soberana (Mandar Salve)** e o **consumo consciente de dados** (otimizado para redes móveis 3G/4G).

---

## 🎛️ Arquitetura de Salas, Recursos & Interação

### 🛰️ Salas Globais de Convergência
* **`[FREQ 01]` Encruzilhada:** Espaço de convergência e colabs. Pontes entre artistas, produtores, VJs e criadores independentes para cooperação justa.
* **`[FREQ 02]` O Corre:** Canal de viabilidade financeira. Mapeamento de editais ativos, chamadas públicas, leis de fomento e guias de gestão/MEI.
* **`[FREQ 03]` Memória Viva:** Acervo e pesquisa. Preservação de fanzines, ensaios decoloniais, registros históricos e saberes tradicionais sem pasteurização corporativa.
* **`[🔴 AO VIVO]` Sintonia Ao Vivo:** Rádio tática comunitária (*Audio-First* / WebRTC) com baixo consumo de dados e suporte a transmissões de VJ/lo-fi.

### 💬 Regra Tática de Interação e Comentários
* **Nas Transmissões:** O áudio, texto e mídias visuais são os protagonistas do post principal.
* **Nos Comentários:** Threads ágeis e leves baseadas em **Texto, Emojis e Figurinhas/Stickers Táticos**. Sem suporte a comentários em áudio ou vídeo para preservar a franquia de dados e evitar poluição sonora.

### 👤 Recursos Soberanos do Perfil do Artista
* **Cartão de Identidade Artística:** Nome, avatar, etiqueta de função (ex: *DJ / Produtora Sonora*), território/localização e minibio de até 500 caracteres.
* **Bastidores do Artista:** Laboratório pessoal e diário de bordo do perfil. Espaço livre para compartilhamento de áudios brutos (até 3 min), fotos, vídeos, links, beats, ensaios e rascunhos do processo criativo.
* **Álbum de Mídia (Portfólio Tático):** Galeria de destaque do artista com espaço para até 6 fotos em alta qualidade e até 3 vídeos curtos (drops de até 15 segundos em 1080p).
* **Mandar Salve:** Canal direto de contato (WhatsApp, Telegram, Signal, E-mail) sem intermediários algorítmicos.
* **Rede de Depoimentos:** Sistema de validação por pares e reputação comunitária (com aprovação prévia pelo perfil).
* **Pasta Privada "Salvos":** Espaço secreto para marcação e organização de oportunidades, contatos e referências.

---

## 📚 Matriz Teórica & Decolonial (12 Pesquisadores Brasileiros)

A Pervie foi desenhada sobre as bases conceituais de 12 intelectuais e pesquisadores brasileiros:

1. **Rita Von Hunty / Guy Debord:** Crítica à espetacularização e mercantilização da arte.
2. **Denise Ferreira da Silva:** Poética Negra e desconstrução da arquitetura colonial de valor.
3. **Rosana Paulino:** Preservação da memória visual e combate ao epistemocídio.
4. **Lúcia Santaella:** Comportamento do leitor ubíquo em redes de hipermídia.
5. **Giselle Beiguelman:** Resistência à pasteurização do design corporativo.
6. **Suely Rolnik:** Combate à cafetinagem da força de criação e do desejo.
7. **Helena Katz:** Teoria do Corpomídia — o impacto dos signos na biologia humana.
8. **Christine Greiner:** O corpo em crise diante da aceleração tecnológica e IA.
9. **Silvana Bahia:** Democratização tecnológica e inovação popular.
10. **Nina da Hora:** Pensamento computacional de base e soberania hacker.
11. **Joana Varon:** Tecnologias transfeministas e combate ao colonialismo de dados.
12. **Tarcízio Silva:** Justiça algorítmica, auditoria técnica e letramento de dados.

---

## 🎨 Identidade & Design System (Cybermano)

* **Dark Mode Tático:** Base em `#141210` (Background) e `#221E1B` (Containers).
* **Cor de Destaque:** Laranja Ácido Reativo (`#FF4500`).
* **Tipografia & Componentes:** Fontes monoespaçadas em caixas altas, etiquetas estilo Dymo táticas, bordas secas (`rounded-none` / `rounded-sm`).

---

## 🛠️ Stack Tecnológica

* **Frontend:** React, Tailwind CSS, Lucide Icons, Vite (desenvolvido via Lovable).
* **Backend & Banco de Dados:** Supabase (PostgreSQL).
* **Storage de Mídia:** Supabase Storage (`avatars`, `portfolio_media`, `audio_notes`).
* **Autenticação & Segurança:** Supabase Auth + RLS (*Row Level Security*).

---

## 🗄️ Estrutura do Banco de Dados (Supabase PostgreSQL)

* `profiles`: Cadastros de artistas, bio, etiquetas funcionais, mídias de portfólio e canal de preferência de contato.
* `posts`: Transmissões e publicações divididas por sala (`bastidores`, `encruzilhada`, `o_corre`, `memoria_viva`).
* `testimonials`: Depoimentos de reputação (sistema de aprovação prévia pelo perfil).
* `saved_posts`: Coleção privada de marcações (*bookmarks*) de cada artista.
* `comments`: Threads leves de comentários por texto, emojis e figurinhas.

---

## 🚀 Como Executar o Projeto Localmente

### Pré-requisitos
* Node.js (v18+)
* Conta ativa no Supabase

### Passo a Passo
1. Clone o repositório:
   ```bash
   git clone [https://github.com/seu-usuario/pervie.git](https://github.com/seu-usuario/pervie.git)
   cd pervie
