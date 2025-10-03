# Cypress OrangeHRM Login Test
Este proyecto contiene pruebas E2E utilizando **Cypress** para el **login de la aplicación OrangeHRM**.  


## Descripción
La prueba valida que un usuario pueda iniciar sesión correctamente con credenciales válidas.
Se verifica:  
- Acceso a la URL de login: `https://opensource-demo.orangehrmlive.com/web/index.php/auth/login`  
- Ingreso de usuario y contraseña (`Admin` / `admin123`)  
- Redirección exitosa al dashboard  
- Visualización del texto "Dashboard" en la página  

## Ubicación del test
- `cypress/e2e/` → (`login.cy.js`)  
 

## Requisitos
- Node.js instalado 
- Cypress instalado


## Cómo ejecutar las pruebas
1. Instalar dependencias:
```bash
npm install
```
2. Abrir Cypress en modo interactivo:
```bash
npx cypress open
```
3. Seleccionar el test `login.cy.js` y ejecutarlo en el navegador.