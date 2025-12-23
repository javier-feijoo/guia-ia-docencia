# ANEXO II – Plantillas de prompts útiles para docentes
Esta sección recolle modelos de prompts deseñados para xerar materiais educativos con intelixencia artificial, especialmente programacións, unidades, rúbricas ou actividades aliñadas coa normativa vixente en Galicia (LOMLOE e decretos autonómicos). Estan estruturados como un modelo editable, e deseñados para:

- Ser copiados directamente nun modelo de IA xerativa.
- Ser modificados facilmente segundo o nivel educativo, materia ou contexto.
- Proporcionar respostas estruturadas e útiles para o traballo docente.
- Lenda de símbolos para personalizar os prompts

!!! info "Notacións empregadas nos prompt"

    - **< OBRIGATORIO >**: Debe ser personalizado polo docente (materia, nivel, normativa...).
    - **[ OPCIONAL ]**: Podes manter, adaptar ou eliminar segundo o contexto.

---

## Como usar estes prompts paso a paso

- Le o prompt completo.
- Substitúe os campos **< OBRIGATORIO >** pola túa información concreta (materia, nivel, normativa…).
- Decide se queres manter ou eliminar os campos **[ OPCIONAL ]**, segundo a realidade do teu centro ou grupo.
- Copia o texto final e pégallo a unha ferramenta de IA como ChatGPT.
- Revisa o resultado xerado e adáptao ao teu contexto educativo, co teu criterio profesional.

**Boas prácticas**

- Non esperes un documento final perfecto: a IA ofrece primeiros borradores que cómpre revisar.
- Canta máis información contextual achegues (normativa, fragmentos do currículo, número de sesións...), mellor será a resposta.
- Os prompts son unha axuda ao traballo docente, non unha substitución do mesmo.

---

## BLOQUE A - Prompts para planificación didáctica
Prompts orientados á planificación anual, trimestral ou de unidades didácticas, especialmente útiles para aforrar tempo e asegurar coherencia co currículo vixente.

!!! note "Prompt 1. Planificación anual dun curso"

    Axuda a xerar unha planificación xeral dun curso completo aliñada coa LOMLOE e coa normativa galega, que logo debe ser revisada e adaptada polo docente.

    ```
    Actúa como un experto en deseño curricular en Galicia, cun coñecemento profundo da LOMLOE e da normativa autonómica vixente segundo a etapa educativa. Estás especializado na materia de <MATERIA> no nivel de <NIVEL EDUCATIVO>.

    Xera unha planificación anual completa e aliñada coa normativa oficial, que inclúa:

    1. Resultados de aprendizaxe (RA) e a súa correspondencia cos criterios de avaliación (CE).

    2. Unidades didácticas organizadas cronoloxicamente, indicando o número estimado de sesións por unidade ([DURACIÓN ESTÁNDAR:50MIN]).

    3. Competencias clave e competencias específicas traballadas en cada unidade.

    4. Metodoloxía proposta (aprendizaxe cooperativa, aprendizaxe baseada en proxectos, gamificación, aprendizaxe por investigación...).
    
    5. Estratexias de avaliación diversificadas (rúbricas, portafolio, avaliación entre iguais, observación sistemática...).
    
    6. [RECURSOS DIXITAIS GRATUÍTOS OU OPEN SOURCE ADAPTADOS Á MATERIA E NIVEL.]
    
    7. Propostas de atención á diversidade (alumnado con NEAE, diferentes ritmos de aprendizaxe, adaptacións metodolóxicas, etc.).

    A planificación debe basearse na seguinte normativa de referencia: <SELECCIONA A NORMATIVA SEGUNDO O NIVEL:  
    - DECRETO 106/2022 (Educación Primaria)
    - DECRETO 157/2022 (ESO e Bacharelato) 
    - LEI ORGÁNICA 3/2022 e RD 659/2023 (Formación Profesional)
    - OUTRAS NORMATIVAS COMPLEMENTARIAS SE PROCEDE>

    [PODES ACHEGAR FRAGMENTOS DO CURRÍCULO OFICIAL DA MATERIA E NIVEL OU ENLACES AOS DOCUMENTOS NORMATIVOS PARA UNHA MELLOR ADAPTACIÓN]
    
    [INDICA SE DESEXAS LIMITAR A EXTENSIÓN DA RESPOSTA (POR EXEMPLO: MÁXIMO 2 PÁXINAS OU 1500 PALABRAS).]

    [SE PREFIRES UN FORMATO CONCRETO, INDÍCAO: 
    - ESQUEMA CON EPÍGRAFES NUMERADOS
    - TÁBOA POR UNIDADES 
    - DOCUMENTO TIPO PROGRAMACIÓN FORMAL 
    - TEXTO CORRIDO PARA ADAPTAR A WORD OU PDF]
    ```



