# constagem-de-peças
'use strict';

var readLineSync = require("readline-sync");
var options
var quantidadedePeças = 100;

do{
    console.log("\n");
    console.log("\t\t------ sistema de cadastro de peças -----")
    console.log("1: controle de peças")
    console.log("0: sair do sistema")

    opcao = readLineSync.question("\tdigite o número de peças :")

    for (let indice =0; indice <= quantidadedePeças; indice++){
        if (indice ===0){
            console.log("A quantidade de peças é igual a 0")
        }else if(indice %2 ===0){
            console.log("O numero de alunos é par"+ indice)
        }else{
            console.log("O numero de alunos é impar:"+indice)
        }
        }

}while(options !=0)
