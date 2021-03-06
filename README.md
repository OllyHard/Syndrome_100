# JaCoCo - Coverage Counters. Счетчики покрытия.

### Instruction
Наименьшая единица отсчета JaCoCo - это инструкции одиночного байтового кода Java. Покрытие инструкций предоставляет информацию об объеме кода, который был выполнен или пропущен. Эта метрика полностью независима от исходного форматирования и всегда доступна, даже при отсутствии отладочной информации в файлах классов.

### Branch
Определяет покрытие ветвей для оперторов if и switch. Этот счетчик подсчитывает общее количество таких ветвей в методе и определяет количество выполненных или пропущенных ветвей.

### Complexity (Цикломатическая сложность)
Просчитывает различные пути, которые могут в формулах, с помощью метода. Таким образом, значение сложности может служить индикатором количества примеров модульного тестирования, которые полностью охватывают определенную часть программного обеспечения. 

### Line
Основываясь на состоянии покрытия каждой ветки, JaCoCo также вычисляет покрытую и пропущенную сложность для каждого метода. Пропущенная сложность снова указывает на то, что количество тестовых случаев отсутствует, чтобы полностью покрыть модуль.
