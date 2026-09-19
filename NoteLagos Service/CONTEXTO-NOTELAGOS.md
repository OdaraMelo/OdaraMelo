# CONTEXTO NOTELAGOS SERVICE — para produzir as artes e finalizar o site (WSL)

> Bloco de handoff autossuficiente. Cole numa sessão do Claude no WSL. Tem tudo pra fazer
> as artes e encaixar as fotos reais no site, sem depender de outra conversa.

## 1. Negócio
- **Marca:** NoteLagos Service · @notelagosservice · notelagosservice@gmail.com
- **Dono:** Fabio **Lobo** (sobrenome Lobo → identidade do lobo). Ama o azul da marca.
- **Nicho:** **microeletrônica** e reparo de **placa-mãe** de Notebook, MacBook e **placa de vídeo** (PC Gamer). Também: projetores, reparo de carcaça com resina, teclado, SSD/RAM, Windows/macOS.
- **Praça:** Cabo Frio - RJ. **Experiência desde 1998 (no Rio); em Cabo Frio desde 2021.**
- **Prova:** Google 5,0 · 84 avaliações · perfil verificado (categoria "Serviço de informática").
- **Contato:** WhatsApp (22) 99238-5666. Atendimento e diagnóstico **presenciais**; a IA do Meta Business responde no WhatsApp.

## 2. Identidade visual
- **Logo:** lobo estilizado formado por trilhas de circuito, em **azul-elétrico/cyan neon** sobre preto; wordmark "NOTE LAGOS SERVICE" em fonte techno quadrada.
- **Paleta:**
  - Preto fundo `#04070A` (quase puro)
  - Cyan neon (acento) `#2EC6F6` · brilho `#63DBFF`
  - Azul `#1E86D6`
  - Branco gelo (texto) `#EAF6FA`
  - Verde LED "online" `#37D39A`
- **Fontes:** títulos **Chakra Petch**; texto **IBM Plex Sans**; rótulos/código **IBM Plex Mono**.
- **Vibe:** tecnológica, forte, neon, masculina. Referência do estilo do Fabio (não obrigatório nas peças): tatuagem oriental + traço old school (bordas grossas).

## 3. Artes a produzir
1. **Logo em HD / vetor**, **fundo transparente (PNG)** — a versão mais recente (circuito em fluxo) está com baixa definição. Preservar o lobo de circuito + wordmark.
2. **Variante conceito "olho vermelho"** — só para mostrar ao Fabio: olhos do lobo em vermelho neon, resto idêntico. Não substitui a azul (é alternativa a avaliar).
3. **Capas de destaque do Instagram** (padrão do perfil): fundo preto + ícone em linha cyan + rótulo curto. Temas: `Placa-mãe` · `MacBook` · `PC Gamer / Placa de vídeo` · `Antes/Depois` · `Garantia` · `Localização` · `Depoimentos`. Estilo consistente entre todas.
4. (Opcional) Moldura de story + assinatura de post na mesma identidade.

**Specs:** alta resolução; transparência onde indicado; manter proporção; cyan neon como cor de acento; preto como base.

## 4. Fotos para o site (Instagram só tem vídeo → tirar frame/print)
Bons frames a usar como imagens reais:
- Bancada com **microscópio trinocular** + monitores azuis (a "cara" do laboratório)
- **Fabio no microscópio** (braço tatuado) — humaniza
- **Placa de vídeo** (GeForce/ASUS) na bancada
- Notebook aberto / placa-mãe em reparo
- Praia de Cabo Frio (para a seção de localização)

No site (`site-notelagos-v1.html`), trocar o visual do herói/placeholders por esses frames reais, mantendo o ajuste da logo (fusão de cor / `mix-blend-mode: screen` para o preto sumir).

## 5. Copy e claims APROVADOS (não inventar fora disto)
- "Microeletrônica de placa-mãe" · "Notebook · MacBook · placa de vídeo"
- "Cabo Frio" · "Experiência desde 1998 · em Cabo Frio desde 2021"
- "5,0 · 84 avaliações no Google" · "Garantia de 90 dias"
- WhatsApp (22) 99238-5666 · @notelagosservice

**NÃO usar:** agendamento online; orçamento remoto; a palavra "console" no destaque; "microssoldagem" como guarda-chuva (usar **microeletrônica**); "Cabo Frio desde 1998" (é desde 2021).

## 6. Onde está tudo
- Repo: `OdaraMelo/OdaraMelo`, pasta **`NoteLagos Service/`**
  - `site-notelagos-v1.html` — site (V2)
  - `previa-presenca-digital.html` — prévia diagnóstica
  - `guia-presenca-digital-modo-solo.html` — guia de execução solo
  - `base-conhecimento-notelagos.md` — base consolidada
  - `CONTEXTO-NOTELAGOS.md` — este arquivo
