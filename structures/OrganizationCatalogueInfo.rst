OrganizationCatalogueInfo
==========================

.. code-block:: c#

	class OrganizationCatalogueInfo {
		Organizations: Organization[],
		DeliveryPoints: Organization[]
	}
	
Информация о структуре организации:

 - Organizations – связанные :doc:`юридические лица и/или индивидуальные предприниматели <../structures/Organization>`;
 - DeliveryPoints – :doc:`точки доставки/отгрузки <../structures/Organization>`.