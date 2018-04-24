DiadocDocumentDeliveredEventContent
============================================

.. code-block:: c#

	class DiadocDocumentDeliveredEventContent {
		DiadocBoxId: string,
		MessageId: string,
		InvoiceId: string,
		Torg12Id: string,
		InvoiceCorrectionId: string,
		UniversalTransferDocumentId: string,
		UniversalCorrectionDocumentId: string,
		DiadocUrls: DiadocUrls,
		OutboxMessageMeta: BasicMessageMeta
		UniversalDocumentFunction: UniversalDocumentFunctionType
	}
	
Информация о новом событии в ящике - поступлении извещения о получении документа, сформированного на основании исходящего Invoic. Соответствует BoxEventType = DiadocDocumentDelivered.

 - DiadocBoxId – идентификатор ящика в Диадоке, из которого были отправлены подписанные отправителем документы,
 - InvoiceId – идентификатор отправленного счета-фактуры,
 - MessageId – идентификатор сообщения в Диадоке,
 - Torg12Id – идентификатор отправленного ТОРГ-12,
 - InvoiceCorrectionId – идентификатор отправленного корректировочного счета-фактуры,
 - UniversalTransferDocumentId – идентификатор отправленного УПД,
 - UniversalCorrectionDocumentId – идентификатор отправленного УКД,
 - DiadocUrls – :doc:`ссылки на документы в Диадоке <../../structures/DiadocUrls>`,
 - OutboxMessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` сообщения Invoic.
 - UniversalDocumentFunction - :doc:`функция УПД <../../enums/UniversalDocumentFunctionType>` сообщения Invoic.