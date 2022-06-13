# HTML - Hypertext Markup Language

   - Hiper Texto,  
   - Marcação,      
   - Tags e atributos,     
   - Linguagem: maneira de escrever.    
  
# CSS
- Cascading Style Sheet (folha de estilo em cascata)

  ## Declaração
    É o modo de instruir o estilo desejado através:  
    -Seletor,    
    -Propriedade e valor.

  ## Conceitos
    - Cascata
    - Especificidade
    - Box Model

# Javascript  
**1. Variáveis:**  
  let  
  ex.:  let estChovendo = true  
  const  
  ex.: const meuNome = "Fabio"  

- Os nomes das variáveis devem ser significativos. Como boa prática, use a técnica "camelCase".
 
**2. Tipos de dados:**  
  - String: textos. "" ou ''  
  
  - Number:  
      Integer (+ -)  
      Float (+ -)  

  - Boolean :  
      true or false  

  - undefined - indefinido  

**3. Operadores:**
  - Atribuição: atribui valor (ex.: =)  
  ex.: let n1 = 12 (lê-se let n1 recebe 12)  

  - Aritméticos: cálculos matemáticos simples (ex.: * / + -)  
    
  - Concatenação de String (+)  

  - Comparação transforma e expressão em true ou false (ex.: > < ==)  
  ex.: const maiorQue = 1 > 2 // false  
  const igualA = 1 == 1 // true  

**4. Condicional (if / else):**  
  ex.:  
  const idade = 17  
  const maiorDeIdade = idade >= 18  
  if(maiorDeIdade) {  
    alert("Pode tirar a CNH")  
  } else {  
    alert ("Não pode dirigir")  
  }  

**5. Estrutura de dados:**  
  *Array - Vetor - Lista*  
  Array - - - -  0   1   2   3  
  const temp = [25, 20, 15, 10]]  
 
  ex.: console.log(temp[2])  
  imprime.:  15  

  *Object*  
  const pessoa = {  
  nome: "Fabio", // são respectivamente - propriedade: valor  
  idade: 40,  
  outros: [1, 2, 3, 4]  
  }  

  ex.: console.log(pessoa.idade)  
  imprime.: 40  

**6. Funções:**  
    6.1 Criação:  
        function nomeDaFuncao() {  
          console.log('código dentro da função')  
        }  

    6.2 Execução:  
        nomeDaFuncao()  

  Parâmetros:  
  function soma(a, b) {  
    console.log(a + b)  
  }  
  soma(35, 45)  
  soma(90, 55)  

  Retorno:  
  function soma(a, b) {  
    return a + b  
  }  
 
  condole.log(soma(2, 2))  

**7. Extensões da Linguagem (ex.: Math, Date ...)**  

Math.random() // gera um número aleatório entre 0 e 1  
Math.floor(1.2) // arredonda para baixo  
Math.ceil(1.2) // arredonda para cima  
Math.pi // retorna o valor de pi  

**8. DOM - Document Object Model:**  

window  
window.alert("alerta")  

document  
document.write("texto")  

manipular elementos  
document.documentElement.style.background = "black"  
