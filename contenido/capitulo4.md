# Capítulo 4. Prompting para docentes

## Que é o prompting?
O prompting é a arte e a técnica de dar instrucións claras, concretas e ben estruturadas a un modelo de intelixencia artificial co obxectivo de obter as respostas máis útiles, fiables e adaptadas posibles. Un prompt é o texto que lle escribimos á IA para que realice unha tarefa, sexa xerar un resumo, crear un exame, elaborar un esquema, explicar un concepto ou mesmo propoñer unha actividade didáctica. Igual que nunha aula unha boa pregunta provoca mellores respostas do alumnado, cunha IA ocorre exactamente o mesmo: canto máis clara e detallada sexa a instrución, máis axeitada e práctica será a resposta.

!!! note ""
    A práctica do prompting require de reflexión e de aprendizaxe progresiva: non é só “preguntar”, senón saber como preguntar para acadar o que necesitamos, aforrando tempo e reducindo frustración. É un proceso iterativo, no que melloramos co uso e que nos permite adaptarnos a diferentes contextos educativos.

**Por que é importante o prompting**
A mesma IA pode dar resultados moi distintos segundo como se formule a petición: dende respostas vagas e superficiais ata explicacións detalladas e adaptadas ao nivel.

- Un bo prompting aforra tempo, reduce o número de intentos fallidos e proporciona materiais máis directamente aproveitables na aula.
- Permite que as respostas se adapten con precisión ao nivel do alumnado, á materia e ao obxectivo didáctico.
- É a base imprescindible para crear GPT personalizados, que funcionan mellor canto máis refinada sexa a redacción das instrucións inciais.
- Facilita que o profesorado manteña o control sobre o que xera a IA, evitando desviacións, erros ou materiais pouco pedagóxicos.
- Axuda a desenvolver no docente unha nova competencia dixital clave: a de comunicarse eficazmente cunha IA.

---

## Estratexias básicas de prompting
1. **Especificar o rol**
    Definir quen debe ser a IA (profesor de Matemáticas, avaliador de redaccións, creador de exames, experto en conceptos concretos, guía para un proxecto interdisciplinar…).
2. **Detallar a tarefa**
    Explicar con claridade que se quere: número de exercicios, extensión dun texto, formato de avaliación, nivel de profundidade, etc.
3. **Definir o formato**
    Indicar como se debe presentar o resultado (lista numerada, táboa comparativa, rúbrica detallada, código comentado paso a paso, esquema visual en texto).
4. **Engadir contexto**
    Precisar o nivel educativo, a materia, os obxectivos de aprendizaxe e se é preciso, adaptacións a alumnado con necesidades específicas.
5. **Poñer exemplos**
    Si se quere un estilo concreto, unha mostra ou exemplos guía no propio prompt axuda á IA a imitalo mellor.
6. **Indicar restricións**
    Si se quere un texto breve, sen tecnicismos ou con vocabulario adaptado, convén deixarllo claro.
7. **Iterar**
    Non quedarse coa primeira resposta. Revisar, mellorar e volver formular ata obter o resultado máis útil.

!!! tip ""
    Non é obrigatorio incluír sempre todos os elementos, pero canto máis claro sexa o contexto, mellor será a resposta.

---

## Exemplos prácticos de prompts sinxelos
**Primaria – Lingua**
```
Rol:
Actúa como docente de Lingua en Educación Primaria.

Tarefa:
Explícalle a un neno/a de 9 anos que é un adxectivo.

Contexto:
4º de Primaria. Nivel inicial. O obxectivo é comprender a idea e aplicala en frases sinxelas.

Formato:
1) Definición en 2–3 frases.
2) 3 exemplos sinxelos (adxectivo + nome) e por que son adxectivos.
3) Mini-exercicio: 5 frases para completar cun adxectivo (deixa un oco).
4) Corrección breve para o profesorado: proposta de respostas e criterio de corrección (acepta sinónimos).

Restricións:
Linguaxe moi sinxela. Evita tecnicismos. Non uses exemplos con contido sensible.

```

