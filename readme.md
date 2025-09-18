# 📝 Atividade Prática 03
#  Atualização de Alunos no Frontend

## Objetivo

Implementar a função `atualizarAluno(id)` no frontend para permitir **editar os dados dos alunos** de forma interativa, consumindo a API já existente (`Node.js + Express + MongoDB`).

O foco é praticar **fetch API, manipulação do DOM e integração com backend**.

---

## Repositório base

Os arquivos já disponíveis estão no repositório:

```
aula_06_pi2_2025/
├─ index.html
├─ style.css
├─ script.js
```

* Clonar o repositório:

```bash
git clone https://github.com/seu-usuario/aula_06_pi2_2025.git
cd aula_06_pi2_2025
```

---

## Instruções

1. **Entender o código existente**

   * `carregarAlunos()` → lista os alunos da API.
   * `deletarAluno(id)` → apaga um registro.
   * `form.addEventListener("submit")` → cria novo aluno.

2. **Implementar `atualizarAluno(id)`**

   * A função deve permitir **editar o nome, idade e curso** do aluno selecionado.
   * Pode ser feito:

     * **Inline** (inputs aparecem no lugar do item da lista) **ou**
     * **Usando um formulário de edição** que preenche os campos existentes.

3. **Enviar atualização para o backend**

   * Usar `fetch` com método `PUT` (ou `PATCH`) para `API_URL/id`.
   * Enviar os campos atualizados como JSON.
   * Atualizar a lista de alunos após a edição.

4. **Atualizar HTML/CSS se necessário**

   * Pode adicionar classes, inputs ou botões no `index.html`.
   * Ajustar o estilo no `style.css` para que a edição fique clara e funcional.

5. **Testar**

   * Criar um novo aluno.
   * Editar o aluno usando a função implementada.
   * Verificar se as alterações aparecem na lista e no banco de dados.

---

## Entregável

* **Link do repositório no GitHub** com o código atualizado, incluindo:

  * `script.js` com a função `atualizarAluno(id)` implementada.
  * Eventuais alterações no `index.html` e `style.css`.
  * Certifique-se de que o projeto **funciona localmente** antes de enviar.

---

## Dicas

* Para edição inline, pode usar `prompt()` para facilitar ou criar inputs dinamicamente.
* Lembre-se de chamar `carregarAlunos()` após o PUT/PATCH para atualizar a lista.
* Teste cada passo antes de prosseguir.