!!! note "Prompt 2. Deseño dunha unidade didáctica con actividades"

    *Permite crear unha primeira versión de apuntes e actividades dunha unidade didáctica, que o docente pode revisar e adaptar ao seu alumnado.*

    ``` prompt

    Actúa como un docente experto en <MATERIA> no nivel educativo de <NIVEL EDUCATIVO>, cun coñecemento sólido da LOMLOE e da normativa curricular vixente en Galicia. Tes experiencia no deseño de unidades didácticas competenciais e inclusivas.

    Elabora uns apuntes didácticos completos para a unidade titulada [NOME DA UNIDADE], pensados para seren empregados tanto en clase presencial como nunha aula virtual. O contido debe estar adaptado á idade do alumnado, redactado en galego normativo, cunha linguaxe clara, didáctica e accesible. A unidade debe incluír os seguintes apartados:

    1. Introdución motivadora
        - Presenta a unidade cun exemplo real, situación cotiá, pregunta guía ou metáfora que conecte cos intereses do alumnado.
        - Indica brevemente para que serve o que se vai aprender.
    
    2. Obxectivos de aprendizaxe
        - Formula os obxectivos de maneira clara, comprensible e orientada á acción do alumnado.
    
    3. Desenvolvemento dos contidos
        - Explica os contidos da unidade de forma estruturada en apartados ou subapartados.
        - Inclúe exemplos prácticos, casos sinxelos ou explicacións paso a paso.
        - Emprega un ton didáctico, como se fosen apuntes explicados polo docente.
    
    4. Esquema ou cadro resumo
        - Resume visualmente os conceptos clave da unidade (listas, táboa ou esquema xerárquico).
    
    5. Relación co currículo
        - Indica a relación da unidade cos criterios de avaliación oficiais correspondentes á materia e nivel.
        - (Se é posible) menciona as competencias clave ou específicas implicadas.
    
    6. Actividades de comprobación
        -   Propoñer dúas actividades breves e variadas para verificar a comprensión inicial dos contidos (preguntas curtas, pequeno exercicio, reflexión guiada…).
    
    7. Tarefa final de aplicación
        - Deseña unha tarefa final competencial na que o alumnado aplique o aprendido nun contexto práctico, realista ou creativo.
        - Indica que se avalía coa tarefa e que produto final se espera.

    8. Atención á diversidade
        - Inclúe propostas sinxelas de adaptación da unidade para diferentes ritmos de aprendizaxe ou necesidades educativas (simplificación, ampliación, apoio visual…).

    9. Resumo final tipo “chuleta”
        - Pecha a unidade cun resumo moi sintético das ideas esenciais que o alumnado debería lembrar.

    [INDICA SE DESEXAS LIMITAR A EXTENSIÓN TOTAL DA UNIDADE (POR EX: 1 PÁXINA, 1200 PALABRAS, ETC.)]

    [INDICA O FORMATO DE SADA PREFERIDO:  
    - TEXTO CORRIDO PARA APUNTES  
    - ESTRUTURA CON TÍTULOS E SUBTÍTULOS  
    - DOCUMENTO PREPARADO PARA AULA VIRTUAL 
    - FORMATO MIXTO (EXPLICACIÓN + ACTIVIDADES DESTACADAS)]

    [PODES ACHEGAR CRITERIOS DE AVALIACIÓN CONCRETOS, FRAGMENTOS DO CURRÍCULO OU CARACTERÍSTICAS DO GRUPO AULA PARA UNHA MAIOR ADAPTACIÓN.]

    ```

---

## BLOQUE B - Prompts para creación de actividades e tarefas
*Modelos de prompts para deseñar actividades, exercicios e tarefas competenciais, pensados para apoiar o traballo docente sen substituír o papel activo do alumnado.*

