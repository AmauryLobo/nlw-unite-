#html 
*tag*

#js 
comandos 
*return* // retorna o valor 
*strong* // negrito 
*small* //letra pequena
*${}* // substituir variavel usando ` crase


//obj js
const participante = {
nome: "Amadeu capa",
email: "capa@gmail.com",
dataIscricao: new Date(2024, 4, 02, 23, 45),
dataCheckin: new Date(2024, 4, 05, 22, 30)
}

// array
let participantes = [
  {
    nome: "Amadeu capa",
    email: "capa@gmail.com",
    dataIscricao: new Date(2024, 4, 02, 23, 45),
    dataCheckin: new Date(2024, 4, 05, 22, 30)
  }, 
]


 let output = ""
  for(let participante of participantes) {
    output = output + criarNovoParticipante(participante)
  }


preventDefault // prevenir q "envie" sem infos 

igual == 
atribuir valor =

  (p) => {
    return p.email == participante.email
  } // é o msm q: 
   (p) => p.email == participante.email

table{
  border-collapse: separate;
 }
 table thead {
  font-size: 14px;
  line-height: 16px;
 }

 thead th, 
 tbody td {
  padding: 12px 16px; 
 }

tbody td {
  border-top: 1px #ffffff1a;
}

html 
svg serve pra imagem (icone, logo)
