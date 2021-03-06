# Especificações e testes funcionais e de interface Web em paralelo, usando Spock, Geb e Cucumber-JVM, para introdução de testes automatizados em ambientes legados

*Nota importante:* Tudo isso pode mudar :D

## POR ONDE COMEÇAR?

* Na seção [Sobre a palestra](#sobre-a-palestra), o conteúdo que foi enviado ao TDC. 
* Na seção [A apresentação](APRESENTACAO.md), o corpo da apresentação é documentado em mais detalhes, para facilitar a sincronização entre nosso entendimento e usarmos como "cola" no dia da mesma.
* A seção [O que eu faço com isso aqui](#o-que-eu-faco-com-isso-aqui) descreve como utilizar os recursos desse repositório: a apresentação de slides, os códigos-fonte, etc.

## <a name="o-que-eu-faco-com-isso-aqui"/> O que eu faço com isso aqui

* A apresentação em si pode ser em HTML5+CSS+JS, com apoio do [deck.js](http://imakewebthings.com/deck.js/). Para editá-la, verifique a documentação do deck.js e edite o arquivo slides/index.html

## Sobre a palestra

### Quando?

Sexta-Feira, 8 de Agosto de 2014

Duração: 50 minutos

Horário: a definir

### Resumo

Michael Feathers define um sistema legado como um sistema sem testes. A idéia de testes unitários pode parecer impossível as vezes em um código complexo, muito acoplado e com muitos code smells que tiram até a fome! Uma abordagem de mais alto nível, com testes funcionais, de integração ou mesmo de interface pode abrir caminho para o refactoring com segurança e capacidade de previsão. Esta palestra apresenta uma abordagem prática de BDD, demonstrando que é possível sim implementar testes que verifiquem os cenários críticos do sistema e abram caminho para o teste unitário de qualidade e valor agregado.

### Descrição

A idéia da palestra é apresentar um modelo para inserção de testes em sistemas legados através de BDD com cucumber e frameworks para testes funcionais e de tela. Abordagem:
* apresentação do sistema legado em java
* apresentação da configuração e da ideia de processo para inserção gradual de testes
* demonstração da criação de especificações executáveis
* demonstração da criação de testes unitários, confiando nas especificações executáveis

## DICAS E BIBLIOGRAFIAS

### Não digitar sempre a senha do github:
Fonte: https://help.github.com/articles/caching-your-github-password-in-git

git config --global credential.helper cache
git config --global credential.helper 'cache --timeout=3600'
