# proyecto-da-promo-d-modulo-4-powerBI-team-4

### :credit_card: Descripción del proyecto y objetivo:   

En este proyecto hemos utilizado Power BI para analizar un conjunto de datos de transacciones financieras con el objetivo de entender el comportamiento de los datos, observar tendencias y detectar posibles señales de riesgo. La visualización se centra en aspectos como comportamiento del usuario, riesgos de fraude y tendencias financieras.

### Estructura del Dataset   
El conjunto de datos contiene múltiples características divididas en las siguientes categorías:

##### :large_blue_circle: Identificación y Contexto   
•	Transaction_ID: Identificador único de la transacción.   
•	User_ID: Identificador único del usuario.   
•	Timestamp: Fecha y hora de la transacción.   
•	Location: Ubicación geográfica de la transacción.   
##### :large_blue_circle: Características Financieras   
•	Transaction_Amount: Cantidad involucrada en la transacción.   
•	Account_Balance: Saldo de cuenta antes de la transacción.   
•	Daily_Transaction_Count: Número de transacciones realizadas por el usuario en ese día.   
•	Avg_Transaction_Amount_7d: Promedio de la cantiadad de transacciones de los últimos 7 días.    
•	Failed_Transaction_Count_7d: Número de transacciones fallidas en los últimos 7 días.   
##### :large_blue_circle: Información del Dispositivo y Método   
•	Device_Type: Tipo de dispositivo utilizado (Móvil, Escritorio, etc.).   
•	Transaction_Type: Tipo de transacción (En línea, en tienda, cajero, etc.).   
•	Authentication_Method: Método de autenticación utilizado (PIN, Biometría, etc.).   
##### :large_blue_circle: Características de Riesgo    
•	Merchant_Category: Tipo de comerciante (Retail, Alimentos, Viajes, etc.).   
•	IP_Address_Flag: Indica si la IP fue marcada como sospechosa (0 o 1).   
•	Previous_Fraudulent_Activity: Número de actividades fraudulentas pasadas del usuario.   
•	Transaction_Distance: Distancia entre la ubicación habitual del usuario y la de la transacción.   
•	Risk_Score: Puntuación de riesgo estimada para la transacción.   
##### :large_blue_circle: Metadatos Adicionales   
•	Card_Type: Tipo de tarjeta utilizada (Crédito, Débito, Prepago, etc.).  
•	Card_Age: Antigüedad de la tarjeta en meses.  
•	Is_Weekend: Indica si la transacción ocurrió en fin de semana (0 o 1). 
##### :large_blue_circle: Etiqueta de Fraude   
•	Fraud_Label: Variable objetivo (0 = No es Fraude, 1 = Es Fraude).


