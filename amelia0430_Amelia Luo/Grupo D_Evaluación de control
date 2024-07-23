import csv

# Banco de preguntas y recomendaciones
banco_preguntas = {
    "Gestión de Acceso": [
        {
            "pregunta": "¿La organización tiene establecidos procedimientos para la gestión de acceso a los sistemas y datos?",
            "recomendaciones": [
                "Desarrollar e implementar procedimientos claros y documentados para la gestión de acceso a sistemas y datos. Involucrar a todas las partes interesadas para asegurar que los procedimientos cubran todos los aspectos críticos. Asegurar la aprobación de estos procedimientos por la alta dirección y revisarlos periódicamente.",
                "Completar la documentación de los procedimientos de gestión de acceso para cubrir todos los sistemas y datos. Realizar una evaluación para identificar áreas de mejora y actualizar los procedimientos en consecuencia. Formar a todo el personal en la implementación y cumplimiento de estos procedimientos.",
                "Revisar y actualizar periódicamente los procedimientos para adaptarse a las mejores prácticas y cambios tecnológicos. Realizar auditorías internas para garantizar la efectividad de los procedimientos de gestión de acceso. Implementar controles de calidad para monitorear el cumplimiento de los procedimientos documentados.",
                "Asegurar la actualización continua de los procedimientos conforme a la evolución de las amenazas y las tecnologías. Documentar y mantener registros detallados de todos los cambios realizados en los procedimientos. Realizar capacitaciones periódicas para el personal sobre los procedimientos actualizados de gestión de acceso.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Los usuarios tienen roles y privilegios claramente definidos y documentados?",
            "recomendaciones": [
                "Definir y documentar claramente los roles y privilegios de todos los usuarios en la organización. Establecer un proceso formal para la asignación y revisión de roles y privilegios. Involucrar a la alta dirección para la aprobación y revisión periódica de los roles y privilegios definidos.",
                "Completar la documentación de roles y privilegios para todos los usuarios y sistemas. Implementar un sistema de gestión de identidad y acceso (IAM) para automatizar la asignación y revisión de privilegios. Realizar auditorías internas para asegurar la correcta definición y documentación de roles y privilegios.",
                "Revisar y actualizar periódicamente la definición de roles y privilegios para adaptarse a cambios organizacionales. Realizar capacitaciones periódicas para el personal sobre la importancia y cumplimiento de roles y privilegios. Documentar todos los cambios en roles y privilegios y mantener un registro de auditoría.",
                "Asegurar la actualización continua de roles y privilegios conforme a las mejores prácticas y cambios en la organización. Implementar controles automáticos para la gestión y revisión de roles y privilegios. Realizar auditorías exhaustivas y regulares para verificar la correcta asignación y documentación.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Se utiliza autenticación multifactor (MFA) para los accesos críticos?",
            "recomendaciones": [
                "Implementar MFA para todos los accesos críticos en la organización de inmediato. Asegurar que MFA sea una política obligatoria y no opcional para todos los usuarios críticos. Capacitar al personal sobre la importancia de MFA y cómo utilizarlo correctamente.",
                "Ampliar la implementación de MFA para cubrir todos los accesos críticos y no solo algunos. Realizar pruebas y evaluaciones regulares para asegurar la efectividad de MFA. Documentar la política de MFA y comunicarla a todos los usuarios relevantes.",
                "Revisar y actualizar regularmente la implementación de MFA para asegurar su eficacia continua. Realizar auditorías periódicas para garantizar que MFA esté siendo utilizado en todos los accesos críticos. Incluir MFA como parte de las capacitaciones periódicas de seguridad para el personal.",
                "Mantener la política de MFA actualizada y alineada con las mejores prácticas de la industria. Asegurar que todos los nuevos sistemas y accesos críticos implementen MFA desde el inicio. Documentar y auditar regularmente el uso de MFA en toda la organización.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Se realiza una revisión periódica de los accesos de los usuarios?",
            "recomendaciones": [
                "Establecer una política clara y documentada para la revisión periódica de los accesos de los usuarios. Asegurar que todas las revisiones sean aprobadas y supervisadas por la alta dirección. Implementar un calendario de revisiones periódicas y cumplirlo rigurosamente.",
                "Ampliar la frecuencia y el alcance de las revisiones periódicas de acceso. Documentar todos los hallazgos de las revisiones y realizar acciones correctivas inmediatas. Formar a los responsables de la revisión en las mejores prácticas y procedimientos actualizados.",
                "Realizar auditorías internas para asegurar la efectividad y cumplimiento de las revisiones de acceso. Revisar y actualizar regularmente la política de revisión de accesos. Documentar y mantener un registro detallado de todas las revisiones y acciones correctivas realizadas.",
                "Mantener y revisar periódicamente la política de revisión de accesos conforme a las mejores prácticas. Asegurar la participación de todas las partes interesadas en las revisiones de acceso. Documentar y auditar regularmente el proceso de revisión de accesos para garantizar su eficacia.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Se mantienen registros de los accesos y modificaciones de privilegios?",
            "recomendaciones": [
                "Implementar un sistema de registro y monitoreo de todos los accesos y modificaciones de privilegios. Asegurar que estos registros sean seguros y accesibles solo para personal autorizado. Establecer una política clara para la revisión y auditoría de estos registros.",
                "Completar y formalizar la política de mantenimiento de registros de accesos y modificaciones de privilegios. Aumentar la frecuencia de las auditorías de estos registros para asegurar su integridad. Documentar y mantener un registro detallado de todas las actividades de acceso y modificaciones de privilegios.",
                "Realizar auditorías regulares para verificar la integridad y exactitud de los registros de accesos y modificaciones. Revisar y actualizar periódicamente la política de mantenimiento de registros. Implementar controles adicionales para asegurar la protección de estos registros contra accesos no autorizados.",
                "Mantener la política de registros actualizada y alineada con las mejores prácticas. Documentar y auditar regularmente el proceso de mantenimiento de registros. Asegurar la implementación de tecnologías avanzadas para la gestión y protección de los registros.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        }
    ],
    "Seguridad Física y Ambiental": [
        {
            "pregunta": "¿Se tiene control de acceso físico a las instalaciones que albergan equipos críticos?",
            "recomendaciones": [
                "Implementar controles de acceso físico en todas las instalaciones críticas inmediatamente. Asegurar que todos los puntos de acceso estén protegidos y monitoreados. Documentar y comunicar la política de control de acceso físico a todo el personal relevante.",
                "Mejorar los controles de acceso físico existentes para cubrir todas las instalaciones críticas. Realizar evaluaciones periódicas para identificar y corregir deficiencias en los controles de acceso físico. Documentar y revisar regularmente la política de control de acceso físico.",
                "Realizar auditorías internas para asegurar la efectividad de los controles de acceso físico. Revisar y actualizar periódicamente la política de control de acceso físico. Incluir controles de acceso físico como parte de las capacitaciones de seguridad para el personal.",
                "Mantener la política de control de acceso físico actualizada y alineada con las mejores prácticas. Documentar y auditar regularmente los controles de acceso físico. Asegurar la implementación de tecnologías avanzadas para el control de acceso físico.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Existen medidas de protección física (cámaras, alarmas, etc.) en las áreas críticas?",
            "recomendaciones": [
                "Instalar inmediatamente cámaras, alarmas y otras medidas de protección física en todas las áreas críticas. Asegurar que todas las medidas de protección estén operativas y sean monitoreadas regularmente. Documentar y comunicar la política de protección física a todo el personal relevante.",
                "Mejorar la cobertura y efectividad de las medidas de protección física existentes. Realizar evaluaciones periódicas para asegurar que todas las medidas de protección estén operativas. Documentar y revisar regularmente la política de protección física.",
                "Realizar auditorías internas para asegurar la efectividad de las medidas de protección física. Revisar y actualizar periódicamente la política de protección física. Incluir medidas de protección física como parte de las capacitaciones de seguridad para el personal.",
                "Mantener la política de protección física actualizada y alineada con las mejores prácticas. Documentar y auditar regularmente las medidas de protección física. Asegurar la implementación de tecnologías avanzadas para la protección física.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Se realizan pruebas regulares de las medidas de seguridad física?",
            "recomendaciones": [
                "Establecer un calendario de pruebas regulares para todas las medidas de seguridad física. Asegurar que todas las pruebas sean documentadas y revisadas por la alta dirección. Implementar acciones correctivas inmediatas para cualquier deficiencia encontrada durante las pruebas.",
                "Aumentar la frecuencia y el alcance de las pruebas de seguridad física. Documentar todos los resultados de las pruebas y realizar acciones correctivas en tiempo y forma. Realizar auditorías internas para verificar la efectividad de las pruebas de seguridad física.",
                "Realizar auditorías regulares para asegurar la efectividad y cumplimiento de las pruebas de seguridad física. Revisar y actualizar periódicamente el calendario de pruebas de seguridad física. Documentar y mantener un registro detallado de todas las pruebas y acciones correctivas realizadas.",
                "Mantener y revisar periódicamente el calendario de pruebas de seguridad física. Asegurar la participación de todas las partes interesadas en las pruebas de seguridad física. Documentar y auditar regularmente el proceso de pruebas de seguridad física para garantizar su eficacia.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Se cuenta con políticas para la gestión de visitantes en áreas restringidas?",
            "recomendaciones": [
                "Desarrollar e implementar políticas claras y documentadas para la gestión de visitantes en áreas restringidas. Asegurar que todas las visitas sean registradas y monitoreadas en todo momento. Capacitar al personal sobre la política de gestión de visitantes y su importancia.",
                "Completar la documentación de las políticas de gestión de visitantes para cubrir todas las áreas restringidas. Realizar auditorías periódicas para asegurar el cumplimiento de las políticas de gestión de visitantes. Documentar y mantener un registro detallado de todas las visitas y monitorearlas regularmente.",
                "Revisar y actualizar periódicamente las políticas de gestión de visitantes para adaptarse a cambios organizacionales. Realizar capacitaciones periódicas para el personal sobre la política de gestión de visitantes. Documentar todos los cambios en la política y mantener un registro de auditoría.",
                "Mantener y revisar periódicamente las políticas de gestión de visitantes conforme a las mejores prácticas. Asegurar la implementación de controles automáticos para la gestión y monitoreo de visitantes. Realizar auditorías exhaustivas y regulares para verificar la correcta implementación de la política de gestión de visitantes.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Hay un plan de contingencia para emergencias físicas (incendios, inundaciones, etc.)?",
            "recomendaciones": [
                "Desarrollar y documentar un plan de contingencia para emergencias físicas inmediatamente. Asegurar que el plan cubra todos los posibles escenarios de emergencia, incluyendo incendios e inundaciones. Capacitar al personal sobre el plan de contingencia y realizar simulacros regulares.",
                "Completar la documentación del plan de contingencia y asegurar que cubra todos los posibles escenarios. Realizar simulacros periódicos para probar la efectividad del plan de contingencia. Documentar y revisar regularmente el plan de contingencia para asegurar su actualización.",
                "Realizar auditorías internas para asegurar la efectividad y cumplimiento del plan de contingencia. Revisar y actualizar periódicamente el plan de contingencia para adaptarse a cambios organizacionales. Documentar todos los cambios en el plan y mantener un registro de auditoría.",
                "Mantener y revisar periódicamente el plan de contingencia conforme a las mejores prácticas. Asegurar la implementación de controles automáticos para la gestión de emergencias. Realizar auditorías exhaustivas y regulares para verificar la correcta implementación del plan de contingencia.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        }
    ],
    "Gestión de Comunicaciones y Operaciones": [
        {
            "pregunta": "¿Existe una política formal para la gestión de redes y comunicaciones?",
            "recomendaciones": [
                "Desarrollar e implementar una política formal y documentada para la gestión de redes y comunicaciones. Asegurar que la política cubra todos los aspectos críticos de la gestión de redes y comunicaciones. Capacitar al personal sobre la política y su importancia para la seguridad de la información.",
                "Completar la documentación de la política de gestión de redes y comunicaciones. Realizar auditorías periódicas para asegurar el cumplimiento de la política. Documentar y revisar regularmente la política para asegurar su actualización.",
                "Revisar y actualizar periódicamente la política de gestión de redes y comunicaciones para adaptarse a cambios tecnológicos. Realizar capacitaciones periódicas para el personal sobre la política de gestión de redes y comunicaciones. Documentar todos los cambios en la política y mantener un registro de auditoría.",
                "Mantener y revisar periódicamente la política de gestión de redes y comunicaciones conforme a las mejores prácticas. Asegurar la implementación de controles automáticos para la gestión y monitoreo de redes y comunicaciones. Realizar auditorías exhaustivas y regulares para verificar la correcta implementación de la política de gestión de redes y comunicaciones.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Se implementan controles para proteger la integridad y confidencialidad de las comunicaciones?",
            "recomendaciones": [
                "Implementar controles básicos y avanzados para proteger la integridad y confidencialidad de las comunicaciones. Asegurar que todos los canales de comunicación estén protegidos contra accesos no autorizados. Capacitar al personal sobre la importancia de proteger la integridad y confidencialidad de las comunicaciones.",
                "Mejorar los controles existentes para proteger la integridad y confidencialidad de las comunicaciones. Realizar auditorías periódicas para asegurar la efectividad de los controles implementados. Documentar y revisar regularmente los controles para asegurar su actualización.",
                "Revisar y actualizar periódicamente los controles para proteger la integridad y confidencialidad de las comunicaciones. Realizar auditorías internas para asegurar la efectividad de los controles implementados. Documentar todos los cambios en los controles y mantener un registro de auditoría.",
                "Mantener y revisar periódicamente los controles conforme a las mejores prácticas. Asegurar la implementación de controles automáticos para la protección de las comunicaciones. Realizar auditorías exhaustivas y regulares para verificar la correcta implementación de los controles.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Se realiza monitorización continua de la red y sistemas para detectar anomalías?",
            "recomendaciones": [
                "Implementar un sistema de monitorización continua para redes y sistemas inmediatamente. Asegurar que la monitorización cubra todos los aspectos críticos y esté operativa en todo momento. Capacitar al personal sobre la importancia de la monitorización continua y cómo responder a las anomalías.",
                "Mejorar la cobertura y efectividad del sistema de monitorización continua existente. Realizar auditorías periódicas para asegurar la efectividad de la monitorización. Documentar y mantener un registro detallado de todas las anomalías detectadas y las acciones correctivas tomadas.",
                "Revisar y actualizar periódicamente el sistema de monitorización continua para adaptarse a cambios tecnológicos. Realizar auditorías internas para asegurar la efectividad del sistema de monitorización. Documentar todos los cambios en el sistema de monitorización y mantener un registro de auditoría.",
                "Mantener y revisar periódicamente el sistema de monitorización continua conforme a las mejores prácticas. Asegurar la implementación de tecnologías avanzadas para la monitorización continua. Realizar auditorías exhaustivas y regulares para verificar la correcta implementación del sistema de monitorización.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Hay procedimientos establecidos para la gestión de cambios en los sistemas y redes?",
            "recomendaciones": [
                "Desarrollar e implementar procedimientos claros y documentados para la gestión de cambios en sistemas y redes. Asegurar que todos los cambios sean aprobados y supervisados por la alta dirección. Capacitar al personal sobre los procedimientos de gestión de cambios y su importancia.",
                "Completar la documentación de los procedimientos de gestión de cambios existentes. Realizar auditorías periódicas para asegurar el cumplimiento de los procedimientos de gestión de cambios. Documentar y revisar regularmente los procedimientos para asegurar su actualización.",
                "Revisar y actualizar periódicamente los procedimientos de gestión de cambios para adaptarse a cambios tecnológicos. Realizar auditorías internas para asegurar la efectividad de los procedimientos de gestión de cambios. Documentar todos los cambios en los procedimientos y mantener un registro de auditoría.",
                "Mantener y revisar periódicamente los procedimientos de gestión de cambios conforme a las mejores prácticas. Asegurar la implementación de controles automáticos para la gestión de cambios en sistemas y redes. Realizar auditorías exhaustivas y regulares para verificar la correcta implementación de los procedimientos de gestión de cambios.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Se llevan a cabo pruebas periódicas de vulnerabilidades y pentesting?",
            "recomendaciones": [
                "Establecer un calendario de pruebas periódicas de vulnerabilidades y pen-testing inmediatamente. Asegurar que todas las pruebas sean documentadas y revisadas por la alta dirección. Implementar acciones correctivas inmediatas para cualquier vulnerabilidad encontrada durante las pruebas.",
                "Aumentar la frecuencia y el alcance de las pruebas de vulnerabilidades y pen-testing. Documentar todos los resultados de las pruebas y realizar acciones correctivas en tiempo y forma. Realizar auditorías internas para verificar la efectividad de las pruebas de vulnerabilidades y pen-testing.",
                "Realizar auditorías regulares para asegurar la efectividad y cumplimiento de las pruebas de vulnerabilidades y pen-testing. Revisar y actualizar periódicamente el calendario de pruebas de vulnerabilidades y pen-testing. Documentar y mantener un registro detallado de todas las pruebas y acciones correctivas realizadas.",
                "Mantener y revisar periódicamente el calendario de pruebas de vulnerabilidades y pen-testing. Asegurar la participación de todas las partes interesadas en las pruebas de vulnerabilidades y pen-testing. Documentar y auditar regularmente el proceso de pruebas de vulnerabilidades y pen-testing para garantizar su eficacia.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        }
    ],
    "Control de Acceso a la Información": [
        {
            "pregunta": "¿Se utilizan mecanismos de control de acceso a la información según los roles de los usuarios?",
            "recomendaciones": [
                "Implementar mecanismos básicos de control de acceso a la información según los roles de los usuarios. Asegurar que todos los accesos estén claramente definidos y documentados. Capacitar al personal sobre la importancia de los controles de acceso y cómo utilizarlos correctamente.",
                "Mejorar la implementación de los mecanismos de control de acceso existentes para cubrir todos los roles de usuarios. Realizar auditorías periódicas para asegurar la efectividad de los controles de acceso implementados. Documentar y revisar regularmente los controles de acceso para asegurar su actualización.",
                "Revisar y actualizar periódicamente los mecanismos de control de acceso para adaptarse a cambios organizacionales. Realizar auditorías internas para asegurar la efectividad de los controles de acceso implementados. Documentar todos los cambios en los controles de acceso y mantener un registro de auditoría.",
                "Mantener y revisar periódicamente los mecanismos de control de acceso conforme a las mejores prácticas. Asegurar la implementación de controles automáticos para la gestión de accesos según los roles de los usuarios. Realizar auditorías exhaustivas y regulares para verificar la correcta implementación de los controles de acceso.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Existe cifrado de datos tanto en reposo como en tránsito?",
            "recomendaciones": [
                "Implementar inmediatamente el cifrado de datos tanto en reposo como en tránsito. Asegurar que todas las políticas y procedimientos de cifrado estén claramente documentados. Capacitar al personal sobre la importancia del cifrado y cómo aplicarlo correctamente.",
                "Mejorar la implementación del cifrado de datos para cubrir todos los datos en reposo y en tránsito. Realizar auditorías periódicas para asegurar la efectividad del cifrado implementado. Documentar y revisar regularmente las políticas y procedimientos de cifrado para asegurar su actualización.",
                "Revisar y actualizar periódicamente las políticas y procedimientos de cifrado para adaptarse a cambios tecnológicos. Realizar auditorías internas para asegurar la efectividad del cifrado implementado. Documentar todos los cambios en las políticas y procedimientos de cifrado y mantener un registro de auditoría.",
                "Mantener y revisar periódicamente las políticas y procedimientos de cifrado conforme a las mejores prácticas. Asegurar la implementación de tecnologías avanzadas para el cifrado de datos tanto en reposo como en tránsito. Realizar auditorías exhaustivas y regulares para verificar la correcta implementación del cifrado.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Se implementan políticas de clasificación y etiquetado de la información?",
            "recomendaciones": [
                "Desarrollar e implementar políticas claras y documentadas de clasificación y etiquetado de la información. Asegurar que todas las políticas sean comunicadas a todo el personal relevante. Capacitar al personal sobre la importancia de la clasificación y etiquetado de la información y cómo aplicarlas correctamente.",
                "Completar la documentación de las políticas de clasificación y etiquetado de la información. Realizar auditorías periódicas para asegurar el cumplimiento de las políticas de clasificación y etiquetado. Documentar y revisar regularmente las políticas para asegurar su actualización.",
                "Revisar y actualizar periódicamente las políticas de clasificación y etiquetado para adaptarse a cambios organizacionales. Realizar auditorías internas para asegurar la efectividad de las políticas de clasificación y etiquetado. Documentar todos los cambios en las políticas y mantener un registro de auditoría.",
                "Mantener y revisar periódicamente las políticas de clasificación y etiquetado conforme a las mejores prácticas. Asegurar la implementación de tecnologías avanzadas para la clasificación y etiquetado de la información. Realizar auditorías exhaustivas y regulares para verificar la correcta implementación de las políticas.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Los sistemas de gestión de documentos aseguran el control de versiones y el acceso autorizado?",
            "recomendaciones": [
                "Implementar sistemas de gestión de documentos que aseguren el control de versiones y el acceso autorizado. Asegurar que todos los documentos críticos estén bajo control de versiones y accesibles solo para personal autorizado. Capacitar al personal sobre la importancia del control de versiones y el acceso autorizado y cómo utilizar los sistemas correctamente.",
                "Mejorar la implementación de los sistemas de gestión de documentos para asegurar el control de versiones y el acceso autorizado. Realizar auditorías periódicas para asegurar la efectividad de los sistemas de gestión de documentos. Documentar y revisar regularmente los sistemas de gestión de documentos para asegurar su actualización.",
                "Revisar y actualizar periódicamente los sistemas de gestión de documentos para adaptarse a cambios organizacionales. Realizar auditorías internas para asegurar la efectividad de los sistemas de gestión de documentos. Documentar todos los cambios en los sistemas y mantener un registro de auditoría.",
                "Mantener y revisar periódicamente los sistemas de gestión de documentos conforme a las mejores prácticas. Asegurar la implementación de tecnologías avanzadas para el control de versiones y el acceso autorizado. Realizar auditorías exhaustivas y regulares para verificar la correcta implementación de los sistemas de gestión de documentos.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Se auditan regularmente los accesos a la información sensible?",
            "recomendaciones": [
                "Establecer un calendario de auditorías regulares para los accesos a la información sensible inmediatamente. Asegurar que todas las auditorías sean documentadas y revisadas por la alta dirección. Implementar acciones correctivas inmediatas para cualquier acceso no autorizado encontrado durante las auditorías.",
                "Aumentar la frecuencia y el alcance de las auditorías de accesos a la información sensible. Documentar todos los resultados de las auditorías y realizar acciones correctivas en tiempo y forma. Realizar auditorías internas para verificar la efectividad de las auditorías de accesos a la información sensible.",
                "Realizar auditorías regulares para asegurar la efectividad y cumplimiento de las auditorías de accesos a la información sensible. Revisar y actualizar periódicamente el calendario de auditorías de accesos a la información sensible. Documentar y mantener un registro detallado de todas las auditorías y acciones correctivas realizadas.",
                "Mantener y revisar periódicamente el calendario de auditorías de accesos a la información sensible. Asegurar la participación de todas las partes interesadas en las auditorías de accesos a la información sensible. Documentar y auditar regularmente el proceso de auditorías de accesos a la información sensible para garantizar su eficacia.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        }
    ],
    "Gestión de Incidentes de Seguridad de la Información": [
        {
            "pregunta": "¿La organización tiene un plan de respuesta ante incidentes de seguridad de la información?",
            "recomendaciones": [
                "Desarrollar y documentar un plan de respuesta ante incidentes de seguridad de la información inmediatamente. Asegurar que el plan cubra todos los posibles escenarios de incidentes de seguridad. Capacitar al personal sobre el plan de respuesta y realizar simulacros regulares.",
                "Completar la documentación del plan de respuesta ante incidentes y asegurar que cubra todos los posibles escenarios. Realizar simulacros periódicos para probar la efectividad del plan de respuesta. Documentar y revisar regularmente el plan de respuesta para asegurar su actualización.",
                "Realizar auditorías internas para asegurar la efectividad y cumplimiento del plan de respuesta. Revisar y actualizar periódicamente el plan de respuesta para adaptarse a cambios organizacionales. Documentar todos los cambios en el plan y mantener un registro de auditoría.",
                "Mantener y revisar periódicamente el plan de respuesta conforme a las mejores prácticas. Asegurar la implementación de controles automáticos para la gestión de incidentes de seguridad. Realizar auditorías exhaustivas y regulares para verificar la correcta implementación del plan de respuesta.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Se realizan simulacros periódicos para probar la efectividad del plan de respuesta?",
            "recomendaciones": [
                "Establecer un calendario de simulacros periódicos para probar la efectividad del plan de respuesta inmediatamente. Asegurar que todos los simulacros sean documentados y revisados por la alta dirección. Implementar acciones correctivas inmediatas para cualquier deficiencia encontrada durante los simulacros.",
                "Aumentar la frecuencia y el alcance de los simulacros de respuesta. Documentar todos los resultados de los simulacros y realizar acciones correctivas en tiempo y forma. Realizar auditorías internas para verificar la efectividad de los simulacros de respuesta.",
                "Realizar auditorías regulares para asegurar la efectividad y cumplimiento de los simulacros de respuesta. Revisar y actualizar periódicamente el calendario de simulacros de respuesta. Documentar y mantener un registro detallado de todos los simulacros y acciones correctivas realizadas.",
                "Mantener y revisar periódicamente el calendario de simulacros de respuesta. Asegurar la participación de todas las partes interesadas en los simulacros de respuesta. Documentar y auditar regularmente el proceso de simulacros de respuesta para garantizar su eficacia.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Existe un proceso documentado para la notificación de incidentes a las partes interesadas?",
            "recomendaciones": [
                "Desarrollar e implementar un proceso documentado para la notificación de incidentes a las partes interesadas inmediatamente. Asegurar que el proceso cubra todas las posibles partes interesadas y escenarios de notificación. Capacitar al personal sobre el proceso de notificación y su importancia para la seguridad de la información.",
                "Completar la documentación del proceso de notificación de incidentes para cubrir todos los posibles escenarios. Realizar auditorías periódicas para asegurar el cumplimiento del proceso de notificación. Documentar y revisar regularmente el proceso para asegurar su actualización.",
                "Revisar y actualizar periódicamente el proceso de notificación de incidentes para adaptarse a cambios organizacionales. Realizar auditorías internas para asegurar la efectividad del proceso de notificación. Documentar todos los cambios en el proceso y mantener un registro de auditoría.",
                "Mantener y revisar periódicamente el proceso de notificación de incidentes conforme a las mejores prácticas. Asegurar la implementación de controles automáticos para la notificación de incidentes. Realizar auditorías exhaustivas y regulares para verificar la correcta implementación del proceso de notificación.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Se realiza un análisis post-incidente para identificar lecciones aprendidas y mejoras?",
            "recomendaciones": [
                "Establecer un proceso formal y documentado para realizar análisis post-incidente inmediatamente. Asegurar que todos los análisis post-incidente sean documentados y revisados por la alta dirección. Implementar acciones correctivas inmediatas basadas en las lecciones aprendidas durante el análisis post-incidente.",
                "Mejorar el proceso de análisis post-incidente para asegurar que cubra todos los aspectos críticos. Documentar todos los resultados del análisis post-incidente y realizar acciones correctivas en tiempo y forma. Realizar auditorías internas para verificar la efectividad del análisis post-incidente.",
                "Realizar auditorías regulares para asegurar la efectividad y cumplimiento del análisis post-incidente. Revisar y actualizar periódicamente el proceso de análisis post-incidente. Documentar y mantener un registro detallado de todos los análisis y acciones correctivas realizadas.",
                "Mantener y revisar periódicamente el proceso de análisis post-incidente conforme a las mejores prácticas. Asegurar la participación de todas las partes interesadas en el análisis post-incidente. Documentar y auditar regularmente el proceso de análisis post-incidente para garantizar su eficacia.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        },
        {
            "pregunta": "¿Se actualiza regularmente el plan de respuesta ante incidentes?",
            "recomendaciones": [
                "Establecer un calendario para la actualización regular del plan de respuesta ante incidentes inmediatamente. Asegurar que todas las actualizaciones sean documentadas y revisadas por la alta dirección. Implementar acciones correctivas inmediatas para cualquier deficiencia identificada durante la actualización del plan.",
                "Mejorar la frecuencia y el alcance de las actualizaciones del plan de respuesta ante incidentes. Documentar todas las actualizaciones del plan y realizar acciones correctivas en tiempo y forma. Realizar auditorías internas para verificar la efectividad de las actualizaciones del plan de respuesta.",
                "Realizar auditorías regulares para asegurar la efectividad y cumplimiento de las actualizaciones del plan de respuesta. Revisar y actualizar periódicamente el calendario de actualizaciones del plan de respuesta. Documentar y mantener un registro detallado de todas las actualizaciones y acciones correctivas realizadas.",
                "Mantener y revisar periódicamente el calendario de actualizaciones del plan de respuesta. Asegurar la participación de todas las partes interesadas en las actualizaciones del plan de respuesta. Documentar y auditar regularmente el proceso de actualización del plan de respuesta para garantizar su eficacia.",
                "No se añaden recomendaciones ya que sí cumple con los criterios de la norma ISO-27001."
            ]
        }
    ]
}

# Función para realizar el cuestionario
def realizar_cuestionario():
    resultados = {}

    for tema, preguntas in banco_preguntas.items():
        print(f"TEMA: {tema}")
        tema_resultados = []
        
        for pregunta in preguntas:
            print(pregunta["pregunta"])
            while True:
                try:
                    valoracion = int(input("Inserte una valoración del 1 al 5: "))
                    if valoracion < 1 or valoracion > 5:
                        raise ValueError
                    break
                except ValueError:
                    print("Por favor, inserte un número válido del 1 al 5.")
            
            print("Recomendación:", pregunta["recomendaciones"][valoracion - 1])
            tema_resultados.append({
                "pregunta": pregunta["pregunta"],
                "valoracion": valoracion,
                "recomendacion": pregunta["recomendaciones"][valoracion - 1]
            })
        
        resultados[tema] = tema_resultados
    
    return resultados

# Función para generar archivo CSV
def generar_resultados_csv(resultados):
    with open("resultados_cuestionario.csv", mode='w', newline='') as file:
        writer = csv.writer(file)
        writer.writerow(["Aspecto", "Pregunta", "Valoración", "Recomendación"])

        for tema, respuestas in resultados.items():
            for respuesta in respuestas:
                writer.writerow([tema, respuesta['pregunta'], respuesta['valoracion'], respuesta['recomendacion']])

# Ejecución del cuestionario y generación de resultados
resultados = realizar_cuestionario()
generar_resultados_csv(resultados)
print("Cuestionario completado. Resultados guardados en 'resultados_cuestionario.csv'.")