!!! note "Prompt 3. Actividade competencial contextualizada"

    *Este prompt permite crear actividades significativas que conectan os contidos coa vida do alumnado. Son útiles para substituír exercicios memorísticos por tarefas prácticas con sentido real e avaliación competencial.*

    ``` prompt 

    Actúa como un docente especialista en <MATERIA> no nivel de <NIVEL EDUCATIVO>, cun coñecemento actualizado da LOMLOE e da normativa curricular vixente en Galicia.

    Deseña unha actividade competencial contextualizada sobre o tema <TEMA OU CONTIDO>, dirixida ao alumnado dese nivel, e adaptada á súa idade e realidade.

    A actividade debe incluír os seguintes elementos:
    1. Situación ou contexto realista
        -Formula un enunciado motivador que presente un problema, reto ou situación significativa e próxima ao alumnado (vida cotiá, contorno social, interese cultural, medio ambiente, tecnoloxía...).

    2. Obxectivos de aprendizaxe
        -Define con claridade que aprendizaxes se buscan desenvolver, en termos comprensibles para o docente.

    3. Instrucións para o alumnado
        -Redacta as indicacións paso a paso, indicando que deben facer, que produto final se agarda e que ferramentas ou recursos poden empregar.

    4.Produto final esperado
        - Describe o resultado que debe elaborar o alumnado (presentación, texto, cartel, mapa, vídeo, maqueta, informe, proposta, etc.).
        - Indica se é individual, en parellas ou en grupo.
    
    5. Criterios de avaliación asociados
        - Establece criterios claros, aliñados co currículo oficial, que permitan avaliar o grao de logro da tarefa.
        - Se é posible, indica as competencias clave implicadas.
    
    6. Variantes de dificultade
        - Proporciona opcións para adaptar a actividade:
            - Variante de reforzo (máis guiada ou simplificada)
            - Variante de ampliación (maior complexidade, reto creativo ou investigación)
    
    7. Consello de deseño
        A actividade non debe ser resoluble automaticamente cunha ferramenta de IA. Debe esixir comprensión, reflexión, toma de decisións, creatividade ou análise por parte do alumnado.

    [SE O DESEXAS, INDICA SE A ACTIVIDADE VAI DIRIXIDA A UN CONTEXTO CONCRETO (POR EXEMPLO: CENTRO RURAL, GRUPO CON NEAE, AULA BILINGÜE...).]

    [PODES INDICAR UN FORMATO DE SAÍDA PREFERIDO (FOLLA DE AULA, PROPOSTA EN FORMATO TEXTO, TÁBOA EDITABLE, ETC.).]

    [TAMÉN PODES INCLUÍR OS CRITERIOS DE AVALIACIÓN CONCRETOS DO CURRÍCULO OU CARACTERÍSTICAS DO TEU ALUMNADO PARA AFINAR A RESPOSTA.]

    ```


!!! note "Prompt 4. Tarefa tipo ABP ou proxecto curto"

    *Este prompt permite deseñar proxectos curtos ou tarefas baseadas en retos, ideais para aplicar metodoloxías activas como o ABP, e fomentar aprendizaxes reais, prácticas e colaborativas. A estrutura permite adaptalos a distintas materias, niveis e duracións.*

    ``` prompt
    Actúa como un deseñador de proxectos educativos con experiencia en metodoloxías activas, especialmente en Aprendizaxe Baseada en Proxectos (ABP). Estás especializado en <ETAPA EDUCATIVA> e coñeces a LOMLOE e a normativa curricular vixente en Galicia.

    Propón un proxecto curto ou tarefa tipo ABP baseada nun reto ou pregunta guía sobre <TEMA OU PROBLEMA>, pensado para desenvolverse en varias sesións e fomentar unha aprendizaxe significativa, activa e colaborativa. A proposta debe incluír os seguintes elementos:

    1. Contexto do reto
        - Formula un escenario realista ou verosímil que contextualice o proxecto e conecte cos intereses ou contorna do alumnado.
        - Pode basearse nun problema local, situación social, reto científico, desafío tecnolóxico, etc.

    2. Pregunta guía ou reto central
        - Formula unha pregunta aberta que sirva de motor da investigación ou acción do alumnado.
        - Debe fomentar a curiosidade, o pensamento crítico e a creatividade.

    3. Fases do proxecto
        - Describe as principais fases ou pasos do proxecto (inicio, exploración, desenvolvemento, presentación...).
        - Indica actividades ou tarefas clave en cada fase.

    4. Roles do alumnado
        - Define como se organiza o alumnado (traballo individual, parellas, grupos).
        - Podes propoñer roles específicos (coordinador/a, investigador/a, creativo/a, relator/a...) para promover a colaboración.

    5. Produtos intermedios e produto final
        - Especifica os produtos que deben xerar durante o proceso e cal será o produto final do proxecto (infografía, presentación, maqueta, vídeo, proposta de mellora, etc.).

    6. Uso da intelixencia artificial (IA)
        - Indica en que fases pode empregarse a IA (permitido), en cales se debería limitar (axuda parcial), e en cales debe evitarse (traballo propio imprescindible).
        - Asegura un uso responsable, creativo e ético da IA.

    7. Evidencias avaliables centradas no proceso
        - Indica que aspectos se poden avaliar durante o desenvolvemento do proxecto (participación, investigación, reflexión, presentación oral, uso de fontes, etc.).
        - Podes engadir criterios de avaliación reais se o desexas.

    8. [ALIÑAMENTO CURRICULAR]
        - [SE O PRECISAS, ENGADE OS CRITERIOS DE AVALIACIÓN E COMPETENCIAS CLAVE ASOCIADOS SEGUNDO O CURRÍCULO DA MATERIA E NIVEL.]

    9. [ADAPTACIÓNS]
        - [PODES INDICAR VARIANTES PARA ATENCIÓN Á DIVERSIDADE (TEMPO EXTRA, APOIO VISUAL, AGRUPAMENTOS FLEXIBLES, ETC.).]
        - [INDICA SE SE PODE FACER INTERDISCIPLINAR, INTEGRANDO MÁIS DUNHA MATERIA.]

    [PODES LIMITAR A DURACIÓN ESTIMADA DO PROXECTO (POR EXEMPLO: 4 SESIÓNS DE 50 MIN).]

    [INDICA O FORMATO DE SAÍDA PREFERIDO:  
        - DOCUMENTO ESTRUTURADO
        - TÁBOA PASO A PASO
        - TEXTO CON EPÍGRAFES POR FASES]
        
    ``` 

