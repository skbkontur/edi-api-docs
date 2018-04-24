ProcessingTimesReportEventContent
=================================

.. code-block:: c#

	class ProcessingTimesReportEventContent {
		DocumentCirculationId: string,
		SenderPartyId: string,
		RecipientPartyId: string,
		InitialMessageId: string,
		InitialDocumentId: DocumentId,
		DocumentType: DocumentType,
		DocumentCirculationStartTimestamp: DateTime,
		DocumentCirculationCompletionTimestamp: DateTime,
		ProcessingTimes: ProcessingTimes
	}
	
Информация о новом событии - разборе исходящего сообщения и успешном определении его основных параметров (формат, тип, отправитель и получатель). Соответствует BoxEventType = ProcessingTimesReport.

 - DocumentCirculationId - внутренний идентификатор сообщения, при помощи этого идентификатора можно просмотреть информацию о сообщении в мониторинге сервиса.
 - SenderPartyId - идентификатор организации отправителя,
 - RecipientPartyId - идентификатор организации получателя,
 - InitialMessageId - идентификатор сообщения
 - InitialDocumentId - :doc:`идентификатор документа в ящике<../../structures/DocumentId>`
 - DocumentType - тип сообщения
 - DocumentCirculationStartTimestamp - время начала документооборота
 - DocumentCirculationCompletionTimestamp - время завершения документооборота
 - ProcessingTimes - :doc:`время, затраченное на различные этапы обработки сообщения, и общее время доставки сообщения<../../structures/ProcessingTimes>`