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

O Code::Blocks cuida automaticamente de:

Criação do executável (.exe)

Configuração do compilador

Inclusão das bibliotecas padrão

Execução do programa pelo botão Build & Run (F9)

Como rodar o projeto no Code::Blocks:

Abra o Code::Blocks

Clique em File → New → Project → Console Application → C

Cole o código do main.c

Salve o projeto

Clique Build & Run (F9)

 Não é necessário usar terminal ou comando gcc no Windows. O Code::Blocks resolve tudo.

--Funcionalidades Implementadas--
 
 Cadastro

[x]cadastrar_cliente()

[x]cadastrar_funcionario()

[x]cadastrar_quarto()

[x] Estadia

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

-[x]Cadastro de cliente-

-[X]Cadastro de funcionário-

-[x]Cadastro de quarto-

-[x]Cadastro de estadia-

-[x]Cálculo de diárias-

-[ ]Baixa de estadia-

-[x]Pesquisas por nome e código-

-[ ]Fidelidade-

-[ ]Relatórios-

-[x]Persistência em arquivos binários-

-[ ]Menu principal-

Sprints do Projeto (Daniel, Vinicius e Marco)

 Sprint 1 – Base e Cadastros

![sprint 1](https://github.com/user-attachments/assets/4bf7010d-e9d6-446a-aea1-41e3fe0f1878)

 Daniel

-[x]Estruturas (struct)

-[x]Arquivos .dat

-[x]Cadastro de clientes

-[x]Código automático

-[x]Caso de teste de cliente

-[x]Função case_insensitive_search()

 Vinicius

-[X]Cadastro de funcionário

-[X]Validação de código

-[X]Teste do módulo

 Marco

-[x]Cadastro de quarto

-[x]Validação de número

-[x]Status inicial

-[x]Teste do módulo

Sprint 2 – Lógica Avançada

![WhatsApp Image 2025-12-05 at 19 56 23](https://github.com/user-attachments/assets/d217c5ff-43bc-499c-95d9-7822d85d023d)

 Daniel

-[x]Cadastro de estadia

-[x]Verificação de disponibilidade

-[x]diff_days()

-[x]encontrar_quarto_disponivel()

-[x]Atualização de status

-[ ]Teste da função

 Vinicius

-[x]Baixa de estadia

-[x]Cálculo de valor total

-[x]Atualização de status

-[x]Testes

 Marco

-[]Pesquisas (cliente/funcionários-

-[]Relatórios

-[]Fidelidades

-[]Testes

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
