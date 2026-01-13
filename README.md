# Mico: Processador de Ciclo Único

Este projeto consiste na implementação do **Mico**, um processador de ciclo único desenvolvido para a disciplina de Arquitetura e Sistemas Operacionais do Bacharelado em Ciência da Computação[cite: 4, 5, 6]. [cite_start]O objetivo é demonstrar o funcionamento de uma via de dados e unidade de controle integrada.

## Conceito do Projeto
O Mico é um processador de **32 bits** com arquitetura baseada em um conjunto reduzido de 16 instruções. Ele foi projetado no simulador **Digital** para executar operações fundamentais de hardware.

### Componentes Principais:
* **Unidade Lógica e Aritmética (ULA):** Processa operações de 32 bits como soma, multiplicação e lógica.
* **Banco de Registradores:** Bloco com 16 registradores de 32 bits, onde o $R0$ é fixo em zero.
* **Unidade de Controle:** ROM que gera sinais para coordenar o fluxo de dados do processador.
* **Memórias:** Possui memória de instruções (ROM) e de dados (RAM), ambas com 64K palavras.

## Referências Utilizadas
O desenvolvimento foi fundamentado nos seguintes materiais técnicos:

* **Sistemas Digitais e Microprocessadores (Hexsel):** [Acessar PDF](https://gvcc.dev.br/teaching/bcc-arqso/hexsel_sdm.pdf)
* **Computer Organization and Design (Patterson & Hennessy):** [Acessar Livro](https://archive.org/details/computer-organization-and-design-fifth-edition-the-hardware-software-interface-by-hennessy/page/n48/mode/1up?view=theater)
* **Sistemas Operacionais Conceitos e Mecanismos (Maziero):** [Acessar Material](https://wiki.inf.ufpr.br/maziero/lib/exe/fetch.php?media=socm:socm-livro.pdf)
* **Arquitetura de Computadores (IFSC):** [Acessar Aula](https://wiki.sj.ifsc.edu.br/index.php/DI2022802_2023_1_AULA09)
* **Aritmética Digital (UFF):** [Acessar Capítulo](https://www.professores.uff.br/lbertini/wp-content/uploads/sites/108/2017/08/Capitulo-5-Aritmetica-Digital.pdf)
* **Organização de Computadores (IFRN):** [Acessar Aula](https://docentes.ifrn.edu.br/jeangaldino/disciplinas/2016.1/organizacao-de-computadores/aula-14-logisim-interligando-as-partes/view)

---
*Projeto desenvolvido para o Instituto Federal do Paraná (IFPR) - Campus Pinhais.* 
