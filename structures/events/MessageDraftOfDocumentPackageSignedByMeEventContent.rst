MessageDraftOfDocumentPackageSignedByMeEventContent
====================================================

.. code-block:: c#

	class
	MessageDraftOfDocumentPackageSignedByMeEventContent {
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
	
Информация о новом событии в ящике отправителя - подписании и отправке черновиков документов, сформированных на основании исходящего Invoic. Соответствует BoxEventType = DraftOfDocumentPackageSignedByMe.

 - OutboxMessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` отправленного сообщения Invoic,
 - DiadocBoxId – идентификатор ящика в Диадоке, из которого отправлены подписанные документы,
 - InvoiceId – идентификатор подписанного счета-фактуры,
 - MessageId – идентификатор сообщения в Диадоке,
 - Torg12Id – идентификатор подписанной ТОРГ-12,
 - InvoiceCorrectionId – идентификатор пришедшего корректировочного счета-фактуры,
 - UniversalTransferDocumentId – идентификатор пришедшего УПД,
 - UniversalCorrectionDocumentId – идентификатор пришедшего УКД,
 - DiadocUrls – :doc:`ссылки на документы в Диадоке <../../structures/DiadocUrls>`,
 - UniversalDocumentFunction - :doc:`функция УПД <../../enums/UniversalDocumentFunctionType>` сообщения Invoic.