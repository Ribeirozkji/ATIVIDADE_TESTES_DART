# PLANO DE TESTE


## IDENTIFICAÇÃO

    **NOME DO SISTEMA: SISTEMA_MATRICULAS**
    **VERSÃO: V1.0.0**
    **TURMA: 3ºB**
    **INTEGRANTES: PEDRO ASSUMPÇÃO**
    **DATA: 13/08/2026 **
    **RESPONSÁVEL: PEDRO ASSUMPÇÃO**

## OBJETIVO 

    O propósito principal do processo é estabelcer a estratégia, o escopo e os procedimentos necessários para validar o sistema de cálculo de matrícula. A intenção é comprovar que por meio de planejamento rigoroso, execução de casos de teste automatizados e manuais que o software atende aos requisitos funcionais e às regras de négocio além de indetificar eventuais defeitos, e validar suas correções

## ESCOPO 

    O escopo deste plano de teste abrange a validação de todas as funcionalidades e regras de négocio

        1. Validação de dados de entrada
        2. Formas de pagamento e restrições
        3. Regras de desconto e acúmulo
        4. Cálculos financeiros
        5. Geração de resumos
        6. Tipos de testes unitários

## FORA DO ESCOPO 

    Os seguintes itens e cénarios que não estão dentro do escopo.

        1.Testes de carga e de estresse
        2.Interface gráfica web e mobile
        3.Segurança e criptografia
        4.Persistência de dados em banco de dados
        5.Testes de usabilidade e acessibilidade

## REQUISITOS

    A tabela e lista abaixo detalham os requisitos funcionais e regras de négocio que o sistema devem atender

      *  RN01 - Nome Obrigatório
      *  RN02 - Idade Mínima
      *  RN03 - Curso Obrigatório
      *  RN04 - Valor do Curso
      *  RN05 - Formas de pagamento válidas
      *  RN06 - Limite de parcelas
      *  RN07 - Restrição de parcelamento via pix
      *  RN08 - Restrição de parcelamento via boleto
      *  RN09 - Desconto via pix
      *  RN10 - Desconto para bolsista
      *  RN11 - Geração de Resumo

## TIPOS DE TESTES

    Para garantir a qualidade e confiabilidade do sistema de matrículas, a estratégia engloba as seguintes abordagens

        1. Testes Unitário
        2. Teste Funcional
        3. Teste de Caixa Preta
        4. Teste de Caixa Branca
        5. Teste de Sitema
        6. Teste de regressão
        7. Reteste

##  AMBIENTE

    Os testes e a execução do sistema de matrículas foram realizados no seguinte ambiente de desenvolvimento e teste
        
        **SISTEMA OPERACIONAL: Windows 11 Pro, Versão 22H2**
        **VERSÃO DO DART: Dart SDK version: 3.12.0**
        **EDITOR DE CÓDIGO: Visual Studio Code**
        **PACOTE DE TESTE: test: ^1.31.2**
        **VERSÃO DO PROJETO: 1.0.0**
        **HARDWARE: 
            1. PROCESSADOR: 11th Gen Intel(R) Core(TM) i7-11800H @ 2.30GHz   2.30 GHz
            2. NOME DO DISPOSITIVO: N60801
            3. RAM INSTALADA: 16,0 GB (utilizável: 15,7 GB)**
        

## DADOS DE TESTES

    1. Válidos: Dados corretos dentro das regras.
    2. Inválidos: Dados foram dos limites ou nulos.
    3. Limites: Valores limítrofes exatos.

## CRITÉRIOS DE ENTRADA
* Código estruturado, pacote `test` instalado, ambiente Dart compilando sem erros e plano de teste elaborado.

## CRITÉRIOS DE SAÍDA
* 100% dos testes executados, defeitos críticos corrigidos e retestados, e documentação finalizada na pasta `documentos/`.

## CRITÉRIOS DE SUSPENSÃO
* Falhas críticas no ambiente/SDK ou erros generalizados no código que impeçam a execução isolada dos testes.

## CRITÉRIOS DE RETOMADA
* Resolução completa dos problemas de ambiente e estabilização do código-fonte.

## RISCOS
1. Divergências de arredondamento de centavos.
2. Incompatibilidade de versões do Dart entre os membros.
3. Atraso na correção de defeitos encontrados.
4. Ambiguidade nas regras de acúmulo de descontos.

## RESPONSABILIDADES
* **Analista de Testes:** Análise de requisitos e planejamento.
* **Executor:** Execução de testes manuais e automatizados.
* **Desenvolvedor:** Correção de bugs no código.
* **Evidências:** Coleta de prints e saídas de terminal.
* **Documentação:** Organização e entrega dos relatórios.

## ENTREGÁVEIS
* `lib/matricula.dart`, `bin/sistema_matriculas.dart`, `test/matricula_test.dart` e os arquivos Markdown (`plano_teste.md`, `casos_teste.md`, `registro_execucao.md`, `relatorio_defeitos.md`, `matriz_rastreabilidade.md`, `relatorio_final.md` e a pasta `evidencias/`).

    Código estruturado, pacote `test` instalado, ambiente Darte comilando sem erros e plano de teste elaborado.
