


====================================================================================================================
    Trabalho do Cesar - 2019/1
====================================================================================================================

    Aqui você encontra os arquivos necessários para implementar o programa de aplicação (APP).

    Os arquivos são os seguintes:

        Especificacao.pdf    -> Especificação do trabalho
        app_ref.ced          -> Arquivo sobre o qual você deve desenvolver a sua solução da APP
	
        FuncoesDoKernel.pdf  -> Descrição das funções que estão implementadas no kernel fornecido pelo professor
        kernel_prof.mem      -> Arquivo com a implementação das funções que você necessita para desenvolver a sua APP
                            Esse arquivo deverá ser carregado no simulador, ANTES de carregar seu programa de aplicação (usando carga parcial)



====================================================================================================================
	CARGA PARCIAL
====================================================================================================================

    Procedimento para "juntar" (mesclar) o kernel_prof.mem com a sua implementação do programa de aplicação.
	
    Esse procedimento é necessário para colocar sua implementação em execução.
	
    Procedimento
        1) Carregue, normalmente, no simulador, o arquivo "KERNEL_PROF.MEM", fornecido pelo professor.
        2) Carregue, usando "carga parcial", no simulador, o seu arquivo ".mem", desenvolvido por você.
        3) Zere o Program Counter (R7) e inicie a execução



====================================================================================================================
    Quais os dados necessários para realizar a carga parcial no simulador?
====================================================================================================================

    Para realizar a carga parcial você deve usar no simulador o menu "Arquivo" >> "Carga Parcial"
	
    O simulador solicitará, então, as seguintes informações, em ordem:
        Arquivo: selecione o seu programa de aplicação (desenvolvido sobre o APP_REF.MEM)
        Endereço inicial da memória a copiar: 256
        Endereço final da memória a copiar: 32767
        Endereço de destino: 256



====================================================================================================================
    Como rodar, passo a passo, sua implementação
====================================================================================================================

    Você deve utilizar o "break point" do simulador.
	
    Escreva o endereço 100 (hexa) ou 256 (decimal) no campo "BP" do simulador (no canto inferior esquerdo.
    Zere o Program Counter (R7)
	Inicie a execução do programa

    Assim que o programa atingir o endereço H100 (início de seu programa de aplicação) a execução vai parar.
    A partir desse instante, você poderá executar seu programa passo a passo
	
	
