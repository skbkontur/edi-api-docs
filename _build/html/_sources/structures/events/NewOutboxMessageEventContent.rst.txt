NewOutboxMessageEventContent
=============================

.. code-block:: c#

	class NewOutboxMessageEventContent {
		OutboxMessageMeta: OutboxMessageMeta
	}
	
Информация о новом событии - отправке исходящего сообщения. Соответствует BoxEventType = NewOutboxMessage.
 - OutboxMessageMeta – :doc:`метаинформация <../../structures/OutboxMessageMeta>` сообщения.