!!! note "Prompt 5. Xeración de exercicios graduados"

    *Este prompt permite crear series de exercicios adaptados a distintos niveis de competencia, útiles para reforzo, avaliación, atención á diversidade e práctica autónoma. A estrutura permite diferenciar entre alumnado que precisa consolidar, aplicar ou ampliar contidos.*

    ``` prompt
    Actúa como docente de <MATERIA> no nivel educativo de <NIVEL>, cun enfoque pedagóxico adaptado á diversidade do alumnado e ao currículo da LOMLOE.

    Xera unha serie de exercicios graduados sobre o contido <CONTIDO OU TEMA>, organizados en tres niveis de dificultade:
        1. Nivel básico: exercicios accesibles para todo o alumnado, centrados na comprensión elemental ou aplicación directa dos contidos.
        
        2. Nivel intermedio: exercicios que requiran aplicar o aprendido en novas situacións ou combinar conceptos.
        
        3. Nivel avanzado: exercicios máis complexos que impliquen reflexión, resolución de problemas, análise ou xeneralización.

    Para cada nivel, inclúe:
        - Unha serie de exercicios variados (mínimo 3 por nivel).
        - Instrucións claras e contextualizadas para o alumnado.
        - Pistas ou exemplos parciais (sen incluír a solución completa).
        - Criterios de corrección orientativos ou criterios clave a ter en conta na avaliación das respostas.

    Requisitos:
        - Non inclúas a resolución completa dos exercicios, só pistas ou modelos parciais cando sexa necesario.
        - Os exercicios deben evitar o copia-pega desde ferramentas de IA: deben requirir pensamento propio, análise ou expresión.

    [INDICA SE PREFIRES UNHA VERSIÓN IMPRIMIBLE OU DIXITAL (FORMATO PDF, EDITABLE, GOOGLE DOCS...)]

    [PODES SOLICITAR QUE SÓ SE INCLÚAN EXEMPLOS RESOLTOS NO NIVEL BÁSICO.]

    [PODES ESPECIFICAR O TIPO DE EXERCICIO DESEXADO (ESCOITA, REDACCIÓN, CÁLCULO, ANÁLISE DE TEXTO, ETC.)]

    [SE O DESEXAS, ACHEGA OS CRITERIOS DE AVALIACIÓN OFICIAIS OU ASPECTOS CLAVE DO CURRÍCULO PARA MAIOR PRECISIÓN.]

    ``` 
---

## BLOQUE C - Adaptación de materiais e atención á diversidade (NEAE)

!!! note "Prompt 6. Adaptación de material a distintos niveis"

    *Este prompt permite modificar un mesmo contido didáctico para facelo accesible a alumnado con distintos niveis de competencia, sen perder os obxectivos comúns. É especialmente útil para reforzo, ampliación e atención á diversidade en aulas heteroxéneas.*

    ``` prompt

    Actúa como docente especializado en <MATERIA> no nivel educativo de <NIVEL>, cun enfoque inclusivo e competencial segundo a LOMLOE.

    Adapta o seguinte material didáctico para tres niveis de dificultade:
        - Versión simplificada (para alumnado con dificultades de comprensión ou ritmos máis lentos).
        - Versión estándar (para a maioría do alumnado).
        - Versión avanzada (para alumnado que precisa reto ou ampliación).

    Mantén en todas as versións os mesmos obxectivos de aprendizaxe, pero adapta a linguaxe, a extensión, a estrutura ou o nivel de apoio segundo o caso.

    Material a adaptar:
        - [PEGA AQUÍ O TEXTO, EXERCICIO OU MATERIAL DIDÁCTICO]

    Inclúe os seguintes elementos na resposta:
    1. As tres versións do material adaptado, identificadas claramente.

    2. Diferenzas principais entre versións, explicadas nun pequeno cadro comparativo (linguaxe, apoio visual, número de tarefas, autonomía requirida...).

    3. Indicación do tipo de alumnado ao que vai dirixida cada versión.

    4. [LIMITA A EXTENSIÓN DO MATERIAL ADAPTADO (EXEMPLO: MÁXIMO 150 PALABRAS POR VERSIÓN OU 1 PÁXINA NO TOTAL).]

    5. [SE PROCEDE, ADAPTA TAMÉN AS INSTRUCIÓNS, OS EXEMPLOS OU O SOPORTE (GRÁFICO, TEXTUAL, AUDIOVISUAL...).]

    Asegúrate de que as adaptacións sexan razoables, realistas e aplicables nunha aula ordinaria, sen recorrer a recursos extraordinarios.

    ```


