FƏSİL 7 — REQRESSİYA MODELLƏRİ VƏ PROQNOZLAŞDIRMA
Mingəçevir Dövlət Universiteti — Riyaziyyat və İnformasiya Texnologiyaları fakültəsi

İSTİFADƏ
1. ZIP arxivini çıxarın.
2. index.html faylını Chrome, Edge və ya Firefox brauzerində açın.
3. Bölmələrə sol menyudan keçin. İnteraktiv OLS kalkulyatoru, proqnoz kalkulyatorları,
   polinomial və regularizasiya qrafikləri, metrik kalkulyatoru, vizuallaşdırma və quiz
   brauzerdə işləyir.
4. Python kod pəncərələrindəki nümunələr Google Colab və ya Jupyter Notebook-da icra edilir.

LABORATORİYA
Dataset: scikit-learn Diabetes dataset (442 müşahidə, 10 giriş xüsusiyyəti).
Quraşdırma: pip install numpy pandas matplotlib scikit-learn
Dataset real tədqiqat verilənidir, lakin tədris nümunəsi kimi istifadə olunur;
klinik qərar və fərdi diaqnostika üçün nəzərdə tutulmayıb.

METODİK QEYDLƏR
- İnteraktiv əmsal, polinom və regularizasiya qrafiklərinin bir qismi konseptual
  simulyasiyadır; elmi nəticə kimi deyil, anlayışı izah etmək üçün verilib.
- Laboratoriyada faktiki model scikit-learn ilə qurulur.
- Test dəstindən hiperparametr seçmək olmaz; model seçimi train/validation və ya
  cross-validation vasitəsilə aparılmalıdır.
- Zaman sırası verilənlərində zaman ardıcıllığını qoruyan bölünmə tətbiq edilməlidir.
