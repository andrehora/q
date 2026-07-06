Por que os testes de unidade são considerados a "base da pirâmide de testes":
- Porque são os mais difíceis de automatizar
- Porque testam o sistema inteiro de ponta a ponta
- Porque são numerosos, rápidos e simples de escrever x
- Porque são executados apenas uma vez por release
- Porque dependem de banco de dados e rede para funcionar

Qual é a principal razão pela qual empresas como Google e Facebook tornam os testes de unidade obrigatórios:
- Para aumentar o tempo de desenvolvimento
- Para garantir que apenas gerentes aprovem mudanças
- Para detectar problemas cedo e manter a qualidade e confiabilidade do código antes que ele chegue à produção x
- Para substituir a necessidade de revisão de código
- Porque é uma exigência legal de compliance

Por que a "fixture" de um teste é importante para garantir que um teste seja repetível:
- Porque ela documenta o código-fonte automaticamente
- Porque ela impede que o teste seja executado mais de uma vez
- Porque ela substitui a necessidade de asserts
- Porque ela conecta o teste diretamente ao banco de dados de produção
- Porque ela define um estado inicial conhecido e controlado x

Qual é a ideia central por trás de escrever um teste para reproduzir um bug reportado por um usuário:
- Documentar formalmente a reclamação do usuário
- Aumentar artificialmente a cobertura de testes do projeto
- Substituir a necessidade de comunicação com o usuário
- Criar uma evidência de que o bug existe e garantir que, uma vez corrigido, ele não volte a ocorrer x
- Servir apenas como registro histórico sem função técnica

Por que recomenda-se evitar escrever todos os testes de unidade somente depois que o sistema estiver totalmente pronto:
- Porque testes escritos no final sempre contêm erros de sintaxe
- Porque isso reduz a chance de detectar problemas o quanto antes x
- Porque frameworks de teste não funcionam em sistemas completos
- Porque testes só podem ser escritos por quem não programou a funcionalidade
- Porque isso viola as regras do JUnit

O que significam as letras do padrão AAA em testes de unidade:
- Assert, Arrange, After
- Analyze, Act, Assert
- Arrange, Act, Assert x

Qual é a semelhança entre os padrões AAA, Given-When-Then e Four-Phase (Setup-Exercise-Verify-Teardown):
- Todos exigem o uso exclusivo da linguagem Java
- Todos servem para organizar um teste em fases lógicas semelhantes x
- Todos eliminam a necessidade de fixtures
- Todos são específicos para testes de interface gráfica
- Todos requerem bancos de dados reais para funcionar

No padrão AAA, o que corresponde à fase "Act"?
- Configurar o objeto testado antes da execução
- Fazer afirmações sobre o resultado esperado
- Agir sobre o objeto x
- Destruir o objeto de teste ao final
- Declarar as variáveis globais do teste
