# Desafio POO

### Diagrama UML (Mermaid)
***mermaid
classDiagram

    class iPhone{
    }
    
    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet

    class ReprodutorMusical {
        -Tocar()
        -Pausar()
        -selecionarMusica(String  musica)
    }

    class AparelhoTelefonico {
        -Ligar(String numero)
        -atender()
        -iniciarCorreioVoz()
    }

    class NavegadorInternet {
        -exibirPagina(String url)
        -adicionarNovaAba()
        -atualizarPagina()
    }
***
