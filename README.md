<<<<<<< HEAD
README
---
# Estrutura dos Dados da Mega-Sena
## Descrição Geral
Este conjunto de dados contém informações detalhadas sobre os resultados dos concursos da Mega-Sena, incluindo dados sobre os números sorteados, premiações, e outras informações relevantes.
## Conteúdo
Usei o projeto do github https://github.com/guto-alves/loterias-api para gerar o dataframe.
Cada registro representa um concurso específico e contém os seguintes campos:
* **loteria:** Indica o tipo de loteria (neste caso, sempre "megasena").
* **concurso:** Número do concurso.
* **data:** Data do sorteio.
* **local:** Local onde o sorteio foi realizado.
* **dezenasOrdemSorteio:** Lista das dezenas na ordem em que foram sorteadas.
* **dezenas:** Lista das dezenas ordenadas numericamente.
* **trevos, timeCoracao, mesSorte:** Campos geralmente vazios para a Mega-Sena, utilizados em outras modalidades de loteria.
* **premiacoes:** Um objeto contendo informações detalhadas sobre as premiações, como faixas, número de ganhadores e valores.
* **estadosPremiados:** Lista dos estados onde houve ganhadores.
* **observacao:** Informações adicionais sobre o concurso.
* **acumulou:** Indica se houve acúmulo de prêmio (True/False).
* **proximoConcurso:** Número do próximo concurso.
* **dataProximoConcurso:** Data estimada para o próximo concurso.
* **localGanhadores:** Detalhes sobre os ganhadores, incluindo quantidade e localização.
* **valorArrecadado:** Valor total arrecadado no concurso.
* **valorAcumuladoConcurso_0_5:** Valor acumulado em faixas específicas.
* **valorAcumuladoConcursoEspecial:** Valor acumulado para concursos especiais.
* **valorAcumuladoProximoConcurso:** Valor acumulado para o próximo concurso.
* **valorEstimadoProximoConcurso:** Valor estimado para o prêmio do próximo concurso.
* **municipioSorteio:** Município onde o sorteio ocorreu.
* **ufSorteio:** Estado onde o sorteio ocorreu.
* **ano:** Ano do concurso.
## Limpeza de Dados
Para garantir a qualidade dos dados, foram realizadas as seguintes etapas de limpeza:
=======
class ADS(object):
  def __init__(self, nome):
     self.nome = nome
  
  
class Turmas(Curso):
  def __init__(self, bloco):
     super().__init__(nome)
     self.bloco = bloco

class Bloco (Turmas):
    def __init__(self, disciplina):
        super().__init__(bloco)
        self.disciplina = disciplina
>>>>>>> ac95110077b942352e6463fec2aefdc88ad7784f