!!! note "Prompt 7. Adaptación de actividades para alumnado con NEAE"

    *Este prompt permite xerar adaptacións metodolóxicas e de acceso para que todo o alumnado poida participar nunha actividade sen modificar os obxectivos curriculares. Resulta útil para deseñar actividades inclusivas en aulas con diversidade, sempre contrastando co equipo de orientación.*

    ``` prompt

    Actúa como especialista en atención á diversidade e adaptacións educativas. A túa función é axudar a docentes a axustar actividades mantendo os obxectivos de aprendizaxe e promovendo unha aula inclusiva.

    Propón adaptacións razoables e aplicables nunha aula ordinaria para a seguinte actividade:
    <DESCRICIÓN DA ACTIVIDADE>, pensando en alumnado con <NEAE OU PERFIL XERAL>
    (exemplos: dificultades específicas de aprendizaxe, TDAH, TEA, dislexia, dificultades cognitivas leves...).

    As adaptacións deben permitir que o alumnado participe da actividade sen modificar os obxectivos curriculares nin substituír a intervención profesional docente.

    Inclúe os seguintes elementos:
    1. Tipo de adaptacións propostas
        - Diferencia entre:
            - Adaptacións metodolóxicas (forma de explicar, estruturación, agrupamentos, instrucións guiadas...).
            - Adaptacións de acceso (formato, presentación, recursos de apoio, tempo adicional...).

    2. Axustes no formato da tarefa
        - Exemplo: lectura en voz alta, uso de pictogramas, versión simplificada do texto, presentación en PowerPoint, etc.

    3. Axustes na carga cognitiva
        - Exemplo: reducir o número de pasos, dividir a tarefa en fases, anticipar a estrutura, apoiar con esquemas visuais.

    4. Axustes no tempo e apoio
        -Exemplo: tempo adicional, pausa entre fases, apoio de compañeiro/a, uso de materiais manipulativos.

    5. Contexto realista de aula ordinaria
        - Propón só medidas viables sen depender de recursos extraordinarios.
        - Non inclúas modificacións curriculares significativas nin cambios que requiran un PI específico.

    [INDICA SE HAI RECURSOS DISPOÑIBLES NO CENTRO (PT, AL, MATERIAIS ADAPTADOS, TECNOLOXÍA ESPECÍFICA...).]

    [PODES SOLICITAR QUE AS ADAPTACIÓNS SE CENTREN NUN ASPECTO CONCRETO: COMPRENSIÓN LECTORA, EXPRESIÓN ESCRITA, ATENCIÓN, ETC.]

    [OPCIONAL: INDICA SE A ACTIVIDADE REQUIRE UN TRABALLO INDIVIDUAL OU EN GRUPO.]

    ```

---


## BLOQUE D – Prompts para deseño de rúbricas e avaliación formativa.
*Modelos de prompts para apoiar ao profesorado no deseño de instrumentos de avaliación coherentes**.*

