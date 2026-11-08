FƏSİL 13 — NEYRON ŞƏBƏKƏLƏRİNİN ÖYRƏDİLMƏSİ VƏ RİYAZİ MEXANİZMLƏRİ

İSTİFADƏ
1. ZIP arxivini çıxarın.
2. index.html faylını Chrome, Edge və ya Firefox brauzerində açın.
3. Sol mündəricatla bölmələrə keçin.
4. Loss, BCE, gradient, Gradient Descent, learning rate, parametr yenilənməsi və batch hesablayıcılarında qiymətləri dəyişin.
5. 13.14-də epoch və overfitting sürgülərini dəyişərək qrafikin necə yeniləndiyini izləyin.
6. Özünü yoxlama suallarını cavablandırın və nəticəni yoxlayın.

PYTHON MÜHİTİ
Python kodlarını brauzerdə deyil, Google Colab və ya Jupyter Notebook-da icra edin.
Əsas kitabxanalar:
pip install numpy matplotlib scikit-learn

TensorFlow:
pip install tensorflow

PyTorch:
https://pytorch.org/get-started/locally/

LABORATORİYA QEYDİ
XOR nümunəsi tədris məqsədlidir. Fərqli random seed, learning rate və başlanğıc çəkilər nəticəni dəyişə bilər. Təcrübələri bir neçə dəfə təkrarlamaq və loss trayektoriyasını təhlil etmək tövsiyə olunur.

YENİLƏNMİŞ DİAQRAMLAR
Bu versiyada neyron şəbəkəsinin real qat quruluşunu göstərən əlavə rəngli SVG diaqramları yerləşdirilib:
- 3 giriş, 4 gizli neyron və 2 çıxışlı tam əlaqəli MLP arxitekturası;
- eyni şəbəkədə Forward Propagation və Backpropagation istiqamətləri;
- Chain Rule üçün neyronun hesablama qrafiki;
- giriş vektoru və çəkilər matrisinin ölçü əlaqəsi;
- çoxqatlı şəbəkədə Dropout mexanizmi;
- optimizator addımlarının loss səthində konseptual trayektoriyası.
Diaqramlar HTML daxilində SVG kimi saxlanılır; ayrıca şəkil faylı tələb etmir. Ekran ölçüsünə uyğunlaşır.
