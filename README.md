# Verdouro Barbearia (demo)

- **Cliente:** Verdouro Barbearia (fictício)
- **Entidade:** tche-sites
- **Stack:** html-css-js
- **Status:** ativo
- **Repo:** https://github.com/tchesites/demo-verdouro-barbearia
- **Deploy:** https://tchesites.github.io/demo-verdouro-barbearia/
- **Como rodar:** Abra `index.html` no navegador ou rode `npx serve` na pasta do projeto.

## Sobre

Site demonstrativo de barbearia, em Curitiba/PR. Página única com as seções Hero, Sobre, O Ambiente, Serviços, Planos, Localização e Footer. O agendamento é feito pelo WhatsApp.

> **Projeto demonstrativo:** marca, logo, textos, endereço, telefone, redes e fotos são fictícios ou ilustrativos. Nenhum dado real de cliente é utilizado.

## Estrutura

- `index.html` — página única
- `css\styles.css` — tokens, layout, componentes e responsividade
- `js\script.js` — menu mobile, header com scroll e scroll reveal
- `assets\logo-verdouro.svg` — logo fictício da marca (emblema circular + navalha)
- `assets\logo-verdouro.png` — versão rasterizada do logo para o header/footer
- `assets\favicon.svg` — favicon da marca
- `assets\sobre-verdouro.jpg` — retrato ilustrativo do barbeiro
- `assets\ambiente-1.jpg`, `ambiente-2.jpg`, `ambiente-3.jpg` — fotos ilustrativas do ambiente

Fotos de banco de imagens (Pexels): #8552627, #20785318, #7518739 e #7518689.

## Dados fictícios

- **Endereço:** Rua Presidente Faria, 128 — Centro, Curitiba/PR — 80000-000
- **Horário:** Terça a Sábado, 09h às 20h
- **WhatsApp:** (41) 90000-0000
- **Agendamento:** https://wa.me/5541900000000
- **Instagram:** @verdouro.barbearia
- **Agência:** https://tchesites.com.br (crédito no rodapé)

## Troca de logo

O logo da demo é próprio da Verdouro e fica em três arquivos:

- `assets\logo-verdouro.svg` — fonte vetorial (nome, emblema e subtítulo).
- `assets\logo-verdouro.png` — versão rasterizada usada no header e no footer.
- `assets\favicon.svg` — ícone da aba.

Para reaproveitar este modelo em outro demo:

1. Edite o SVG com o novo nome e símbolo, mantendo o mesmo espírito premium.
2. Gere o PNG a partir do SVG, com fundo transparente, e substitua `logo-verdouro.png`.
3. Atualize o `favicon.svg` e os textos alternativos das imagens.
4. Troque também os dados fictícios e as fotos ilustrativas.

O logo atual é intencionalmente parecido em linguagem (emblema circular + tipografia serifada + "BARBEARIA"), mas usa nome e símbolo próprios, para não identificar a marca original.

## Decisões

- **HTML/CSS/JS puro** — sem build, para facilitar manutenção e personalização.
- **Paleta verde/dourado/creme** — transmite exclusividade e sofisticação.
- **Agendamento via WhatsApp** — no demo, todos os CTAs principais apontam para o número fictício.
- **7 serviços** — corte masculino, design de barba, depilação com cera, hidratação, selagem e progressiva, camuflagem e limpeza de pele.
- **Planos Prata e Ouro** — Prata com acesso de terça a quinta; Ouro de terça a sábado.
- **Identidade fictícia** — logo próprio (Verdouro), com o mesmo espírito premium do modelo, mas sem reutilizar nome, símbolo ou materiais da marca original.
- **Crédito da agência** — rodapé com link para o site do Tchê Sites, como projeto demonstrativo.

## Deploy

Publicado no **GitHub Pages** em https://tchesites.github.io/demo-verdouro-barbearia/.

- O deploy é feito pelo workflow `.github/workflows/deploy.yml` a cada push na `main`.
- O workflow copia o site estático para `_site` e publica com as actions oficiais do Pages.
- **Primeira configuração:** em **Settings → Pages → Source**, selecione **GitHub Actions**. O token do Actions não tem permissão de administração na organização para criar o site do Pages sozinho; por isso essa habilitação inicial é manual.
- Para rodar manualmente: aba **Actions** → **Deploy no GitHub Pages** → **Run workflow**.
