Структуры данных
=================

Для описания структур используется понятие класса. Класс – объединение других классов или примитивных типов. Под примитивными типами понимается следующие типы:

 - enum – перечисление. Фиксированный набор значений. Сериализуется как строка, по написанию равная одному из значений;
 - int – целое число;
 - string – строка;
 - dateTime – дата и время. Сериализуется в строку согласно формату ISO 8601 (например: 2008-04-12T12:53Z);
 - byte[] – массив байтов. Сериализуется в base64-строку;
 - bool – логический тип.
 
 .. toctree::
   :name: structures
   :maxdepth: 2
   :caption: Структуры данных
   
	BankAccount <structures/BankAccount>
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
	DocumentSettings <structures/DocumentSettings>
	DocumentSettingsForPartner <structures/DocumentSettingsForPartner>
	ForeignAddressInfo <structures/ForeignAddressInfo>
	InboxMessageEntity <structures/InboxMessageEntity>
	InboxMessageMeta <structures/InboxMessageMeta>
	IPInfo <structures/IPInfo>
	MessageData <structures/MessageData>
	Organization <structures/Organization>
	OrganizationCatalogueInfo <structures/OrganizationCatalogueInfo>
	OrganizationInfo <structures/OrganizationInfo>
	OutboxMessageEntity <structures/OutboxMessageEntity>
	OutboxMessageMeta <structures/OutboxMessageMeta>
	Parties <structures/Parties>
	PartiesInfo <structures/PartiesInfo>
	Partner <structures/Partner>
	PartyAddress <structures/PartyAddress>
	PartyInfo <structures/PartyInfo>
	RussianAddressInfo <structures/RussianAddressInfo>
	RussianPartyInfo <structures/RussianPartyInfo>
	ULInfo <structures/ULInfo>
	UserInfo <structures/UserInfo>
	UsersInfo <structures/UsersInfo>