OutboxMessageMeta
==================

.. code-block:: c#

	class OutboxMessageMeta {
		BoxId: string,
		MessageId: string,
		DocumentCirculationId: string
	}
	
Метаинформация исходящего сообщения.
 - BoxId – идентификатор ящика клиента, из которого сообщение отправлено.
 - MessageId – идентификатор исходящего сообщения.
 - DocumentCirculationId – внутренний идентификатор исходящего сообщения.