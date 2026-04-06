# Práctica RA5 · a+b — Datos e información

## 1) Caso
- **Sistema:** Plataforma de streaming de video
- **Contexto:** Una app similar a Netflix donde los usuarios ven series y películas, generando datos sobre su comportamiento.

## 2) Datos
- ID del usuario  
- Tiempo de visualización (minutos vistos)  
- Título del contenido reproducido  
- Fecha y hora de acceso  
- Dispositivo utilizado (móvil, TV, ordenador)  
- Pausas o abandonos de reproducción  

## 3) Información
- Los usuarios prefieren ver series por la noche  
- El contenido más popular es una serie específica  
- La mayoría de usuarios abandona un contenido después de 10 minutos si no les interesa  

## 4) Diferencia
- **Dato:** Es un valor bruto sin interpretar (por ejemplo, “usuario 123 vio 15 minutos de una serie”).  
- **Información:** Es el resultado de procesar y analizar los datos para obtener significado (por ejemplo, “los usuarios abandonan contenidos rápidamente si no les interesa”).  

## 5) Ciclo del dato
- **Captura:** La app registra automáticamente las acciones del usuario (clics, reproducciones, tiempo visto).  
- **Almacenamiento:** Los datos se guardan en bases de datos en servidores.  
- **Procesamiento:** Se organizan y limpian los datos (eliminando duplicados o errores).  
- **Análisis:** Se aplican algoritmos para detectar patrones de comportamiento.  
- **Uso:** Se generan recomendaciones personalizadas y decisiones de negocio.  
- **Eliminación:** Datos antiguos o innecesarios se eliminan o archivan según políticas de privacidad.  

## 6) Aplicación
- **Decisiones:**
  - Recomendar contenido personalizado a cada usuario  
  - Producir nuevas series basadas en preferencias detectadas  
  - Mejorar la interfaz según el uso observado  

- **Valor:**
  - Mejora la experiencia del usuario  
  - Aumenta el tiempo de uso de la plataforma  
  - Incrementa los beneficios de la empresa  

## 7) Tabla
| Dato | Información |
|------|-------------|
| Usuario ve 20 min de una serie | Los usuarios prefieren episodios cortos |
| Acceso a las 22:00 | Mayor uso en horario nocturno |
| Uso desde móvil | Preferencia por dispositivos móviles |
| Abandono en minuto 5 | Contenido poco atractivo al inicio |
| Reproducción repetida | Contenido muy popular |
