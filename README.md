# exercicio_diagrama_uml

classDiagram
    class ReprodutorMusical {
        +void tocar()
        +void pausar()
        +void selecionarMusica(String musica)
    }

    class AparelhoTelefonico {
        +void ligar(String numero)
        +void atender()
        +void iniciarCorreioVoz()
    }

    class NavegadorNaInternet {
        +void exibirPagina(String url)
        +void adicionarNovaAba()
        +void atualizarPagina()
    }

    class Iphone {
      
    }

    Iphone --|> ReprodutorMusical
    Iphone --|>  AparelhoTelefonico
    Iphone --|>  NavegadorNaInternet
