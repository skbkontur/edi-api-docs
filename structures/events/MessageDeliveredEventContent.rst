MessageDeliveredEventContent
=============================

.. code-block:: c#

	class MessageDeliveredEventContent {
		OutboxMessageMeta: BasicMessageMeta
	}
	
Информация о новом событии - доставке исходящего сообщения получателю. Соответствует BoxEventType = MessageDelivered.

 - OutboxMessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` доставленного сообщения.