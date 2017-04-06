BoxSettings
============

.. code-block:: c#

	class BoxSettings {
		TransportType: TransportType,
		IsMain: bool,
		DocumentTypes: DocumentType,
		CustomMessageFormats: MessageFormat,
		InboxRelativePath: string,
		OutboxRelativePath: string,
		ProviderTransportBoxId: string
	}
	
Настройки ящика:
 - TransportType – :doc:`тип транспорта, используемый в ящике <../enums/TransportType>`.
 - IsMain – признак основного транспорта.
 - DocumentTypes – :doc:`типы сообщений <../enums/DocumentType>`, настроенные для ящика. Если возвращено значение Any, это означает, что данный ящик соответствует настройкам "Транспорт по умолчанию".
 - CustomMessageFormats – :doc:`форматы сообщений <../enums/MessageFormat>`, настроенные для ящика. Если возвращено значение Any, это означает, что данный ящик соответствует настройкам "Транспорт по умолчанию".
 - InboxRelativePath – путь папки входящих сообщений на Ftp. Заполняется только в том случае, если тип транспорта - "Ftp" и ящик используется для входящих сообщений.
 - OutboxRelativePath – путь папки исходящих сообщений на Ftp. Заполняется только в том случае, если тип транспорта - "Ftp" и ящик используется для исходящих сообщений.
 - ProviderTransportBoxId – идентификатор ящика провайдера. Заполняется только в том случае, если тип транспорта - "Provider".