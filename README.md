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

____________________________________________________________________________________________________________________________________


from Classes import *

p1 = Pessoa('Pedro',23,80)
p2 = Pessoa("Maria",17,50)
print(f"olá meu nome é {p1.nome} tenho  {p1.idade} e peso {p1.peso} quero falar sobre {p1.falar}")
p1.comer('cuzcuz com ovo ','Café')
p1.falar(f' quero fala sobre {p1.falar}')
print('olá sou Pedro tenho 23 anos')
p1.dormir(f' {p1.dormir}')
print('estou dormindo porra cai fora')
  
