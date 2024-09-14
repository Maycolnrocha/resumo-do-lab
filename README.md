# resumo-do-lab
Repositorio de aprendizado DIO

### 1. **O que é Git?**
   Git é um sistema de controle de versões distribuído que permite acompanhar as mudanças no código ao longo do tempo, colaborar com outros desenvolvedores e gerenciar diferentes versões de um projeto. Ele é amplamente usado para desenvolvimento de software e se integra com plataformas como GitHub e GitLab.

### 2. **Principais Conceitos do Git**
   - **Repositório**: Diretório onde o histórico de versões do projeto é armazenado.
   - **Commit**: Uma "foto" do código em um determinado momento, contendo mudanças.
   - **Branch (ramo)**: Uma linha paralela de desenvolvimento, permitindo que várias funcionalidades sejam desenvolvidas de forma independente.
   - **Merge**: Ação de unir mudanças de diferentes branches.
   - **Pull request**: Solicitação de revisão e fusão de mudanças entre branches (em plataformas como GitHub).
   - **Staging Area**: Área temporária onde arquivos modificados são preparados para o commit.

### 3. **Instalando Git**
   - **Instalar o Git**: [Download Git](https://git-scm.com/downloads)
   - Após a instalação, configure seu nome e e-mail:

     ```bash
     git config --global user.name "Seu Nome"
     git config --global user.email "seu.email@exemplo.com"
     ```

### 4. **Comandos Básicos do Git**

#### Inicialização e Configuração
- **Inicializar um repositório Git**:
  ```bash
  git init
  ```

- **Clonar um repositório existente**:
  ```bash
  git clone URL-DO-REPOSITORIO
  ```

#### Controle de Versão
- **Adicionar arquivos ao staging area**:
  ```bash
  git add NOME_DO_ARQUIVO
  ```

- **Fazer um commit com uma mensagem**:
  ```bash
  git commit -m "Mensagem do commit"
  ```

- **Ver o status dos arquivos modificados**:
  ```bash
  git status
  ```

- **Ver o histórico de commits**:
  ```bash
  git log
  ```

#### Branching e Merging
- **Criar um novo branch**:
  ```bash
  git branch nome-do-branch
  ```

- **Mudar para outro branch**:
  ```bash
  git checkout nome-do-branch
  ```

- **Mesclar um branch com o branch atual**:
  ```bash
  git merge nome-do-branch
  ```

#### Repositório Remoto
- **Adicionar um repositório remoto**:
  ```bash
  git remote add origin URL-DO-REPOSITORIO
  ```

- **Enviar alterações para o repositório remoto**:
  ```bash
  git push origin nome-do-branch
  ```

- **Atualizar o repositório local com as mudanças do remoto**:
  ```bash
  git pull origin nome-do-branch
  ```

#### Controle de Versão
- **Reverter para um commit anterior**:
  ```bash
  git checkout COMMIT_ID
  ```

- **Ver diferenças entre versões do código**:
  ```bash
  git diff
  ```

### 5. **Fluxo de Trabalho Básico no Git**
   1. Faça mudanças no código localmente.
   2. Use `git add` para mover as alterações para a staging area.
   3. Faça um commit com `git commit -m "mensagem"`.
   4. Use `git push` para enviar as mudanças para o repositório remoto.
   5. Quando houver mudanças no repositório remoto, use `git pull` para integrar as alterações.

---

