MessageCheckingFailEventContent
================================

.. code-block:: c#

	class MessageCheckingFailEventContent {
		OutboxMessageMeta: BasicMessageMeta,
		Errors: string[],
		ReportNumber: string
	}
	
Информация о новом событии - исходящее сообщение не прошло проверку на стороне получателя. Соответствует BoxEventType = MessageCheckingFail.

 - OutboxMessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` проверенного сообщения,
 - Errors – ошибки, обнаруженные в сообщении, не прошедшем проверку,
 - ReportNumber – номер статусного сообщения, соответствующего данному событию: актуален только для статусных сообщений, отправляемых по схеме с формированием документов после проверки сообщения Invoic.