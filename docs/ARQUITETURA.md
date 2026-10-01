# Arquitetura e autenticação

## Estado atual

O material de pré-produção descreve uma visual novel para computador, executada localmente com Ren'Py. Não define site, serviço online, contas de jogador, sincronização em nuvem, API ou banco de dados.

Portanto, no escopo atual:

- não há componente de autenticação especificado;
- não há fluxo de requisição HTTP do jogo para um servidor especificado;
- não há credenciais, tokens ou segredos de jogador que o jogo precise guardar;
- escolhas e progresso devem ser tratados como estado/saves locais do jogo, salvo decisão futura em contrário.

Não invente endpoints ou tokens nesta documentação. Atualize este arquivo se a equipe aprovar um recurso online.

## Se surgir uma necessidade online

Antes de implementar, registrar em decisão de equipe: por que o jogo precisa de rede; quais dados trafegam; quem opera o serviço; quais credenciais são usadas; onde ficam armazenados; como expiram e são revogados; como erros e indisponibilidade afetam a experiência; e como proteger dados dos jogadores.

Nunca colocar senhas, chaves privadas, tokens reais ou dados pessoais em scripts, commits, Issues, Pull requests ou exemplos públicos. Use valores fictícios em exemplos e siga orientação técnica revisada pela equipe.
