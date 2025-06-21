# Finding Optimum Threshold on MBB Filter Image Retrieval

This project represents an **exploratory study** complementing a Master's thesis, which introduced the novel **MBB (Murat Büşra Burcu) edge detection filter**. While its threshold was previously determined manually, this work investigates the efficacy of a **deep learning-based Image Retrieval** system for **automatically identifying its optimum threshold**.

By employing a **pretrained VGG16 model** for robust image feature extraction and using the **BIPED dataset** for evaluation, outputs from the MBB filter at different threshold settings are systematically compared with ground truth images. The primary objective is to pinpoint the threshold value that yields the highest fidelity and visual accuracy in edge detection, thereby demonstrating a potential pathway for automating and significantly improving the MBB filter's practical performance.

**Code Source:**

Some code structures and approaches in this project were inspired by or adapted from the following GitHub repository:

* [Content based image retrieval via feature extraction](https://github.com/bnsreenu/python_for_microscopists/tree/master/306%20-%20Content%20based%20image%20retrieval%E2%80%8B%20via%20feature%20extraction) by bnsreenu

<br>
<br>
<br>

## MBB Filtresi için Görsel Geri Çağırma ile Optimum Eşik Tespiti

Bu depo, Yüksek Lisans tezimi tamamlayan ve **MBB (Murat Büşra Burcu) kenar tespit filtresini** tanıtan **keşifsel bir çalışma** niteliğindedir. MBB filtresinin eşik değeri daha önce manuel olarak belirlenirken, bu çalışma **optimal eşik değerini otomatik olarak belirlemek** için **derin öğrenmeye dayalı bir Görüntü Geri Çağırma (Image Retrieval)** sisteminin etkinliğini araştırmaktadır.

Güçlü görüntü özellik çıkarma için **önceden eğitilmiş bir VGG16 modeli** kullanılarak ve değerlendirme için **BIPED veri seti** ile, MBB filtresinin farklı eşik ayarlarındaki çıktıları, zemin gerçekliği (ground truth) görüntüleriyle sistematik olarak karşılaştırılır. Birincil amaç, kenar tespitinde en yüksek doğruluk ve görsel hassasiyeti sağlayan eşik değerini belirlemek, böylece MBB filtresinin pratik performansını otomatikleştirmek ve önemli ölçüde iyileştirmek için potansiyel bir yol göstermektir.

**Kod Kaynağı:**

Bu projedeki bazı kod yapıları ve yaklaşımlar, aşağıdaki GitHub deposundan esinlenilmiştir:

* [Content based image retrieval via feature extraction](https://github.com/bnsreenu/python_for_microscopists/tree/master/306%20-%20Content%20based%20image%20retrieval%E2%80%8B%20via%20feature%20extraction) by bnsreenu

