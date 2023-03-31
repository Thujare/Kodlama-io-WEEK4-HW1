# Kodlama-io-WEEK4-HW1

Python’da Decorator Ne İşe Yarar?

Python ortamında decorator tanımlamak için örnek kod. Amaç, fonksiyon tanımlayan fonksiyon oluşturmak ve daha sonra bu fonksiyonu her çağırdığımızda bir değişkene yeni fonksiyon tanımlamış olmak. Burada, kullanıcının kendi fonksiyonunu tanımlaması dahi mümkün hale geliyor. exec ile(evet, biraz riskli bir fonksiyon) kullanıcıdan aldığımız bir fonksiyonu bu şekilde örneklemek mümkün. Tek fonksiyon için çok geremese de artan sayılara cevap verecek nitelikte. Daha önce Flask framworkünde decoratorlere rastlamıştım ama şimdi anlamak nasip oldu. Bu kodun daha ilkel bir haline dökümantasyonun en başındaki tutorial kısmında rastlamıştım. Bir de @ ile bir kullanımı var. Etkin kullandığımda onun örnek programını da eklemeyi düşünüyorum. Umarım işinize yarar.


@pytest.mark.timeout: dekoratörü; yapılan test uygulamasının önceden belirlenen bir zaman içerisinde bitirilmesi gerektiğini ifade eder.

@pytest.mark.skip: dekoratörü; yapılan test çalışmasında testin çalıştırılmadan atlanılmasını sağlar.

@pytest.mark.parametrize; dekoratörü; testin farklı değişkenler ile kullanabileceğini ifade etmektedir.

@pytest.mark.xfail; dekoratörü; yapılan testin sonucunun başarısız olmasının öngörüldüğü durumlarda kullanılır.

@pytest.mark.dependency: dekoratörü; bir testin başarılı olmasının diğer teste bağlı olması durumunu belirtir.

@pytest.mark.flaky: dekoratörü, testin öngörülemeyen sebeplerden dolayı bazen başarısız olabileceği durumu ifade eder.
