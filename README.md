## Planner Pessoal e Financeiro

### Compartilhar com quem usa celular (iOS ou Android)

**Não mande o arquivo .html** — no celular abrir arquivo não funciona direito e os dados não salvam.

**Mande este link.** A pessoa só abre no Safari (iPhone) ou no Chrome (Android). Ninguém precisa saber o que é GitHub.

**Link para copiar e enviar (WhatsApp, mensagem, e-mail):**

```
https://thomazte.github.io/planner/Planner_Pessoal_Financeiro.html
```

Quem receber: abre o link no navegador do celular → se quiser, toca em **Compartilhar** → **Adicionar à Tela de Início** e o planner vira um ícone na tela, como um app. O layout se adapta à tela (notch, Dynamic Island e bordas) em iPhone e Android.

---

### Link para abrir o planner (GitHub Pages)

Use este link no navegador ou no celular (não use o link do repositório):

**[https://thomazte.github.io/planner/Planner_Pessoal_Financeiro.html](https://thomazte.github.io/planner/Planner_Pessoal_Financeiro.html)**

| Link | O que é |
|------|---------|
| `github.com/thomazte/planner` | Página do repositório (código). Não abre o app. |
| `thomazte.github.io/planner/...` | Página publicada. Este abre o planner. |

No celular: abra o **Safari** (iPhone) ou **Chrome** (Android), cole o link na barra de endereço. Depois: Compartilhar → Adicionar à Tela de Início.

---

### Como rodar no computador

Abra o arquivo `Planner_Pessoal_Financeiro.html` no navegador (Chrome, Edge ou Firefox) — duplo clique ou arraste o arquivo para a janela do navegador.

### Por que no celular não abre ao clicar no arquivo?

No iPhone/Android, tocar no `.html` no app Arquivos não abre no navegador como página normal, e páginas em `file://` costumam não salvar dados (LocalStorage). Por isso use o link do GitHub Pages acima.

### Publicar no GitHub Pages (para usar no celular)

1. Crie um repositório no GitHub e suba a pasta do projeto (`.html` e `manifest.json`).
2. No repositório: **Settings** → **Pages** → Source: **Deploy from a branch** → branch **main**, pasta **/(root)** → Save.
3. O endereço será: `https://seu-usuario.github.io/nome-do-repo/Planner_Pessoal_Financeiro.html`

---

### Como usar o planner

- Selecione **mês** e **ano** no topo.
- Em **Ganhos** e **Gastos**, preencha e clique em **Adicionar**.
- O topo mostra totais, % gasto dos ganhos e **saldo do mês**.
- **Gastos por grupo**: distribuição dos gastos.
- **Objetivo pessoal (meta)**: valor e prazo em meses; o planner mostra quanto juntar por mês e compara com o saldo.
- **Campo pessoal**: texto livre (não entra nos cálculos).

### Backup

- **Exportar JSON**: baixa um arquivo com todos os dados.
- **Importar JSON**: restaura em outro navegador ou celular.

### Reset

- **Limpar mês**: apaga só os lançamentos do mês selecionado.
- **Resetar tudo**: apaga todos os dados neste navegador.
