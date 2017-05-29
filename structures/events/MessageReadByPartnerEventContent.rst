MessageReadByPartnerEventContent
=================================

.. code-block:: c#

	class MessageReadByPartnerEventContent {
		OutboxMessageMeta: BasicMessageMeta
	}
	
Информация о новом событии - прочтении исходящего сообщения получателем. Соответствует BoxEventType = MessageReadByPartner.

 - OutboxMessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` прочитанного сообщения.