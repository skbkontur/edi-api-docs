BasicMessageMeta
==================

.. code-block:: c#

	class BasicMessageMeta {
		BoxId: string,
		MessageId: string,
		DocumentCirculationId: string
	}
	
Метаинформация сообщения:

 - BoxId – идентификатор ящика клиента, в которое пришло сообщение или из которого сообщение было отправлено.
 - MessageId – идентификатор сообщения.
 - DocumentCirculationId – внутренний идентификатор сообщения.