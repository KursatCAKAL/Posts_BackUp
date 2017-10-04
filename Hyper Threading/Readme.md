
<h3>Hyper-Threading Nedir?</h3><br><br>  
	Hyper-Threading işlemciyi daha etkili bir şekilde kullanarak her bir çekirdek için daha fazla iş parçacığının daha performanslı olarak yürütülmesini sağlayan Intel firması tarafından üretilmiş bir teknolojidir.  HT teknolojisi, bu teknolojiyi destekleyen işlemci, işletim sistemine ve donanımsal niteliklere sahip bilgisayar sistemlerini gerektirir. <br>
<br><br>
<h4>Hyper-Threading Çalışma Prensibi Nedir?</h4><br><br>
	Intel HT teknolojisi işlemcideki core sayısını mantıksal olarak 2 katına çıkmasını sağlar. Yani tek çekirdekli bir işlemci HT teknolojisi ile mantıksal olarak 2 çekirdekli bir işlemci gibi çalışmasını sağlar. Bu teknoloji ile nasıl bir çekirdekli işlemci iki çekirdekli gibi çalışıyorsa, iki çekirdekli işlemci dört, dört çekirdekli işlemci de sekiz çekirdekli gibi çalışmaktadır. Fakat dikkat edilmesi gereken husus tek çekirdeğe sahip ve HT teknolojisi ile desteklenen bir işlemcinin ayrı ayrı 2 çekirdeği olan bir işlemci performansına ulaşamayacağıdır. Yani tek çekirdeği olan ve HT teknolojisi ile desteklenmiş bir işlemci iki çekirdeği olan ve HT teknolojisi ile desteklenmemiş bir işlemciye göre daha az performans sunar.<br><br>

<img src="https://raw.githubusercontent.com/KursatCAKAL/Posts_BackUp/master/Hyper%20Threading/HyperThreading_1.png"><br>
HT teknolojisi ile desteklenen bir işlemci, iki farklı iş parçasını eş zamanlı olarak aynı işlemci üzerinde işleyerek süreci tamamlayabilmektedir. İki farklı işlem yapmak istendiğinde ikinci işlemin gerçekleşmesi için birinci işlemin tamamlanması gerekirken HT teknolojisi ile bu problem ortadan kaldırılarak bir işlemci içinde iki farklı komut zinciri işlenebilir hale gelmiştir.<br><br>
Hyper-Threading Ne Değildir?<br><br>
	Hyper-Threading teknolojisi ile ilgili bir çok yerde aynı anda birden fazla işi yapabilmemize olanak sağlar şeklinde ifadeler yer almaktadır. HT teknolojisi multitasking olarak bilinen aynı anda birden fazla görev, uygulama ve bilgisayar programı çalıştırabilmesini sağlayan teknoloji ile karıştırılmamalıdır.<br><br>

<img src="https://raw.githubusercontent.com/KursatCAKAL/Posts_BackUp/master/Hyper%20Threading/HyperThreading_2.png"><br>
Multitasking teknolojisinin desteklendiği bir işlemcide arka planda işlemci birden fazla işi aynı anda yapmamasına rağmen kullanıcının algılayamayacağı kadar küçük zaman dilimleri içerisinde birden fazla işlem birbiri arasında anahtarlamalar gerçekleştirilerek kullanıcıya sanki bütün işlemler aynı anda çalışıyormuş gibi hizmet sunulur. Fakat aslında işlemci aynı anda birden fazla işlem yapamamaktadır. 
<br><br>
Hyper-Threading teknolojisinde ise bu durum multitasking’den tamamen farklı olarak birden fazla komut dizini işlemcinin sahip olduğu core sayısına göre aynı anda işletilebilmektedir. HT’in multitasking’den farkı işlemcinin iki komut dizisini gerçekten eş zamanlı olarak işleyebiliyor ve sonuç üretebiliyor olmasıdır.<br><br>
Hyper-Threading Sistemi ile Örnekler<br><br><br>
Server uygulamalarında performans?<br><br>
Hyper-Threading ile sanal sunucu üzerinde çalışan uygulamalar için de performans artışı sağlanabilir. Örneğin Amazon gibi büyük bir e-ticaret sitesinden kat kat daha az veri ve işlem karmaşası içeren basit bir blog sitesinin yanıt süresi bu büyük e-ticaret sitesine göre çok daha fazla oluyor. Bunun HT teknolojisi dışında birden fazla web teknolojisi özelliği ile alakası olabilir. Fakat sonuç olarak bir web uygulamasının barındırıldığı server ve sunucunun kendine ait donanımsal nitelikleri mevcuttur. Böylelikle internet uygulamalarında yanıt süresi performansı arttırılabilir.<br>
Görüntü-Rendering uygulamarında performans?<br><br>
	Dijital ortamdaki görüntü ve videoların düzenlenmesi ile ilgili uygulamalarda render ve diğer düzenleme işlemleri için çok fazla iş parçacığı olduğu için işlemci için oldukça ağır bir yüktür. Bu tip uygulamalarda da yine Hyper-Threading teknolojisi oldukça büyük bir performans kazancı sağlar.<br><br>

Oyun teknolojilerinde performans? <br>
	Bilgisayar oyunları için gerek server üzerinde gerek ise local bilgisayar üzerinde çalışan oyunlar için oldukça büyük bir iş parçacığının işlenerek çıktı alınması söz konusudur. Yine bu tip uygulamalarda Hyper-Threading teknolojisi oldukça büyük bir performans kazancı sağlar. Bu bilgiler Kaynak 5 yardımıyla özümsenmiştir.<br><br>
	Sonuç<br>
Hyper-Threading teknolojisi sayesinde normal bir işlemci ile elde edebileceğimiz performans değerinin çok daha üstünü elde edebiliyoruz. Daha fazla işi aynı anda kesintiye uğramadan yürütebilir ve eş zamanlı gerçekleşen işlem sayısını arttırarak verimlilik sağlanabilir. Hyper-Threading teknolojisi kullanan ve kullanmayan iki bilgisayarın üzerinde yapılan analiz kaynaklardan 7 nolu kaynakta büyük bir performans farkı gözetilerek incelendi. <br>



<img src="https://raw.githubusercontent.com/KursatCAKAL/Posts_BackUp/master/Hyper%20Threading/HyperThreading_3.png">
<br><br>
Hyper-Threading her zaman tamamen fayda sağlayan bir teknoloji olmaz dez avantajları vardır. Bu dezavantajlar işlemcinin çalışma prensibinden kaynaklanan fazla ısı çıkışı ve fazla güç tüketimi gibi sebeplerden kaynaklanan maliyet sorunlarıdır.Bu bilgiler Kaynak 8 yardımıyla özümsenmiştir.<br><br>

Ayrıca SQL Server gibi thread-intensitive çalışan uygulamalarda Hyper-Threading teknolojisi her zaman beklendiği gibi performans artışı sağlamayabilir. Çünkü çok fazla işlem parçacığı içermesinin yanı sıra aynı zamanda işlemcideki core’ların iş parçalarını optimize etmesi bu tip uygulamalarda pek etkili olmamaktadır. Bu sebepten bu tip uygulamalar için HT teknolojisinin aktifleştirilmesi önerilmez. 


