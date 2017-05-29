AmendmentRequestedEventContent
============================================

.. code-block:: c#

	class AmendmentRequestedEventContent {
		AmendmentRequestMessage: string,
		DiadocBoxId: string,
		InvoiceId: string,
		MessageId: string,
		Torg12Id: string,
		InvoiceCorrectionId: string,
		UniversalTransferDocumentId: string,
		UniversalCorrectionDocumentId: string,
		DiadocUrls: DiadocUrls,
		MessageMeta: BasicMessageMeta
	}
	
Информация о новом событии в ящике - поступлении уведомления об уточнении документа, сформированного на основании исходящего Invoic. Соответствует BoxEventType = AmendmentRequested.

 - AmendmentRequestMessage – текст уведомления об уточнении,
 - DiadocBoxId – идентификатор ящика в Диадоке, в который пришли подписанные отправителем документы,
 - InvoiceId – идентификатор пришедшего счета-фактуры,
 - MessageId – идентификатор сообщения в Диадоке,
 - Torg12Id – идентификатор пришедшей ТОРГ-12,
 - InvoiceCorrectionId – идентификатор пришедшего корректировочного счета-фактуры,
 - UniversalTransferDocumentId – идентификатор пришедшего УПД,
 - UniversalCorrectionDocumentId – идентификатор пришедшего УКД,
 - DiadocUrls – :doc:`ссылки на документы в Диадоке <../../structures/DiadocUrls>`,
 - MessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` сообщения Invoic.