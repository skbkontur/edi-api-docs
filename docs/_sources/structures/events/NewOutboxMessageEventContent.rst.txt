NewOutboxMessageEventContent
=============================

.. code-block:: c#

	class NewOutboxMessageEventContent {
		OutboxMessageMeta: BasicMessageMeta
	}
	
Информация о новом событии - отправке исходящего сообщения. Соответствует BoxEventType = NewOutboxMessage.

 - OutboxMessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` сообщения.