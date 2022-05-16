# TicTacToe. Requisitos Ficheros
Universo Santa Tecla  
[uSantaTecla@gmail.com](mailto:uSantaTecla@gmail.com)  
  
**Índice**

1. [Requisitos](#requisitos)  
2. [Vista de Casos de Uso](#vista-de-casos-de-uso)  
2.1. [Vista de Caso de Uso Start](#vista-de-caso-de-uso-start)  
2.2. [Vista de Caso de Uso Open](#vista-de-cas-de-uso-open)  
2.3. [Vista de Caso de Uso Play](#vista-de-caso-de-uso-play)  
2.4. [Vista de Caso de Uso Undo](#vista-de-caso-de-uso-undo)  
2.5. [Vista de Caso de Uso Redo](#vista-de-caso-de-uso-redo)  
2.6. [Vista de Caso de Uso Exit](#vista-de-cas-de-uso-exit)  
2.7. [Vista de Caso de Uso Save](#vista-de-cas-de-uso-save)  
2.8. [Vista de Caso de Uso Resume](#vista-de-caso-de-uso-resume)  
2.9. [Prototipo de Interfaz](#prototipo-de-interfaz)  
2.9.1. [Consola](#consola)  

## Requisitos  

| * _Funcionalidad: **Básica + Undo/Redo**_<br/>  * _Interfaz: **Gráfica y Texto**_<br/>  * _Distribución: **Standalone + Client/Server**_<br/>  * _Persistencia: **Ficheros**_<br/> | ![TicTacToe](../docs/images/tictactoe.png) | 
| :------- | :------: |  

## Vista de Casos de Uso  

| Diagrama de Actores y Casos de Uso | Diagrama de Contexto |
|---|---|
| ![TicTacToe](./docs/diagrams/out/vistaCasosUso/casosUso/useCase.svg) | ![TicTacToe](./docs/diagrams/out/vistaCasosUso/diagramaEstadosGeneral/StateDiagramGameStates(ContextDiagram).svg) |  

## Vista de Caso de Uso Start  
![Start](./docs/diagrams/out/vistaCasosUso/casoUsoStart/StateDiagramFluxInitialState.svg)  

## Vista de Caso de Uso Open
![Open](./docs/diagrams/out/vistaCasosUso/casoUsoOpen/StateDiagramFluxOpenState.svg)  

## Vista de Caso de Uso Play  
![Play](./docs/diagrams/out/vistaCasosUso/casoUsoPlay/StateDiagramFluxPlayState.svg)  

## Vista de Caso de Uso Undo  
![Play](./docs/diagrams/out/vistaCasosUso/casoUsoUndo/StateDiagramFluxUndoState.svg)  

## Vista de Caso de Uso Redo  
![Play](./docs/diagrams/out/vistaCasosUso/casoUsoRedo/StateDiagramRedoUndoState.svg)  

## Vista de Caso de Uso Exit
![Exit](./docs/diagrams/out/vistaCasosUso/casoUsoExit/StateDiagramFluxExitState.svg)  

## Vista de Caso de Uso Save
![Save](./docs/diagrams/out/vistaCasosUso/casoUsoSave/save.svg)  

## Vista de Caso de Uso Resume  
![Resume](./docs/diagrams/out/vistaCasosUso/casoUsoResume/resume_usecase.svg) 

### Prototipo de Interfaz  

#### Consola  
```
--- TIC TAC TOE ---
----- Choose one option -----
1) Start a new game
2) Open a saved game
1
Number of users [0-2] 1
----- Choose one option -----
1) Do a movement
2) Exit game
1
---------------
| - | - | - |
| - | - | - |
| - | - | - | 
---------------
Enter a coordinate to put a token:
Row: 1
Column: 1
---------------
| X | - | - |
| - | - | - |
| - | - | - |
---------------
----- Choose one option -----
1) Do a movement
2) Undo previous movement
3) Exit game
1
---------------
| X | - | - |
| - | - | - |
| - | - | - |
---------------
---------------
| X | - | O |
| - | - | - |
| - | - | - | 
---------------
----- Choose one option -----
1) Do a movement
2) Undo previous movement
3) Exit game
1
---------------
| X | - | O |
| - | - | - |
| - | - | - |
---------------
Enter a coordinate to put a token:
Row: 2
Column: 1
---------------
| X | - | O |
| X | - | - | 
| - | - | - |
---------------
----- Choose one option -----
1) Do a movement
2) Undo previous movement
3) Exit game
1
---------------
| X | - | O |
| X | - | - |
| - | - | - |
---------------
---------------
| X | - | O |
| X | - | O |
| - | - | - |
---------------
----- Choose one option -----
1) Do a movement
2) Undo previous movement
3) Exit game
3
Do you want to save the game?? (y/n): y
Name: game1
Do you want to continue? (y/n): y

--- TIC TAC TOE ---
----- Choose one option -----
1. Start a new game
2. Open a saved game
2
----- Choose one option -----
1. game1.mm
1
game1.mm
---------------
| X | - | O |
| X | - | O |
| - | - | - |
---------------
----- Choose one option -----
1) Do a movement
2) Undo previous movement
3) Exit game
1
---------------
| X | - | O |
| X | - | O |
| - | - | - |
---------------
Enter a coordinate to put a token:
Row: 3
Column: 1
---------------
| X | - | O |
| X | - | O |
| X | - | - |
---------------
X Player: You win!!! :-)
Do you want to save the game?? (y/n): n
Do you want to continue? (y/n):
```