!!! note "Prompt 8. Rúbrica competencial centrada no proceso"

    *Este prompt permite xerar rúbricas completas que avalíen tanto o camiño percorrido polo alumnado como o resultado final. Son especialmente útiles en tarefas competenciais, proxectos ABP, retos ou situacións de aprendizaxe, incluíndo o uso responsable da IA.*

    ``` prompt
    Actúa como experto en avaliación competencial segundo a LOMLOE e a normativa galega. Deseña unha rúbrica de avaliación para a seguinte tarefa ou proxecto:

        - Tarefa ou proxecto: <DESCRICIÓN DA TAREFA OU SITUACIÓN DE APRENDIZAXE>
        - Materia: <MATERIA>
        - Nivel educativo: <NIVEL EDUCATIVO>

    A rúbrica debe servir para avaliar tanto:
        - O proceso de traballo do alumnado (planificación, toma de decisións, autonomía, revisión e mellora, uso do tempo…).
        - O produto final (calidade, adecuación, presentación, creatividade…).

    Inclúe os seguintes elementos:
    1. Criterios de avaliación, tanto de proceso como de produto, aliñados co currículo oficial da materia e nivel.

    2. Descritores claros e observables, para cada criterio, formulados en 4 niveis de logro progresivos, evitando termos ambiguos como “axeitado” ou “correcto”.

    3. Indicadores específicos de evidencias que o docente debe observar en cada nivel.

    4. Distinción entre traballo individual e traballo en grupo, se a tarefa o require.

    5. Criterio específico sobre uso responsable da IA, se procede: Valorando aspectos como uso ético, citación das fontes, integración crítica da información xerada por IA.

    6. Formato de saída en táboa, clara e reutilizable.

    [PODES PEDIR QUE SE REDUZA O NÚMERO DE CRITERIOS SE A TAREFA É SINXELA.]

    [SE O NIVEL EDUCATIVO O REQUIRE, ADAPTA O NÚMERO DE NIVEIS (POR EXEMPLO: 3 NIVEIS PARA 1º CICLO DE PRIMARIA).]

    [PODES INDICAR SE QUERES QUE A RÚBRICA INCLÚA COMENTARIOS EXEMPLARES OU EXEMPLOS REAIS DE PRODUCIÓNS DO ALUMNADO.]

    [SE PRECISAS ADAPTAR PARA AULA VIRTUAL, SOLICITA VERSIÓN EDITABLE EN GOOGLE DOCS, MOODLE OU PDF.]

    ```




!!! note "Prompt 9. Instrumento de avaliación formativa con feedback"

    *Este prompt permite xerar ferramentas de avaliación orientadas ao proceso, sen cualificacións numéricas. Son útiles para revisións intermedias, autoavaliacións, coavaliacións ou acompañamento docente en tarefas complexas.*

    ``` prompt

    Actúa como docente con experiencia en avaliación formativa e retroalimentación cualitativa, aliñado coa LOMLOE. Deseña un instrumento de avaliación formativa para a seguinte actividade: <DESCRICIÓN DA ACTIVIDADE OU TAREFA>.

    O instrumento debe permitir facer seguimento do proceso de aprendizaxe, favorecer a autorreflexión e orientar a mellora. Debe estar pensado para ser usado por <DOCENTE / ALUMNADO / AMBOS>.

    Inclúe os seguintes elementos:
    1. Preguntas de reflexión sobre o proceso
        - Formula de 3 a 5 preguntas abertas que axuden ao alumnado a analizar o seu propio proceso: dificultades, estratexias empregadas, cambios feitos, aprendizaxes identificadas...

    2. Indicadores de progreso claros e comprensibles
        - Lista de aspectos clave a observar na tarefa ou proceso (ex: planificación, comprensión, creatividade, uso de fontes…).        
        - Indicadores redactados en primeira persoa cando sexa para auto/coavaliación.

    3. Espazo para feedback cualitativo
        - Zona onde o docente, un compañeiro ou o propio alumno/a poida facer observacións construtivas sobre puntos fortes e aspectos a mellorar.

    4. Propostas de mellora
        - Recomendacións específicas para avanzar no seguinte paso do proceso:
            - Que pode facer mellor.
            - Que pode intentar distinto.
            - En que debe seguir traballando.

    5. Formato de saída en táboa ou folla editable, segundo o uso previsto.

    Requisitos:
        - Non debe incluír cualificación numérica nin porcentaxes.
        - A linguaxe debe estar adaptada á etapa educativa correspondente.
        - O foco debe estar na mellora continua, non no control.

    [PODES SOLICITAR VERSIÓN ADAPTADA A ETAPAS INICIAIS CON LINGUAXE SIMPLIFICADA.]

    [INDICA SE A FERRAMENTA VAI EMPREGARSE UNHA SOA VEZ (P. EX., REVISIÓN DUN BORRADOR) OU VARIAS VECES AO LONGO DUNHA UNIDADE.]

    [PIDE EXEMPLOS DE RESPOSTAS POSIBLES OU BOAS PRÁCTICAS DE FEEDBACK.]

    ```


