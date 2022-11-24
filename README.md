## Desafio TDD resolvido

Implemente as funcionalidades necessárias para que os testes do projeto passem

---

### TDD - Test Driven Development
É um método de desenvolver software. Consiste em um desenvolvimento guiado pelos testes.

* Princípios / vantagens:
  * Foco nos requisitos
  * Tende a melhorar o design do código, pois o código deverá ser testável
  * Incrementos no projeto têm menos chance de quebrar a aplicação

* Processo básico:
  * Escreva o teste como esperado (naturalmente que ele ainda estará falhando)
  * Implemente o código necessário para que o teste passe
  * Refatore o código conforme necessidade


---

### Boas práticas e padrões
* Nomenclatura de um teste

`<AÇÃO> should <EFEITO> [when <CENÁRIO>]`

* Padrão AAA
  * Arrange: instancie os objetos necessários
  * Act: execute as ações necessárias
  * Assert: declare o que deveria acontecer (resultado esperado)

Princípio da inversão de dependência (SOLID)
  * Se uma classe A depende de uma instância da classe B, não tem como testar a classe A isoladamente. Na verdade nem seria um teste unitário.
  * A inversão de controle ajuda na testabilidade, e garante o isolamento da unidade a ser testada.

* Independência / isolamento
  * Um teste não pode depender de outros testes, nem da ordem de execução

* Cenário único
  * O teste deve ter uma lógica simples, linear
  * O teste deve testar apenas um cenário
  * Não use condicionais e loops

* Previsibilidade
  * O resultado de um teste deve ser sempre o mesmo para os mesmos dados
  * Não faça o resultado depender de coisas que variam, tais como timestamp atual e valores aleatórios.
  
  ---
### Annotations usadas nas classes de teste 
  
![anotações](https://github.com/Dev-HideyukiTakahashi/devsuperior-tests/blob/main/anotations.png)