**ESO – Historia**
```
Rol:
Actúa como profesor/a de Historia en ESO.

Tarefa:
Crea un resumo sobre a Revolución Francesa.

Contexto:
3º ESO. O alumnado precisa unha visión xeral (causas, fases, consecuencias) e vocabulario básico.

Formato:
1) Resumo de media páxina (aprox. 150–200 palabras).
2) Mapa conceptual en formato texto (con frechas ou sangrías).
3) 3 preguntas tipo test (A/B/C/D) con resposta correcta marcada.
4) Actividade final de reflexión curta (1–2 preguntas abertas) para conectar co presente.

Restricións:
Evita exceso de datas e nomes secundarios. Prioriza conceptos clave. Ton neutro e rigoroso.

```

**Bacharelato – Filosofía**
```
Rol:
Actúa como docente de Filosofía en Bacharelato.

Tarefa:
Explica o pensamento de Kant de forma clara.

Contexto:
2º de Bacharelato. O obxectivo é comprender ideas centrais (deber, imperativo categórico, autonomía) para aplicalas en comentarios e preguntas.

Formato:
1) Explicación en ~200 palabras.
2) 2 preguntas abertas para avaliar comprensión (non memorísticas).
3) 1 cita curta e relevante de Kant (indicando obra se é posible).
4) Comparación moi breve (3–4 liñas) cun outro filósofo (p.ex. Aristóteles, Hume ou Mill), sinalando unha diferenza clave.

Restricións:
Linguaxe clara, sen tecnicismos excesivos. Se introduces un termo, explícalo en 1 frase.

```

**FP – Programación**
```
Rol:
Actúa como docente de FP en Programación (Java).

Tarefa:
Ensina como facer unha conexión a MySQL desde Java usando JDBC.

Contexto:
Ciclo formativo (GM/GS). O alumnado xa viu variables, clases e métodos. Precisa un exemplo guiado e seguro.

Formato:
1) Código Java completo e comentado (inclúe importacións e exemplo de consulta simple).
2) Explicación paso a paso do que fai cada parte (en viñetas).
3) Lista de 5 erros comúns + solución (driver, URL, credenciais, excepcións, charset).
4) Exercicio práctico para o alumnado (variante do exemplo, con obxectivo claro).
5) Boas prácticas de seguridade (mínimo 4): variables de contorno, non hardcodear credenciais, prepared statements, mínimos privilexios, etc.

Restricións:
Non xeres contrasinais reais. Usa credenciais de exemplo. Prioriza prepared statements fronte a concatenación.

```

**Bacharelato – Bioloxía**
```
Rol:
Actúa como docente de Bioloxía en Bacharelato.

Tarefa:
Explica a fotosíntese de forma clara e estruturada.

Contexto:
1º de Bacharelato. O alumnado debe comprender fases e factores que inflúen.

Formato:
1) Explicación (200–250 palabras) con exemplos da vida cotiá.
2) Esquema textual (sangrías) coas etapas principais: fase luminosa e ciclo de Calvin (sen excesivo detalle).
3) 2 preguntas curtas de avaliación (unha conceptual e unha aplicada).
4) Proposta de práctica experimental sinxela para a aula: materiais, pasos e que se observa.

Restricións:
Evita simplificacións erróneas (non dicir que “as plantas comen luz”). Linguaxe científica accesible.

```

**FP – Administración e finanzas**
```
Rol:
Actúa como docente de FP de Administración e Finanzas (Contabilidade).

Tarefa:
Elabora un suposto práctico de contabilidade básica para alumnado de 1º curso.

Contexto:
Primeiras unidades de contabilidade. O obxectivo é practicar asentos e entender a súa utilidade.

Formato:
1) Enunciado do caso (contexto empresarial sinxelo).
2) Datos das operacións (4–6 movementos) con importes claros.
3) Asentos contables correspondentes (ben presentados).
4) Explicación dos pasos: que contas se usan e por que (breve).
5) 3 preguntas de reflexión sobre aplicación no mundo real (xestión, control, decisións).

Restricións:
Non uses normativa complexa nin casos avanzados. Asegura que os importes cadran e que o exercicio é autocontido.

```

---

