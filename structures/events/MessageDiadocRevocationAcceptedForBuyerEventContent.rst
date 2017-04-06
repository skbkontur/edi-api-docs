MessageDiadocRevocationAcceptedForBuyerEventContent
====================================================

.. code-block:: c#

	class MessageDiadocRevocationAcceptedForBuyerEventContent {
		AcceptedRevocationInfo: AcceptedRevocationInfo,
		DiadocBoxId: string,
		InvoiceId: string,
		MessageId: string,
		Torg12Id: string,
		InvoiceCorrectionId: string,
		UniversalTransferDocumentId: string,
		DiadocUrls: DiadocUrls,
		InboxMessageMeta: InboxMessageMeta
	}
	
Информация о новом событии в ящике получателя - успешном аннулировании ТОРГ-12, счета-фактуры или УПД, сформированного на основании входящего Invoic. Соответствует BoxEventType = DiadocRevocationAcceptedForBuyer.
 - AcceptedRevocationInfo – информация об аннулированном документе.
 - DiadocBoxId – идентификатор ящика в Диадоке, в который пришли подписанные отправителем документы.
 - InvoiceId – идентификатор пришедшего счета-фактуры.
 - MessageId – идентификатор сообщения в Диадоке.
 - Torg12Id – идентификатор пришедшей ТОРГ-12.
 - InvoiceCorrectionId – идентификатор пришедшего корректировочного счета-фактуры.
 - UniversalTransferDocumentId – идентификатор пришедшего УПД.
 - UniversalCorrectionDocumentId – идентификатор пришедшего УКД.
 - DiadocUrls – :doc:`ссылки на документы в Диадоке <../../structures/DiadocUrls>`.
 - InboxMessageMeta – :doc:`метаинформация <../../structures/InboxMessageMeta>` входящего сообщения Invoic.