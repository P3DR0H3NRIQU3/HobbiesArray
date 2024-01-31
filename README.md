// Criando um array de hobbies com três elementos
let hobbies = ['Futebol','Viajar','Jogar']
// Exibindo o array completo no console
console.log(hobbies)
// Acessando e exibindo os elementos do array
console.log(hobbies[0])
console.log(hobbies[1])
console.log(hobbies[2])
// Modificando o segundo elemento do array para 'ler livros'
hobbies[1]= 'ler livros'
console.log(hobbies)
// Exibindo o tamanho do array
console.log(hobbies.length)
// Adicionando um elemento 'Cozinhar' ao final do array utilizando o método correto
hobbies.push = "Cozinhar" 
console.log(hobbies)
// Removendo o último elemento do array
hobbies.pop();
console.log(hobbies)
// Encontrando a posição do elemento 'Viajar' no array
let posicao = hobbies.indexOf('Viajar')
// Removendo 1 elemento a partir da posição encontrada
hobbies.splice(posicao,1)
console.log(hobbies)
// Removendo todos os elementos do array (deixando-o vazio)
hobbies.splice(0)
console.log(hobbies)
// Criando arrays adicionais de hobbies
const hobbiesDoAmigo = ['Musica ','Aposta','Sexo']
// Concatenando os arrays de hobbies
const todosOsHobbies = hobbies.concat(hobbiesDoAmigo)
console.log(todosOsHobbies)
// Definindo arrays de diferentes categorias de hobbies
const hobbiesMusicais = ['Cantar', 'Dançar', 'Tocar violão']
const hobbiesEsportivos = ['Futebol', 'Nadar', 'Correr']
const hobbiesCriativos = ['Desenhar', 'Escrever', 'Meditar']
// Criando um array que contém as diferentes categorias de hobbies
const categoriasDeHobbies = [hobbiesMusicais, hobbiesEsportivos, hobbiesCriativos]
console.log(categoriasDeHobbies[2])
console.log(categoriasDeHobbies[2][2])
