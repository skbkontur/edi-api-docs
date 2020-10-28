Структуры данных
=================

Для описания структур используется понятие класса. Класс – объединение других классов или примитивных типов. Под примитивными типами понимается следующие типы:

 - enum – перечисление: представляет собой фиксированный набор значений, сериализуется как строка, по написанию равная одному из значений,
 - int – целое число,
 - string – строка,
 - dateTime – дата и время: сериализуется в строку согласно формату ISO 8601 (например: 2008-04-12T12:53Z),
 - byte[] – массив байтов: cериализуется в base64-строку,
 - bool – логический тип,
 - guid - уникальный идентификатор: сериализуется в строку согласно формату "xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", где x - шестнадцатиричное число в нижнем регистре (например: 6f9619ff-8b86-d011-b42d-00cf4fc964ff).
 
 .. toctree::
   :name: structures
   :maxdepth: 2
   :caption: Структуры данных
   
	AcceptedRevocationInfo <structures/AcceptedRevocationInfo>
	BankAccount <structures/BankAccount>
	BasicMessageMeta <structures/BasicMessageMeta>
	BoxDocumentSettings <structures/BoxDocumentSettings>
	BoxesInfo <structures/BoxesInfo>
	BoxEvent <structures/BoxEvent>
	BoxEventBatch <structures/BoxEventBatch>
	BoxEventContent <structures/BoxEventContent>
	BoxInfo <structures/BoxInfo>
	BoxSettings <structures/BoxSettings>
	ContactInformation <structures/ContactInformation>
	DiadocUrls <structures/DiadocUrls>
	DocumentDetails <structures/DocumentDetails>
	DocumentId <structures/DocumentId>
	DocumentSettings <structures/DocumentSettings>
	DocumentSettingsForPartner <structures/DocumentSettingsForPartner>
	ForeignAddressInfo <structures/ForeignAddressInfo>
	GeoCoordinates <structures/GeoCoordinates>
	InboxMessageEntity <structures/InboxMessageEntity>
	InboxMessageMeta <structures/InboxMessageMeta>
	IPInfo <structures/IPInfo>
	MessageData <structures/MessageData>
	Organization <structures/Organization>
	OrganizationCatalogueInfo <structures/OrganizationCatalogueInfo>
	OrganizationInfo <structures/OrganizationInfo>
	OutboxMessageEntity <structures/OutboxMessageEntity>	
	PaidFeatureInfo <structures/PaidFeatureInfo>
	PaidPeriod <structures/PaidPeriod>
	Parties <structures/Parties>
	PartiesInfo <structures/PartiesInfo>
	Partner <structures/Partner>
	PartyAddress <structures/PartyAddress>
	PartyInfo <structures/PartyInfo>
    ProcessingTimes <structures/ProcessingTimes>
	RussianAddressInfo <structures/RussianAddressInfo>
	RussianPartyInfo <structures/RussianPartyInfo>
	ULInfo <structures/ULInfo>
	UserInfo <structures/UserInfo>
	UsersInfo <structures/UsersInfo>