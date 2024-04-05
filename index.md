const participante = {
  nome: "Rafael Silva",
  email: "rafael@gmail.com",
  dataInscricao: new Date (2024, 2, 22, 19,20),
  dataCheckIn: new Date(2024, 2, 25, 22, 00)
}

let participantes = [
  {
  nome: "Rafael Silva",
  email: "rafael@gmail.com",
  dataInscricao: new Date (2024, 2, 22, 19,20),
  dataCheckIn: new Date(2024, 2, 25, 22, 00)
  },
]
 
 Estrutura de repetição - loop
for(let participante of participantes){
    output = output +  criarNovoParticipante(participante)
  }


