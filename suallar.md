1. translator ve assembler nedir?
- Translator programçının programlama dili vasitəsi ilə yazdığı qurulmuş bir algoritmi təsvir edən mətni kompüterin anlayacağı dilə çevirən bir vasitədir.
- Assembler aşağı səviyyəli programlaşdırma dilidir. Aşağı səviyyəli programlaşdırma dili dedikdə daha çox insan dilinə yox, kompüter dilinə yaxın olması başa düşülür. Assembler əmrləri maşın kodları şəklində verir. Assembler vasitəsi ilə çox səmərəli və kompakt programlar yazmaq mümkündür. Bu dildə yazılan programlar yaddaşda daha az yer tutur və daha sürətlə işləyirlər. Assemblerdən daha çox program-driverlərin, sistem əlavələrinin yazılmasında istifadə olunur. Bu programlama dilindən adətən peşəkar programçılar istifadə edirlər.

2. Reqem ve ededlerin 2 li say sistemine tercume olunmasi bilirik.Bes hərflər ve simvollar binary code-a nece tercume olunur?
- Mətin tipli informasiyanın kodlaşdırılması bir neçə standartlara əsaslanaraq yerinə yetirilir. Əsas standard ASCII (American Standard Code or Information Interchange) olmuşdur. ASCII-də hər bir simvol üçün xüsusi kod verilmişdir. ASCII-də ümumi 256 kod vardır. Hər bir kod yaddaşda 1 bayt (8 bit) yer tutur.

3. Butun proqramlasdirma dillerinde ortaq istifade olunan data tipleri hansilardir ve qisaca izahatini yazin.
- Data tiplər programlaşdırmada verilənlərin tiplərin müəyyən edilməsi, bu verilənlərin üzərində aparıla bilən əməliyyatların müəyyən edilməsi və bu qiymətləri yaddaşda saxlanılma xarakteristikasını müəyyənləşdirir.
- İnteger - tam ədədləri müəyyən edir.
- floating point (real) - kəsr ədədləri müəyyən edir
- string - ardıcıl simvollar
- Boolean - məntiqi (doğru və ya yanlış)
- nothing - boşluq

4. Type Conversion ya da Type Casting nədir? Hansı hallarda ehtiyac duyulur? 
- Type Casting bir type-ın buna uyğun olan başqa bir type kimi istifadəsidir. Məsələn float, int, double type olaraq ədəddir. Biz int type-ı float və ya double olaraq istifadə edə bilsək bu Type Casting-dir. Bəs biz float type reqemini int type reqemi kimi yaza bilərikmi? Yaza bilərik, amma float kəsirli bir rəqəm olduğuna görə int type nan yazarsaq int type-ı bu kəsirli ədədi bizə yuvarlaqlaşdırıb verəcək. Qısaca bir-birinin yerinə istifadə edilə bilən dəyişənlərin istifadəsi Casting-dir.
- Bir-birinin yerinə birbaşa istifadə edə bilmədiyimiz dəyişənləri istifadə edə biləcəyimiz hala gətirilmə prosesi isə Type Conversion deyilir. 
Məsələn: 20 bir rəqəmdir və biz onu int =20; kimi yazmalıyıq. string= "20"; kimi yazdığımızda isə komputer 20 ədədini ədəd kimi deyil də mətn kimi qəbul edir.
  
5. Operator precedence nədir və əhəmiyyətini izah edin.
- Operator precedence operatorların bir-birinə nisbətən üstünlüyünü müəyyən edir və üstün olan əmri birici yerinə yetirir.
Məsələn: 2+3*5 burada cavab 25 deyil 17 dir. Çünki "*"(vurma) operatoru "+" (toplama) operatoruna nisbətən üstünlüyə sahibdir. Və üstün olan operatoru birinci yerinə yetirir.

6. Automatic Type Conversion ve Type Conversion Methodlar arasındakı fərqləri izah edin.
Avtomatic Type Conversion Type Conversionda bizim yerinə yetirdiyimiz prosesləri avtomatik yerinə yetirir.