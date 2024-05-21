# Pedro
Projeto CDD
 class Pessoa():
    def init(self, nome, idade, peso):
        self.nome = nome
        self.peso = peso
        self.idade = idade

    def comer(self, comida, bebida):
        print(F"{self.nome} foi comer...{comida} e {bebida}")

    def falar(self, pessoa):
        print(f"{self.nome} está falando com {pessoa}")

    def dormir(self):
        print(f"{self.nome} está dormindo")
  
