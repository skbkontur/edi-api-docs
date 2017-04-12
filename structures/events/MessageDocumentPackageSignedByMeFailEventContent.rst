MessageDocumentPackageSignedByMeFailEventContent
=================================================

.. code-block:: c#

	class MessageDocumentPackageSignedByMeFailEventContent {
		DiadocBoxId: string,
		InvoiceId: string,
		MessageId: string,
		Torg12Id: string,
		InvoiceCorrectionId: string,
		UniversalTransferDocumentId: string,
		UniversalCorrectionDocumentId: string,
		DiadocUrls: DiadocUrls
	}
	
Информация о новом событии в ящике получателя - отказе в подписи ТОРГ-12, счета-фактуры или УПД, сформированного на основании входящего Invoic, а также корректировочных документов, сформированных на основании входящего Coinvoic. Соответствует BoxEventType = DocumentPackageSignedByMeFail.

 - DiadocBoxId – идентификатор ящика в Диадоке, в который пришли подписанные отправителем документы.
 - InvoiceId – идентификатор пришедшего счета-фактуры.
 - MessageId – идентификатор сообщения в Диадоке.
 - Torg12Id – идентификатор пришедшей ТОРГ-12.
 - InvoiceCorrectionId – идентификатор пришедшего корректировочного счета-фактуры.
 - UniversalTransferDocumentId – идентификатор пришедшего УПД.
 - UniversalCorrectionDocumentId – идентификатор пришедшего УKД.
 - DiadocUrls – :doc:`ссылки на документы в Диадоке <../../structures/DiadocUrls>`.