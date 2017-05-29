MessageUndeliveredEventContent
===============================

.. code-block:: c#

	class MessageUndeliveredEventContent {
		OutboxMessageMeta: BasicMessageMeta,
		MessageUndeliveryReasons: string[]
	}
	
Информация о новом событии - ошибке доставки исходящего сообщения получателю. Соответствует BoxEventType = MessageUndelivered.

 - OutboxMessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` недоставленного сообщения,
 - MessageUndeliveryReasons – описание причин, по которым сообщение не доставлено.