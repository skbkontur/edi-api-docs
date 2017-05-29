BoxInfo
========

.. code-block:: c#

	class BoxInfo {
		Id: string,
		PartyId: string,
		Gln: string,
		IsTest: bool,
		BoxSettings: BoxSettings
	}
	
Информация о ящике:

 - Id – идентификатор ящика,
 - PartyId – идентификатор организации, которой принадлежит ящик,
 - Gln – gln ящика,
 - IsTest – флаг, показывающий, что данный ящик является тестовым,
 - :doc:`BoxSettings <../structures/BoxSettings>` – настройки ящика.