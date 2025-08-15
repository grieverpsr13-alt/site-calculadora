# Calculadora de Juros Compostos - Deploy no GitHub Pages

## Estrutura do projeto
- `index.html` → HTML final com iframe do app Streamlit e anúncios
- `README.md` → instruções de deploy

## Passos para colocar no ar
1. Crie um repositório no GitHub.
2. Envie os arquivos `index.html` e `README.md` para o repositório.
3. No GitHub, vá em **Settings > Pages**.
4. Em **Source**, selecione a branch (`main` ou `gh-pages`) e a pasta (`/` ou `/docs`) onde está o `index.html`.
5. Salve e aguarde alguns minutos.
6. O GitHub Pages vai gerar um link público:  
   `https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO/`
7. Configure seu domínio próprio (opcional):
   - Crie um arquivo `CNAME` com seu domínio na raiz do repositório.
   - Aponte os registros DNS (CNAME ou A record) para o GitHub Pages.

## Observações
- Substitua os placeholders do AdSense antes do deploy.
- Teste em desktop e mobile para confirmar responsividade.
- A unidade flutuante é opcional e pode ser removida se não quiser.