## Erros frecuentes no prompting e como evitalos
- **Ser demasiado vago**: pedir “Explícame a Revolución Francesa” dará unha resposta xeral e pouco adaptada. Mellor engadir nivel, extensión, formato e obxectivo.
- **Non indicar o contexto educativo**: Unha mesma explicación non é igual para 6º de Primaria que para 2º de Bacharelato.

- **Esquecer o formato**: Se non se especifica, a IA pode dar unha resposta longa, desorganizada ou pouco práctica.
- **Non revisar a saída**: A IA pode cometer erros factuais ou simplificacións excesivas. O profesorado debe comprobar e corrixir antes de empregar.
- **Confiar demasiado na IA**: A IA non debe substituír o estudo nin o traballo autónomo. É un apoio, nunca o eixo central da aprendizaxe.
- **Non marcar límites claros**: Se non se indica “texto breve” ou “explicación en linguaxe sinxela”, a resposta pode ser demasiado complexa ou extensa.

---

## Boas prácticas de prompting
- Usar linguaxe clara, sen ambigüidades nin frases abertas.
- Indicar sempre o nivel do alumnado e o contexto da materia.
- Pedir exemplos, explicacións paso a paso ou esquemas cando se trate de contidos complexos.
- Mellorar o prompt en varias iteracións para afinar o resultado.
- Verificar a información e adaptala ao currículo antes de usala na aula.
- Usar a IA como apoio, non como substituto: o alumnado debe seguir desenvolvendo pensamento crítico, memoria, capacidade de síntese e esforzo autónomo.
- Crear un repositorio propio de prompts efectivos, para aforrar tempo en futuras ocasións.

---

## Promptings avanzados
Unha das limitacións máis habituais no uso da intelixencia artificial en educación é que, cando lle pedimos algo a un modelo de linguaxe, a resposta pode ser demasiado xenérica ou incluso afastada do contexto que necesitamos. Para solucionar isto, podemos empregar prompting avanzado, que consiste en achegar á IA documentos de referencia ou materiais de consulta. Deste xeito, a resposta non parte só da súa base de coñecementos, senón tamén da información que lle achegamos, adaptándose mellor ás nosas necesidades reais na aula.

O prompting avanzado con documentos é especialmente útil cando traballamos con currículos oficiais, artigos científicos, manuais de estudo ou apuntes propios. Con esta técnica, a IA convértese nun asistente que interpreta e reformula materiais xa existentes, ofrecendo versións adaptadas ao nivel do alumnado, xerando exercicios, ou resumindo contidos complexos.

**Exemplos prácticos de uso**

!!! note "Preparación de clases a partir do currículo oficial"

    ```
    Rol:
    Actúa como docente de Tecnoloxía en Bacharelato.

    Tarefa:
    Resume os puntos clave do currículo oficial e propón actividades prácticas.

    Contexto:
    Documento achegado: currículo oficial de Tecnoloxía en Galicia (Decreto 157/2022).
    Nivel: 1.º de Bacharelato.
    O obxectivo é deseñar actividades coherentes cos obxectivos e competencias oficiais.

    Formato:
    1) Resumo estruturado dos puntos clave do currículo (obxectivos, saberes básicos e criterios).
    2) Proposta de 4–5 actividades prácticas, indicando:
    - competencia traballada,
    - tipo de tarefa,
    - produto final esperado.

    Restricións:
    Emprega linguaxe clara e práctica. Non copies literalmente o texto legal; interpreta e sintetiza.
    ```

    - O docente recibe un resumo directo da normativa.    
    - Xéranse actividades contextualizadas segundo os obxectivos e competencias oficiais.
    - Aforro de tempo na lectura e interpretación de documentos legais.

