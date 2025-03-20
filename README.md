Hora de Codar: Atividade 7 - Um Hotel Terabithia
Nesta atividade, o objetivo é desenvolver um sistema para um hotel fictício chamado Hotel Terabithia, utilizando a linguagem de programação Kotlin. O programa é voltado para funcionários do hotel, permitindo que eles realizem diversas operações administrativas diretamente pelo console do IDE. O usuário pode escolher entre várias funcionalidades, como reservar quartos, cadastrar clientes, gerenciar eventos, abastecer o carro do hotel e organizar a manutenção dos ar-condicionados.

Abaixo, descrevo as principais funcionalidades do sistema:

Funcionalidades do Sistema
Reserva de Quartos:

O usuário pode reservar um quarto para um hóspede.

O sistema solicita o valor da diária e a quantidade de dias de hospedagem.

Se o quarto escolhido estiver disponível, o programa calcula o valor total da estadia e pergunta se o usuário deseja confirmar a reserva.

Caso o quarto já esteja ocupado, o sistema sugere outro quarto disponível.

Após a confirmação, os dados da reserva são armazenados.

Cadastro de Clientes:

O usuário pode cadastrar hóspedes no sistema do hotel.

Durante o cadastro, o hóspede informa seu nome e idade.

O sistema verifica se o hóspede tem direito a gratuidade (menores de 6 anos), meia-entrada (maiores de 60 anos) ou deve pagar o valor integral.

Os dados dos hóspedes são armazenados para futuras consultas.

Pesquisar e Cadastrar Hóspedes:

O sistema permite pesquisar se um hóspede já está cadastrado.

Se o hóspede não estiver na lista, o usuário pode cadastrá-lo diretamente.

Os dados dos hóspedes são armazenados para consultas futuras.

Cadastrar Evento:

O usuário pode cadastrar eventos no hotel, como conferências ou festas.

O sistema solicita informações como o nome da empresa, o número de convidados, o horário de início, a duração e o dia do evento.

O hotel possui dois auditórios:

Auditório Laranja: Capacidade para até 220 pessoas.

Auditório Colorado: Capacidade para até 350 pessoas.

O sistema escolhe automaticamente o auditório adequado com base no número de convidados.

Além disso, o programa calcula o número de garçons necessários e o custo do buffet para o evento.

Abastecer o Carro:

O hotel disponibiliza um carro para passeios com os hóspedes.

O sistema compara os preços do álcool e da gasolina em dois postos de combustível: Wayne Oil e Stark Petrol.

O programa verifica qual combustível é mais vantajoso (álcool ou gasolina) e qual posto oferece o melhor custo-benefício.

Se o álcool estiver 30% mais barato que a gasolina, o sistema recomenda o uso de álcool.

Manutenção do Ar Condicionado:

O hotel contrata empresas terceirizadas para realizar a manutenção dos ar-condicionados.

O sistema permite ao usuário cadastrar várias empresas, informando o valor do serviço por aparelho, a quantidade de aparelhos, o percentual de desconto e a quantidade mínima de aparelhos para obter o desconto.

O programa calcula o custo total do serviço para cada empresa e, ao final, exibe qual empresa oferece o melhor custo-benefício.

Tecnologias Utilizadas
O sistema foi desenvolvido utilizando os seguintes conceitos e estruturas da programação em Kotlin:

Programação Estruturada: O código é organizado em funções que realizam tarefas específicas.

Condicionais (if-else e when): Utilizados para tomar decisões com base nas entradas do usuário.

Loops (while): Permitem repetir ações até que uma condição seja satisfeita.

Listas: Armazenam dados como quartos disponíveis, hóspedes cadastrados e orçamentos de empresas.

Como Funciona o Sistema?
Ao iniciar o programa, o usuário é recebido com uma mensagem de boas-vindas e solicitado a inserir seu nome e senha.

Após a autenticação, o usuário acessa um menu principal com todas as funcionalidades disponíveis.

Cada funcionalidade é acessada por meio de uma escolha no menu, e o sistema guia o usuário passo a passo para realizar as operações desejadas.

Ao final de cada operação, o usuário é redirecionado de volta ao menu principal, onde pode escolher outra funcionalidade ou sair do sistema.

Objetivo do Projeto
O objetivo principal desta atividade é criar um sistema modular e funcional para gerenciar as operações de um hotel, utilizando conceitos básicos e intermediários de programação em Kotlin. O projeto combina lógica de programação, estruturas de dados e interação com o usuário para oferecer uma experiência completa e intuitiva.
