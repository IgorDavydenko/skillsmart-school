masterDataFields - masterDataFieldList
// список корневых полей договора
mdf - masterDataField
// for (var mdf : masterDataFields) - перебор полей в цикле. Убираем сокращение, получаем понятное название переменной + переименовываем выше лист становится понятнее.
numerics - pathIdArray
// массив id из которых состоит путь к элементу. Подобие ip. Полнота описания + точность описания
ch - currentChar
// указатель на текущий символ в цикле. Полнота описания
pattern - programPathPattern
// имя шаблона регулярного выражения, для поиска и вырезания из строки json-пути
expressionOp - expressionOperator
// значение оператора в вычисляемом выражении. Добиваемся полноты описания
isCheckMissingAttribute - isAttributeFound
// boolean; проверяет наличие атрибута в договоре
regex - regexBuilder
// new StringBuilder("^"); строит регулярное выражение, используя паттер builder. Без указателя на тип может показаться что переменную можно использовать как есть. А по факту в конце надо вызвать .build(). Итого - добиваемся точности описания  
toString - resultLogMessage
// сформированное сообщение для логгера
curAttribute - currentAttribute
// указатель на текущий атрибут договора при переборе полей
result - validationErrorList
// List<ValidationError> - список ошибок валидации. Полнота описания
filteredSlaves - attributeSlaveDataFieldList
// список зависимых полей атрибута договора. Список даже никто не фильтровал!
