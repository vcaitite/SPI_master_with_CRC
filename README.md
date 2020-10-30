# SPI_master_with_CRC_example

Introduction: This program was developed as a work in the discipline of Embedded Systems Programming at UFMG - Prof. Ricardo de Oliveira Duarte - Department of Electronic Engineering. The program was developed and tested with Stm32F401RE (Nucleo 64 board).

O intuito desse programa é mostrar de maneira didática a utilidade e importância da unidade de cálculo do CRC. O programa foi desenvolvido para a placa Stm32F401RE (Nucleo 64) e se trata de um SPI master. Basicamente, o programa cria um vetor de dados, calcula o CRC para esse vetor (utilizando a unidade de cálculo de CRC, disponível nos microcontroladores STM32), insere o CRC ao final da mensagem e a envia, via SPI, para um slave, cujo código está disponível em https://github.com/vcaitite/SPI_slave_with_CRC_example.

Os passos executados por esse programa são:

[1.] Criação de um vetor de dados a ser enviado.

[2.] Inicialização da SPI no modo master.

[3.] Inicialização do periférico de cálculo do CRC.

[4.] Cálculo do CRC para o vetor de dados.

[5.] Adição do inteiro contendo o CRC no final do vetor de dados que será enviado via SPI.

[6.] Envio de dados.

[7.] Atualização do vetor de dados.

[8.] Volta para o item 4.

Para mais informações entre em contato com os desenvolvedores:

Amanda Alkmim Rezende Teixeira: amandaarteixeira@hotmail.com e Vitor Gabrie Reis Caitite: vitorgabriel1000@hotmail.com.


