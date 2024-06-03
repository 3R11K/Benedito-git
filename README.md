# Git Cheat Sheet

Este é um guia rápido com alguns comandos básicos do Git e uma breve explicação sobre conceitos importantes.

## Versionamento

O versionamento é o processo de controle de alterações em um projeto ao longo do tempo. O Git é uma ferramenta de versionamento distribuído que permite rastrear e gerenciar as alterações em um projeto.

## Branch

Um branch é uma ramificação do código-fonte principal (geralmente chamado de branch "main") em um repositório Git. Ele permite que você trabalhe em novas funcionalidades ou correções de bugs sem afetar o código principal. Você pode criar, alternar e mesclar branches usando comandos do Git.

## Merge

O merge é o processo de combinar as alterações de um branch em outro. Quando você finaliza o trabalho em um branch e deseja incorporar as alterações no branch principal, você pode fazer um merge. O Git combina automaticamente as alterações e resolve conflitos, se houver.

## Conflito

Um conflito ocorre quando o Git não consegue mesclar automaticamente as alterações de dois branches. Isso geralmente acontece quando as mesmas linhas de código foram modificadas em ambos os branches. Nesse caso, você precisa resolver manualmente o conflito, escolhendo qual versão do código deve ser mantida.

## Commit

Um commit é uma operação que registra as alterações feitas em um repositório Git. Cada commit possui uma mensagem descritiva que explica as alterações realizadas. Os commits são usados para rastrear o histórico do projeto e permitem que você volte a versões anteriores, se necessário.

## Git Flow

O Git Flow é um modelo de fluxo de trabalho para o Git que define uma estrutura para organizar branches e releases em um projeto. Ele utiliza dois branches principais: "main" e "develop". O branch "main" contém o código estável e o branch "develop" é usado para desenvolvimento contínuo. Além disso, o Git Flow define branches adicionais para features, releases e hotfixes.

### Branches principais

- **Main**: O branch "main" contém o código estável do projeto. É a versão de produção que está pronta para ser implantada.

- **Develop**: O branch "develop" é usado para desenvolvimento contínuo. É a partir deste branch que novas funcionalidades são desenvolvidas e testadas antes de serem mescladas no branch "main".

### Branches adicionais

- **Feature**: O branch "feature" é usado para desenvolver novas funcionalidades. Cada funcionalidade é desenvolvida em um branch separado, que é criado a partir do branch "develop". Após a conclusão do desenvolvimento, o branch "feature" é mesclado de volta no branch "develop".

- **Release**: O branch "release" é usado para preparar uma nova versão do projeto para implantação. Ele é criado a partir do branch "develop" e contém as alterações finais antes da versão ser lançada. Após a conclusão do processo de release, o branch "release" é mesclado no branch "main" e também no branch "develop".

- **Hotfix**: O branch "hotfix" é usado para corrigir bugs críticos em produção. Ele é criado a partir do branch "main" e contém as correções necessárias. Após a conclusão do processo de hotfix, o branch "hotfix" é mesclado no branch "main" e também no branch "develop".

### Esquema explicativo


## Comandos básicos do Git

Aqui estão alguns comandos básicos do Git para começar:

- `git init`: Inicializa um novo repositório Git.
- `git clone <url>`: Clona um repositório Git existente.
- `git add <arquivo>`: Adiciona um arquivo ao próximo commit.
- `git commit -m "<mensagem>"`: Cria um novo commit com as alterações adicionadas.
- `git push`: Envia os commits locais para um repositório remoto.
- `git pull`: Atualiza o repositório local com as alterações do repositório remoto.
- `git branch`: Lista os branches existentes.
- `git checkout <branch>`: Alterna para um branch específico.
- `git merge <branch>`: Realiza o merge das alterações de um branch em outro.

Lembre-se de consultar a documentação oficial do Git para obter mais informações sobre esses comandos e outros recursos.
