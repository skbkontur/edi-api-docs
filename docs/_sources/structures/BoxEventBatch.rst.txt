BoxEventBatch
==============

.. code-block:: c#

	class BoxEventBatch {
		Events: BoxEvent[],
		LastEventId: string
	}
	
Набор событий:

 - Events – список :doc:`событий <../structures/BoxEvent>`.
 - LastEventId – идентификатор последнего события в наборе. В следующий вызов метода :doc:`GetEvents <../methods/GetEvents>` необходимо передать именно его.