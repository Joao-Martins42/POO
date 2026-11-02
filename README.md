# Relatório de Operações com Git e GitHub

Este repositório contém a documentação e as evidências das operações realizadas no Git utilizando o terminal do Windows (PowerShell), demonstrando o fluxo de clonagem, criação de arquivos, versionamento, criação e publicação de ramos (branches).

---

## Descrição das Etapas Realizadas e Evidências

### 1. Clonagem do Repositório Remoto

O repositório foi clonado do GitHub para o ambiente local para dar início ao trabalho.

**Comando utilizado:**
```bash
git clone https://github.com/Joao-Martins42/POO.git
```

![Clonagem do Repositório](assets/Captura%20de%20tela%202026-11-02%20140546.png)

---

### 2. Navegação e Verificação de Diretório

Acesso à pasta do projeto clonado e listagem dos arquivos existentes no diretório.

**Comandos utilizados:**
```bash
cd POO
ls
```

![Navegação e Verificação de Diretório](assets/Captura%20de%20tela%202026-11-02%20142247.png)

---

### 3. Criação e Edição de Arquivos via Terminal

Utilização do editor de texto `nano` no terminal para criar e editar o arquivo `TESTE.md`.

**Comandos utilizados:**
```bash
nano TESTE.md
```

![Edição de Arquivo pelo Terminal](assets/Captura%20de%20tela%202026-11-02%20143708.png)

---

### 4. Verificação dos Arquivos no Diretório Local

Confirmando a criação e presença do novo arquivo no diretório do projeto.

**Comando utilizado:**
```bash
nano README.md
ls
```

![Verificação de Arquivos Criados](assets/Captura%20de%20tela%202026-11-02%20143810.png)

---

### 5. Versionamento e Envio de Alterações na Branch Principal (main)

Adição de alterações ao ambiente de staging, commit das mudanças, verificação de status e envio das atualizações para o GitHub.

**Comandos utilizados:**
```bash
git commit -m "Adicionado texto ao teste"
git status
git push
git status
```

![Commit e Push na Branch main](assets/Captura%20de%20tela%202026-11-02%20144442.png)

---

### 6. Gerenciamento e Troca de Ramos (Branches)

Listagem das branches existentes, criação da nova branch `novo_ramo` e alternância para o novo ramo.

**Comandos utilizados:**
```bash
git branch
git branch novo_ramo
git branch
git checkout novo_ramo
nano texto.md
```

![Criação e Alternância para a nova Branch](assets/Captura%20de%20tela%202026-11-02%20144854.png)

---

### 7. Publicação da Nova Branch e Associação com o Repositório Remoto

Adição de arquivo no novo ramo, realização de commit e envio da branch para o GitHub estabelecendo o rastreamento remoto.

**Comandos utilizados:**
```bash
git add texto.md
git commit -m "adicionando um arquivo no novo branch"
git status
git push --set-upstream origin novo_ramo
```

![Commit e Push da Nova Branch](assets/Captura%20de%20tela%202026-11-02%20145108.png)

---

### 8. Validação do Estado Local e Repositórios Remotos

Verificação do endereço remoto do repositório (`git remote -v`) e confirmação de que a árvore de trabalho está limpa.

**Comandos utilizados:**
```bash
git remote -v
git status
```

![Validação do Estado Local e Remoto](assets/Captura%20de%20tela%202026-11-02%20145139.png)

---

## Evidências do Histórico de Commits e Ramos no GitHub

As capturas de tela a seguir confirmam que o GitHub registrou a existência dos múltiplos ramos (*branches*) no repositório remoto após os envios realizados pelo terminal.

### Indicação de Ramos Ativos

Visualização da indicação de duas branches ativas na interface do repositório no GitHub.

![Indicação de 2 Branches no GitHub](assets/Captura%20de%20tela%202026-11-02%20150444.png)

---

### Listagem das Branches Cadastradas no GitHub

Confirmação das duas branches existentes no repositório remoto: a branch padrão (`main`) e a nova branch criada (`novo_ramo`).

![Listagem de Branches no GitHub](assets/Captura%20de%20tela%202026-11-02%20150450.png)
