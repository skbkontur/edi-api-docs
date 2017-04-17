MessageDraftOfDocumentPackageDeletedFromDiadocEventContent
===========================================================

.. code-block:: c#

	class MessageDraftOfDocumentPackageDeletedFromDiadocEventContent {
		OutboxMessageMeta: OutboxMessageMeta,
		DiadocBoxId: string,
		InvoiceId: string,
		MessageId: string,
		Torg12Id: string,
		InvoiceCorrectionId: string,
		UniversalTransferDocumentId: string,
		DiadocUrls: DiadocUrls
	}

Информация о новом событии - удалении отправителем черновиков счета-фактуры, ТОРГ-12, сформированных на основании исходящего Invoic. Соответствует BoxEventType = DraftOfDocumentPackageDeletedFromDiadoc.

 - OutboxMessageMeta – :doc:`метаинформация <../../structures/OutboxMessageMeta>` отправленного сообщения Invoic.
 - DiadocBoxId – идентификатор ящика в Диадоке, из которого удалены черновики документов.
 - InvoiceId – идентификатор удаленного счета-фактуры.
 - MessageId – идентификатор сообщения в Диадоке.
 - Torg12Id – идентификатор удаленной ТОРГ-12.
 - InvoiceCorrectionId – идентификатор удаленного корректировочного счета-фактуры.
 - UniversalTransferDocumentId – идентификатор удаленного УПД.
 - UniversalCorrectionDocumentId – идентификатор удаленного УКД.
 - DiadocUrls – :doc:`ссылки на документы в Диадоке <../../structures/DiadocUrls>`.