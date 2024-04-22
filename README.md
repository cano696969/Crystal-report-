Crystal Reports para Visual Studio 2022

PorMiguel Ramírez
 FEB 13, 2023  #Crystal Reports, #Visual Studio 2022
Crystal Reports for Visual Studio 2022 fue lanzado en mayo de 2022, la ultima versión es la Crystal Reports SP32. Aquí te dejaré los archivos necesarios para que puedas descargar y asi crear tus reportes con Crystal Reports para Visual Studio 2022.


![image](https://github.com/cano696969/Crystal-report-/assets/158393938/8b83da2e-8b0b-4455-97cd-51b267a96543)


SAP Crystal Report para VS 2022 necesita dos paquetes de instalación de SAP Crystal Report.

Descargue SAP Crystal Reports versión SP32 de 64 bits (Edición de desarrollador), CRforVS6413SP32_0-80007712.EXE, que instalará:
a) Crystal Reports para Microsoft Visual Studio 2022 (instala las plantillas de proyectos y elementos del cuadro de herramientas),
b) motor de tiempo de ejecución CR de 32 bits también.
En el caso de que ocurra un error al iniciar la instalación, que hace referencia a que falta instalar el Paquete Redistribuible de Visual C++ 2013, debes primero descargar e instalar este archivo vcredist_x64.exe.
Luego descargue SAP Crystal Report versión SP32 de 64 bits (motor de tiempo de ejecución para 64 bits, CR13SP32MSI64_0-80007712.MSI) y procesa a instalar.

esto lograrás tener disponible la plantilla para proyectos de Crystal Reports en Visual Studio 2022, como así también los controles respectivos en el cuadro de herramientas.


Como extra, dejo los paquetes para redistribución de aplicaciones con Crystal Reports 32bits y 64bits, y para ClickOnce.

Paquete para ClickOnce: CR13SP32ClikOnce_0-80007712.ZIP
Paquete redistribución 32bits: CR13SP32Redist32_0-80007712.ZIP
Paquete redistribución 64bits: CR13SP32Redist64_0-80007712.ZIP

