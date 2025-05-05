## 📛 Manejo de Excepciones 

Muestra cómo manejar excepciones al realizar una operación de división entre dos números ingresados por el usuario.

### 🚀 Funcionalidades Principales

- Permite al usuario ingresar dos números y realizar la división.
- Manejo de excepciones para entradas inválidas y división por cero.
- Muestra mensajes de advertencia o error según el tipo de excepción capturada.
- Limpia los campos de entrada al finalizar la operación (éxito o error).

### ⚠️ Excepciones Controladas

- `FormatException`: cuando el usuario no introduce un número válido.
- `DivideByZeroException`: cuando se intenta dividir entre cero.
- `Exception`: captura cualquier otro error inesperado.

### 🪟 Interfaz

- `TextBox (txtNumero1, txtNumero2)`: para ingresar los números.
- `Button (btnDividir)`: ejecuta la operación de división.
- `Label (lblResultado)`: muestra el resultado.
- `MessageBox`: Mensajes emergentes sirve para mostrar errores y advertencias.
