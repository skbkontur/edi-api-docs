InboxMessageEntity
===================

.. code-block:: c#

	class InboxMessageEntity {
		Meta: InboxMessageMeta,
		Data: MessageData
	}
	
Входящее сообщение:

 - Meta – :doc:`метаинформация <../structures/InboxMessageMeta>` сообщения,
 - Data – :doc:`данные <../structures/MessageData>` сообщения.