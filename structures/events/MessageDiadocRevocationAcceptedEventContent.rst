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
		OutboxMessageMeta: BasicMessageMeta,
		UniversalDocumentFunction: UniversalDocumentFunctionType
	}
	
Информация о новом событии в ящике отправителя - успешном аннулировании документа в Диадоке, сформированного на основании исходящего Invoic. Соответствует BoxEventType = DiadocRevocationAccepted.

 - AcceptedRevocationInfo – :doc:`информация об аннулированном документе <../../structures/AcceptedRevocationInfo>`,
 - DiadocBoxId – идентификатор ящика в Диадоке, из которого были отправлены подписанные отправителем документы,
 - InvoiceId – идентификатор отправленного счета-фактуры,
 - MessageId – идентификатор сообщения в Диадоке,
 - Torg12Id – идентификатор отправленного ТОРГ-12,
 - InvoiceCorrectionId – идентификатор отправленного корректировочного счета-фактуры,
 - UniversalTransferDocumentId – идентификатор отправленного УПД,
 - UniversalCorrectionDocumentId – идентификатор отправленного УКД,
 - DiadocUrls – :doc:`ссылки на документы в Диадоке <../../structures/DiadocUrls>`,
 - OutboxMessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` исходящего сообщения Invoic,
 - UniversalDocumentFunction - :doc:`функция УПД <../../enums/UniversalDocumentFunctionType>` сообщения Invoic.
 