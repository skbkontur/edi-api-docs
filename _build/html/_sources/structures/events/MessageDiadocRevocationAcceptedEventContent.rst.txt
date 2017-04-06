MessageDiadocRevocationAcceptedEventContent
============================================

.. code-block:: c#

	class MessageDiadocRevocationAcceptedEventContent {
		AcceptedRevocationInfo: AcceptedRevocationInfo,
		DiadocBoxId: string,
		InvoiceId: string,
		MessageId: string,
		Torg12Id: string,
		InvoiceCorrectionId: string,
		UniversalTransferDocumentId: string,
		UniversalCorrectionDocumentId: string,
		DiadocUrls: DiadocUrls,
		OutboxMessageMeta: OutboxMessageMeta
	}
	
Информация о новом событии в ящике отправителя - успешном аннулировании ТОРГ-12 или счета-фактуры, сформированного на основании исходящего Invoic. Соответствует BoxEventType = DiadocRevocationAccepted.
 - AcceptedRevocationInfo – информация об аннулированном документе.
 - DiadocBoxId – идентификатор ящика в Диадоке, в который пришли подписанные отправителем документы.
 - InvoiceId – идентификатор пришедшего счета-фактуры.
 - MessageId – идентификатор сообщения в Диадоке.
 - Torg12Id – идентификатор пришедшей ТОРГ-12.
 - InvoiceCorrectionId – идентификатор пришедшего корректировочного счета-фактуры.
 - UniversalTransferDocumentId – идентификатор пришедшего УПД.
 - UniversalCorrectionDocumentId – идентификатор пришедшего УКД.
 - DiadocUrls – :doc:`ссылки на документы в Диадоке <../../structures/DiadocUrls>`.
 - OutboxMessageMeta – :doc:`метаинформация <../../structures/OutboxMessageMeta>` исходящего сообщения Invoic.