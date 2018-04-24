Форматы сообщений
==================

.. code-block:: c#

	enum MessageFormat {
		Unknown,
		Any,
		KonturXml,
		KorusXml,
		Eancom2002,
		EcrRusXml		
	}
	
Unknown и Any - специальные значения, возвращаемые в следующих случаях:
 - Unknown – не удалось определить формат собщения.
 - Any – не задан отдельный формат сообщения. Значение может быть возвращено при вызове метода :doc:`GetBoxesInfo <../methods/GetBoxesInfo>` в структуре :doc:`BoxSettings <../structures/BoxSettings>`.