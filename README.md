Hotel Descanso Garantido – Sistema de Gestão em C

Sistema desenvolvido para as disciplinas:

Fundamentos de Engenharia de Software (FES)

Algoritmos e Estruturas de Dados I (AEDs I)

PUC Minas – Engenharia de Software

O projeto está sendo desenvolvido, testado e executado no Code::Blocks (MinGW), utilizando arquivos binários para persistência e uma arquitetura modular.

**Descrição Geral do Sistema**

O sistema permite gerenciar:

- Clientes
  
- Funcionários
  
- Quartos
  
- Estadias
  
- Cálculo de diárias
  
- Fidelidade por diárias
  
- Pesquisas por código ou nome
  
- Testes automatizados
  
- Limpeza de dados
  

Todo o armazenamento é realizado em:

- clientes.dat
  
- funcionarios.dat
  
- quartos.dat
  
- estadias.dat

**Funcionalidades Implementadas**

Cadastro:

[x] cadastrar_cliente()

[x] cadastrar_funcionario()

[x] cadastrar_quarto()

[x] cadastrar_estadia()

Estadia:

[x] Busca automática de quarto compatível

[x] Verifica sobreposição de períodos

[x] Cálculo automático de diárias (diff_days())

[x] Atualização de status do quarto


Baixa de Estadia:

[x] Cálculo automático do valor total

[x] Atualiza status para "desocupado"

Pesquisas e Relatórios:

[x] Busca por nome/código (cliente/funcionário)

[x] Listar estadias por cliente

[x] Calcular pontos de fidelidade

Utilitários:

[x] Limpeza de arquivos de dados

[x] Testes automatizados

**Backlog do Produto**

[x] Cadastro de cliente

[x] Cadastro de funcionário

[x] Cadastro de quarto

[x] Cadastro de estadia

[x] Cálculo de diárias

[x] Baixa de estadia

[x] Pesquisas por nome e código

[x] Fidelidade

[x] Relatórios

[x] Persistência em arquivos binários

[x] Menu principal

[x] Testes automatizados

[x] Limpeza de dados

**Sprints do Projeto (Daniel, Vinicius e Marco)**

Sprint 1 – Base e Cadastros

Daniel:

[x] Estruturas (struct)

[x] Arquivos .dat

[x] Cadastro de clientes

[x] Código automático

[x] Caso de teste de cliente

[x] Função case_insensitive_search()

Vinicius:

[x] Cadastro de funcionário

[x] Validação de código

[x] Teste do módulo

Marco:

[x] Cadastro de quarto

[x] Validação de número

[x] Status inicial

[x] Teste do módulo

Sprint 2 – Lógica Avançada

Daniel:

[x] Cadastro de estadia

[x] Verificação de disponibilidade
[x] diff_days()

[x] encontrar_quarto_disponivel()

[x] Atualização de status

[x] Teste da função

Vinicius:

[x] Baixa de estadia

[x] Cálculo de valor total

[x] Atualização de status

[x] Testes

Marco:

[x] Pesquisas (cliente/funcionário)

[x] Relatórios

[x] Fidelidade

[x] Testes

[x] Limpeza de arquivos

**Testes Automatizados**

Teste 1: Busca Case-Insensitive

Teste 2: Cálculo de Datas (formato DDMMAAAA)

Teste 3: Cadastro de Cliente

Teste 4: Cadastro de Quarto

Teste 5: Sobreposição de Períodos

Teste 6: Cadastro de Funcionário

Teste 7: Cálculo de Pontos de Fidelidade

Teste 8: Status do Quarto

**Formato de Datas**

- Todas as datas no sistema usam formato DDMMAAAA (dia/mês/ano)
  
- Exemplo: 15/12/2024 é armazenado como 15122024
  
- Função principal: ddmmaaaa_to_time_days()

**Integrantes**

Daniel Ischaber Xavier

Vinicius Daniel Santos

Marco Túlio Sales de Deus
