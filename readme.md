# Code Challenge: ChessKnight

Dada la posición de un caballo en el tablero de ajedrez estándar, 
encuentre el número de movimientos diferentes que puede realizar el caballo.

### Movimiento del Caballero
El caballero puede moverse a un cuadrado que tiene dos cuadrados 
horizontalmente y un cuadrado verticalmente, o dos cuadrados verticalmente 
y un cuadrado horizontalmente alejado de él. Por lo tanto, el movimiento 
completo se parece a la letra L. 

Consulte la imagen de abajo para ver todos los movimientos válidos para una pieza de 
caballo que se coloca en uno de los cuadrados centrales.

![](https://firebasestorage.googleapis.com/v0/b/fullstack-extraordinary.appspot.com/o/TheCodeChallenge%2Fchessknight.jpg?alt=media&token=5e8d20d4-fb22-497a-bf39-919f1412ea46)

### Coordenadas en tablero de Ajedrez
La posición de una celda en el tablero de ajedrez se identifica mediante una coordenada alfanumérica.

El eje horizontal o eje X se identifica con una letra entre la "A" y la "H" (A,B,C,D,E,F,G,H)
El eje vertical o eje Y se identiica con un numero entre el "1" y el "8" (1,2,3,4,5,6,7,8)
Por ejemplo: "A1", "G7", "F3"

![](https://firebasestorage.googleapis.com/v0/b/fullstack-extraordinary.appspot.com/o/TheCodeChallenge%2FtablerAjedrez.jpg?alt=media&token=d6ba9a45-7646-49a1-b7c2-45138e9df7fd)

## Instrucciones
- Crear un nuevo repositorio utilizando este repositorio como template (Boton: use this template).
- Editar el código de la función definida en el archivo index.js con un algoritmo que permita obtener los resultados esperados en los test.
- Ejecutar los test validando que todos resulten exitosos

## Ejecutar Pruebas

Instalar dependencias (mocha)
```
npm install
```

Ejecutar test
```
npm run test
```
## Entrada

##### Parámetro 1
- **nombre**: num
- **tipo**: Number (Integer)
- **limitaciones**: 0 < **num** <= 10

## Salida

- **tipo**: Number (Integer)

## Ejemplo
**1** debe retornar **1** porque: 1 == 1

## Tests

### Test 1  

- **Parametros**: param = 1  
- **Resultado esperado**: xxx
---
### Test 2  

- **Parametros**:  param = 2  
- **Resultado esperado**: xxx
---
### Test 3  

- **Parametros**: param = 3  
- **Resultado esperado**: xxx
