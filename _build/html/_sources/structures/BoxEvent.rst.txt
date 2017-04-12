BoxEvent
=========

.. code-block:: c#

	class BoxEvent {
		BoxId: string,
		PartyId: string,
		EventId: string,
		EventDateTime: dateTime,
		EventType: BoxEventType,
		EventContent: BoxEventContent
	}
	
Информация о событии, связанном с входящим или исходящим сообщением:

 - BoxId – идентификатор ящика.
 - PartyId – идентификатор организации, которой принадлежит ящик.
 - EventId – уникальный идентификатор события.
 - EventDateTime – дата и время события.
 - EventType – :doc:`тип события <../enums/BoxEventType>`.
 - EventContent – :doc:`содержимое события <../structures/BoxEventContent>`.