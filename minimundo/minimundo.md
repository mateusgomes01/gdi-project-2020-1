# Minimundo

## gitboomer

Um gitboomer possui multiplos usuarios, multiplas organizações, multiplos repositóros. Repositórios podem possuir um ou mais ramos. Ramos podem possuir um ou mais arquivos. Usuários podem ser comum ou premium. Repositórios podem ser públicos ou privados. 

Usuários podem possuir repositórios e organizações. Repositórios podem pertencer a um usuário ou a uma organização. Uma organização pode possuir um ou mais repositórios. Usuários podem pertencer a uma ou mais organizações. Uma organização deve possuir um ou mais usuários.

Usuários podem possuir repositórios locais ou remotos (aqui podemos dividir em 2 tipos de repositório usando herança. Lembrar para colocar mais tarde). Repositórios devem possuir um ou mais ramos. Um ramo pode possuir um ou mais arquivos. Usuários podem ler, escrever e acrescentar em arquivos de ramos de repositórios os quais pertencem a ele ou que ele seja um colaborador.

Ramos devem possuir um ou mais commits. Um commit deve pertencer a um ou mais ramos. Um commit pode possuir um ou mais arquivos. Um arquivo pode estar contido em um ou mais commits. Usuários podem possuir um ou mais commits. Um commit deve pertencer a um usuário. Um usuário pode editar ou apagar um ou mais commit que pertençam a ele. Um commit pode ser editado ou apagado por um usuário que o possua.

Descrição do Minimundo

Um empregado tem CPF, nome, sexo, salário, data de nascimento, um ou
mais telefones e um endereço (formado por descrição e CEP). Um empregado
pode supervisionar outros empregados, os quais podem ser supervisionados por
um único empregado.
Ao longo de sua vida na empresa, o empregado pode trabalhar em vários
departamentos, nos quais podem trabalhar vários empregados. Além do
histórico dos departamentos em que cada empregado trabalhou, pede-se que
seja guardado o código e a descrição dos departamentos. Um empregado pode
chefiar um departamento, o qual deve ser chefiado por um único empregado.
Um empregado que trabalha em um departamento pode receber uma
gratificação, a qual pode ser usufruída por outros empregados. Ressalta-se que
toda gratificação tem um código e uma descrição.
Empregados podem participar de vários projetos, os quais podem envolver
vários empregados. Todo projeto tem um código, uma descrição e um valor. Todo
empregado que participa em um projeto deve realizar atividades, as quais
podem ser realizadas por outros empregados no mesmo projeto. Toda atividade
tem um código e uma descrição.
Empregados podem ser graduados ou técnicos. Para os empregados
técnicos, pede-se que seja guardada a sua última série de estudo. Para os
empregados graduados, pede-se que sejam guardadas todas as suas titulações,
incluído as datas em que estas foram obtidas. Ressalta-se que as titulações de um
empregado devem ser identificadas a partir do seu CPF.
Toda titulação de um empregado é outorgada por uma IES (Instituição de
Ensino Superior), que pode outorgar várias titulações. Pede-se que seja
registrado o código, o nome e a sigla das IES. Toda titulação de um empregado
tem um grau, que tem um código, um tipo (Graduação, Especialização, Mestrado
ou Doutorado) e pode ser de várias titulações.

Recife, [dia] de [mês] de [ano].

O seu minimundo deve ter, no mínimo, todos os elementos abaixo:  

* Atributo simples;
* Atributo composto;
* Atributo multivalorado;
* ~~Relacionamento 1:1;~~
* ~~Relacionamento 1:N;~~
* ~~Relacionamento M:N;~~
* Relacionamento identificador;
* ~~Relacionamento com participação obrigatória;~~
* Auto-relacionamento com papel;
* Relacionamento ternário;
* Relacionamento com atributo comum;
* Relacionamento com discriminador;
* Entidade associativa;
* Especialização.

Atenção:
* ~~Pelo menos 03 atributos por entidade;~~
* ~~Pelo menos 01 atributo de tipo numérico;~~
* ~~Pelo menos 01 atributo de tipo data;~~
* Não pode haver entidade livre.
