DocumentSettingsForPartner
===========================

.. code-block:: c#

	class DocumentSettingsForPartner {
		Partner: Partner,
		DocumentSettings: DocumentSettings[]
	}

Настройки обмена документами с конкретным контрагентом:

 - Partner – :doc:`организация-контрагент <../structures/Partner>`,
 - DocumentSettings – :doc:`набор документов <../structures/DocumentSettings>`, которыми можно обмениваться с контрагентом.