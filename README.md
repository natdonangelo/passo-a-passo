# Passo a passo
 Nesta seção, explico como integrar o Git local com o GitHub, criando branches para alterações e enviando essas modificações para o repositório remoto. Além disso, mostro como o uso do GitFluence pode facilitar a geração dos comandos Git, tornando o processo de colaboração mais eficiente e organizado.


## 1. Fork do Repositório Original
#### Primeiramente, abri o link do repositório original no GitHub: https://github.com/andersonrmgomes/git-local. Depois, na página do repositório original, no canto superior direito, cliquei no botão "Fork". Esse botão criou uma cópia do repositório na minha conta do GitHub.
#### Após a criação do fork, o repositório ficou disponível na minha conta do GitHub.

## 2. Documentação e Uso do GitFluence
#### Agora, com o objetivo de adicionar mais documentação, com foco na integração entre o Git local e o GitHub e no processo de colaboração, usei o GitFluence (https://www.gitfluence.com/) para me auxiliar na geração dos comandos Git necessários ao longo do processo. O GitFluence é uma ferramenta que me ajudou a entender e gerar rapidamente os comandos Git certos, tornando o processo de colaboração mais eficiente e sem erros.
### Clonagem e Configuração Local
<img width="543" height="114" alt="image" src="https://github.com/user-attachments/assets/88a57e8f-e9ff-48f1-945d-e1856573a8ac" />

> Nestes comandos, baixei a cópia do repositório para a minha máquina local e em seguida, entrei na pasta do repositório clonado.

<img width="550" height="52" alt="image" src="https://github.com/user-attachments/assets/74a95888-8b66-44c6-9766-0be82ec8c043" />

> Aqui, criei um novo branch para a documentação, mantendo o main limpo.
### Uso do GitFluence para Comandos de Integração
<img width="630" height="448" alt="image" src="https://github.com/user-attachments/assets/b8fb0200-230e-42cf-bb17-2456f39db4f6" />

> Nesta parte do projeto, usei o comando "git push -u origin documentacao-colaboracao" para enviar o novo branch para o GitHub. Em seguida, busquei visualizar os branches locais e remotos e verificar o estado dos arquivos antes do commit.

### Edição da Documentação
#### Nesta etapa, editei os arquivos de documentação. Adicionei seções importantes, incluindo como integrar o Git local ao GitHub, detalhando os comandos principais como clone, add, commit e push. Também incluí instruções sobre como adicionar colaboradores a um repositório privado, com passos detalhados para facilitar o processo. Além disso, fiz uma breve menção ao uso do GitFluence, mostrando como essa ferramenta pode ajudar a gerar os comandos Git de forma prática e eficiente. Assim, preparei a documentação para que fique clara e acessível para quem for colaborar no projeto.
### Commit e Push das Alterações
<img width="624" height="338" alt="image" src="https://github.com/user-attachments/assets/0b42ad29-839e-47aa-930d-3c6ec9f2e3b7" />

> Usei o comando "git add ." para preparar todos os arquivos modificados para o commit. No comando seguinte, salvei as alterações no histórico local e utilizando "git push origin documentacao-colaboracao" enviei o novo branch com as alterações para o repositório no GitHub.

## Integração e Colaboração
#### Após concluir as alterações no arquivo README.md, abri um Pull Request (PR) no GitHub para enviar as mudanças para o repositório original. O GitHub verificou que não havia conflitos entre as branches, então as alterações poderiam ser integradas sem problemas. . O próximo passo seria aguardar a revisão e, se tudo estivesse correto, as alterações seriam integradas ao repositório original. A tarefa foi concluída com sucesso, e agora o código está disponível para ser integrado ao repositório principal.
<img width="1397" height="859" alt="image" src="https://github.com/user-attachments/assets/6f621fd3-112f-4c15-b7a4-4502dca9aa89" />
