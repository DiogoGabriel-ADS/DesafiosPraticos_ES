# Controle de Projetos

"Os gerentes de projeto devem conseguir cadastrar novos projetos, incluindo informações como nome do projeto, localização, cliente, escopo inicial e data de início prevista. Além disso, os gerentes de projeto devem conseguir remover, consultar ou alterar um determinado projeto".

Considere que o tech lead da sua squad atribuiu que você elabore uma documentação didática e sintetizada explicando cada uma das propriedades de bons projetos (integridade conceitual; ocultamento de informação; coesão; acoplamento) e dos princípios de bons projetos (SOLID, Prefira Interfaces a Classes e Demeter). Em tal documento, você deve apresentar qual é o propósito e um cenário prático para demonstrar o seu uso de acordo com a funcionalidade de Controle de Projetos previamente mencionada. Se por acaso você não conseguir implementar a referida funcionalidade, tente pelo menos entregar a explicação conceitual de cada propriedade e princípio.

## Propriedades de Bons projetos

### Integridade Conceitual
**Propósito:** Assegurar que o sistema mantenha uma representação unificada e coerente de suas funcionalidades para a melhor resolução de problemas.

**Cenário:** Ao cadastrar um novo projeto no Controle de Projetos da empresa, é necessário certificar se todas as informações essenciais estão presentes e coerentes, como nome, localização e cliente.


### Ocultamento de Informação
**Propósito:** Tornar sistemas de software mais flexíveis e fáceis de entender, protegendo as informações sensíveis e expondo apenas o necessário.

**Cenário:** Quando um gerente de projeto consultar as informações de um projeto específico, verá somente os detalhes relevantes, como nome do projeto e cliente, mantendo os dados sensíveis ocultos.


### Coesão
**Propósito:** Fazer com que os elementos de uma classe (métodos e atributos) se relacionem e foquem na realização de uma única funcionalidade ou serviço.

**Cenário:** Dividir as funcionalidades do Controle de Projetos em módulos distintos, como cadastro, consulta e alteração, garantindo que cada um execute apenas uma tarefa específica e em conjunto executem uma ação maior.


### Acoplamento
**Propósito:** Reduzir as dependências entre diferentes partes do sistema, facilitando modificações e atualizações.

**Cenário:** Utilizar as interfaces para definir contratos entre módulos do Controle de Projetos, permitindo que diferentes partes do sistema evoluam independentemente.


## Princípios de Bons Projetos

### SOLID
#### S - Responsabilidade Única
**Propósito:** Um módulo deve ter apenas uma razão para mudar.

**Cenário:** Criar classes específicas para cada responsabilidade no Controle de Projetos, evitando que classes únicas executem diversas funções.

#### O - Aberto/Fechado
**Propósito:** Um módulo deve estar aberto para extensão, mas fechado para modificação.

**Cenário:** Permitir a extensão de funcionalidades no Controle de Projetos, porém sem alterar o código existente.


#### L - Substituição de Liskov
**Propósito:** Subtipos devem ser substituíveis por seus tipos base.

**Cenário:** Garantir que as classes derivadas no Controle de Projetos possam ser usadas, em vez de suas classes base, sem afetar o comportamento do sistema.


#### I - Segregação de Interface
**Propósito:** Muitas interfaces específicas são melhores do que uma única interface geral.

**Cenário:** Preferir interfaces específicas para cada parte do Controle de Projetos, evitando interfaces grandes e genéricas.


#### D - Inversão de Dependência
**Propósito:** Módulos de alto nível não devem depender de módulos de baixo nível, ambos devem depender de abstrações.

**Cenário:** Utilizar-se da injeção de dependência para permitir a substituição de implementações no Controle de Projetos sem modificar o código cliente.


### Prefira Interfaces a Classes
**Propósito:** Permitir maior flexibilidade e adaptabilidade ao projetar sistemas.

**Cenário:** Utilizar interfaces para definir contratos claros, permitindo diferentes implementações.


### Demeter
**Propósito:** Evitar dependências indesejadas entre componentes.

**Cenário:** Ao alterar um projeto, interagir apenas com objetos imediatamente relacionados, evitando acessar objetos indiretamente relacionados.
