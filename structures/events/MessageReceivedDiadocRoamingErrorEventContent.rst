MessageReceivedDiadocRoamingErrorEventContent
==============================================

.. code-block:: c#

	class MessageReceivedDiadocRoamingErrorEventContent {
		OutboxMessageMeta: BasicMessageMeta,
		Reason: string,
		DiadocBoxId: string,
		InvoiceId: string,
		MessageId: string,
		Torg12Id: string,
		InvoiceCorrectionId: string,
		UniversalTransferDocumentId: string,
		DiadocUrls: DiadocUrls,
		UniversalDocumentFunction: UniversalDocumentFunctionType
	}
	
Информация о новом событии - на стороне получателя были обнаружены ошибки в документах, сформированных на основании исходящего Invoic. Соответствует BoxEventType = ReceivedDiadocRoamingError.

 - OutboxMessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` исходящего сообщения Invoic,
 - Reason – ошибки, обнаруженные в документах, не прошедших проверку у получателя,
 - DiadocBoxId – идентификатор ящика в Диадоке, из которого были отправлены подписанные отправителем документы,
 - InvoiceId – идентификатор отправленного счета-фактуры,
 - MessageId – идентификатор сообщения в Диадоке,
 - Torg12Id – идентификатор отправленного ТОРГ-12,
 - InvoiceCorrectionId – идентификатор отправленного корректировочного счета-фактуры,
 - UniversalTransferDocumentId – идентификатор отправленного УПД,
 - UniversalCorrectionDocumentId – идентификатор отправленного УКД,
 - DiadocUrls – :doc:`ссылки на документы в Диадоке <../../structures/DiadocUrls>`,
 - UniversalDocumentFunction - :doc:`функция УПД <../../enums/UniversalDocumentFunctionType>` сообщения Invoic.