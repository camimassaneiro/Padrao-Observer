# Padrao-Observer
Atividade realizada na aula de Padrões de Projeto pela Universidade do Estado de Santa Catarina - UDESC

## Problema: Nosso sistema precisa permitir que o cliente envie a mensagem com o problema que deseja solucionar.

### Solução: Implementar os observadores no programa onde o suporte envia uma mensagem ao cliente para solução do problema.

Intenção: Definir a dependência um para muitos entre objetos, de maneira que quando um objeto muda de estado todos os seus dependentes são notificados e atualizados automaticamente.

Aplicabilidade - Use o padrão Observer quando:
	- Quando uma abstração tem dois aspectos, um dependente do outro. Encapsulando esses aspectos em objetos separados, permite-se variá-los e reutilizá-los independentemente.
	- Quando uma mudança em um objeto exige mudanças em outros, e você não sabe quantos objetos necessitam ser mudados.
	- Quando um objeto deveria ser capaz de notificar outros objetos sem fazer hipóteses, ou usar informações, sobre quem são esses objetos. Em outras palavras, você não quer que esses objetos sejam fortemente acoplados.
  
Estrutura

![Estrutura Observer]()
