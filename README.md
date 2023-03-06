# Teste-tecnico-Elofy

Teste Técnico para equipe de QA
Objetivo
Este teste tem como objetivo avaliar as competências técnicas do candidato, assim
como seu entendimento de regras de negócio e sua capacidade de criar cenários de
testes.
Outras soft skills também serão avaliadas, tais como, organização e comunicação.
Definição
Temos uma interface de configuração de réguas, a qual pode ser editada somente se
o usuário possuir permissão em seu perfil.
Cada régua pode possuir diferentes tamanhos, sendo de 1 à 7.
Exemplo de uma régua de tamanho 5:
Análise de negócio
● Os números abaixo de cada campo da régua são os limites, mínimo e máximo.
● Esses limites são configurados separadamente em cada ponto da régua.
● Entre um ponto da régua e outro, não pode existir lacunas nem números
repetidos, ou seja:
○ O campo mínimo não pode ser igual ou menor ao campo máximo do
valor anterior.
○ O mínimo do próximo ponto, deve possuir um intervalo de 0,01 do
máximo do ponto anterior.
● O mínimo e máximo de um ponto, devem estar dentro do valor inserido no
Score.
● O campo Score deve seguir uma sequência lógica:
○ 1, 2, 3, 4... | 2, 4, 6... | 3, 6, 9...
● O campo Score deve aceitar somente números
Desconsiderar o "não aplica" para esse teste.
● Para cada ponto da régua:
○ é necessário inserir um score
○ é necessário inserir um nome
○ é necessário inserir mínimo e máximo
○ é possível inserir uma legenda/descrição
○ é possível alterar a cor
○ é possível informar se deseja um comentário ou não quando o usuário
marcar esse ponto.
● Todas essas validações ocorrem ao clicar em "salvar".
● Caso algum campo não esteja de acordo, deve exibir uma mensagem para o
usuário e destacar o campo em vermelho
● Caso o preenchimento ocorra corretamente, ao clicar em salvar, a aplicação
deve redirecionar o usuário para a lista de réguas já cadastradas no sistema.
● Se o usuário desejar cancelar qualquer alteração realizada, é necessário clicar
em "cancelar", a aplicação deve exibir uma mensagem de confirmação e
redirecionar o usuário para a lista de réguas já cadastradas no sistema.
Resultados esperados
Neste teste, esperamos que o candidato entregue uma lista do que é necessário testar
dentro da configuração das réguas.
Ex.:
● Validar se o usuário selecionou o tamanho da régua
● Validar se o usuário inseriu um nome para régua
Assim por diante (não utilizar os exemplos acima).

1.	Verificar se apenas usuários com permissão de edição de réguas podem acessar a interface de configuração de réguas.
2.	Validar se cada régua deve possuir um tamanho válido de 1 a 7.
3.	Verificar se os números abaixo de cada campo da régua são os limites, mínimo e máximo.
4.	Validar se os limites são configurados separadamente em cada ponto da régua.
5.	Verificar se entre um ponto da régua e outro, não existem lacunas nem números repetidos.
6.	Validar se o campo mínimo não é igual ou menor ao campo máximo do valor anterior.
7.	Verificar se o mínimo do próximo ponto possui um intervalo de 0,01 do máximo do ponto anterior.
8.	Validar se o mínimo e máximo de um ponto estão dentro do valor inserido no Score.
9.	Verificar se o campo Score segue uma sequência lógica: 1, 2, 3, 4... | 2, 4, 6... | 3, 6, 9...
10.	Validar se o campo Score aceita somente números.
11.	Verificar se para cada ponto da régua é necessário inserir um score.
12.	Validar se para cada ponto da régua é necessário inserir um nome.
13.	Verificar se para cada ponto da régua é necessário inserir mínimo e máximo.
14.	Validar se é possível inserir uma legenda/descrição para cada ponto da régua.
15.	Verificar se é possível alterar a cor de cada ponto da régua.
16.	Validar se é possível informar se deseja um comentário ou não quando o usuário marcar esse ponto.
17.	Verificar se todas as validações ocorrem ao clicar em "salvar".
18.	Validar se a aplicação exibe uma mensagem para o usuário e destaca o campo em vermelho caso algum campo não esteja de acordo.
19.	Verificar se ao clicar em salvar, a aplicação redireciona o usuário para a lista de réguas já cadastradas no sistema caso o preenchimento ocorra corretamente.
20.	Validar se ao clicar em "cancelar", a aplicação exibe uma mensagem de confirmação e redireciona o usuário para a lista de réguas já cadastradas no sistema caso o usuário deseje cancelar qualquer alteração realizada.
