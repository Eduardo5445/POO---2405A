# POO---2405A
fun main() {
   //POO - Programação Orientadaa a Objetivos - Simular coisas da realidade na programação
   //
   //Objetos - possui Estados(nome, idade, endereço, altura e etc),
   // comportamentos(andar, correr, dormir, comer etc)
   // 
   //a POO é dividida:
   //
   //Classes - São modelos que servem para a construção de objs derivados dele mesmo (Ex classe pessoa)
   //as classes - recebem atributos (os estados)
   //
   //metodos - sera as instancias de classe , as formas de agir
   //Estrutura de uma classe
   // class Nome(){ocorridos de obj}
   /*
   val Rogério = Pessoa() //instaciando um obj
   Rogério.nome = "Rogério Ant Agiota"
    Rogério.altura = 1.78
    Rogério.corDosOlhos = "castanhos"
   Rogério.peso = 62.3 
   println(Rogério.altura) //para exibir um atributo em específico
   */
   val convidado1 = Pessoa("zé da pinga", 1.79, "castanho", 83.0)
   println(convidado1.nome)
   val convidado2 = Pessoa("neide", 1.5, "azul", 53.5)
   println(convidado2.nome)
   val convidado3 = Pessoa("rogério", 1.80, "verde", 72.3)
   println(convidado3.nome)
   val convidado4 = Pessoa("jucileide", 1.84, "azul claro", 92.0)
   println(convidado4.nome)
   val convidado5 = Pessoa("bartolomeu", 2.0, "azul", 103.0)
   println(convidado5.nome)
   val convidado6 = Pessoa("cleusa", 1.63, "castanho", 60.0)
   println(convidado6.nome)
   //Exercício: Criem um churras e exiba a lista de convidados no console, no min 6 pessoa
}
class Pessoa(val nome: String,
             val altura: Double,
             val corDosOlhos: String, 
             val peso: Double){
    //declarando atributos para a classe
    /*
    var nome = ""
    var altura = 0.0
    var corDosOlhos = ""
    var peso = 0.0
    */
}
