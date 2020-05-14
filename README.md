# SISTEMA FINANCEIRO DE CLÍNICA

# OPÇÕES DO MENU PRINCIPAL

## CADASTROS

  - Empresa
    - para criar a empresa (clínica), pode ter mais de uma
      - cd_empresa
      - razao_social
      - nome_fantasia
      - cnpj
      - incricao_municipal
      - conselho
      - conselho_numero
      - logradouro_tipo
      - logradouro_nome
      - logradouro_nome
      - logradouro_bairro
      - logradouro_complemento
      - logradouro_cep
      - fone1_ddd
      - fone1_numero
      - fone2_ddd
      - fone2_numero
      - fone3_ddd
      - fone3_numero
      - contato1_nome
      - contato1_setor
      - contato2_nome
      - contato2_setor
      - contato3_nome
      - contato3_setor
      - email1
      - email2
      - site
      - logomarca
      - percentual_multa_por_atraso
      - percentual_juros_por_mes
      - desconto_maximo_permitido
      - ativo

  - Clínicas
    - para criar as clínicas que irão realizar atendimentos para a empresa
      - cd_clinica
      - razao_social
      - nome_fantasia
      - cnpj
      - inscricao_municipal
      - conselho
      - conselho_numero
      - logradouro_tipo
      - logradouro_nome
      - logradouro_nome
      - logradouro_bairro
      - logradouro_complemento
      - logradouro_cep
      - fone1_ddd
      - fone1_numero
      - fone2_ddd
      - fone2_numero
      - fone3_ddd
      - fone3_numero
      - contato1_nome
      - contato1_setor
      - contato2_nome
      - contato2_setor
      - contato3_nome
      - contato3_setor
      - data_contrato_inicio
      - data_contrato_cancelamento
      - email1
      - email2
      - site
      - logomarca
      - ativo

  - Banco

  - Agência

  - Conta

  - Operações Financeiras
    - Exemplo
      - TED
      - DOC
      - Depósito em conta
      - Cartão Débito
      - Cartão Crédito
      - Cheque
      - Dinheiro

  - Médicos
    - para criar os médicos que atendem na clínica, o mesmo médico pode
      atender em mais de uma clínica
      - cd-medico
      - nome
      - conselho_sigla
      - conselho_numero
      - fone1_ddd
      - fone1_numero
      - fone2_ddd
      - fone2_numero
      - celular1_ddd
      - celular1_numero
      - celular2_ddd
      - celular2_numero
      - email1
      - email2
      - site
      - data-cadastro
      - ativo

  - Planos
    - para criar os planos de cobertura com seus respectivos valores iniciais
      (iniciais porque tem reajustes anuais)
      - cd-plano
      - descricao
      - observacoes
      - ativo

  - Beneficiários
    - para cadastrar os clientes que podem ser Títular ou Dependente, o valor
      da mensalidade deve ficar amarrado a cada beneficiário pois o reajuste
      é individual
    - cada dependente é amarrado a um titular
    - além dos campos cadastrais normais tem que ter campo para dia do vencimento
      - cd_beneficiário
      - nome
      - cpf
      - rg
      - orgao_expedidor
      - cartao_sus
      - outro_sistema
      - matricula
      - tipo_logradouro
      - logradouro
      - numero_logradouro
      - complemento_logradouro
      - bairro
      - cep
      - cidade
      - uf
      - fone_residencial
      - fone_comercial
      - fone_celular
      - fone_recados
      - data_cadastro
      - ativo
      - cd_vendedor
      - dia_vencimento
      - email1
      - email2
      - ativo

  - Relatórios
      - Clínicas: todos os dados cadastrais
      - Banco
      - Agência
      - Conta
      - Operações Financeiras
      - Médicos
      - Planos
      - Beneficiários: com filtro para período de cadastro / ativos Sim ou Não / em ordem alfabética

## CONTAS A RECEBER

  - Títulos Receber
    - Incluir/Alterar/Cancelar/Baixa
      - não se pode excluir títulos
      - para cancelar é necessário um motivo
      - ao realizar baixa o usuário escolhe a operação financeira
      - ao cancelar deve solicitar senha definida em Configurações, anotar o nome do usuário que cancelou, a data e o motivo

  - Baixa via arquivo retorno do banco

  - Gera Mensalidades
    - essa opção vai pegar todos os titulares e seus dependentes e gerar um
      título no contas a receber em nome do titular com o valor total e com
      o dia do vencimento constante no cadastro do titular

  - Relatórios
    - Títulos em Aberto: pedir período
    - Títulos Pagos: pedir período
 
## CONFIGURAÇÕES:
   - Senhas gerais
   - Usuários: deve ter 4 níveis de acesso: Operador / Supervisor / Gerencia / Administrador
   - 
