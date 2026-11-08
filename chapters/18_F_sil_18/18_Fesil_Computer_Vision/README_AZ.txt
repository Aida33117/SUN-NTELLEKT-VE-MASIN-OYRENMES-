MDU — Fəsil 18. Kompüter görməsinin nəzəri əsasları və təsvirlərin emalı

Fayllar:
- index.html: interaktiv veb kitab. Faylı Chrome, Edge və ya Firefox brauzerində açın.
- MDU_Fesil_18_Computer_Vision_Colab.ipynb: Google Colab/Jupyter notebook. Google Colab-da File > Upload notebook ilə yükləyin.
- README_AZ.txt: bu təlimat.

Veb kitab internet olmadan açılır; xarici rəsmi sənəd linkləri internet tələb edir.
Colab notebook üçün internet, Google hesabı və yüklənəcək şəkil/video faylı lazımdır.
GPU seçimi Colab hesabı və resurs əlçatanlığından asılıdır.

Video üzrə YOLO nümunəsi əvvəlcədən öyrədilmiş modeldən inference edir; bu, tələbənin öz datasetində model təlimi ilə eyni deyil.
Öz obyekt siniflərinizi tanıtmaq üçün etiketlənmiş dataset, train/validation/test bölgüsü və ayrıca model təlimi aparılmalıdır.
Colab uzaq serverdir; source=0 lokal USB kameranı birbaşa görməyə bilər.

Təhlükəsizlik və etika:
- Yalnız istifadə hüququ olan şəkil/video və datasetlərdən istifadə edin.
- İnsan görüntüləri üçün razılıq, məxfilik və saxlanma müddətini nəzərə alın.
- Kamera və enerji qurğularını uyğun elektrik standartlarına əsasən qoşun.

Yenilənmiş versiya:
- Kod bloklarının kontrastı düzəldilib; kodu köçürmə düymələri əlavə edilib.
- Ultralytics-in avtobus demo fotosu üzərində real inference nümunəsi əlavə edilib.
- OpenCV klassik emalı ilə YOLO semantik aşkarlanmasının fərqi real eyni foto üzərində izah olunur.
- Real demo foto internet bağlantısı olduqda görünür; Colab hüceyrəsi şəkli yükləyib nəticəni annotasiya edir.
