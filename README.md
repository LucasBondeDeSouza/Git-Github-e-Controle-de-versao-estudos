# Qual é a diferença entre Repositório Local e Repositório Remoto?

### Repositório Local:
Quando você inicializa um novo repositório com git init ou clona um repositório remoto com git clone, você está trabalhando em um repositório local no seu computador.

### Repositório Remoto:
Quando você adiciona um repositório remoto com git remote add origin <URL> e faz git push para enviar suas mudanças para o GitHub, você está interagindo com um repositório remoto.

# Introdução a Controle de versão e Git

## Comandos 

### git init
Inicializa um novo repositório Git em um diretório. Isso cria um subdiretório .git que contém todos os arquivos necessários do repositório, como a estrutura do repositório, histórico, etc.

**Quando usar:** Quando você deseja começar a usar o Git em um novo projeto ou em um diretório existente que ainda não está sob controle de versão do Git.

### git add <nome do arquivo>
Adiciona o arquivo à área de stage (ou área de preparação). Isso significa que você está preparando este arquivo para o próximo commit.

**Quando usar:** Quando você fez alterações em chapter1.txt e deseja incluir essas alterações no próximo commit.

### git commit -m <"mensagem">
Cria um novo commit com as mudanças que estão na área de stage, e inclui uma mensagem descritiva.

**Quando usar**: Quando você deseja salvar um snapshot do seu projeto, incluindo todas as mudanças que foram adicionadas à área de stage. A mensagem do commit deve descrever claramente o que foi alterado.

### git add .
Adiciona todas as mudanças feitas (em novos arquivos, arquivos modificados e arquivos excluídos) no diretório atual e subdiretórios à área de stage.

**Quando usar:** Quando você deseja preparar todas as mudanças feitas no seu projeto para o próximo commit.

### git diff <nome do arquivo>
Mostra as diferenças entre as mudanças feitas no arquivo e a versão dele que está no último commit (ou na área de stage, se ele já tiver sido adicionado à área de stage).

**Quando usar:** Quando você deseja ver as mudanças que foram feitas no arquivo desde o último commit (ou desde que ele foi adicionado à área de stage).

### git checkout <nome do arquivo>
Descarta as mudanças feitas no arquivo e restaura a versão do arquivo que está no último commit.

**Quando usar:** Quando você deseja descartar todas as modificações feitas no arquivo e voltar para a versão mais recente dele que está no repositório.

# Github e Repositório Remoto

## Comandos 

### git remote add origin <caminho do projeto>
Conecta seu repositório local a um repositório remoto chamado origin no caminho especificado.

**Quando usar:** Quando você deseja conectar seu repositório local a um repositório remoto para que possa enviar (push) e buscar (pull) mudanças entre eles.

### git push -u origin main
Envia suas mudanças da ramificação main local para o repositório remoto origin e define a ramificação upstream para facilitar futuros push/pull.

**Quando usar:** Quando você deseja enviar as mudanças do seu repositório local para o repositório remoto pela primeira vez ou quando deseja definir a ramificação upstream para a ramificação atual.

# Clonando Repositório

## Comando
git clone <url>