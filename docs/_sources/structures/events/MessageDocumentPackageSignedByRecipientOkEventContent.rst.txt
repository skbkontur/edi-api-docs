MessageDocumentPackageSignedByRecipientOkEventContent
======================================================

.. code-block:: c#

	class MessageDocumentPackageSignedByRecipientOkEventContent {
		DiadocBoxId: string,
		InvoiceId: string,
		MessageId: string,
		Torg12Id: string,
		InvoiceCorrectionId: string,
		UniversalTransferDocumentId: string,
		UniversalCorrectionDocumentId: string,
		DiadocUrls: DiadocUrls,
		OutboxMessageMeta: BasicMessageMeta
	}
	
Информация о новом событии в ящике отправителя - успешном подписании ТОРГ-12, счета-фактуры или УПД, сформированного на основании входящего Invoic, а также корректировочных документов, сформированных на основании входящего Coinvoic. Соответствует BoxEventType = DocumentPackageSignedByRecipientOk.

 - DiadocBoxId – идентификатор ящика в Диадоке, из которого отправлены подписанные документы.
 - InvoiceId – идентификатор отправленного счета-фактуры.
 - MessageId – идентификатор сообщения в Диадоке.
 - Torg12Id – идентификатор отправленной ТОРГ-12.
 - InvoiceCorrectionId – идентификатор отправленного корректировочного счета-фактуры.
 - UniversalTransferDocumentId – идентификатор отправленного УПД.
 - UniversalCorrectionDocumentId – идентификатор отправленного УKД.
 - DiadocUrls – :doc:`ссылки на документы в Диадоке <../../structures/DiadocUrls>`.
 - OutboxMessageMeta – :doc:`метаинформация <../../structures/BasicMessageMeta>` исходящего сообщения Invoic.