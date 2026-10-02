Projeto Acadêmico: Portal da Biodiversidade e Ecossistemas

Este é um site estático desenvolvido exclusivamente em **HTML5**, focado em **estruturação semântica** e **práticas avançadas de acessibilidade web (WCAG e ARIA)** para garantir uma navegação fluida a pessoas com deficiência visual e utilizadores de leitores de tela.

---

## 📌 Sobre o Projeto

O objetivo deste trabalho é apresentar um portal informativo sobre **Biodiversidade e Ecossistemas** com conteúdo 100% autoral (reescrito para evitar plágio, com base em fontes de conhecimento livre da Wikipédia).

### Estrutura de Páginas do Site
* `index.html`: Página inicial com conceitos básicos de biodiversidade e serviços ecossistêmicos.
* `ecossistemas.html`: Detalhamento dos principais tipos de ecossistemas terrestres e aquáticos.
* `ameacas.html`: Principais fatores de degradação ambiental e perda de biodiversidade.
* `conservacao.html`: Ações, políticas públicas e práticas sustentáveis para preservação.

---

## ♿ Recursos de Acessibilidade Implementados

Para garantir a total inclusão e facilidade de leitura por tecnologias assistivas (leitores de tela como NVDA, JAWS e TalkBack), o projeto conta com:

1. **Atalho de Salto (`skip-link`)**: Link posicionado no início do código (`<a href="#conteudo-principal">`) para permitir que o utilizador salte o menu de navegação via teclado e vá direto ao conteúdo.
2. **Semântica HTML5 Nativa**: Uso rigoroso dos elementos `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>` e `<footer>`.
3. **Atributos e Rótulos ARIA**:
   - `lang="pt-BR"` no elemento `<html>` para voz e pronúncia corretas do leitor.
   - `role="banner"`, `role="contentinfo"` para identificação clara de regiões da página.
   - `aria-label` e `aria-labelledby` para nomear menus e seções de forma contextualizada.
   - `aria-current="page"` para indicar qual página está ativa no menu principal.
4. **Logótipo Acessível**: Imagem do logótipo no cabeçalho acompanhada do atributo `alt` descritivo.
5. **Navegação por Âncoras Internas**: Barra lateral à direita (`<aside>`) contendo links para os tópicos da própria página através de `id`s exclusivos.
6. **Estrutura de Títulos Hierárquica**: Organização lógica de cabeçalhos (`<h1>` para o título principal, `<h2>` para seções e `<h3>` para subseções).
