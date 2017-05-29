BoxEventBatch
==============

.. code-block:: c#

	class BoxEventBatch {
		Events: BoxEvent[],
		LastEventId: string
	}
	
Набор событий:

 - Events – список :doc:`событий <../structures/BoxEvent>`,
 - LastEventId – идентификатор последнего события в наборе: при следующем вызове метода :doc:`GetEvents <../methods/GetEvents>` необходимо передать именно его.