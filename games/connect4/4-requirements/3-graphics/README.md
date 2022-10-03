# TicTacToe. Requisitos Gráficos
Universo Santa Tecla  
[uSantaTecla@gmail.com](mailto:uSantaTecla@gmail.com)  
  
**Índice**

1. [Requisitos](#requisitos)  
2. [Vista de Casos de Uso](#vista-de-casos-de-uso)  
2.1. [Vista de Caso de Uso Start](#vista-de-caso-de-uso-start)  
2.2. [Vista de Caso de Uso Play](#vista-de-caso-de-uso-play)  
2.3. [Vista de Caso de Uso Resume](#vista-de-caso-de-uso-resume)  
2.4. [Prototipo de Interfaz](#prototipo-de-interfaz)  
2.4.1. [Grafica](#grafica)  
2.4.2. [Consola](#consola)  

## Requisitos  

| * _Funcionalidad: **Básica**_<br/>  * _Interfaz: **Gráfica y Texto**_<br/>  * _Distribución: **Standalone**_<br/>  * _Persistencia: **No**_<br/> | ![TicTacToe](../docs/images/tictactoe.png) | 
| :------- | :------: |  

## Vista de Casos de Uso  

| Diagrama de Actores y Casos de Uso | Diagrama de Contexto |
|---|---|
| ![TicTacToe](./docs/diagrams/out/vistaCasosUso/actores.svg) | ![TicTacToe](./docs/diagrams/out/vistaCasosUso/contexto.svg) |  

## Vista de Caso de Uso Start  
![Start](./docs/diagrams/out/vistaCasosUso/StateDiagramFluxInitialState.svg)  

## Vista de Caso de Uso Play  
![Play](./docs/diagrams/out/vistaCasosUso/StateDiagramFluxPlayState.svg)  

## Vista de Caso de Uso Resume  
![Resume](./docs/diagrams/out/vistaCasosUso/resume_usecase.svg)  

### Prototipo de Interfaz  

#### Grafica

| Pantallas | Diálogos |
|---|---|
| ![TicTacToe](./docs/images/pantallas.png) | ![TicTacToe](./docs/images/dialogos.png) |

#### Consola  
  
```
--- TIC TAC TOE ---
-------------
|   |   |   | 
|   |   |   | 
|   |   |   | 
-------------
Coordinate to put
Row: 1
Column: 1
-------------
| X |   |   | 
|   |   |   | 
|   |   |   | 
-------------
Coordinate to put
Row: 3
Column: 2
-------------
| X |   |   | 
|   |   |   | 
|   | O |   | 
-------------
Coordinate to put
Row: 1
Column: 2
-------------
| X | X |   | 
|   |   |   | 
|   | O |   | 
-------------
Coordinate to put
Row: 3
Column: 3
-------------
| X | X |   | 
|   |   |   | 
|   | O | O | 
-------------
Coordinate to put
Row: 1
Column: 3
-------------
| X | X | X | 
|   |   |   | 
|   | O | O | 
-------------
X Player: You win!!! :-)
Do you want to continue? (y/n):
```
