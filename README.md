# Pruebas
Pruebas de conocimiento básico.

Primer ejercicio.
Números primos, se generan los primeros 10 numeros primos.
function Nup(num) {

for(var i=2;i<=num-1;i++) {

if(num%i==0) {

return false;

}

}

return true;

}

for(var i=1;i<=23;i++) {

if(Nup(i)) {

console.log(i);

} 
}
