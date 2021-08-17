MessageDraftOfDocumentPackageDeletedFromDiadocEventContent
===========================================================

.. code-block:: c#

	class MessageDraftOfDocumentPackageDeletedFromDiadocEventContent {
		OutboxMessageMeta: BasicMessageMeta,
		DiadocBoxId: string,
		InvoiceId: string,
		MessageId: string,
		Torg12Id: string,
		InvoiceCorrectionId: string,
		UniversalTransferDocumentId: string,
		UniversalCorrectionDocumentId: string,
		DiadocUrls: DiadocUrls,
		UniversalDocumentFunction: UniversalDocumentFunctionType
	}

Информация о новом событии - удалении отправителем черновиков документов, сформированных на основании исходящего Invoic. Соответствует BoxEventType = DraftOfDocumentPackageDeletedFromDiadoc.

 - OutboxMessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` отправленного сообщения Invoic,
 - DiadocBoxId – идентификатор ящика в Диадоке, из которого удалены черновики документов,
 - InvoiceId – идентификатор удаленного счета-фактуры,
 - MessageId – идентификатор сообщения в Диадоке,
 - Torg12Id – идентификатор удаленной ТОРГ-12,
 - InvoiceCorrectionId – идентификатор удаленного корректировочного счета-фактуры,
 - UniversalTransferDocumentId – идентификатор удаленного УПД,
 - UniversalCorrectionDocumentId – идентификатор удаленного УКД,
 - DiadocUrls – :doc:`ссылки на документы в Диадоке <../../structures/DiadocUrls>`,
 - UniversalDocumentFunction - :doc:`функция УПД <../../enums/UniversalDocumentFunctionType>` сообщения Invoic.