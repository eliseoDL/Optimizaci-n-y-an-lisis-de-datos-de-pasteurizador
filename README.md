# Simulación y optimización de un reactor tubular (PFR) utilizando DWSIM, Python y Power BI

Introducción.

Este proyecto busca integrar conocimiento técnicos de ingenieria con las herramientas actuales útilizadas en el análisis de datos como son; Python, MysQL y PowerBI, con el fin de buscar optimizar energeticamente el proceso de pasteurizacion de leche, utilizando un intercambiador de calor de placas, el cual opera en las condiciones de la tabla1.

Etapas de flujo de datos en el proyecto.

1) Simulacion del proceso de pasteurizacion y guardados de los datos del proceso en archivo CSV
2) Scripts de python lee el archivo CSV, se modelan/organizan los datos, se cálculan kpis relevantes y se guarda en una base de datos en MysQL (esto se hace para buscar una automatizacion del flujo)
3) Se conecta a PowerBI la base de datos MysQL (Se genera una query con los datos necesarios), podemos utilizar o no (scrips de python para graficos o objetos que no esten en powebi)
4) Se crea el tablero dashboard para compartir (puede automatizarse un scrips que lo comparta con mail, dada cierta frecuencia establecida)
