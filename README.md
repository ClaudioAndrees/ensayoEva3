# Registro de Equipaje - VuelosChile ✈️

Este es un script interactivo en **Python** diseñado para automatizar y validar el proceso de registro y clasificación de equipaje para la aerolínea ficticia *VuelosChile*.

El programa recopila los datos de cada equipaje, valida que la información sea correcta (evitando errores de ingreso) y clasifica automáticamente los bultos según su peso para generar un manifiesto de carga final.

## 🚀 Características

* **Validación de entrada robusta:** Controla que la cantidad de equipajes y los pesos sean números enteros positivos, manejando excepciones (`ValueError`) para evitar que el programa se caiga.
* **Filtros de seguridad para tickets:** Verifica que el código del ticket tenga un mínimo de 5 caracteres y no contenga espacios intermedios.
* **Clasificación automática:** Separa el equipaje según las reglas de la aerolínea:
    * 🧳 **Cabina:** Peso menor o igual a 10 kg.
    * 📦 **Bodega:** Peso mayor a 10 kg.
* **Resumen final:** Genera un conteo total ("Manifiesto de carga") con la distribución del equipaje en el avión.

## 🛠️ Requisitos

* Python 3.x instalado en tu sistema.

## 💻 Cómo ejecutar el proyecto

1. **Clona este repositorio** en tu máquina local:
   ```bash
   git clone [https://github.com/TU_USUARIO/TU_REPOSITORIO.git](https://github.com/TU_USUARIO/TU_REPOSITORIO.git)
