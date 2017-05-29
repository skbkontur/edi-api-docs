Типы документов
================

.. code-block:: c#

	enum DocumentType {
		Unknown,
		Any,
		Orders,
		Ordrsp,
		Desadv,
		Recadv,
		Invoic,
		Coinvoic,
		Alcrpt,
		Stsmsg,
		Retann,
		Retins,
		Retdes,
		Retrec,
		Retinv,
		POrders,
		PriceList,
		Invrpt,
		Slsrpt
	}
	
Unknown и Any - специальные значения, возвращаемые в следующих случаях:
 - Unknown – не удалось определить тип собщения.
 - Any – не задан отдельный тип сообщения. Значение может быть возвращено при вызове метода :doc:`GetBoxesInfo <../methods/GetBoxesInfo>` в структуре :doc:`BoxSettings <../structures/BoxSettings>`.