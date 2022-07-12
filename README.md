# Princípios SOLID


<b>Single Responsibility Principle (SRP)</b>, ou, <b>Princípio da Responsabilidade Única</b>. Esse princípio diz que as classes devem ser coesas, ou seja, terem uma única responsabilidade. Classes assim tendem a ser mais reutilizáveis, mais simples, e propagam menos mudanças para o resto do sistema.

<img src="/img/single-responsibility-principle.jpg" width="500px" height="400px" alt="Single Responsibility Principle"/>

</br></br>

<b>Open Closed Principle (OCP)</b>, ou <b>Princípio do Aberto Fechado</b>. Diz que as classes devem poder ter seu comportamento facilmente estendidas quando necessário, por meio de herança, interface e composição. Ao mesmo tempo, não deve ser necessário abrir a própria classe para realizar pequenas mudanças. No fim, o princípio diz que devemos ter boas abstrações espalhadas pelo sistema.

<img src="/img/open-closed-principle.jpg" width="500px" height="400px" alt="Open Close Principle"/>

</br></br>

<b>Liskov Substitution Principle (LSP)</b>, ou <b>Príncipio da Substituição de Liskov</b>. Esse princípio diz que precisamos ter cuidado para usar herança. Herança é um mecanismo poderoso, mas deve ser usado com parcimônia, evitando os casos de Gato-estende-Cachorro, apenas por possuírem algo em comum.

<img src="/img/liskov-substitution-principle.jpg" width="500px" height="400px" alt="Liskov Substitution Principle"/>

</br></br>

<b>Interface Segregation Principle (ISP)</b>, ou <b>Princípio da Segregação de Interfaces</b>. Esse princípio diz que nossos módulos devem ser enxutos, ou seja, devem ter poucos comportamentos. Interfaces que tem muitos comportamentos geralmente acabam se espalhando por todo o sistema, dificultando manutenção.

<img src="/img/interface_segregation_principle.jpg" width="500px" height="400px" alt="Interface Segregation Principle"/>

</br></br>

<b>Dependency Inversion Principle (DIP)</b>, ou <b>Princípio da Inversão de Dependências</b>. Esse princípio diz que devemos sempre depender de abstrações, afinal abstrações mudam menos e facilitam a mudança de comportamento e as futuras evoluções do código.

<img src="/img/dependency-inversion-principle.jpg" width="500px" height="400px" alt="Interface Segregation Principle"/>
