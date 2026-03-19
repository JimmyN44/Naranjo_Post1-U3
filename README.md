# Naranjo_Post1-U3

Descripción del proyecto

TaskApp es una aplicación Android desarrollada como ejercicio práctico para implementar una arquitectura moderna basada en MVVM (Model-View-ViewModel) utilizando Jetpack Compose, StateFlow, Coroutines y Hilt para la inyección de dependencias.

La aplicación permite visualizar una lista de tareas almacenadas en memoria mediante un repositorio simulado, demostrando buenas prácticas de separación de responsabilidades y manejo reactivo del estado de la interfaz de usuario.

Objetivo
Implementar una aplicación funcional que evidencie:
Uso de arquitectura limpia (Clean Architecture)
Manejo de estado con StateFlow
Inyección de dependencias con Hilt
UI declarativa con Jetpack Compose
Pruebas unitarias en ViewModel

Arquitectura
El proyecto sigue el patrón MVVM, dividido en capas:
domain → Entidades y contratos (lógica de negocio)
data → Implementación del repositorio
presentation → ViewModel y estados de UI
ui → Interfaz de usuario con Compose
di → Inyección de dependencias con Hilt

Tecnologías utilizadas
Kotlin
Jetpack Compose
Hilt (Dagger)
Coroutines + StateFlow
ViewModel
JUnit (Testing)
