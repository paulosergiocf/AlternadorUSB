# AlternadorUSB

Projeto de Placa PCB simples para alterar dispositvo usb entre dois compudatores

## Porque?

Este projeto foi implementado devido há uma demanda pessoal. Possuo um notebook pessoal, e um de trabalho. Como  tenho um _setup_ configurado com um monitor teclado e mouse, alternar os cabos entre ambos era uma opção desgastante, havia a necessidade que ficar passando os cabos por baixo e por cima da mesa de acordo com o notebook que ia utilizar, além de desgastar as entradas de ambas as maquinas.

> **Nota**: busquei varias formas de implementar a solução para esse problema, não tenho quase nenhum conhecimento no assunto, então sofri demais. No entanto, em um [site](http://www.seekic.com/circuit_diagram/Control_Circuit/USB_Printer_Sharing_Switch.html) encontrei um esquema feito para resolver o mesmo problema, mas direcionado a impressora.
>
> Aqui estou deixando a implementação desse esquema pronto para ser impresso, a pcb fabricada, bem como a lista de componentes e um valor aproximado do gasto.

![esquema](https://github.com/paulosergiocf/AlternadorUSB/assets/49497668/b77c0cae-a919-450c-bf0c-fdb45481d322)

Como um bonus adicionei a placa mais duas passagem usb que podem ser chaveadas tambem, tem em mente futuramente implementar uma chave analógica para a WebCam e o Microfone.

![projeto](https://github.com/paulosergiocf/AlternadorUSB/assets/49497668/07d97ab2-d95a-44a5-8cd9-a93c1b362e42)

[PROJETO PDF PRONTO PARA IMPRESSÃO - COM PROJETO LIMPO]()

## Que que isso faz?

Esse dispositivo recebe um dispositivo USB (no meu caso um hub com Mouse e teclado) e possui duas saidas **usb** se conectam a ambos os notebooks, e atrávez de uma chave podemos alter qual notebook receberá os dados.


## Custos

|Descrição| Valor|
|:--|:--:|
|2 Diodo schottky 1n5819|R$ 0,60|
|1 Chave Alavanca Mts-202 Interruptor 6t Ld Dpdt 6a|R$ 1,50|
|1 Lamina | R$ 5,00 |

Claro os custos podem mudar se nmão tiver o material para a fabricação da PDB, neste caso você precisará de:

- Placa De Fenolite Cobreado.
- Caneta Permaente.
- Percloreto de Ferro.
- luvas de borracha.
- Recipiente de plastico para fazer a mistura.
- Bicarbonato de Sódio.

---

> **ATENÇÃO**: Utilize o percloreto com cuídado, procure tutoriais sobre o assunto, o bicarbonato neutraliza o percloreto e pode ser util em caso de emergência. 
