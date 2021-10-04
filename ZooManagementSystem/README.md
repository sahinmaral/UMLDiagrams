### Ödev - Hayvanat Bahçesi

Bir hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için bir sistem tasarlıyorsunuz.


<ul>
Hayvanlar:

<li>
Atlar (atlar, zebralar, eşekler vb.),
</li>

<li>
Kedigiller (kaplanlar, aslanlar vb.),
</li>

<li>
Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.
</li>

<li>
Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.
</li>

<li>
tür adı, ağırlığı, yaşı vb.
</li>

<li>
Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()
</li>

<li>
Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()
</li>

</ul>

Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.



Polimorfizm modelini kullanarak, yukarıda açıklanan durumu ele almak için bir sınıf diyagramı tasarlayın.