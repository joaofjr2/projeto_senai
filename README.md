CONTROLE DE VERSÕES
# DESAFIO 01:
•	Com suas palavras defina o que é um sistema de controle de versões (VCS)?
•	Cite 5 vantagens em utilizar um VCS
•	Cite 3 exemplos de VCS


Um sistema de controle de versões (VCS) é uma ferramenta essencial para gerenciar mudanças em arquivos e projetos ao longo do tempo. Ele funciona como um "historiador digital", registrando todas as alterações, quem as fez e quando foram realizadas. Isso é especialmente útil em projetos colaborativos, onde várias pessoas trabalham nos mesmos arquivos simultaneamente.
Com um VCS, é possível voltar no tempo e recuperar versões anteriores caso algo dê errado, evitando a perda de trabalho. Além disso, ele permite trabalhar em paralelo, onde novas funcionalidades ou correções podem ser testadas sem afetar a versão principal do projeto.
Possibilita a resolução de conflitos já que o sistema ajuda a identificar e mesclar mudanças feitas por diferentes pessoas. E parte de sua função é armazenar e compartilhar código de forma organizada.
Em resumo, um sistema de controle de versões que traz segurança, organização e eficiência para qualquer projeto, seja de programação, design ou documentação. Sem ele, gerenciar mudanças seria caótico e propenso a erros irreversíveis.


5 VANTAGENS EM UTILIZAR UM VCS:
Histórico Completo – Mantém um registro detalhado de todas as alterações, permitindo voltar a versões anteriores se algo der errado.
Trabalho em Equipe Facilitado – Várias pessoas podem colaborar no mesmo projeto sem sobrescrever o trabalho umas das outras, com controle de mudanças e autoria.
Prevenção de Perda de Dados – Como todo o histórico é salvo, arquivos excluídos ou corrompidos podem ser recuperados facilmente.
Branches (Ramos) para Experimentação – Permite criar linhas de desenvolvimento paralelas (branches) para testar novas funcionalidades sem afetar a versão principal.
Integração e Deploy Contínuo – Facilita a automação de testes e a implantação de atualizações, essencial para DevOps e CI/CD (Integração Contínua/Entrega Contínua).

3	Exemplos de VCS

Git: Mais popular, flexível e poderoso (mas complexo).

Subversion (SVN) SVN: Centralizado, bom para controle rígido de versões.

Mercurial (Hg) Mercurial: Simplicidade e eficiência, porém menos difundido que Git.


# Desafio 02:

Crie uma nova branch em seu repositório local com o nome "desafio02",

responda as perguntas no documento README.md:


Com suas palavras defina o que é programação orientada a objetos (POO) e cite seus pilares? (mínimo 10 linhas);

A Programação Orientada a Objetos (POO) é um paradigma de programação que organiza o código em estruturas chamadas de objetos, que representam entidades do mundo real ou conceitos abstratos. Esses objetos possuem atributos (características) e métodos (ações/comportamentos). A POO visa tornar o código mais modular, reutilizável e de fácil manutenção, aproximando a modelagem de software de como pensamos no mundo real.


Seus quatro pilares são:

•	Abstração: Simplificar complexidades, focando no essencial.
•	Encapsulamento: Proteger dados e expor apenas o necessário.
•	Herança: Reutilizar e estender características de classes existentes.
•	Polimorfismo: Permitir que um mesmo método se comporte de formas diferentes.

Exemplifique e explique um cenário de abstração;

Exemplo de Abstração

Cenário: Um sistema de reserva de hotéis.
Em vez de modelar todos os detalhes de um hotel (como tubulações elétricas ou materiais da construção), a abstração foca no que é relevante para o sistema:
•	Atributos: Nome, localização, número de quartos, preço.
•	Métodos: reservarQuarto(), verificarDisponibilidade().
Aqui, ignoramos detalhes irrelevantes (como a cor das paredes) e destacamos apenas o necessário para o contexto.

Exemplifique e explique um cenário de encapsulamento;

Cenário: Uma classe ContaBancaria.

Os atributos como saldo e senha são privados (não acessíveis diretamente). Para interagir com eles, usamos métodos controlados:


Exemplifique e explique um cenário de herança;

Cenário: Sistema de veículos.

Uma classe Veiculo (superclasse) define atributos/métodos genéricos (marca, acelerar()), enquanto subclasses como Carro e Moto herdam e especializam esses comportamentos:
Exemplifique e explique um cenário de polimorfismo;
 Exemplo de Polimorfismo
Cenário: Sistema de formas geométricas.
Diferentes classes (Circulo, Quadrado) implementam um método calcularArea() de formas distintas, mas com a mesma assinatura:

Cite 5 vantagens da POO.

Vantagens da POO

1.	Reutilização de código: Herança e composição reduzem duplicação.
2.	Manutenibilidade: Código organizado em objetos facilita ajustes.
3.	Modularidade: Componentes isolados (classes) são mais testáveis.
4.	Segurança: Encapsulamento protege dados inconsistentes.
5.	Escalabilidade: Modelagem próxima do mundo real simplifica expansão.