!!! note "Prompt 10. Guía de defensa oral ou reflexión final"

    *Este prompt permite xerar un conxunto de preguntas abertas para que o alumnado reflexione sobre o seu proceso de aprendizaxe. Resulta útil en presentacións, proxectos, tarefas finais ou calquera situación onde se avalíe tanto a autoría como a comprensión e a transferencia.*

    ``` prompt

    Actúa como docente avaliador cun enfoque formativo e competencial. Elabora unha guía de preguntas para unha defensa oral ou reflexión final sobre a seguinte tarefa ou proxecto:

        - Tarefa ou proxecto: <DESCRICIÓN DA TAREFA OU SITUACIÓN DE APRENDIZAXE>
        - Materia: <MATERIA>
        - Nivel educativo: <NIVEL EDUCATIVO>
        - Tipo de defensa: <INDIVIDUAL / GRUPAL>

    O obxectivo é comprobar a comprensión profunda do traballo realizado, a toma de decisións, o grao de implicación e a transferencia do aprendido a outros contextos. A guía debe permitir unha avaliación formativa e unha posible verificación da autoría do traballo.

    Inclúe:
    1. Preguntas abertas e progresivas, organizadas por bloques:
        - Comprensión dos contidos traballados.
        - Xustificación das decisións tomadas durante o proceso.
        - Reflexión sobre as dificultades atopadas e como foron superadas.
        - Aplicación do aprendido a novos contextos ou situacións reais.
        - Uso da IA no proceso: se foi empregada, como, con que criterio, e que parte do traballo é persoal.

    2. Linguaxe adaptada ao nivel educativo, clara e accesible.

    3. [INDICA O NÚMERO MÁXIMO DE PREGUNTAS, SEGUNDO O TEMPO DISPOÑIBLE (EX: 5 PREGUNTAS PARA 10 MINUTOS).]

    4. [SE A DEFENSA É GRUPAL, INCLÚE PREGUNTAS PARA REPARTIR ROLES OU ASEGURAR A PARTICIPACIÓN DE TODAS AS PERSOAS.]

    5. [PODES PEDIR QUE SE ENGADAN RÚBRICAS OU CRITERIOS DE AVALIACIÓN DA PRESENTACIÓN ORAL.]


    A guía debe evitar preguntas pechadas ou memorísticas, e centrarse en evidencias de reflexión, comprensión, análise e toma de decisións.

    ```

---

## BLOQUE E - Prompts para coordinación e traballo en equipo

!!! note "Prompt 11. Apoio á coordinación de departamento ou ciclo"

    *Este prompt permite xerar propostas iniciais para organizar o traballo dun equipo docente. É útil en reunións de coordinación, revisión de programacións ou deseño de liñas comúns, sempre deixando espazo para o acordo colectivo.*

    ``` prompt

    Actúa como asistente de coordinación pedagóxica, cun coñecemento actualizado da LOMLOE e da normativa galega. Axuda a organizar e estruturar o traballo dun departamento ou equipo docente de <MATERIA OU ETAPA EDUCATIVA>, tendo en conta o seguinte contexto:

        - Número de docentes implicados: <INDICA CANTIDADE OU PERFÍS>
        - Tipo de centro e situación: <PÚBLICO / CONCERTADO / CONTORNO RURAL / URBANO / OUTRO>

    Elabora unha proposta inicial que sirva de base para o debate e a toma de decisións compartida durante unha reunión de coordinación. A proposta debe incluír:

    1. Obxectivos comúns para o curso
        - Propón de 3 a 5 obxectivos xerais (didácticos, organizativos ou metodolóxicos), adaptados á realidade do equipo.

    2. Criterios compartidos de metodoloxía e avaliación
        - Liñas comúns sobre metodoloxías activas, inclusión, uso de rúbricas, avaliación formativa...
        - Indica espazos abertos a decisións colectivas (non peches o acordo).

    3. Propostas para o uso coherente da intelixencia artificial
        - Posibles acordos sobre cando é adecuado o uso de IA, tanto por parte do profesorado como do alumnado.
        - Suxestións de ferramentas útiles para programación, avaliación ou creación de recursos.

    4. Ideas de tarefas, proxectos ou situacións de aprendizaxe comúns
        - Exemplos de actividades ou unidades que poderían ser compartidas por varios docentes ou niveis.

    5. Formato claro e visual
        - Presenta a proposta en formato esquemático ou táboa, lista para ser revisada e completada nunha reunión.

    Requisitos:
    - A proposta debe ser flexible, sen pechar decisións, para permitir o debate e a adaptación.
    - Emprega unha linguaxe profesional, clara e neutra.
    - Evita dar por supostas medidas que deben ser consensuadas.

    [PODES SOLICITAR QUE A PROPOSTA ESTEA ESTRUTURADA EN TORNO AO CALENDARIO ESCOLAR (1º TRIMESTRE, 2º, 3º).]

    [PODES PEDIR QUE SE INCLÚAN SUXESTIÓNS PARA A COORDINACIÓN INTERETAPAS OU INTERDISCIPLINAR.]

    [SE O EQUIPO É NOVO OU POUCO COHESIONADO, SOLICITA QUE SE ENGADAN RECOMENDACIÓNS PARA ESTABLECER ACORDOS MÍNIMOS.]

    ```

