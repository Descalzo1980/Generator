# Generator

fun main(){
val wordArray1 = arrayOf("В первую очередь", "С другой стороны,", "Таким образом", "Мы уверены, что", "Наш опыт показывает,")
val wordArray2 = arrayOf("выполнение поставленных KPI", "архитектура сервиса", "новая бизнес-модель", "дальнейшее масштабирование","сбор юзер кейсов")
val wordArray3 = arrayOf("играет важную роль в формировании", "требует от нас анализа", "требует пересмотра", "способствует подготовке и реализации", "обеспечивает ключевым сотрудникам участие в формировании")
val wordArray4 = arrayOf("маркетинговой стратегии.", "ключевых метрик.", "продуктовой стратегии.", "нового видения.", "нового подхода в реализации фич.")
val arraySize1 = wordArray1.size
val arraySize2 = wordArray2.size
val arraySize3 = wordArray3.size
val arraySize4 = wordArray4.size

val rand1 = (Math.random() * arraySize1).toInt()
val rand2 = (Math.random() * arraySize2).toInt()
val rand3 = (Math.random() * arraySize3).toInt()
val rand4 = (Math.random() * arraySize4).toInt()
val phrase = "${wordArray1[rand1]} ${wordArray2[rand2]} ${wordArray3[rand3]} ${wordArray4[rand4]}"
    println(phrase)
}
