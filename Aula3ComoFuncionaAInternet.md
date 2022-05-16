# Aula 3 - Como funciona a internet - 15/05/2022

Link da aula - https://www.youtube.com/watch?v=LMfeZ6XD0No

Computadores podem se comunicar, mas para se comunicarem quando estão muitos distantes é necessário toda uma estrutura de comunicação, e é sobre essa estrutura que iremos aprender.

Os dados nos computadores são armazenados no formato binário onde os dados são armazenados em bits, ou seja, um bit pode ser 0 ou 1.

Por isso os computadores produzem ondas de sinais digitais, que precisam ser convertidas para sinais analógicos (ondas senoidais), isso porque os computadores usam a infraestrutura já construidas das linhas telefonicas, que foram contruidas a muitos anos atras para comunicação, logo seria mais fácil produzirem conversores dessa onda do que contruir toda uma linha de computação compatível com as ondas de sinais digitais.

O conversor dessas ondas é o Modem, chamamos de modulação a conversão de ondas digitais para ondas senoidais e demodulação a conversão de ondas senoidais para ondas digitais.

Os computadores podem trocar dados através da infraestruturas telefonicas já construídas mas como os computadores se identificam para mandarem e receberem dados? a resposta é o número de **IP** para se conectar a internet os computadores recebem dos provedores de acesso um números de IP que identifica os computadores, e os dominios de internet (nomes www) passam por um processo de conversão então quando digitamos youtube.com.br esse dominio é convertido para um número IP, como esse IP é dinâmico ele fica salvo em uma lista DNS (domain name system, sistema de nomes de domínio), assim quando você digita esse dominio essa lista DNS procura o IP atual desse dominio e assim você pode receber e enviar dados para esse servidor (um computador dedicado para as trocas de dados).
