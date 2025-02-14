# 📜 Tabela de Requisitos do Jogo da Forca

| **ID**   | **Tipo**        | **Título**                                  | **Descrição** |
|---------|---------------|----------------------------------------------|--------------|
| RF-01   | Funcional     | Cadastro e Gerenciamento de Palavras         | O sistema deve permitir a adição, remoção e edição de palavras no banco de palavras do jogo. |
| RF-02   | Funcional     | Escolha Aleatória da Palavra                 | O sistema deve selecionar uma palavra aleatória para cada nova partida. |
| RF-03   | Funcional     | Exibição da Palavra com Letras Descobertas   | O sistema deve exibir a palavra oculta, mostrando apenas as letras já descobertas pelo jogador. |
| RF-04   | Funcional     | Entrada de Letras pelo Jogador               | O jogador deve poder inserir uma letra por tentativa. |
| RF-05   | Funcional     | Validação da Letra Inserida                  | O sistema deve verificar se a letra digitada está presente na palavra e atualizar a exibição da palavra oculta. |
| RF-06   | Funcional     | Contagem Máxima de 6 Tentativas              | O sistema deve manter um contador de até 6 tentativas erradas. |
| RF-07   | Funcional     | Exibição Progressiva do Boneco da Forca      | O sistema deve exibir a imagem do boneco conforme as tentativas erradas aumentam (cabeça, tronco, braço esquerdo, braço direito, perna direita, perna esquerda). |
| RF-08   | Funcional     | Exibição de Mensagem de Vitória ou Derrota   | O sistema deve exibir uma mensagem ao jogador informando se ele venceu ou perdeu a partida. |
| RF-09   | Funcional     | Opção de Jogar Novamente                     | O sistema deve oferecer ao jogador a opção de iniciar uma nova partida após o término do jogo. |
| RF-10   | Funcional     | Modo de Jogo para um Jogador                 | O jogo deve permitir que um único jogador tente adivinhar a palavra selecionada pelo sistema. |
| RF-11   | Funcional     | Exibição do Histórico de Partidas            | O sistema deve permitir a visualização de partidas passadas, incluindo número de tentativas e palavras utilizadas. |
| RNF-01  | Não Funcional | Tempo de Resposta Rápido                      | O tempo de resposta para exibir atualizações na tela após uma entrada do jogador deve ser inferior a 500ms. |
| RNF-02  | Não Funcional | Compatibilidade com Diferentes Navegadores   | O jogo deve ser compatível com os navegadores Chrome, Firefox, Edge e Safari. |
| RNF-03  | Não Funcional | Interface Responsiva                         | A interface deve ser responsiva, permitindo o uso em dispositivos móveis e desktop. |
| RNF-04  | Não Funcional | Armazenamento e Persistência de Palavras     | O jogo deve armazenar as palavras em um banco de dados local ou remoto, garantindo persistência entre sessões. |
| RNF-05  | Não Funcional | Segurança Contra Entradas Maliciosas         | O jogo deve validar e sanitizar todas as entradas do usuário para evitar ataques como SQL Injection e XSS. |
| RNF-06  | Não Funcional | Suporte a Múltiplos Idiomas                  | O sistema deve permitir a customização do idioma do jogo, incluindo português e inglês. |
| RNF-07  | Não Funcional | Capacidade de Expansão para Novas Funcionalidades | A arquitetura do sistema deve permitir a adição futura de novos modos de jogo e funcionalidades sem impactar a estabilidade. |
| RNF-08  | Não Funcional | Interface Intuitiva e Fácil de Usar          | O design da interface deve seguir princípios de usabilidade, garantindo que o jogador compreenda as ações disponíveis sem necessidade de tutoriais extensos. |
