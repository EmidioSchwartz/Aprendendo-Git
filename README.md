Comandos do Git e do GitHub, divididos por categorias:  

---

## 🔹 **Configuração Inicial**  
Estes comandos são usados para configurar o Git na sua máquina:  
- `git config --global user.name "Seu Nome"` → Define o nome do usuário globalmente.  
- `git config --global user.email "seu@email.com"` → Define o e-mail globalmente.  
- `git config --global core.editor "vim"` → Define o editor de texto padrão.  
- `git config --list` → Exibe as configurações atuais do Git.  

---

## 🔹 **Inicialização e Clone**  
Comandos usados para iniciar um repositório ou clonar um existente:  
- `git init` → Inicializa um novo repositório Git no diretório atual.  
- `git clone URL_DO_REPOSITORIO` → Clona um repositório remoto para sua máquina.  

---

## 🔹 **Status e Histórico**  
Para visualizar informações sobre mudanças no repositório:  
- `git status` → Mostra o status atual do repositório.  
- `git log` → Exibe o histórico de commits.  
- `git log --oneline` → Exibe o histórico de commits de forma resumida.  
- `git log --graph --oneline --decorate` → Mostra o histórico em formato gráfico.  
- `git show COMMIT_ID` → Mostra detalhes de um commit específico.  

---

## 🔹 **Rastreamento de Arquivos**  
Gerencia quais arquivos serão monitorados pelo Git:  
- `git add NOME_DO_ARQUIVO` → Adiciona um arquivo específico à área de stage.  
- `git add .` → Adiciona todas as alterações para serem commitadas.  
- `git reset NOME_DO_ARQUIVO` → Remove um arquivo da área de stage.  
- `git reset --hard` → Descarta todas as mudanças desde o último commit.  

---

## 🔹 **Commits**  
Comandos usados para salvar alterações no repositório:  
- `git commit -m "mensagem"` → Cria um commit com a mensagem especificada.  
- `git commit --amend -m "nova mensagem"` → Modifica o último commit.  

---

## 🔹 **Branches (Ramificações)**  
Para gerenciar diferentes versões do código:  
- `git branch` → Lista as branches no repositório.  
- `git branch NOME_DA_BRANCH` → Cria uma nova branch.  
- `git checkout NOME_DA_BRANCH` → Troca para a branch especificada.  
- `git checkout -b NOME_DA_BRANCH` → Cria e troca para a nova branch.  
- `git merge NOME_DA_BRANCH` → Mescla outra branch na branch atual.  
- `git branch -d NOME_DA_BRANCH` → Deleta uma branch localmente.  

---

## 🔹 **Repositórios Remotos (GitHub, GitLab, etc.)**  
Conecta e sincroniza o repositório local com um repositório remoto:  
- `git remote add origin URL` → Associa um repositório remoto ao repositório local.  
- `git remote -v` → Lista os repositórios remotos vinculados.  
- `git push origin main` → Envia os commits locais para o repositório remoto.  
- `git push -u origin main` → Envia commits e define a branch remota como padrão.  
- `git pull origin main` → Atualiza o repositório local com as mudanças remotas.  

---

## 🔹 **Revertendo Alterações**  
Para desfazer ou modificar mudanças:  
- `git revert COMMIT_ID` → Cria um novo commit que desfaz as mudanças do commit especificado.  
- `git reset --soft COMMIT_ID` → Retorna a um commit específico, mantendo as alterações.  
- `git reset --hard COMMIT_ID` → Retorna a um commit específico, descartando todas as mudanças.  

---

## 🔹 **Git Stash (Salvar Alterações Temporariamente)**  
Para salvar mudanças temporariamente sem commitá-las:  
- `git stash` → Salva as mudanças atuais sem commitá-las.  
- `git stash list` → Lista os stashes salvos.  
- `git stash apply` → Aplica as mudanças salvas no stash mais recente.  
- `git stash drop` → Remove o stash mais recente.  

---

## 🔹 **Tags (Marcação de Versões)**  
Para marcar versões específicas do código:  
- `git tag` → Lista todas as tags.  
- `git tag -a v1.0 -m "Versão 1.0"` → Cria uma nova tag anotada.  
- `git push origin --tags` → Envia as tags para o repositório remoto.  

---

## 🔹 **GitHub - Comandos Específicos**  
Algumas operações úteis no GitHub:  
- `gh repo create` → Cria um novo repositório no GitHub.  
- `gh repo clone USUARIO/REPO` → Clona um repositório do GitHub.  
- `gh pr create` → Cria um novo Pull Request no GitHub.  
- `gh pr list` → Lista os Pull Requests abertos.  

---
