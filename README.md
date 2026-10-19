# fraud-detection

El Problema Real

Los sistemas antifraude legacy de la banca funcionan con reglas estáticas ("si transacción > X€ y país != habitual → alerta"). Resultado:

~95% de falsos positivos — los analistas están enterrados en alertas inútiles
Los fraudes coordinados son invisibles — synthetic identity fraud, mule networks, y smurfing implican múltiples cuentas que individualmente parecen normales
Concept drift — los defraudadores se adaptan en días; tu modelo de ayer no sirve mañana

La clave: el fraude sofisticado no vive en las transacciones, vive en la topología del grafo.

Una cuenta que recibe dinero de 50 cuentas distintas recién creadas y lo envía a una sola cuenta en otro país es obvia cuando miras el grafo. Mirando transacciones individuales, cada una parece legítima.
