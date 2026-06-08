---
title: "Curso de SQL - Configuração do Ambiente"
---

# Configuração do Ambiente do Aluno

Este guia mostra o passo a passo para preparar o ambiente básico necessário para testar o curso de SQL.

Neste momento, vamos configurar apenas:

- Conta no GitHub
- Git
- Visual Studio Code
- Extensões do VS Code
- DBeaver
- Clonagem do repositório do curso

A parte de ambiente virtual, instalação de pacotes Python e configurações mais avançadas será feita depois.

---

## 1. Criar uma conta no GitHub

O GitHub será usado para acessar o repositório do curso. Se você já tiver conta no GitHub, pule essa etapa.

### Passo a passo

1. Acesse: <https://github.com/>

2. Clique em **Sign up**.

3. Crie uma conta usando seu e-mail.

- Escolha um nome razoavelmente **profissional** (por exemplo, primeiro nome e sobrenome: caiocvelasco), pois você pode precisar usar no seu trabalho futuro.

4. Confirme o e-mail, caso o GitHub solicite.

5. Depois de criar a conta, faça login.

---

## 2. Instalar o Git

O Git é a ferramenta usada para baixar o repositório do curso para o seu computador. Se você já tiver o Git, pule essa etapa.

### Passo a passo

1. Acesse: <https://git-scm.com/>

2. Clique em **Download**.

3. Escolha a versão para o seu sistema operacional:

   - Windows
   - macOS
   - Linux

4. Instale usando as opções padrão.

5. Depois da instalação, abra um terminal.

O terminal é o lugar onde digitamos comandos no computador.

No **Windows**, você pode abrir de uma destas formas:

- Clique no menu **Iniciar** e pesquise por `Git Bash`;
- ou clique no menu **Iniciar** e pesquise por `PowerShell`;
- ou clique com o botão direito dentro de uma pasta e escolha **Open Git Bash here**, caso essa opção apareça.

Para este curso, recomendamos usar o **Git Bash** no Windows, pois ele já vem junto com a instalação do Git.

No **macOS**, você pode abrir o terminal assim:

- Pressione `Command + Espaço`;
- digite `Terminal`;
- pressione `Enter`.

No **Linux**, você pode abrir o terminal pesquisando por `Terminal` no menu de aplicativos.

6. Teste se o Git foi instalado corretamente usando o comando abaixo no terminal:

`git --version`

Se aparecer algo parecido com:

`git version 2.xx.x`

significa que a instalação funcionou.

---

## 3. Instalar o Visual Studio Code

O Visual Studio Code será o editor usado para abrir a pasta do curso e editar os arquivos. Se você já tiver o VS Code, pule essa etapa.

### Passo a passo

1. Acesse: <https://code.visualstudio.com/>

2. Clique em **Download**.

3. Escolha a versão para o seu sistema operacional.

4. Instale usando as opções padrão.

5. Abra o Visual Studio Code.

---

## 4. Instalar as extensões recomendadas no VS Code

As extensões ajudam o VS Code a trabalhar melhor com Git, notebooks e arquivos Python.

### Passo a passo geral

1. Abra o VS Code.

2. Clique no ícone de extensões na barra lateral esquerda.

   O ícone parece pequenos blocos.

3. Pesquise pelo nome da extensão.

4. Clique em **Install**.

---

### 4.1 Instalar GitLens

Pesquise por:

`GitLens`

Instale a extensão:

`GitLens — Git supercharged`

Essa extensão ajuda a visualizar informações de Git dentro do VS Code, como alterações nos arquivos e histórico do repositório.

---

### 4.2 Instalar Jupyter

Pesquise por:

`Jupyter`

Instale a extensão oficial da Microsoft.

Essa extensão permite abrir notebooks `.ipynb` no VS Code.

---

### 4.3 Instalar Python

Pesquise por:

`Python`

Instale a extensão oficial da Microsoft.


### Ao final desta etapa, você deve ter instalado:

- GitLens
- Jupyter
- Python

---

## 5. Instalar o DBeaver

O DBeaver será usado para escrever e executar consultas SQL em uma interface gráfica.

### Passo a passo

1. Acesse: <https://dbeaver.io/>

2. Clique em **Download**.

3. Escolha a versão para o seu sistema operacional.

4. Instale usando as opções padrão.

5. Abra o DBeaver.

### Ao final desta etapa, você deve ter:

O DBeaver instalado e abrindo normalmente.

---

## 6. Clonar o repositório do curso

Depois que Git, GitHub e VS Code estiverem prontos, o próximo passo é baixar o repositório do curso para o seu computador.

No GitHub, os arquivos do curso ficam em um **repositório**.

Um repositório é uma pasta de projeto versionada. Ele pode conter arquivos, exercícios, scripts, dados, instruções e histórico de mudanças. Ao clonar um repositório, você está baixando uma cópia desse projeto para o seu computador.

---

### Antes de clonar: crie uma pasta para seus repositórios

Como você provavelmente usará Git e GitHub em outros projetos no futuro, é uma boa prática criar uma pasta específica no seu computador para guardar seus repositórios.

Você pode criar uma pasta chamada:

`repositorios`

Por exemplo, no Windows, você pode criar a pasta dentro de **Documentos**:

`Documentos/repositorios`

No macOS ou Linux, você pode criar a pasta dentro da sua pasta de usuário:

`~/repositorios`

Essa pasta será o lugar onde você guardará projetos baixados do GitHub, incluindo o repositório deste curso.

---

### Passo a passo

1. Acesse o link do repositório do curso no GitHub.

2. Clique no botão **Code**.

3. Copie o link HTTPS do repositório.

O link será parecido com:

`https://github.com/usuario/nome-do-repositorio.git`

4. No seu computador, crie uma pasta chamada `repositorios`.

Sugestões:

- Windows: crie a pasta dentro de **Documentos**.
- macOS/Linux: crie a pasta dentro da sua pasta de usuário.

5. Abra o VS Code.

6. Na tela inicial do VS Code, clique em:

`Clone Git Repository`

ou, em português:

`Clonar Repositório Git`

7. Cole o link HTTPS do repositório do curso.

O link será parecido com:

`https://github.com/usuario/nome-do-repositorio.git`

8. Escolha a pasta `repositorios` como o local onde o projeto será salvo.

9. Confirme a clonagem.

O VS Code irá baixar o repositório do curso para dentro da pasta `repositorios`.

10. Quando o VS Code perguntar se você deseja abrir o repositório clonado, clique em:

`Open`

ou, em português:

`Abrir`

---

### Ao final desta etapa, você deve ter:

- uma pasta chamada `repositorios` no seu computador;
- o repositório do curso baixado dentro dessa pasta;
- a pasta do curso aberta no VS Code;
- acesso aos arquivos, exercícios e instruções do curso.