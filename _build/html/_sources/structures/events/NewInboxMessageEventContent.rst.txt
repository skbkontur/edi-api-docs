NewInboxMessageEventContent
============================

.. code-block:: c#

	class NewInboxMessageEventContent {
		InboxMessageMeta: InboxMessageMeta
	}
	
Информация о новом событии - получении входящего сообщения. Соответствует BoxEventType = NewInboxMessage.
 - InboxMessageMeta – :doc:`метаинформация <../../structures/InboxMessageMeta>` сообщения.