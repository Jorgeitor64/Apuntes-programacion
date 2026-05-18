# Sistema Inputs
En el nuevo sistema introducido en Unity los inputs dejan de usar "Input.GetKey" para pasar a usar un sistema más complejo que mejora la compatibilidad con mandos
## Comando básico
```C#
InputSystem.actions.FindAction("Accion");
```
Todas estas acciones deberán ser configuradas con anterioridad en el Input System, indicando el nombre de la acción, el cual será el que se pondrá entre comillas, y la tecla asociada, tanto del teclado como del mando u cualquier otra clase de control.
## Documentación
https://docs.unity3d.com/Packages/com.unity.inputsystem@1.19/manual/index.html