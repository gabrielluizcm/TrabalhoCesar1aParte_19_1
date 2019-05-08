#IMPORTANTE
A parte de comparação da string digitada com a string a ser copiada foi feita de maneira errônea, acessando diretamente a memória do visor (periférico), algo que só deferia ser feito pelo kernel, não pela app.
Apesar do programa estar funcionando, ele será atualizado futuramente para que a app não acesse áreas de memória não permitidas.

# TrabalhoCesar1aParte_19_1
Trabalho do Cesar (primeira parte) para a cadeira de ARQ1 (2019/1), contendo arquivo fonte em .ced

Especificação completa do trabalho em "..\EspecificacoesEReferencias\Especificacao.pdf"

Resumidamente, o programa deve exibir uma sequência alfanumérica de 8 caracteres e contar o tempo necessário para o usuário digitar essa sequência, correta ou incorretamente. Além disso, deverá comparar se a entrada do usuário é igual à sequencia fornecida pelo programa. A entrada deve tratar a tecla ENTER e BACKSPACE, além de considerar apenas teclas alfanuméricas.
Os detalhes de como o processador interage com os periféricos (teclado, visor e timer) não serão trabalhados nesta parte da atividade, e sim gerenciados pelo kernel já fornecido (documentação do kernel em "..\EspecificacoesEReferencias\FuncoesDoKernel.pdf").

Para utilizar o programa, deve ser aberto o executável do processador ("..\CesarEMontador\Wcesar16.13.5.2.exe) e carregado o kernel fornecido em ("..\EspecificacoesEReferencias\kernel_prof.mem") pela função Carregar (Ctrl + C). Com o kernel carregado, use a função Carregar Parcial (Ctrl + P) para carregar o programa em si, disponível em ("..\TrabalhoCesar1aParte_19_1.mem) usando os seguintes parâmetros:
    -Endereço Inicial: 256
    -Endereço Final: 32767
    -Endereço de Destino: 256
Seguindo estes passos, o programa está pronto para rodar teclando F9.

As sequências a serem digitadas são semi-aleatórias, uma vez que já foram definidas na programação e são selecionadas com base no relógio do kernel.

O arquivo fonte ("..\TrabalhoCesar1aParte_19_1.ced") pode ser lido em qualquer editor de texto e montado usando o montador Daedalus fornecido em ("..\CesarEMontador\Daedalus.1.0.6.1.exe").

Qualquer cópia do código, seja parcial ou total, é expressamente proibida, tendo em vista a anulação do trabalho para todas as partes caso constatado plágio.