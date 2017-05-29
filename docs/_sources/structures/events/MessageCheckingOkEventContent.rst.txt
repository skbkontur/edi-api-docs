MessageCheckingOkEventContent
==============================

.. code-block:: c#

	class MessageCheckingOkEventContent {
		OutboxMessageMeta: BasicMessageMeta,
		Warnings: string[],
		ReportNumber: string
	}
	
Информация о новом событии - исходящее сообщение прошло проверку на стороне получателя. Соответствует BoxEventType = MessageCheckingOk.

 - OutboxMessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` проверенного сообщения,
 - Warnings – замечания к сообщению, прошедшему проверку,
 - ReportNumber – номер статусного сообщения, соответствующего данному событию: актуален только для статусных сообщений, отправляемых по схеме с формированием документов после проверки сообщения Invoic.