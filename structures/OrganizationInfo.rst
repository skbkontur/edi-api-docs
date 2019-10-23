OrganizationInfo
=================

.. code-block:: c#

	class OrganizationInfo {
		Gln: string,
		PartyAddress: PartyAddress,
		GeoCoordinates: GeoCoordinates,
		RussianPartyInfo: RussianPartyInfo,
		BankAccount: BankAccount,
		SupplierCodeInBuyerSystem: string,
		BusinessEntityMercuryId: string,
		AreaEntityMercuryId: string,
		Chief: ContactInformation,
		Bookkeeper: ContactInformation,
		SalesAdministration: ContactInformation,
		OrderContact: ContactInformation,
		LocalizationType: string,
		FilialGln: string
	}
	
Реквизиты и адрес организации или точки доставки/отгрузки:

 - Gln – Gln,
 - PartyAddress – :doc:`адрес <../structures/PartyAddress>`,
 - GeoCoordinates - :doc:`географические координаты<../structures/GeoCoordinates>`,
 - RussianPartyInfo – :doc:`реквизиты <../structures/RussianPartyInfo>`,
 - BankAccount – :doc:`банковские реквизиты <../structures/BankAccount>`,
 - SupplierCodeInBuyerSystem – дополнительный идентификатор,
 - BusinessEntityMercuryId - идентификатор хозяйствующего субъекта в ФГИС Меркурий,
 - AreaEntityMercuryId - идентификатор торговой площадки ФГИС Меркурий,
 - Chief – :doc:`данные о руководителе <../structures/ContactInformation>`,
 - Bookkeeper – :doc:`данные о бухгалтере <../structures/ContactInformation>`,
 - SalesAdministration – :doc:`данные о менеджере <../structures/ContactInformation>`,
 - OrderContact – :doc:`данные о контактном лице <../structures/ContactInformation>`,
 - LocalizationType - тип организации,
 - FilialGln - Gln филиала точки доставки.