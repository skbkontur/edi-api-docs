DocumentDetails
================

.. code-block:: c#

	class DocumentDetails {
		DocumentType: DocumentType,
		DocumentIsTest: bool,
		DocumentNumber: string,
		DocumentDate: dateTime,
		DeliveryPointGln: string
	}
	
Информация о документе:

 - DocumentType – :doc:`тип документа <../enums/DocumentType>`,
 - DocumentIsTest – флаг, показывающий, что данный документ является тестовым,
 - DocumentNumber – номер документа,
 - DocumentDate – дата документа,
 - DeliveryPointGln - GLN точки доставки, указанный в документе.