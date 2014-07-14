# A apresentação

## Agenda
## Introdução
### Quem somos?
### Porque o título da palestra é tão grande? 

Explicar que o título da palestra é uma síntese de várias coisas que queríamos colocar
no mesmo assunto, e por isso acabou ficando grande. A ideia é apenas um modelo que poderia guiar a implementação de testes, e está baseado em nossas experiencias em sistemas legados.
* Especificações: apresentar a idéia de que especificações podem seguir um modelo, para facilitar a comunicação. O livro Specification by Example fala bastante disso, especialmente sobre *executable specifications* e sobre o quão importante é para comunicação entre as partes do projeto que a especificação não seja *traduzida* para linhas de código complexas, pois informação se perde durante essa tradução. Tentamos usar o conceito de *specification by example* como base para este modelo, ou seja, "*especificações que se transformam em referências do que o sistema, tão relevantes quanto o código fonte, porém mais fáceis de ler*"
* testes funcionais e de interface Web: apresentar a idéia de que pensamos em testes de alto nível em duas frentes: testes funcionais e testes de interface, porque é o que muitas empresas com sistemas legados, especialmente antigos, considera como garantia de que o sistema funciona. Antes de tentar instaurar conceitos mais básicos como o uso de testes unitários e testes adequados por camada da aplicação, pode ser mais fácil atacar o ponto onde a empresa já acredita ser a solução para testes, como forma de iniciar o diálogo mais profundo sobre o que é ou não é teste de software.
Ainda é importante salientar os conceitos que consideramos:
** testes funcionais: conforme o livro "Continuous Enterprise Development with Java" (dentre outros, deve ter fonte mais forte), é o teste que garante que as funcionalidades atingem os requisitos de negócio (todas as funções fazem aquilo que é esperado delas)
** testes de interface: verificar, através da interface do sistema, que os requisitos do sistema são atingidos. Ainda que a ideia de cobertura extensiva através da interface venha caindo por terra (http://www.thoughtworks.com/radar/#/techniques/exhaustive-browser-based-testing), muitas organizações mais resistentes insistem nessa técnica como única ou mais importante técnica de teste.

* em paralelo: explicar que, como o ambiente legado nem sempre possui consistência no que diz respeito a testes ou processo de escrita de testes, é importante que o modelo permita atacar diversas frentes (especificação, testes funcionais, testes de UI, testes de integração...) em paralelo, para que o trabalho não "empaque" ou incite um "cascatismo"
* Spock, Geb e Cucumber-JVM: tecnologia, apenas: como viemos do mundo java procuramos coisas java, mas o modelo é aplicável, com adaptações, para outros sistemas legados.
* para introdução de testes automatizados: *I automate it because time is valuable to me* (http://lyonsinbeta.com/2014/05/why-i-code/)
* ambientes legados: "Legacy code is code without tests" Michael Feathers

## Conceitos básicos
* BDD: Behavior Driven Development
* Specification by Example: como no livro
* UI Tests
* Functional tests

## Apresentação do sistema legado em Java
* apresentamos um sistema legado e sem testes. Podemos fazer um ou achar um na net, o que for mais fácil. Preferencialmente um todo gambiarrento, com Ant e sem testes. Podíamos fazer um cadastro de locadora JEE!
## Idéia de processo para inserção gradual de testes
* em iterações
* ninguém é obrigado a nada...mas o jenkins vai mostrar tudo que não tá coberto!
* corridas: vamos ver quem consegue cobrir mais o sistema
* hackatons
## Apresentação da configuração
## Demonstração da criação de especificações executáveis
## Demonstração da criação de testes unitários, confiando nas especificações executávei
## TDD is dead, isso tem a ver com testes unitários e algumas verdades que também devem ser ditas


