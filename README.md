# CNN İle Kaykay ve Bisiklet Görsellerini Sınıflandırma
İki sınıflı CNN tabanlı bir derin öğrenme problemi çözülmüştür. Problem 4 adımda değerlendirilmiştir.

A) **İLK ADIM:** Normal olarak CNN-maxpool olayı sürecinde 30 epoch seçilerek uygulandı. 
		
B) **İKİNCİ ADIM:** Data augmentation yöntemi ile deney tekrarlandı.

C) **ÜÇÜNCÜ ADIM:** Drop-out ile deney tekrarlandı yani: augmentation + drop_out etkisi gözlendi. 

D) **DÖRDÜNCÜ ADIM:** Overfit eden nokta gözlendiği için train süreci erken bir EPOCH’ta kesilerek deney tekrarlandı.    
	
