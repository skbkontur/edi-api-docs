OutboxMessageEntity
====================

.. code-block:: c#

	class OutboxMessageEntity {
		Meta: OutboxMessageMeta,
		Data: MessageData
	}
	
Исходящее сообщение:

 - Meta – :doc:`метаинформация <../structures/BasicMessageMeta>` исходящего сообщения.
 - Data – :doc:`данные <../structures/MessageData>` исходящего сообщения.