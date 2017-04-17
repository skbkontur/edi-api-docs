MessageReceivedDiadocRoamingErrorEventContent
==============================================

.. code-block:: c#

	class MessageReceivedDiadocRoamingErrorEventContent {
		OutboxMessageMeta: OutboxMessageMeta,
		Reason: string,
		DiadocBoxId: string,
		InvoiceId: string,
		MessageId: string,
		Torg12Id: string,
		InvoiceCorrectionId: string,
		UniversalTransferDocumentId: string,
		DiadocUrls: DiadocUrls
	}
	
Информация о новом событии - на стороне получателя были обнаружены ошибки в счете-фактуре, ТОРГ-12, сформированных на основании исходящего Invoic. Соответствует BoxEventType = ReceivedDiadocRoamingError.

 - OutboxMessageMeta – :doc:`метаинформация <../../structures/OutboxMessageMeta>` исходящего сообщения Invoic.
 - Reason – ошибки, обнаруженные в документах, не прошедших проверку у получателя.
 - DiadocBoxId – идентификатор ящика в Диадоке, в который пришли подписанные отправителем документы.
 - InvoiceId – идентификатор пришедшего счета-фактуры.
 - MessageId – идентификатор сообщения в Диадоке.
 - Torg12Id – идентификатор пришедшей ТОРГ-12.
 - InvoiceCorrectionId – идентификатор пришедшего корректировочного счета-фактуры.
 - UniversalTransferDocumentId – идентификатор пришедшего УПД.
 - UniversalCorrectionDocumentId – идентификатор пришедшего УКД.
 - DiadocUrls – :doc:`ссылки на документы в Диадоке <../../structures/DiadocUrls>`.