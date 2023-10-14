# EDI-TareaFinal
Tarea final de EDI - Alumnos Erreca, Nunez, Martinez
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