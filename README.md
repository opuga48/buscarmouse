# buscarmouse
es un script en Python que utiliza la biblioteca pyautogui para rastrear la posición actual del cursor del mouse en tiempo real y mostrarla en la terminal
Se importa la biblioteca pyautogui, que permite automatizar el control del mouse y el teclado.
Se inicia un bucle infinito que se ejecutará continuamente para capturar y mostrar la posición del cursor en tiempo real.
La función pyautogui.position() devuelve las coordenadas actuales del cursor en la pantalla como una tupla (x, y).
x → Coordenada horizontal (en píxeles).
y → Coordenada vertical (en píxeles).
Crea una cadena de texto (positionStr) con las coordenadas x e y de forma ordenada.
rjust(4) → Alinea las coordenadas a la derecha, asegurando que tengan un ancho mínimo de 4 caracteres para mantener el formato ordenado.
print(positionStr, end='') → Imprime las coordenadas sin añadir una nueva línea
Si el usuario presiona Ctrl + C, el programa sale del bucle while.
print('\n') añade una nueva línea para que el cursor vuelva a la posición inicial de la terminal.
