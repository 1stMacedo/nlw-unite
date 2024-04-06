



*HiperText*

*Markup*
-Tag
-Atributos

*Language*


#CSS
Cascading StyleSheet 
#JavaScript
```css
```
/* declaracoes */
body {
  background-color: black; 
  color: white;
}

``` js
// variaveis
const mensagem = `Oi, tudo bem?`
// tipos de dados
  // number
  //string
//funcao
alert(mensagem)

// objeto javascript
const participante = {
   nome: "Cleonir Macêdo",
   email: "1stmacedo.cleonir@gmail.com",
   dataInscricao: new Date(2024, 2, 22, 19, 20),
   dataCheckIn: new Date(2024, 2, 25, 22, 00) 
}

//array
let participantes = [
   {
      nome: "Cleonir Macêdo",
      email: "1stmacedo.cleonir@gmail.com",
      dataInscricao: new Date(2024, 2, 22, 19, 20),
      dataCheckIn: new Date(2024, 2, 25, 22, 00) 
      },

]
// estrutura de repeticao - loop
   for(let participante of participantes) {
      output = output + criarNovoParticipante(participante)
   }
   linha 46 // faca alguma coisa aqui
            // enquanto tiver participantes nessa lista