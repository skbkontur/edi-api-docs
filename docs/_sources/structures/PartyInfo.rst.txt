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
		OrganizationCatalogueUpdateTime: dateTime
	}
	
Реквизиты организации:

 - Id – идентификатор организации.
 - Gln – Gln организации.
 - Name – наименование организации.
 - Inn – ИНН организации.
 - Kpp – КПП организации.
 - PartyTypeCode – :doc:`тип организации <../enums/PartyType>`.
 - DiadocOrgId – идентификатор организации в Диадок.
 - OrganizationCatalogueUpdateTime – время последнего изменения реквизитов организации или структуры организации.