## Aritméticos: Retornam o resultado de uma operação
+ somar
- subtrair
* multiplicar
/ dividir
% resto da divisão

## Comparadores matemáticos: teste logico, retorno booleano (true/false)
< menor que
> maior que 
<= menor ou igual
>= maior ou igual

## Comparadores Lógicos: teste lógico, retorno booleano (true/false)
== igualdade entre sentenças (valor)
!= diferença entre sentenças (valor)
=== igualdade entre sentenças (valor e tipo)
!== diferença entre sentenças (valor e tipo)

## Operadores de lógica e junção lógica
! NÃO (NOT)
&& E (AND)
|| OU (OR)

## Calculo MNédia de Aluno

var nota1 = 10;
var nota2 = 9;
var nota3 = 2;
var nota4 = 6;
var media = (nota1 + nota2 + nota3 + nota4) / 4;
if(media >= 8 ) {
    console.log("Aluno Aprovado")
} else {
    console.log("Aluno em Recuperação")
}

## Laços de Repetição 

var km 
var revisao = 10

for(km = 0; km < revisao ; km++){
    console.log)("Dirigiu " +km+ " Km")
}

for([expressaoInicial];[condicao];[incremento])

## calculo de media de alunos

var alunos = [
    [6,7,9,8],
    [10,2,3,4],
    [2,5,1,5]
]

var nota = 0;
for (var i = 0; i < alunos.length; i++){
    nota = 0
    aluno = alunos[i]
    console.log("Aluno: " + aluno);

    for (c = 0; c < aluno.length; c++){
        nota += aluno[c];
    }

    media = nota / 4;
    if(media >= 7) {
        resultado = "aprovado";
        } else {
            resultado = "reprovado";
        }

        console.log("Media: " + media + " " + resultado);
        document.getElementById("result").innerHTML = ("Media"+ media + " " + resultado);
        
}