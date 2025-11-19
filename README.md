 README – Plataforma Educacional "Pega o Bit" (Python – Terminal)
 Descrição do Projeto

“Pega o Bit” é uma plataforma educacional desenvolvida em Python, executada no terminal, com o objetivo de auxiliar estudantes na introdução à tecnologia.
O sistema oferece login/cadastro, aulas teóricas, questionários automáticos e registro de notas, além de gerar usuários falsos com o Faker para testes.

O programa também inclui:

Geração automática de usuários com dados realistas

Sistema de login e senha

Cursos com conteúdos educativos

Questionários com correção automática

Sistema de pontuação e armazenamento de notas

Arquivos JSON como banco de dados

Interface colorida com colorama

 Funcionalidades
 Autenticação

Login de alunos

Cadastro com validação de idade

Senhas geradas automaticamente ou inseridas manualmente

 Cursos Disponíveis

Cada curso possui conteúdo explicativo + questionário:

1. Pensamento Lógico Computacional

Pilares

Competências

Conceitos básicos

Questionário com atualização de nota

2. Infraestrutura Computacional

Hardware, software e redes

Componentes essenciais

Questionário com correção automática

3. Cibersegurança

Conceito

Tipos de segurança

Principais ameaças

Questionário avaliativo

Sistema de Notas

Cada resposta correta soma pontos

Notas são armazenadas no arquivo usuarios_notas.json

O aluno pode consultar seu desempenho no menu

Gerenciamento de Dados

Usuários gerados automaticamente com Faker

Dados salvos em:

usuarios.json
usuarios_notas.json


Cada usuário possui:

nome

senha

idade

nota acumulada

data de entrada

tempo logado

Tecnologias Utilizadas

Python 3.x

colorama – para interface colorida no terminal

Faker – geração de dados falsos

JSON – armazenamento dos dados

datetime – cálculo de tempo logado

Como Executar

Instale as dependências:

pip install colorama faker


Execute o programa:

python pim.py


Navegue pelos menus no terminal.

Estrutura do Projeto
/Projeto
│-- pim.py
│-- usuarios.json
│-- usuarios_notas.json
│-- README.md

Pontos de Destaque do Código

Estrutura organizada por funções

Questionários com lógica de pontuação

Geração realista de usuários com Faker

Salvamento automático de progresso

Interface amigável com cores e menus

Melhorias Futuras

Separar funções em módulos (login.py, cursos.py, etc.)

Criar interface gráfica com Tkinter ou web com Flask

Adicionar sistema de administrador

Implementar ranking de alunos

Criar mais cursos e questionários

Autor

João Pedro Silva
Estudante de Análise e Desenvolvimento de Sistemas
