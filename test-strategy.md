 }
 .lowOrHi {
        color: white;
        padding: 3px;
      } // colocarle al label el color de letra blanco ya que con el color negro que tenia no se podia ver el mensaje solicitado.
      
 const ATTEMPS = 5;  // el valor de ATTEMPS debe de ser 10 debido a que es nuestro límite de oportunidades.
 
 const lowOrHi = document.querySelector('lowOrHi'); // en la declaración de la variable falto el punto que nos permite mostrar el mensaje en el laber.
   
 let userGuess = (guessField.value); // a la varible se le debe de pasar Numbre para que reconozca los números ingresados Number(guessField.value);.

//los mensajes estan en un orden diferente, debido a que la comparación que estamos realizando no podemos decir que ha perdido si el número ingresado es correcto
//colocando el color que corresponda a cada solicitud.
if(userGuess === randomNumber) {
      lastResult.textContent = '!!!Pérdistes!!!';
 // o felicitarlo que debido a que llego al límite de oportunidades que tenia.
    } else if(guessCount === ATTEMPS) {
      lastResult.textContent = 'Felicitaciones! adivinaste el número!';
      
      //lo ideal es
       if(guessCount === ATTEMPS) { 
      lastResult.textContent = '!!!Pérdistes!!!';

    } else if(userGuess === randomNumber) { 
      lastResult.textContent = 'Felicitaciones! adivinaste el número!';
      
//el nombre de los métodos debe de contener una E mayúscula en la cuarta posición despues del punto.
guessSubmit.addeventListener('click', checkGuess);
resetButton.addEventListener('click', resetGame);
      
      
  
 
     
