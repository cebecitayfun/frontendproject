https://www.youtube.com/watch?v=Fa1uybpY2Fo
Elixir — Bootstrap Landing Page / How to make a responsive website using HTML CSS and Bootstrap
my purposes:
learn responsive structure
practice htmk css bootstrap 

notes for myself:
1.Bu örnekte, d-flex sınıfı, div elementini flex container haline getirir. İçerisindeki üç kutu (box sınıfına sahip) yatay olarak hizalanır.

Ek Flexbox Sınıfları
Bootstrap, flex container ve flex item'ların davranışını kontrol etmek için birçok ek sınıf sağlar. İşte bazı yaygın kullanılan sınıflar:

Hizalama ve Yönlendirme:

flex-row: Öğeleri yatayda sıralar (varsayılan).
flex-row-reverse: Öğeleri yatayda ters sırada sıralar.
flex-column: Öğeleri dikeyde sıralar.
flex-column-reverse: Öğeleri dikeyde ters sırada sıralar.
Hizalama (Aligning Items):

align-items-start: Öğeleri yukarıda hizalar.
align-items-center: Öğeleri ortada hizalar.
align-items-end: Öğeleri aşağıda hizalar.
Dağıtma (Justifying Content):

justify-content-start: Öğeleri başa hizalar.
justify-content-center: Öğeleri ortaya hizalar.
justify-content-end: Öğeleri sona hizalar.
justify-content-around: Öğeleri eşit aralıklarla hizalar.
justify-content-between: Öğeler arasında boşluk bırakır ve ilk öğeyi başa, son öğeyi sona hizalar.

2.align-items-center: Flexbox düzeni ile kullanılır ve flex container içindeki öğeleri dikey olarak ortalar.
text-center: Metin içeriklerini yatay olarak ortalar.
Her iki sınıf da belirli durumlar için kullanışlıdır, ancak farklı amaçlar için kullanılırlar. Flexbox düzeninde öğeleri dikey olarak ortalamak için align-items-center kullanılırken, metin içeriklerini yatay olarak ortalamak için text-center kullanılır.

3.(https://developer.mozilla.org/)css için güzel bir kaynak.

4.Tabii! Aşağıda .iconbox sınıfına uygulanan CSS kurallarını adım adım açıklayacağım:
<!-- bu yapı iconlar için yapılır mesela flex:none; iconun boyutunun değişmemesini sağlar -->
<!-- icon boyutu font size la değişiyor burada iconu remixicondan aldık git kodlarından yada siteye koduğum için tarayıcıdan inceyerek kaynak kodlarına bakarsan icon aslında font boyut ve rengini color ve font size ile değiştiriyoruz. -->

css
Kodu kopyala
.iconbox {
    width: 70px;
    height: 70px;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    background: rgba(var(--c-brand-rgb), 0.1);
    color: var(--c-brand);
    font-size: 34px;
    flex: none;
}
Ayrıntılı Açıklama
width: 70px;

Elementin genişliğini 70 piksel olarak ayarlar.
height: 70px;

Elementin yüksekliğini 70 piksel olarak ayarlar.
display: inline-flex;

Elementi bir inline-level flex container olarak ayarlar. Bu, elementin diğer inline elementler gibi davranmasını ve aynı zamanda içindeki çocuk elementlerin flexbox düzenine göre hizalanmasını sağlar.
align-items: center;

Flex container içindeki çocuk elementlerin dikey (cross axis) eksende ortalanmasını sağlar.
justify-content: center;

Flex container içindeki çocuk elementlerin yatay (main axis) eksende ortalanmasını sağlar.
background: rgba(var(--c-brand-rgb), 0.1);

Elementin arka plan rengini yarı saydam yapar. rgba fonksiyonu kullanılarak var(--c-brand-rgb) değişkeniyle belirtilen renkten yararlanılır ve 0.1 opaklık (transparency) değeri uygulanır. Bu, arka plan renginin %10 oranında opak olduğunu gösterir.
color: var(--c-brand);

Elementin içindeki metin veya ikonların rengini var(--c-brand) değişkenine ayarlar. Bu, genellikle marka rengi gibi tanımlanmış bir renk olabilir.
font-size: 34px;

Elementin içindeki metin veya ikonların font boyutunu 34 piksel olarak ayarlar.
flex: none;

Flexbox düzeninde, elementin esnemesini veya bükülmesini engeller. Bu, elementin kendi boyutlarında kalmasını sağlar ve esnek konteynerde büyümemesini veya küçülmemesini garanti eder.
Özet
Bu CSS kuralları, .iconbox sınıfına sahip bir elementin:

Sabit genişlikte (70px) ve yükseklikte (70px) olmasını,
İçerdiği öğelerin hem dikey hem yatay olarak ortalanmasını,
Yarı saydam bir arka plan rengine ve belirli bir metin/ikon rengine sahip olmasını,
Font boyutunun büyük (34px) olmasını,
Flex konteyner içinde sabit boyutlarda kalmasını sağlar.
Bu, genellikle ikon veya kısa metinler içeren kutular için kullanılan bir tasarım yaklaşımıdır. Flexbox düzeni sayesinde içeriği ortalamak ve sabit boyutlar belirlemek, tasarımın daha düzenli ve kullanıcı dostu görünmesini sağlar.





