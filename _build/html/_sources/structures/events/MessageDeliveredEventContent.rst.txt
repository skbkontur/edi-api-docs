MessageDeliveredEventContent
=============================

.. code-block:: c#

	class MessageDeliveredEventContent {
		OutboxMessageMeta: OutboxMessageMeta
	}
	
Информация о новом событии - доставке исходящего сообщения получателю. Соответствует BoxEventType = MessageDelivered.
 - OutboxMessageMeta – :doc:`метаинформация <../../structures/OutboxMessageMeta>` доставленного сообщения.