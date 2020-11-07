`class ADS(object):
  def __init__(self, nome):
     self.nome = nome
  
  
class Turmas(Curso):
  def __init__(self, bloco):
     super().__init__(nome)
     self.bloco = bloco

class Bloco (Turmas):
    def __init__(self, disciplina):
        super().__init__(bloco)
        self.disciplina = disciplina`
