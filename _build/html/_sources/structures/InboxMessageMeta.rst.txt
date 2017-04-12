InboxMessageMeta
=================

.. code-block:: c#

	class InboxMessageMeta {
		BoxId: string,
		MessageId: string,
		DocumentCirculationId: string,
		SendDateTime: dateTime,
		Sender: Partner,
		MessageFormat: MessageFormat,
		DocumentDetails: DocumentDetails
	}
	
Метаинформация входящего сообщения:

 - BoxId – идентификатор ящика, в который было доставлено сообщение.
 - MessageId – идентификатор входящего сообщения.
 - DocumentCirculationId – внутренний идентификатор входящего сообщения.
 - SendDateTime – дата и время отправки сообщения контрагентом.
 - Sender – :doc:`организация <../structures/Partner>` - отправитель сообщения.
 - MessageFormat – :doc:`формат сообщения <../enums/MessageFormat>`.
 - DocumentDetails – :doc:`информация о документе <../structures/DocumentDetails>`.