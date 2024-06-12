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