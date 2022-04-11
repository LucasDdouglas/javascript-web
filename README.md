# JavaScript Web

<br>

###   Selecionando Tag do HTML 



const element = document.getElementById("main-text")  **(Element)** 

const paragraph = document.getElementsByClassName("paragraph") **(HTML Collection)**

const subtitle = document.getElementsByTagName("h2") **(HTML Collection**)



const element = document.querySelector(".paragraph") **(Element)** 

const elementTwo = document.querySelectorAll("h2") **(NodeList)**

const element  = document.getElementsByName("Text")  **(NodeList)** 

<br>

###  Manipulando Textos



const element = document.getElementById("main-text")



element.innerText = "Manipulando Textos com innerText"



element.textContent= "Manipulando Textos com textContent"



element.innerHTML= "Manipulando Textos com...<p>InnerHTML</p>"

<br>

### Manipulando Estilos



const element = document.querySelector("body")



element.style.backgroundColor = 'green'

<br>

###  Eventos 



 const button = document.querySelector("button")



button.onclick = () => {

  alert ("Texto Enviado")} 

<br>

### Propriedades dos Eventos



const input = document.querySelector("input")



input.onkeypress = (*event*) => {

  console.log(*event*.key)}

<br>

### Event Lisening 



const input = document.querySelector("input")

const select = document.querySelector("select")

const button = document.querySelector("button")



const changeSelect = () => {

  console.log(select.value) }



select.addEventListener("change", changeSelect)



button.addEventListener("click", () => {

  alert("Arquivos Enviados")}) 
