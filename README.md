# Cakes JL Confeitaria — Página de Links

Página estilo "link na bio" (tipo Linktree), em HTML/CSS puro, hospedada de graça no GitHub Pages. Sem propaganda.

---

## 📁 Arquivos do projeto
- `index.html` — a página (arquivo único, sem dependências)
- `logo.png` — a logo da confeitaria
- `README.md` — este guia

---

## 🔘 Ordem dos botões (de cima pra baixo)
1. **Reserva 4º Festival de Fatias** → WhatsApp (mensagem já preenchida sobre as fatias) — botão em destaque com etiqueta "Por tempo limitado".
2. **Cardápio - Encomendas** → cardápio no Google Drive.
3. **Faça seu pedido aqui** → WhatsApp (mensagem já preenchida sobre encomenda de tortas).

---

## ✏️ Como editar os links
Abra o `index.html` em qualquer editor de texto e procure pelos comentários `<!-- BOTÃO 1 -->`, `<!-- BOTÃO 2 -->`, `<!-- BOTÃO 3 -->`.

**WhatsApp:** o número está no formato `wa.me/55` + DDD + número.
Exemplo: `(48) 99999-8888` vira `wa.me/5548999998888`.
Para mudar a mensagem automática, edite o texto depois de `?text=`.

**Instagram / TikTok:** procure pelos endereços `instagram.com/...` e `tiktok.com/...`.

---

## 🎪 Quando o Festival acabar (esconder o botão)
No `index.html`, ache o bloco marcado como `BOTÃO 1: FESTIVAL DE FATIAS`.
Para esconder, apague todo o trecho de `<a class="link-button featured" ...>` até o `</a>` correspondente.
Quando voltar a ter festival, é só colar o trecho de volta. (Dica: guarde uma cópia desse bloco num bloco de notas pra reusar.)

---

## 🌙 Modo claro / escuro
A página tem um botão sol/lua no canto superior direito. Ao clicar, alterna entre os dois temas.

A página **sempre abre no modo claro** por padrão. Se a pessoa preferir o escuro, basta clicar no botão — e essa escolha fica salva no navegador (via `localStorage`), então da próxima vez que ela visitar, abre direto no tema que escolheu.

---

## 🚀 Publicar no GitHub Pages (resumo)
1. Crie um repositório **público** em github.com.
2. **Add file → Upload files** e suba `index.html`, `logo.png` e `README.md`. Commit.
3. **Settings → Pages → Source: Deploy from a branch → Branch: main → /(root) → Save**.
4. Em ~1 min sua página estará em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.
5. Coloque esse link na bio do Instagram/TikTok no lugar do Linktree.

Para atualizar depois: abra o arquivo no GitHub, clique no lápis ✏️, edite e **Commit changes**.

---

## 🎨 Cores
No topo do `<style>`, a seção `:root` tem todas as cores em variáveis (paleta rosé/rose gold da logo). Mude ali e a página inteira acompanha.

---

## ❓ Dúvidas rápidas
- **Tem propaganda?** Não. GitHub Pages não insere anúncios.
- **É grátis pra sempre?** Sim, para repositórios públicos (até 100 GB de tráfego/mês).
- **Funciona no celular, tablet e PC?** Sim, é responsiva.
