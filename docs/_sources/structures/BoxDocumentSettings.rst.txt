BoxDocumentsSettings
=====================

.. code-block:: c#

	class BoxDocumentsSettings {
		BoxId: string,
		DocumentsSettingsForPartner: DocumentSettingsForPartner[]
	}
	
Настройка возможности обмена документами с различными контрагентами в рамках одного ящика:

 - BoxId – идентификатор ящика,
 - DocumentsSettingsForPartner – :doc:`настройки документов <../structures/DocumentSettingsForPartner>` по контрагентам.