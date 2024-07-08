´´´mermaid

classDiagram
Iphone --|> ReprodutorMusical
Iphone --|> AparelhoTelefonico
Iphone --|> NavegadorInternet
class ReprodutorMusical{ 
    +tocar()
    +pausar()
    +selecionarMusica(string musica)
}
class AparelhoTelefonico{
    +ligar(string numero)
    +atender()
    +iniciarCorreioVoz()

}
class NavegadorInternet{
    +exibirPagina(String url)
    +adionarNovaAba()
    +atualizarPagina()
}
