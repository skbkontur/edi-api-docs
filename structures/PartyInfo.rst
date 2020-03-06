PartyInfo
==========

.. code-block:: c#

	class PartyInfo {
		Id: string,
		Gln: string,
		Name: string,
		Inn: string,
		Kpp: string,
		PartyTypeCode: string,
		DiadocOrgId: string,
		OrganizationCatalogueUpdateTime: dateTime,
		LicenseAgreementAccepted: bool,
		BuyerBoxSelectionStrategy: BuyerBoxSelectionStrategy,
		SupplierBoxSelectionStrategy: SupplierBoxSelectionStrategy
	}
	
Реквизиты организации:

 - Id – идентификатор организации,
 - Gln – Gln организации,
 - Name – наименование,
 - Inn – ИНН,
 - Kpp – КПП,
 - PartyTypeCode – :doc:`тип организации <../enums/PartyType>`,
 - DiadocOrgId – идентификатор в Диадок,
 - OrganizationCatalogueUpdateTime – время последнего изменения реквизитов организации или ее структуры,
 - LicenseAgreementAccepted - организация приняла публичную оферту,
 - BuyerBoxSelectionStrategy - :doc:`cтратегия маршрутизации сообщений сети <../enums/BuyerBoxSelectionStrategy>`,
 - SupplierBoxSelectionStrategy - :doc:`cтратегия маршрутизации сообщений поставщика <../enums/SupplierBoxSelectionStrategy>`.