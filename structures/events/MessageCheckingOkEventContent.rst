MessageCheckingOkEventContent
==============================

.. code-block:: c#

	class MessageCheckingOkEventContent {
		OutboxMessageMeta: OutboxMessageMeta,
		Warnings: string[],
		ReportNumber: string
	}
	
Информация о новом событии - исходящее сообщение прошло проверку на стороне получателя. Соответствует BoxEventType = MessageCheckingOk.
 - OutboxMessageMeta – :doc:`метаинформация <../../structures/OutboxMessageMeta>` проверенного сообщения.
 - Warnings – замечания к сообщению, прошедшему проверку.
 - ReportNumber – номер статусного сообщения, соответствующего данному событию. Актуален только для статусных отправляемых при схеме MetroOkNotOk.