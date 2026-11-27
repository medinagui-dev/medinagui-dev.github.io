# 🌐 O meu site · Modelo da aula do AMS

Este é um **modelo de site** pronto para você copiar, colocar no ar e deixar com a sua cara.

O site é sobre **um interesse seu**: um hobby, um jogo, o seu time, uma banda ou o que você quer criar com tecnologia. Ele fica num endereço só seu:

```
https://<seu-usuario>.github.io
```

O site inteiro está num arquivo só, o **`index.html`**. Lá dentro tem três partes:

| Parte | O que é | Comparando com… |
|---|---|---|
| **HTML** | Os títulos, os textos e as listas | O **esqueleto** do site |
| **CSS** | As cores, as letras e os tamanhos | A **roupa** do site |
| **JavaScript** (o 🤖 robô, no fim) | Atualiza o site sozinho quando você muda alguma coisa, sem precisar de F5 | Os **músculos** do site (não precisa mexer) |

Cada pedaço do arquivo tem um comentário com ✏️ **TROQUE** explicando o que dá para mudar ali.

---

## 🔒 Regra de privacidade (leia antes de começar!)

O seu site é **público**: qualquer pessoa na internet pode ver. Por isso:

- ✅ **Pode:** falar do seu interesse e usar só o seu **primeiro nome** ou um **apelido** (e isso é opcional).
- ❌ **Não pode:** foto do seu rosto (nem de colegas), nome da escola, cidade, telefone, e-mail, endereço ou rede social.

---

## 🚀 Passo a passo: colocar o seu site no ar

> Você precisa estar **logado** no GitHub. Não tem conta? Crie em https://github.com/signup (é grátis).

**1. Faça a sua cópia do modelo**
Nesta página, clique no botão verde **Use this template** (em cima, à direita) e escolha **Create a new repository**.

**2. Dê o nome certo**
No campo **Repository name**, escreva o **seu nome de usuário** seguido de **`.github.io`**:

```
seu-usuario.github.io
```

Por exemplo: se o seu usuário é `astro123`, o nome fica `astro123.github.io`.
⚠️ Tem que ser **exatamente** o seu usuário, com o `.github.io` no final. Deixe marcado **Public** e clique em **Create repository**.

**3. Espere o site ficar pronto**
O GitHub Pages leva **cerca de 1 minuto** para colocar o site no ar. Enquanto isso, o mesmo tipo de robô do mural trabalha para publicar o seu site.

**4. Abra o seu site**
Entre em `https://seu-usuario.github.io` (trocando pelo seu usuário). Apareceu a página de astronomia? 🎉 O seu site está no ar! Agora é só deixar com a sua cara.

> **Não apareceu?** Espere mais um pouco e aperte **F5**. Se continuar com erro 404, vá em **Settings → Pages**, em *Branch* escolha **main** e clique em **Save**. Espere 1 minuto e tente de novo.
>
> **Já tinha um repositório `seu-usuario.github.io`?** Dê outro nome ao novo (ex.: `meu-site`) e ligue o Pages em **Settings → Pages**, como acima. O seu site vai ficar em `https://seu-usuario.github.io/meu-site`.

---

## ✏️ Deixar o site com a sua cara

1. No **laboratório** (o instrutor passa o link na aula), troque os textos e as cores e veja o resultado na hora.
2. Clique em **Copiar código**.
3. Aqui no GitHub, no **seu** repositório, clique no arquivo **`index.html`** e depois no **lápis** ✏️ (*Edit this file*).
4. Apague tudo o que tem lá (**Ctrl + A** e depois **Delete**) e cole o seu código (**Ctrl + V**).
5. Clique em **Commit changes** e de novo em **Commit changes** na janelinha. Isso é um **commit**: salvar uma mudança, como salvar o jogo.
6. Espere cerca de 1 minuto e recarregue o seu site.

> **Quebrou alguma coisa?** Tudo bem! Todo commit fica guardado no histórico. Volte ao laboratório, clique em **Voltar ao modelo** e cole de novo.

---

## 🏆 Desafios

Fez o básico? Tente os desafios, um nível de cada vez.

### 🥉 Bronze: cores e letras
No CSS (dentro de `<style>`), troque:
- a cor de fundo da página (`background` do `body`);
- a cor do título (`color` do `h1`);
- o tipo de letra (`font-family`). Experimente `Georgia`, `"Courier New"` ou `"Comic Sans MS"`.

### 🥈 Prata: mais uma parte no site
No HTML, crie mais uma seção, com subtítulo, texto e lista:

```html
<p class="subtitulo">Meus favoritos</p>
<ul>
  <li>⭐ O primeiro favorito</li>
  <li>⭐ O segundo favorito</li>
</ul>
```

Cole dentro do `<main>`, antes do rodapé.

### 🥇 Ouro: link ou animação
**Um link** para um site sobre o seu interesse:

```html
<p>Quer saber mais? <a href="https://pt.wikipedia.org/wiki/Astronomia">Veja na Wikipédia</a></p>
```

O que fica em `href="..."` é o endereço. O texto entre `<a ...>` e `</a>` é o que aparece para clicar.

**Uma animação** para o emoji ficar pulando. Cole no fim do CSS, logo antes de `</style>`:

```css
.emoji {
  animation: pular 2s infinite;
}

@keyframes pular {
  50% { transform: translateY(-15px); }
}
```

`pular` é o nome da animação, `2s` é quanto tempo leva cada pulo e `infinite` faz repetir para sempre.

> 🖼️ **Imagens:** se quiser pôr uma imagem, use só o **link** de uma imagem livre (de um site como a Wikipédia). **Nunca** foto de pessoas, nem a sua nem a de colegas.

---

Aula ministrada por Guilherme Medina (Thompson Tecnologia) para a turma do AMS · Centro Paula Souza, em 27/11/2026.
