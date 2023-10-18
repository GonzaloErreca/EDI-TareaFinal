# EDI-TareaFinal
Tarea final de EDI - Alumnos Erreca, Nunez, Martinez
---------------------------------------------------------------------------------------------------------------------------

## LOGS

commit 15bd39193473f995e456943d99afd64080cdf353 (HEAD -> FacuRAMA, origin/FacuRAMA)
Author: Facuu2002 <agusfacu1031asgojuni@gmail.com>
Date:   Mon Oct 16 15:38:24 2023 -0300

    cambios por facu

commit 636a8ab38e755a769018117e8b412c6c7d6f2f4b (origin/main, origin/HEAD, main)
Merge: dbd44e6 bb0103c
Author: kevin-nunez <142445284+kevin-nunez@users.noreply.github.com>
Date:   Sat Oct 14 15:01:13 2023 -0300

    Merge pull request #2 from GonzaloErreca/Gonzalo

    Gonzalo

commit bb0103c9597676a2cf6f5224de79529a1586d095 (origin/Gonzalo)
Author: Gonzalo Erreca <gonzaerreca@gmail.com>
Date:   Sat Oct 14 14:58:16 2023 -0300

    Nueva function

commit 9b24e5df04bd0cfe4cbd9460dd5362ca9ff37129
Merge: 84d7f8c dbd44e6
Author: Gonzalo Erreca <gonzaerreca@gmail.com>
Date:   Sat Oct 14 14:57:24 2023 -0300

    Merge branch 'main' of https://github.com/GonzaloErreca/EDI-TareaFinal into Gonzalo

commit dbd44e615ec7641d9691230c70fb92b1da136a0d
Merge: 75bfde7 2c8a329
Author: kevin-nunez <142445284+kevin-nunez@users.noreply.github.com>
Date:   Sat Oct 14 14:32:56 2023 -0300

    Merge pull request #1 from GonzaloErreca/KevinNuñez

    cambios kevin

commit 2c8a329d6e5b535ea036d27ba45eb04ce64904cd (origin/KevinNuñez)
Author: kevin-nunez <142445284+kevin-nunez@users.noreply.github.com>
Date:   Sat Oct 14 14:28:20 2023 -0300

    Conflicto resuelto

commit 4cdcda154f66ed8d4c92cfe98cc4abc99dcf9dd0
Merge: a83e2f6 7f0c00c
Author: kevin-nunez <142445284+kevin-nunez@users.noreply.github.com>
Date:   Sat Oct 14 14:27:37 2023 -0300

    Merge branch 'KevinNuñez' of https://github.com/GonzaloErreca/EDI-TareaFinal into KevinNuñez


    
---------------------------------------------------------------------------------------------------------------------------

function addNumbers(a, b) {
    return a + b;
  }
  const num1 = 5;
  const num2 = 10;
  const result = addNumbers(num1, num2);
  console.log("La suma de ${num1} y ${num2} es: ${result}"");
  
Modificacion desde el main

function random_MAC_adress() {
    let direccionMAC = '';

    for (let i = 0; i < 6; i++) {
    const car1 = randomHexaNumberGenerator(); // llamo a la funcion anterior
    const car2 = randomHexaNumberGenerator();
    direccionMAC += cara1 + car2;
    if (i < 5) {
      direccionMAC += ':';
    }
  }

  return direccionMAC;
}
function calcular(operacion, a, b) {
  if (operacion === 'sumar') {
    return a + b;
  } else if (operacion === 'restar') {
    return a - b;
  } else {
    return 'Operación no válida';
  }
}

// Ejemplos de uso
console.log('Suma: ' + calcular('sumar', 5, 3));    // Suma: 8
console.log('Resta: ' + calcular('restar', 10, 7));  // Resta: 3
