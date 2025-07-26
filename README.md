✅ 🚀 COLA DO GIT — COMANDOS ESSENCIAIS
🟢 1️⃣ Ver o que mudou
bash

git status
🟢 2️⃣ Adicionar tudo que mudou
bash

git add .
O . significa “todos os arquivos modificados”.

🟢 3️⃣ Fazer o commit com mensagem
bash

git commit -m "Descrição clara do que mudou"
Exemplo:

bash

git commit -m "Atualizei formulário e CSS"
🟢 4️⃣ Enviar para o GitHub
bash

git push origin main
✅ 📌 Se der erro de remote duplicado
Use:

bash

git remote remove origin
git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
git push -u origin main
✅ 📌 Se for o PRIMEIRO PUSH
A sequência é:

bash

git init
git add .
git commit -m "Primeiro commit"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
git push -u origin main
✅ 🚨 DICA EXTRA
Sempre rode git status antes!
Assim você vê se esqueceu algum arquivo.

Depois do push, o GitHub Pages atualiza sozinho em 30 segundos.

🗂️ Bônus: ver histórico de commits
bash

git log --oneline
Veja todos os commits já feitos, num resumo.

