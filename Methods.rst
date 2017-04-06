Поддерживаемые операции
========================

Во многих командах коммуникации между клиентом и сервером осуществляются посредством JSON-сериализованных объектов. Для обозначения таких объектов будет использоваться термин структура. То есть, если в тексте документации будет сказано, что сервер вернул структуру вида

.. code-block:: c#

	class someClass {
		someStringProperty: string,
		someIntProperty: int,
		someSubClassProperty: {
			someSubClassStringProperty: string,
		}
	}
	
то это означает, что пример ответа сервера будет выглядеть следующим образом:

.. code-block:: json

	{"SomeStringProperty":"string1","SomeIntProperty":12,"SomeSubClassProperty":{"SomeSubClassStringProperty":"string2"}}
	
.. toctree::
   :name: methods
   :maxdepth: 1
   :caption: Поддерживаемые операции
   
		Authenticate <methods/Authenticate>
		GetAccessiblePartiesInfo <methods/GetAccessiblePartiesInfo>
		GetBoxDocumentsSettings <methods/GetBoxDocumentsSettings>
		GetBoxesInfo <methods/GetBoxesInfo>
		GetEvents <methods/GetEvents>
		GetEventsFrom <methods/GetEventsFrom>
		GetInboxMessage <methods/GetInboxMessage>
		GetMainApiBox <methods/GetMainApiBox>
		GetOrganizationCatalogueInfo <methods/GetOrganizationCatalogueInfo>
		GetOutboxMessage <methods/GetOutboxMessage>
		GetPartyInfo <methods/GetPartyInfo>
		GetUsersInfo <methods/GetUsersInfo>
		SendMessage <methods/SendMessage>