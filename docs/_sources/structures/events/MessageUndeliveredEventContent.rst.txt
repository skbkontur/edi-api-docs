MessageUndeliveredEventContent
===============================

.. code-block:: c#

	class MessageUndeliveredEventContent {
		OutboxMessageMeta: OutboxMessageMeta,
		MessageUndeliveryReasons: string[]
	}
	
Информация о новом событии - ошибке доставки исходящего сообщения получателю. Соответствует BoxEventType = MessageUndelivered.

 - OutboxMessageMeta – :doc:`метаинформация <../../structures/OutboxMessageMeta>` недоставленного сообщения.
 - MessageUndeliveryReasons – описание причин, по которым сообщение не доставлено.