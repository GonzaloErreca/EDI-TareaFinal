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