!!! note "Prompt 12. Preparación de reunións e actas"

    *Este prompt permite elaborar documentos formais de coordinación docente, tanto antes dunha reunión (orde do día) como despois (resumo ou acta). É útil para traballo de equipo, seguimento de acordos e documentación oficial.*

    ``` prompt

    Actúa como apoio á organización interna dun centro educativo. A partir da seguinte información ou puntos tratados, axuda a elaborar un documento oficial de reunión, segundo o seu momento e finalidade:
        - Información achegada: <PEGA AQUÍ AS NOTAS, TEMAS OU ACORDOS>
        - Tipo de documento: <ORDE DO DÍA / RESUMO DE ACORDOS / ACTA DE REUNIÓN>
        - Tipo de reunión: <EQUIPO DOCENTE / DEPARTAMENTO / CICLO / TITORÍA / OUTRO>
        - Nivel educativo ou etapa:<PRIMARIA / ESO / BACHARELATO / FP / OUTRO>
        - Versión: <BORRADOR / VERSIÓN FINAL>

    Elabora o documento solicitado co seguinte enfoque:

    1. Se é unha orde do día (antes da reunión):
        - Presenta unha estrutura clara e numerada, cos temas a tratar e, se procede, o tempo estimado para cada punto.
        - Engade un espazo para “roldas abertas” ou “preguntas e propostas” ao final.

    2. Se é un resumo de acordos ou acta posterior:
        - Resume os puntos tratados con claridade e obxectividade.
        - Enumera os acordos adoptados, as tarefas asignadas e as persoas responsables.
        - Se procede, indica o prazo previsto para cada tarefa.
        - Usa unha linguaxe formal, precisa e coherente coa documentación oficial do centro.

    [INDICA SE QUERES QUE O DOCUMENTO SEXA EDITABLE EN FORMATO .DOCX, .ODT OU COMPATIBLE CON GOOGLE DOCS.]

    [PODES PEDIR QUE O ESTILO SEXA MÁIS ESQUEMÁTICO (VIÑETAS) OU MÁIS TEXTUAL E NARRATIVO.]

    [OPCIONAL: ENGADE UN ESPAZO FINAL PARA SINATURAS OU VALIDACIÓN DA XEFATURA DE DEPARTAMENTO/EQUIPO.]

    ```

!!! note "Prompt 13. Apoio á elaboración de documentos de centro"

    *Este prompt permite xerar borradores estruturados e profesionais de documentos oficiais dun centro educativo (proxecto educativo, políticas de IA, plans, memorias...). O modelo xerado serve como base para revisión, debate e adaptación por parte dos equipos directivos e órganos colexiados.*

    ``` prompt
    Actúa como apoio á redacción institucional dun centro educativo público. Elabora un borrador inicial e estruturado do seguinte documento oficial:

        - Tipo de documento: <INDICA O DOCUMENTO: Proxecto Educativo, Plan de Convivencia, Política de uso da IA, Memoria Anual, etc.>
        - Etapa/nivel: <INFANTIL / PRIMARIA / ESO / BACHARELATO / FP / CENTRO INTEGRADO>
        - Nivel de detalle desexado:<ESQUEMA XERAL / REDACCIÓN COMPLETA / VERSIÓN SINTÉTICA PARA DEBATE>

    O borrador debe:
    1. Estar aliñado con marco legal e normativo vixente, tanto estatal (LOMLOE) como autonómico (normativa galega específica).

    2. Empregar unha linguaxe institucional, clara, neutra e profesional.

    3. Presentar unha estrutura lóxica e coherente, con epígrafes e subapartados numerados.

    4. Ser apto para revisión e adaptación posterior polo equipo directivo, claustro ou consello escolar.

    5. Non incluír datos identificativos do centro, nin referencias a persoas concretas ou localizacións específicas.

    [PODES INDICAR APARTADOS OBRIGATORIOS SEGUNDO NORMATIVA ESPECÍFICA (POR EXEMPLO: OBXECTIVOS XERAIS, PRINCIPIOS PEDAGÓXICOS, MEDIDAS DE INCLUSIÓN, ATENCIÓN Á DIVERSIDADE, USO DA IA, COORDINACIÓN ENTRE ETAPAS...).]

    [INDICA SE O DOCUMENTO ESTÁ PENSADO PARA O CURSO ACTUAL OU COMO MARCO PLURIANUAL.]

    [PODES SOLICITAR QUE SE ENGADAN EXEMPLOS OU FÓRMULAS TIPO ADAPTABLES (EX: “O CENTRO PROMOVERÁ…” “A COORDINACIÓN HORIZONTAL REALIZARASE MEDIANTE…”).]

    [SE É UNHA REVISIÓN DUN DOCUMENTO XA EXISTENTE, PODES PEGAR FRAGMENTOS CONCRETOS PARA REFORMULAR OU ACTUALIZAR.]

    ```