# MestreDosCodigos
https://db1group.github.io/mestre-dos-codigos/#/dotnet?id=n%C3%ADvel-escudeiro

Perguntas teóricas de introdução

1) Em quais linguagens o C# foi inspirado?  

    C# é uma linguagem baseada em C e C++ e foi inspirada na criação da linguagem Java.

2) Inicialmente o C# foi criado para qual finalidade?

    Foi criada para ser uma linguagem com foco na compilação de soluções de alto nível, com o objetivo de simplificar de modo significativo a complexidade como por exemplo o C++ tem, e trazendo novos elementos em relação ao Java

3) Quais os principais motivos para a Microsoft ter migrado para o Core?

    Desenvolvimento em multiplataforma, funcionar nas plataformas Linux e no Mac além do Windows, além de necessidades técnicas para evolução tecnologica

4) Cite as principais diferenças entre .Net Full Framework e .Net Core.

    Com o Net Core você pode tem o desenvolvimento em multiplataforma, maior performasse, possibilidade de usar containers do docker

Trabalhando no Console 
  Projetos estão numerados de acordo com os exercicios
  
Utilizando POO
1) Responda e demonstre no código os itens abaixo:
  
     O que é POO?

      Programação orientada a objeto, sai da ideia da programação estruturada, e tenta trazer mais para o mundo real, manipulando objetos de forma separada, e tras algumas vantagens no desenvolvimento, como o a reutilização de códigos.

     O que é polimorfismo?

      Polimofirmos é aplicado quando um objeto aplica uma herança, ou seja, herda comportamento de um outro objeto "pai", o polimorfismo é o conceito que permite alterar esses métodos de acordo com a necessidade de cada objeto "filho".
      
    ![image](https://user-images.githubusercontent.com/66972790/115273909-82c17100-a116-11eb-8c1c-93dfdbbe8144.png)

     O que é abstração?
     
      Um objeto possui elementos e caracteristicas que o definem, na POO isso são as propriedades, além de ter ações, que são os métodos. A abstração consiste em definir quais serão as caracteristicas e ações de um objeto, de uma forma geral e podendo ser usadas para definir um padrão que serão usados na criação de outros objetos, que poderão ser apenas usados a mesma implementação da classe abstrata ou uma implementação específica usando o polimorfismo citado no item acima.
      
      ![image](https://user-images.githubusercontent.com/66972790/115274088-aedcf200-a116-11eb-971f-5c65e8043f24.png)

     O que é encapsulamento?
     
     Encapsulamento é uma técnica para evitar dar o acesso direto as propriedades do objeto, adicionando uma outra camada para a segurança, possibilitando fazer tratamentos especificos para receber e disponibilizar informações do objeto, normalmente são feitos usando métodos getters e setters.
     
     ![image](https://user-images.githubusercontent.com/66972790/115274158-c4521c00-a116-11eb-8b3b-4072715f339c.png)


     Quando usar uma classe abstrata e quando devo usar uma interface?
     
     Uma interface é usada quando se quer apenas definir o esqueleto, sem nenhum implementação, deixar apenas definido as assinaturas dos métodos para serem implementadas pelos objetos que implementaram a interface. Já uma classe abstrata é usada quando se quer ter parte da implementação definida num objeto pai, ou implementações de métodos feitos para serem usados nos objetos que implementaram essa classe abstrata.
     
     ![image](https://user-images.githubusercontent.com/66972790/115274489-1bf08780-a117-11eb-957a-62584f965cf4.png)


     O que faz as interfaces IDisposable, IComparable, ICloneable e IEnumerable?
     
     IDisposable, trás a assinatura de um método Dispose, ela é usada principalmente para liberar recursos não gerenciados, já que o coletor de lixo automaticamente libera a memória alocada para um objeto gerenciado quando esse objeto não é mais usado, portanto usamos o método Dispose para liberar recursos não gerenciados explicitamente.
     
     ![image](https://user-images.githubusercontent.com/66972790/115321089-7f9ba480-a159-11eb-936f-ef6e2d71eaee.png)
     
     IComparable, trás a assinatura de um método CompareTo, essa método retorna um inteiro, é usada para obrigar a implementação da comparação de dois elemento o enviado por parametro e o proprio objeto que é implementado, é usado normalmente para definir critério para dizer se dois objetos são iguais, ou para realizar ordenações em combinação com o método Sort
     
     ![image](https://user-images.githubusercontent.com/66972790/115319350-02226500-a156-11eb-9f1e-a8e873e21468.png)
     
     ICloneable, trás a assinatura de um método Clone, que permite que seja clonado um objeto, criando uma nova instancia, com os mesmo valores do objeto inicial
     
     ![image](https://user-images.githubusercontent.com/66972790/115319656-a86e6a80-a156-11eb-8935-245a43ea213e.png)

     IEnumerable, trás a assinatura de um método GetEnumerator, que por sua vez é de uma interface IEnumerator que retorna um objeto que implementa a interface IEnumerator, que é responsavel por permitir as interações de listas, para usarmos um foreach por exemplo, aonde é usado internamente o método MoveNext
     
     ![image](https://user-images.githubusercontent.com/66972790/115320507-6d6d3680-a158-11eb-9231-fe9760d980dc.png)

     Existe herança múltipla (de classes) em C#?
     
     Não, só é permitido uma herança no C#, um objeto pode implementar várias interfaces, porém apenas herdar de uma classe base




 Trabalhando com testes
    Quais os principais frameworks que podemos usar no desenvolvimento de testes?
      
     MSTest, NUnit e xUnit


