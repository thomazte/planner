## Planner Pessoal e Financeiro (local)

### Rodar no Android e no iOS
O planner é uma página web: funciona em **qualquer navegador**. Para usar no celular (Android ou iPhone), ele precisa estar numa **URL na internet** (não abrir o arquivo direto do aparelho), assim os dados são salvos corretamente.

**Passo a passo (vale para Android e iOS):**

1. **Subir o projeto na web**  
   - Crie uma conta no [GitHub](https://github.com) (grátis).  
   - Crie um repositório (ex.: `planner-pessoal-financeiro`).  
   - Envie **toda a pasta** do projeto (incluindo `Planner_Pessoal_Financeiro.html` e `manifest.json`) para o repositório.  
   - Ative o **GitHub Pages**: **Settings** → **Pages** → Source: **main** → Save.  
   - Anote o endereço, algo como:  
     `https://seu-usuario.github.io/planner-pessoal-financeiro/Planner_Pessoal_Financeiro.html`

2. **No Android**  
   - Abra o **Chrome**, cole o endereço e acesse.  
   - Toque nos **três pontinhos** (⋮) → **Adicionar à tela inicial** (ou **Instalar app**).  
   - O planner aparecerá como um ícone na tela inicial e abrirá em tela cheia, como app.

3. **No iPhone (iOS)**  
   - Abra o **Safari**, cole o endereço e acesse.  
   - Toque no ícone **Compartilhar** (quadrado com seta) → **Adicionar à Tela de Início**.  
   - O planner aparecerá como um ícone na tela inicial e abrirá em tela cheia.

**Importante:** Se você abrir o arquivo `.html` direto do app Arquivos ou por um link de arquivo local, os dados podem não ser salvos entre uma abertura e outra. Por isso use sempre o endereço da web (GitHub Pages ou outro servidor).

### Como usar
- Abra o arquivo `Planner_Pessoal_Financeiro.html` no seu navegador (Chrome/Edge).
- Selecione **mês** e **ano** no topo.
- Em **Ganhos** e **Gastos**, preencha e clique em **Adicionar**.
- O topo mostra:
  - **Ganhos (total)**, **Gastos (total)**
  - **% gasto dos ganhos**
  - **Saldo do mês**
- Em **Gastos por grupo**, você vê a distribuição por grupos.
- Em **Objetivo pessoal (meta)**, informe:
  - **Valor do objetivo**
  - **Prazo (meses)**
  - Ele calcula **quanto juntar por mês** e compara com seu **saldo do mês**.
- Em **Campo pessoal**, você pode escrever livremente (não entra nos cálculos).

### Usar no iPhone (Safari)
Para usar no celular, o planner precisa ser aberto por uma **URL na internet** (não abrindo o arquivo direto do app Arquivos). Assim os dados são salvos corretamente.

**Opção 1 – Deixar na web (recomendado)**  
1. Crie uma conta no [GitHub](https://github.com) (grátis).  
2. Crie um repositório novo (por exemplo: `meu-planner`).  
3. Envie o arquivo `Planner_Pessoal_Financeiro.html` para o repositório (pode arrastar o arquivo na interface do GitHub).  
4. Ative o GitHub Pages: em **Settings** → **Pages** → Source: **main** → Save.  
5. Anote o endereço que aparecer (tipo `https://seu-usuario.github.io/meu-planner/Planner_Pessoal_Financeiro.html`).  
6. No iPhone, abra o **Safari**, cole esse endereço e acesse.  
7. Toque no ícone de **Compartilhar** (quadrado com seta) → **Adicionar à Tela de Início**.  
8. Pronto: o planner vira um “app” na tela inicial. Os dados ficam salvos no Safari desse endereço.

**Opção 2 – Servidor na sua rede (PC/Mac ligado na mesma Wi‑Fi)**  
1. No computador, coloque o arquivo `.html` numa pasta e suba um servidor HTTP nessa pasta (por exemplo com Python: `python -m http.server 8080` ou com Node/outra ferramenta).  
2. Anote o IP do computador (ex.: 192.168.1.10) e a porta (ex.: 8080).  
3. No iPhone, no Safari, abra `http://192.168.1.10:8080/Planner_Pessoal_Financeiro.html`.  
4. Adicione à tela inicial pelo **Compartilhar** → **Adicionar à Tela de Início**.  
5. Enquanto o PC estiver ligado e o servidor rodando, o planner no celular funciona e salva os dados.

**Importante:** Se você abrir o arquivo direto do app **Arquivos** ou do iCloud (link do arquivo), o Safari pode não salvar os dados entre uma abertura e outra. Por isso o ideal é usar uma das opções acima.

### Usar no computador
Abra o arquivo `Planner_Pessoal_Financeiro.html` no navegador (Chrome, Edge, Firefox). Tudo funciona igual; os dados ficam salvos no navegador.

### Backup (recomendado)
Este planner salva dados no navegador (LocalStorage). Para não perder:
- Clique em **Exportar JSON** para salvar um arquivo com tudo.
- Para restaurar em outro computador/navegador, use **Importar JSON**.

### Reset
- **Limpar mês** apaga apenas os lançamentos do mês selecionado.
- **Resetar tudo** apaga todos os dados do planner neste navegador.

