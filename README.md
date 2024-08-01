# CI/CD Pipeline

Este repositorio contiene la configuración del pipeline CI/CD para una aplicación de ejemplo.

## Contenido

- **azure-pipelines.yml**: Configuración del pipeline para Azure DevOps.
- **deployment.yaml**: Archivo de despliegue para Kubernetes en AKS.

## Pasos del Pipeline

1. Clonar el repositorio de GitHub.
2. Instalar dependencias de Node.js.
3. Ejecutar análisis de código estático.
4. Ejecutar pruebas unitarias.
5. Construir una imagen Docker.
6. Enviar la imagen Docker a un registro de contenedores en Azure.
7. Desplegar la aplicación en un clúster de AKS.

## Configuración

### Variables de Pipeline

- **imageRepository**: Repositorio de imágenes Docker.
- **containerRegistry**: Registro de contenedores de Azure.
- **dockerfilePath**: Ruta del archivo Dockerfile.
- **tag**: Etiqueta de la imagen Docker.
- **azureSubscription**: Conexión de servicio a Azure.
- **resourceGroup**: Grupo de recursos de Azure.
- **aksCluster**: Nombre del clúster de AKS.

### Instrucciones de Despliegue

1. Clonar este repositorio.
2. Configurar las variables de entorno según las necesidades.
3. Ejecutar el pipeline en Azure DevOps.

## Enlaces

- [Repositorio del Script de Verificación de Estado del Servidor](https://github.com/argon1996/server-health-check)
