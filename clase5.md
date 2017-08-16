# Categorías de las Intrucciones
Las instrucciones SPARC V8 se pueden agrupar en seis categorías:  

+ Load/Store (carga / almacenamiento)
+ Aritmético-lógicas
+ **CTI(Control Transfer Instruction - Instrucciones de tranferencia de control)**
+ Acceso a registros de estado
+ Instrucciones de unidad de punto flotante
+ Intrucciones de co-procesador



## Intrucciones de control de transferencia (CTI).
 Las instrucciones de control de tranferencia se conforman por instrucciones que modifican el **nPC**. (Next program Counter)**nPC** es un registro de 32 bits que contiene las direccón de la próxima instrucción a ejectutar. Las instrucciones de control de tranferencia son: 
 
 - Saltos y ramas condicionados **Branch** (**Bicc, FBfcc,CPccc**)
 - Llamados **Call and Link** (**CALL**)
 - saltos **Jump and Link**(**JUMPL**)
 - Retorno de excepciones **Return from Trap**(**RETT**)
 - Excepciones **Trap** (**TIcc**)
 
 Estas categorias se clasifican de acuedo a la forma en la que se calcula la dirección de salto. 