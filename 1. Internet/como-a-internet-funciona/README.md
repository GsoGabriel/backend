# Como a internet funciona?

## Internet

A internet é uma conexão mundial, um lugar onde podemos transferir dados e mídias através das conexões entre os dispositivos. Ele funciona usando os protocolos de internet (IP) e protocolos de controle de transmissão (TCP).

###### Mas o que são IP e TCP?

|                              IP                              |                             TCP                              |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| Esses protocolos endereçam os pacotes que trafegam pela internet através do endereço de IP (IP Adress). Em outras palavras, são regras que governam a forma como os pacotes serão enviados de um computador ao outro de forma ordenada. | Esse protocolo utiliza o IP para fazer a conexão e o envio dos dados entre os computadores. É uma linguagem para que as máquinas possam se comunicar. |

> Os dados enviados são chamados de mensagens (message). Antes das mensagens serem enviadas, elas são repartidas em vários pacotes (packet). 

> Endereços de IP público são acessíveis a toda internet. Os endereços de IP privados são acessíveis a somente um grupo seleto de máquinas, seja numa empresa, ou em casa. 



## Então, como tudo isso funciona?

Quando um cliente faz uma requisição, ele envia informações para o provedor de internet(ISP), o provedor envia a informação ao endereço de IP informado e logo depois a requisição é retornada pelo mesmo caminho de volta ao cliente. 

Como eles sabem todos esses caminhos? Os roteadores trabalham para que tudo seja enviado aos endereços corretos. Os roteadores estão vários pontos, direcionando ao local certo até chegar ao endereço de IP informado. O TCP faz com que essas informações cheguem seguras, de forma que não haja perda de pacotes durante o percurso, ou que não haja delay negativo, afetando, dessa forma, a qualidade dos pacotes em transferência. 

As requisições enviadas aos provedores são feitas através do DNS. Para aprender mais, deixo o link para o artigo que explica sobre DNS. ()

As respostas dos servidores obedecem ao protocolo HTTP. Para aprender mais, deixo o link para o artigo que explica sobre o protocolo HTTP. ()



## Fontes e referências

[How Does the Internet Work (Infographic) | HP® Tech Takes](https://www.hp.com/us-en/shop/tech-takes/how-does-the-internet-work)

[How does the Internet work? - Learn web development | MDN (mozilla.org)](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work)

[Protocolo de Internet: tudo o que você precisa saber sobre o IP (ecoit.com.br)](https://blog.ecoit.com.br/protocolo-de-internet/)

[O que é TCP/IP? | Como o Modelo e Protocolos funcionam | Avast](https://www.avast.com/pt-br/c-what-is-tcp-ip)

