# 📜 Tabela de Requisitos do Jogo da Forca

| **ID**   | **Tipo**        | **Título**                                  | **Descrição** |
|---------|---------------|----------------------------------------------|--------------|
| RF-01   | Funcional     | Cadastro de palavras                        | O sistema deve permitir a adição, remoção e edição de palavras no banco de palavras do jogo. |
| RF-02   | Funcional     | Escolha aleatória de palavra                | O sistema deve selecionar uma palavra aleatória para cada nova partida. |
| RF-03   | Funcional     | Exibição do estado da palavra               | O sistema deve exibir a palavra oculta, mostrando apenas as letras já descobertas pelo jogador. |
| RF-04   | Funcional     | Entrada de letras pelo jogador              | O jogador deve poder inserir uma letra por tentativa. |
| RF-05   | Funcional     | Validação da letra inserida                 | O sistema deve verificar se a letra digitada está presente na palavra e atualizar a exibição da palavra oculta. |
| RF-06   | Funcional     | Contagem de tentativas                      | O sistema deve manter um contador do número de tentativas erradas. |
| RF-07   | Funcional     | Exibição do boneco da forca                 | O sistema deve exibir a imagem do boneco conforme as tentativas erradas aumentam. |
| RF-08   | Funcional     | Mensagem de vitória ou derrota              | O sistema deve exibir uma mensagem ao jogador informando se ele venceu ou perdeu a partida. |
| RF-09   | Funcional     | Jogar novamente                             | O sistema deve oferecer ao jogador a opção de iniciar uma nova partida após o término do jogo. |
| RF-10   | Funcional     | Modo de jogo para um jogador                | O jogo deve oferecer um modo onde apenas um jogador tenta adivinhar a palavra. |
| RF-11   | Funcional     | Modo de jogo multiplayer (opcional)         | O jogo pode permitir que um jogador insira a palavra secreta enquanto outro tenta adivinhar. |
| RF-12   | Funcional     | Exibição do histórico de partidas          | O sistema deve permitir a visualização de partidas passadas, incluindo número de tentativas e palavras utilizadas. |
| RNF-01  | Não Funcional | Tempo de resposta                           | O tempo de resposta para exibir atualizações na tela após uma entrada do jogador deve ser inferior a 500ms. |
| RNF-02  | Não Funcional | Compatibilidade com navegadores             | O jogo deve ser compatível com os navegadores Chrome, Firefox, Edge e Safari. |
| RNF-03  | Não Funcional | Interface responsiva                        | A interface deve ser responsiva, permitindo o uso em dispositivos móveis e desktop. |
| RNF-04  | Não Funcional | Armazenamento de palavras                   | O jogo deve armazenar as palavras em um banco de dados local ou remoto, garantindo persistência entre sessões. |
| RNF-05  | Não Funcional | Segurança das entradas                      | O jogo deve validar e sanitizar todas as entradas do usuário para evitar ataques como SQL Injection e XSS. |
| RNF-06  | Não Funcional | Suporte a múltiplos idiomas                 | O sistema deve permitir a customização do idioma do jogo, incluindo português e inglês. |
| RNF-07  | Não Funcional | Escalabilidade                              | A arquitetura do sistema deve permitir a adição futura de novos modos de jogo e funcionalidades sem impactar a estabilidade. |
| RNF-08  | Não Funcional | Design intuitivo                            | O design da interface deve seguir princípios de usabilidade, garantindo que o jogador compreenda as ações disponíveis sem necessidade de tutoriais extensos. |
