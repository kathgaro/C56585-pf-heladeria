### Error 
sass : No se puede cargar el archivo C:\Users\kathgaro\AppData\Roaming\npm\sass.ps1 porque la ejecución de scripts está deshabilitada en    
este sistema. Para obtener más información, consulta el tema about_Execution_Policies en https:/go.microsoft.com/fwlink/?LinkID=135170.     
En línea: 1 Carácter: 1
+ sass scss/style.scss css/styles.css
+ ~~~~
    + CategoryInfo          : SecurityError: (:) [], PSSecurityException
    + FullyQualifiedErrorId : UnauthorizedAccess

### Solucion
Solucion:
- comando de instalacion: npm install -g sass -
1. Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
2. Volver a ejecutar comando -   



## Cambiar nombre de repositorio
Settings > Nombre de repo
En visual code > Abrimos terminal > git pull