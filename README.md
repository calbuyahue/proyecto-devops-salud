
# Proyecto DevOps - Reserva de Horas Médicas

## Descripción
Proyecto académico desarrollado para la asignatura DevOps de IACC.

Simula una plataforma web de reserva de horas médicas para el Centro Médico Salud Integral.

## Tecnologías utilizadas
- HTML y CSS
- Nginx Alpine
- Docker Desktop
- Docker Compose
- Git y GitHub

## Requisitos
- Docker Desktop instalado y funcionando.
- Docker Compose disponible.
- Navegador web.

## Ejecución
Abrir PowerShell en la carpeta del proyecto y ejecutar:

docker compose up -d --build

## Verificación
Acceder desde el navegador a:

http://localhost:8080

Comprobar el estado del contenedor:

docker compose ps

## Monitoreo
Consultar registros:

docker logs reservas-medicas

Consultar métricas:

docker stats --no-stream reservas-medicas

## Detener el servicio
docker compose down

## Seguridad
La aplicación es demostrativa y no almacena reservas.

No utiliza datos reales de pacientes ni credenciales.

El archivo .gitignore excluye configuraciones privadas.
El archivo .env.example contiene solamente valores de ejemplo.

## Limitaciones
El formulario es estático y no realiza reservas reales.
No utiliza base de datos ni API.
