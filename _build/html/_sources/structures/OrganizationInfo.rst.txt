OrganizationInfo
=================

.. code-block:: c#

	class OrganizationInfo {
		Gln: string,
		PartyAddress: PartyAddress,
		RussianPartyInfo: RussianPartyInfo,
		BankAccount: BankAccount,
		SupplierCodeInBuyerSystem: string,
		Chief: ContactInformation,
		Bookkeeper: ContactInformation,
		SalesAdministration: ContactInformation,
		OrderContact: ContactInformation
	}
	
Реквизиты и адрес организации или точки доставки/отгрузки:
 - Gln – Gln.
 - PartyAddress – :doc:`адрес <../structures/PartyAddress>`.
 - RussianPartyInfo – :doc:`реквизиты <../structures/RussianPartyInfo>`.
 - BankAccount – :doc:`банковские реквизиты <../structures/BankAccount>`.
 - SupplierCodeInBuyerSystem – дополнительный идентификатор.
 - Chief – :doc:`данные о руководителе <../structures/ContactInformation>`.
 - Bookkeeper – :doc:`данные о бухгалтере <../structures/ContactInformation>`.
 - SalesAdministration – :doc:`данные о менеджере <../structures/ContactInformation>`.
 - OrderContact – :doc:`данные о контактном лице <../structures/ContactInformation>`.