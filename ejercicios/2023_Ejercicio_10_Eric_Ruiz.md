# Ejercicio 10: Sistema de Gestión de Jugadores

**Descripción del Problema:**

Diseña un sistema que permita a un estudio de videojuegos gestionar a los jugadores, sus logros y estadísticas en varios juegos.

## Arquitectura Sugerida

Monolítica

### Descripción

Como este pseudocódigo solo cuenta con dos clases, Jugador y Logro. Una arquitectura monolítica permite mantener todas las funciones en un solo sistema, lo que facilita tanto el desarrollo como el mantenimiento. Además en cuanto a recursos es mas eficiente esta arquitectura ya que las dos clases estan relacionadas y en cuanto a la escalabilidad, si el sistema se volviese mas complejo en el futuro se podria reescribir en componentes mas pequeños o en microservicios.

![arquitectura de software ejercicio 10](https://github.com/Chispasgg/euneiz-eda/assets/131948669/46d18d73-6765-4591-b068-4d20d12b6b7a)


## Se requiere

- Pseudocodigo:
  - [ ] del método para actualizar estadisticas de un jugador:
        
    Clase Jugador:
    Atributos:
        - Nombre
        - Lista de Logros
        - Estadísticas (puntuación, tiempo jugado, etc.)

    Métodos:
        - Constructor (nombre)
        - DesbloquearLogro(logro)
        
        Método ActualizarEstadisticas(puntuacion, tiempo_jugado):
            // Actualizar la puntuación del jugador
            this.Estadisticas.Puntuacion = this.Estadisticas.Puntuacion + puntuacion
            
            // Actualizar el tiempo jugado del jugador
            this.Estadisticas.TiempoJugado = this.Estadisticas.TiempoJugado + tiempo_jugado

 ![diagrama de flujo 1 ej 10](https://github.com/Chispasgg/euneiz-eda/assets/131948669/41283b08-e3fb-44a8-918f-f8f41689b1f3)



  - [ ] del método para desbloquear logro:
        
  Clase Jugador:
    Atributos:
        - Nombre
        - Lista de Logros
        - Estadísticas (puntuación, tiempo jugado, etc.)
        
    Métodos:
        - Constructor (nombre)
        
        Método DesbloquearLogro(logro):
            // Añadir el logro a la lista de logros del jugador
            this.ListaDeLogros.Agregar(logro)
  
![DIAGRAMA DE FLUJO 2 EJ 10](https://github.com/Chispasgg/euneiz-eda/assets/131948669/6a181649-7bda-4bd5-8447-d6ae6d582e45)


  
 

