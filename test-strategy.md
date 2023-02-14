 }
 .lowOrHi {
        color: white;
        padding: 3px;
      } // colocarle al label el color de letra blanco ya que con el color negro que tenia no se podia ver el mensaje solicitado.
      
 const ATTEMPS = 5;  // el valor de ATTEMPS debe de ser 10 debido a que es nuestro límite de oportunidades.
 
 const lowOrHi = document.querySelector('lowOrHi'); // en la declaración de la variable falto el punto que nos permite mostrar el mensaje en el laber.
   
 let userGuess = (guessField.value); // a la varible se le debe de pasar Numbre para que reconozca los números ingresados Number(guessField.value);.