!!! note "Actividade con artigos científicos para ciclos formativos"

    ```
    Rol:
    Actúa como docente dun ciclo formativo de Desenvolvemento de Aplicacións Multiplataforma (DAM).

    Tarefa:
    Analiza un artigo técnico e crea un cuestionario de avaliación.

    Contexto:
    Documento achegado: artigo científico/técnico sobre seguridade en bases de datos (PDF).
    Nivel: Ciclo Superior de DAM.
    O obxectivo é avaliar comprensión lectora e aplicación profesional.

    Formato:
    1) Breve síntese do artigo (ideas clave).
    2) Cuestionario de 10 preguntas:
    - 6 de comprensión técnica,
    - 4 de aplicación práctica.
    3) Solucións xustificadas de forma breve.

    Restricións:
    Non simplifiques en exceso os conceptos técnicos. As preguntas deben poder responderse a partir do artigo.

    ```
    
    - O alumnado recibe exercicios directamente relacionados con textos científicos ou técnicos reais.
    - Pódese avaliar comprensión lectora en contextos profesionais.
    - Axuda a preparar probas prácticas máis rigorosas e aplicables ao mundo laboral.

!!! note "Complemento de apuntes de aula con fontes abertas"

    ```
    Rol:
    Actúa como docente de Historia en Educación Secundaria.

    Tarefa:
    Elabora un resumo didáctico a partir dun manual.

    Contexto:
    Documento achegado: capítulo dun manual de historia (formato .docx).
    Nivel: 4.º da ESO.
    O obxectivo é reforzar a comprensión e facilitar o estudo.

    Formato:
    1) Resumo en formato esquema (sangrías e palabras clave).
    2) 5 preguntas tipo test con 4 opcións cada unha.
    3) Indicación da resposta correcta.

    Restricións:
    Emprega linguaxe accesible. Evita parágrafos longos e datos secundarios.

    ```

    - Conversión de materiais densos en resumos sinxelos e didácticos.
    - Creación de autoavaliacións rápidas para o alumnado.
    - Apoio para alumnado con dificultades de aprendizaxe ou necesidades de reforzo.

!!! note "Deseño de proxectos interdisciplinares"

    ```
    Rol:
    Actúa como equipo docente interdisciplinar de ESO.

    Tarefa:
    Deseña un proxecto educativo a partir dun documento real.

    Contexto:
    Documento achegado: informe ambiental local (PDF).
    Nivel: 3.º da ESO.
    Materias implicadas: Bioloxía, Xeografía e Lingua Galega.
    O obxectivo é traballar competencias mediante un proxecto contextualizado.

    Formato:
    1) Título e descrición do proxecto.
    2) Obxectivos de aprendizaxe por materia.
    3) Actividades principais (mínimo 4).
    4) Produto final e exposición oral.
    5) Proposta básica de avaliación (criterios e evidencias).

    Restricións:
    O proxecto debe ser realista en tempo e recursos. Prioriza a conexión co contexto local.

    ```

    - A IA integra información dun documento real co currículo de varias materias.
    - Favorece o deseño de proxectos competenciais.
    - Conecta a aprendizaxe co contexto local e actual.

---

## Recomendacións de uso
- **Seleccionar documentos adecuados:** Preferiblemente textos oficiais, de acceso libre, de produción propia ou artigos dispoñibles en aberto. Evitar contidos protexidos por copyright sen permiso.
- **Dividir documentos longos:** Se o texto é extenso, é mellor achegar capítulos ou fragmentos. Isto facilita respostas máis precisas.
- **Formular a tarefa de xeito claro:** Indicar sempre o nivel educativo, o tipo de produto esperado (resumo, cuestionario, proxecto, esquema, etc.) e o obxectivo da actividade.
- **Revisar a saída:** O docente debe supervisar a resposta para asegurar que respecta o sentido orixinal do documento.
- **Adaptar ao alumnado:** Usar a IA como base, pero personalizar e contextualizar o material para cada grupo ou realidade educativa.

---

!!! note "Recursos de apoio"
    - **Guía de Ingeniería de Prompt**  
        Aprender sobre como desarrollar y optimizar los prompts

        [https://www.promptingguide.ai/es](https://www.promptingguide.ai/es)

    - **GPT Prompt Engineer**  
        Un chat al que le puedes pedir que cree, mejore o corriga un prompt

        [https://chatgpt.com/g/g-5XtVuRE8Y-prompt-engineer](https://chatgpt.com/g/g-5XtVuRE8Y-prompt-engineer)


