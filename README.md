# Clube do Botox Bayma — Landing Page Premium

Landing page premium e exclusiva para o **Clube do Botox** da **Dra. Renata Bayma (Harmonização Facial)**.

## Como Executar Localmente (Local Hosting)

Você pode rodar um servidor local no seu computador de forma muito simples usando o terminal.

1. Abra o **Terminal** no seu Mac.
2. Navegue até a pasta do projeto (ou abra o terminal diretamente nesta pasta).
3. Execute o comando para iniciar o servidor embutido do Python:
   ```bash
   python3 -m http.server 8000
   ```
4. Abra o seu navegador de internet (Chrome, Safari, etc.) e acesse:
   [http://localhost:8000](http://localhost:8000)

## Como Hospedar no GitHub Pages (Online)

Para colocar o site no ar gratuitamente usando o GitHub Pages, siga estes passos:

1. **Crie um repositório no seu GitHub** (ex: `clube-do-botox-bayma`).
2. **Inicialize o Git localmente** e envie os arquivos para o repositório criado:
   ```bash
   git init
   git add .
   git commit -m "feat: landing page premium clube do botox"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
   git push -u origin main
   ```
3. **Ative o GitHub Pages**:
   - Vá nas configurações do seu repositório no site do GitHub (**Settings**).
   - No menu lateral esquerdo, clique em **Pages**.
   - Em **Build and deployment**, selecione a branch `main` e a pasta `/ (root)`.
   - Clique em **Save**.
   - Em poucos minutos, o GitHub fornecerá um link público para o seu site (ex: `https://seu-usuario.github.io/seu-repositorio/`).
