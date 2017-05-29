MessageDraftOfDocumentPackageSignedBySenderEventContent
========================================================

.. code-block:: c#

	class MessageDraftOfDocumentPackageSignedBySenderEventContent {
		InboxMessageMeta: BasicMessageMeta,
		DiadocBoxId: string,
		InvoiceId: string,
		MessageId: string,
		Torg12Id: string,
		InvoiceCorrectionId: string,
		UniversalTransferDocumentId: string,
		DiadocUrls: DiadocUrls
	}
	
Информация о новом событии в ящике получателя - подписании и отправке черновиков документов, сформированных на основании входящего Invoic. Соответствует BoxEventType = DraftOfDocumentPackageSignedBySender.

 - InboxMessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` полученного сообщения Invoic,
 - DiadocBoxId – идентификатор ящика в Диадоке, в который пришли подписанные отправителем документы,
 - InvoiceId – идентификатор пришедшего счета-фактуры,
 - MessageId – идентификатор сообщения в Диадоке,
 - Torg12Id – идентификатор пришедшей ТОРГ-12,
 - InvoiceCorrectionId – идентификатор пришедшего корректировочного счета-фактуры,
 - UniversalTransferDocumentId – идентификатор пришедшего УПД,
 - UniversalCorrectionDocumentId – идентификатор пришедшего УКД,
 - DiadocUrls – :doc:`ссылки на документы в Диадоке <../../structures/DiadocUrls>`.