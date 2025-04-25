# ABC-analizi
# ABC analizi nədir və niyə vacibdir?
Şirkətlər və analitiklər üçün qərarvermədə resursların düzgün bölüşdürülməsi olduqca vacibdir. ABC analizi ehtiyatların və ya məhsulların dəyərinə əsaslanaraq sinifləndirilməsini təmin edən sadə, amma güclü bir analiz üsuludur.
# ABC analizində kateqoriyalar:
A kateqoriyası: Vacib olan və buna görə də ciddi nəzarət tələb edən məhsullar.

B kateqoriyası: Daha az əhəmiyyət kəsb edən məhsullar, lakin buna baxmayaraq, orta səviyyəli nəzarətlə idarə olunmalıdır.

C kateqoriyası: Daha az əhəmiyyət kəsb edən və yalnız ən sadə nəzarət səviyyəsini tələb edən məhsullar.

Exceldə ABC analizi apardım. Məhsulların illik faiz bölgüsü və kommulativ faiz bölgüsünü hesabladım. Pareto Prinsipinə (80/20 qaydası) görə əgər məhsulun kommulativ faizi 80%-dən azdırsa , deməli o ən vacib məhsuldur → A kateqoriyaya aiddir. Əgər 80%-95% arasındadırsa, bu orta vaciblikdə məhsuldur → B kateqoriyaya aiddir
Əgər 95%-dən çoxdursa, deməli bu məhsul az əhəmiyyət kəsb edən məhsuldur → C kateqoriyaya aiddir
# =IFS(F2<0,8;"A";F2<0,95;"B";TRUE;"C") 
