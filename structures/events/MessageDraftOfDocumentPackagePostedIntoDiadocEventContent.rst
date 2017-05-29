MessageDraftOfDocumentPackagePostedIntoDiadocEventContent
==========================================================

.. code-block:: c#

	class MessageDraftOfDocumentPackagePostedIntoDiadocEventContent {
		OutboxMessageMeta: BasicMessageMeta,
		DiadocBoxId: string,
		InvoiceId: string,
		MessageId: string,
		Torg12Id: string,
		InvoiceCorrectionId: string,
		UniversalTransferDocumentId: string,
		UniversalCorrectionDocumentId: string,
		DiadocUrls: DiadocUrls
	}

Информация о новом событии - формировании на основе исходящего Invoic черновиков документов в Диадоке. Соответствует BoxEventType = DraftOfDocumentPackagePostedIntoDiadoc.

 - OutboxMessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` отправленного сообщения Invoic,
 - DiadocBoxId – идентификатор ящика в Диадоке, в котором сформированы черновики документов,
 - InvoiceId – идентификатор черновика счета-фактуры,
 - MessageId – идентификатор сообщения в Диадоке,
 - Torg12Id – идентификатор черновика ТОРГ-12,
 - InvoiceCorrectionId – идентификатор черновика корректировочного счета-фактуры,
 - UniversalTransferDocumentId – идентификатор черновика УПД,
 - UniversalCorrectionDocumentId – идентификатор черновика УКД,
 - DiadocUrls – :doc:`ссылки на документы в Диадоке <../../structures/DiadocUrls>`.