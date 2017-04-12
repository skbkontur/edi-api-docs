MessageReadByPartnerEventContent
=================================

.. code-block:: c#

	class MessageReadByPartnerEventContent {
		OutboxMessageMeta: OutboxMessageMeta
	}
	
Информация о новом событии - прочтении исходящего сообщения контрагентом. Соответствует BoxEventType = MessageReadByPartner.

 - OutboxMessageMeta – :doc:`метаинформация <../../structures/OutboxMessageMeta>` прочитанного сообщения.