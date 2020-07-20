### TÜRKİYE İL ve İLÇELER LİSTESİ

basvuru.turkiye.gov.tr/ilceler.json üzerinden çekilen ve hazırlanan Türkiye il ve ilçeler listesi.

İlçelere erişmek için JSON dosyasını atadığınız değişkende ilgili ilin adını anahtar değer olarak kullanmak yeterli.

> with open('data.json') as json_file: <br />
data = json.load(json_file)

İstek:
> data['ADANA']

Yanıt:
> ['ALADAĞ', 'CEYHAN', 'ÇUKUROVA', 'FEKE', 'İMAMOĞLU', 'KARAİSALI', 'KARATAŞ', 'KOZAN', 'POZANTI', 'SAİMBEYLİ', 'SARIÇAM', 'SEYHAN', 'TUFANBEYLİ', 'YUMURTALIK', 'YÜREĞİR']

