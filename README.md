Hotel Descanso Garantido – Sistema de Gestão em C

Sistema desenvolvido para as disciplinas:

Fundamentos de Engenharia de Software (FES)

Algoritmos e Estruturas de Dados I (AEDs I)

PUC Minas – Engenharia de Software

O projeto esta sendo desenvolvido, testado e executado no Code::Blocks (MinGW), utilizando arquivos binários para persistência e uma arquitetura modular.

Descrição Geral do Sistema

--O sistema deve permite gerenciar:--

Clientes

Funcionários

Quartos

Estadias

Cálculo de diárias

Fidelidade por diárias

Pesquisas por código ou nome

Todo o armazenamento é realizado em:

clientes.dat

funcionarios.dat

quartos.dat

estadias.dat


--Ambiente de Desenvolvimento--

Este projeto esta sendo projetado e testado no Code::Blocks 20.03 (Windows / MinGW-GCC).

[ ] O Code::Blocks cuida automaticamente de:

Criação do executável (.exe)

Configuração do compilador

Inclusão das bibliotecas padrão

Execução do programa pelo botão Build & Run (F9)

[ ] Como rodar o projeto no Code::Blocks:

Abra o Code::Blocks

Clique em File → New → Project → Console Application → C

Cole o código do main.c

Salve o projeto

Clique Build & Run (F9)

 Não é necessário usar terminal ou comando gcc no Windows. O Code::Blocks resolve tudo.

--Funcionalidades Implementadas--
 
[ ] Cadastro

cadastrar_cliente()

cadastrar_funcionario()

cadastrar_quarto()

[ ] Estadia

Busca automática de quarto compatível

Verifica sobreposição de períodos

Cálculo automático de diárias (diff_days())

Atualização de status do quarto

[ ] Baixa de Estadia

Cálculo automático do valor total

Atualiza status para “desocupado”

[ ] Pesquisas e Relatórios

Busca por nome/código (cliente/funcionário)

Listar estadias por cliente

Calcular pontos de fidelidade

--Backlog do Produto--

-[ ]Cadastro de cliente-

-[ ]Cadastro de funcionário-

-[ ]Cadastro de quarto-

-[ ]Cadastro de estadia-

-[ ]Cálculo de diárias-

-[ ]Baixa de estadia-

-[ ]Pesquisas por nome e código-

-[ ]Fidelidade-

-[ ]Relatórios-

-[ ]Persistência em arquivos binários-

-[ ]Menu principal-

Sprints do Projeto (Daniel, Vinicius e Marco)

 Sprint 1 – Base e Cadastros

![sprint 1](https://github.com/user-attachments/assets/4bf7010d-e9d6-446a-aea1-41e3fe0f1878)

 Daniel

-[ ]Estruturas (struct)

-[ ]Arquivos .dat

-[ ]Cadastro de clientes

-[ ]Código automático

-[ ]Caso de teste de cliente

-[ ]Função case_insensitive_search()

 Vinicius

-[ ]Cadastro de funcionário

-[ ]Validação de código

-[ ]Teste do módulo

 Marco

-[ ]Cadastro de quarto

-[ ]Validação de número

-[ ]Status inicial

-[ ]Teste do módulo

Sprint 2 – Lógica Avançada

 Daniel

-[ ]Cadastro de estadia

-[ ]Verificação de disponibilidade

-[ ]diff_days()

-[ ]encontrar_quarto_disponivel()

-[ ]Atualização de status

-[ ]Teste da função

 Vinicius

-[ ]Baixa de estadia

-[ ]Cálculo de valor total

-[ ]Atualização de status

-[ ]Testes

 Marco

-[ ]Pesquisas (cliente/funcionários-

-[ ]Relatórios

-[ ]Fidelidades

-[ ]Testes

--Como Executar no Code::Blocks--

--Casos de testes--

-Método recomendado:-

-Abrir o projeto .cbp (ou criar um novo)

-Criar/abrir o arquivo main.c

-Adicionar o código completo

-Pressionar F9 para compilar e executar

--Observações:--

Os arquivos .dat serão criados automaticamente na pasta do executável

Caso queira limpar os dados, basta excluir os .dat

O console é limpo com system("cls") automaticamente (Windows)

 --Integrantes--

Daniel Ischaber Xavier/
Vinicius Daniel/
Marco Túlio Sales de Deus
