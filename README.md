# Small Scale Service Bus (S3B)

Projeto desenvolvido como parte do trabalho final de graduação em Ciência da 
Computação na Universidade Federal de Itajubá (UNIFEI). O projeto consiste de uma
implementação simplificada de um barramento de serviços para ambiente de 
pequena escala (SoHo) e com capacidade para atender múltiplos protocolos.

O projeto foi dividio em 3 subrepositórios. O `barramento-de-servicos` representa
a implementação do S3B em Java usando a IDE IntelliJ IDEA Community Edition. Os
outros dois repositórios, `aplicacao-cliente` e `aplicacao-servidor`, foram usados
para validar as funcionalidades do S3B e disponibilizados como exemplos.

No diretório `diagramas` estão os diagramas relativos a modelagem do S3B, salvos 
em formato PNG e PDF. Os diagramas são:

- [Legenda das classes](diagramas/diagrama_classes_legenda.png), com o signficado
de cada notação e das cores usadas nas representações das classes;
- Diagrama de Classes, dividia em 3 diagramas:
  - [Entrada e Saída de dados](diagramas/diagrama_classes_entrada_saida.png);
  - [Processamento](diagramas/diagrama_classes_processamento.png); e
  - [Modelo e Utilitárias](diagramas/diagrama_classes_modelos_utilitarios.png).
- [Diagrama de Pacotes](diagramas/diagrama_pacotes.png), com a relação de 
dependência entre os módulos do S3B; e
- [Diagrama de Sequência](diagramas/diagrama_sequencia_caso_geral.png), 
representando o fluxo de uma mensagem na troca entre cliente e servidor, com o 
S3B intermediando essa troca.
