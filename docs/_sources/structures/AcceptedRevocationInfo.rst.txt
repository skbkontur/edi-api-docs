AcceptedRevocationInfo
====================================================

.. code-block:: c#

	class AcceptedRevocationInfo {
		DiadocDocumentType: DiadocDocumentType,
		RevocationReason: string
	}
	
Информация об аннулировании документа:
	
 - DiadocDocumentType – :doc:`тип аннулированного документа <../../enums/DiadocDocumentType>`,
 - RevocationReason – причина аннулирования.