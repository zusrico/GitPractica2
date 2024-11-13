Alumno1: Jesus García Sánchez
Alumno2: José Antonio Montes Solano & Manuel 

Ejercicio 4 - Alumno 2:
git clone https://github.com/zusrico/GitPractica2.git

Hasta el ejercicio 6 - Almuno 1:
mkdir Git_IA
cd Git_IA
git init
git commit -m "Inicialización del repositorio con archivos Farmacia"
git remote add origin https://github.com/zusrico/GitPractica2.git
git remote
git push origin main
git config --global credential.helper store
git push origin main
git pull origin main

08/11/2024
Ejercicio 7 - Alumno 1:
git status
git branch
git branch ramaAlumno1
git branch 

Ejercicio 7 - Alumno 2:
git checkout -b ramaAlno2
git branch -m ramaAlno2 ramaAlumno2



git branch

Ejercicio 8 - Alumno 1:
git branch
El asterisco significa la rama en la que me encuentro.

Ejercicio 8 - Alumno 2:
git branch

Ejercicio 9.1 - Alumno 1:
git add almacen_cli.java
git commit -m "Añadiendo fichero almacen_cli.java"

Ejercicio 9.2 - Alumno 2:
git add cliente.java
git commit -m "Añadiendo fichero cliente.java"

Ejercicio 10 - Alumno 1:
git diff ramaAlumno1..main

Ejercicio 10 - Alumno2
La diferencia que encuentro: 
diff --git a/cliente.java b/cliente.java
new file mode 100644
index 0000000..d8070d5
--- /dev/null
+++ b/cliente.java
@@ -0,0 +1,58 @@
+package jungle;
+import java.lang.String;
+public class Cliente
+{
+private String cod_cli;
+private String nombre_cli;
+private String fecha_nacimiento;
+private String sexo;
+private String grupo_sanguineo;
+//Constructor
+public Cliente(String cod_cli_, String nombre_cli_, String fecha_nacimiento_,
+String sexo_, String grupo_sanguineo_)
+{
+this.cod_cli = cod_cli_;
+this.nombre_cli = nombre_cli_;
+this.fecha_nacimiento = fecha_nacimiento_;
+this.sexo = sexo_;
:...skipping...
diff --git a/cliente.java b/cliente.java
new file mode 100644
index 0000000..d8070d5
--- /dev/null
+++ b/cliente.java
@@ -0,0 +1,58 @@
+package jungle;
+import java.lang.String;
+public class Cliente
+{
+private String cod_cli;
+private String nombre_cli;
+private String fecha_nacimiento;
+private String sexo;
+private String grupo_sanguineo;
+//Constructor
+public Cliente(String cod_cli_, String nombre_cli_, String fecha_nacimiento_,
+String sexo_, String grupo_sanguineo_)
+{
+this.cod_cli = cod_cli_;
+this.nombre_cli = nombre_cli_;
+this.fecha_nacimiento = fecha_nacimiento_;
+this.sexo = sexo_;
+this.grupo_sanguineo = grupo_sanguineo_;
+}
+//Metodos observadores
+public String getCod_cli()
+{
+return cod_cli;
+}
+public String getNombre_cli()
+{
+return nombre_cli;
+}
+public String getFecha_nacimiento()
+{
+return fecha_nacimiento;
+}
+public String getSexo()
+{
+return sexo;
+}


Ejercicio 11 - Alumno 1:
git merge ramaAlumno1
git push origin master