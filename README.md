
# Calculadora Simples  

Esta é uma aplicação simples de calculadora com funcionalidades de soma, subtração, multiplicação e divisão.  


## Instalação  

Para instalar as dependências, execute o comando:  

 npm install jest --save-dev


##Teste

Após baixar, va no terminal e execute o comando:

npm test



### Relatório de Automação de Testes  

Utilizei o framework Jest para criar um conjunto de testes automatizados para uma aplicação simples de calculadora. A calculadora implementa quatro operações básicas: soma, subtração, multiplicação e divisão. A realização dos testes foi fundamental para validar cada uma dessas operações e garantir a integridade dos resultados, especialmente no caso da divisão, onde implementamos uma verificação para evitar a divisão por zero.  

Durante a criação dos testes, enfrentei desafios como a formulação de cenários que cobrissem todas as operações e casos de erro, especialmente para a divisão. No entanto, isso aprofundou meu entendimento sobre a importância de considerar diferentes cenários em testes automatizados.  

A automação de testes é crucial para garantir a qualidade do software, pois permite detectar falhas precocemente e reforça a confiança nas funcionalidades desenvolvidas. A implementação e organização dos testes foram feitas de forma clara e o projeto foi estruturado conforme as melhores práticas, assegurando que cada parte do código está bem documentada e compreensível.  

### Principais Cenários Cobridos  
- Testes básicos de adição, subtração, multiplicação e divisão.  
- Tratamento de exceções para divisão por zero.  

### Conclusão  
O uso de Jest se mostrou eficiente e eficaz para a automação de testes. A cobertura dos principais cenários foi satisfatória, garantindo a funcionalidade da calculadora.  
