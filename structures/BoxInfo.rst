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
 - Id – идентификатор ящика.
 - PartyId – идентификатор организации, которой принадлежит ящик.
 - Gln – gln, относящийся к данному ящику.
 - IsTest – тестовый признак, относящийся к ящику.
 - :doc:`BoxSettings <../structures/BoxSettings>` – настройки ящика.