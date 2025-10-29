# chocolate_sales_analysis

trabalho hodi analysa chocolate sales data husi mateira LPA semestre 6

wainhira ita atu tama ba iha descriptiv, diagnostic, predictive dan prescriptive analyse ita tenke liu  ona sesaun data preprocessing.

no tuir mai mak parte sira ne'ebe mak ita presiza hodi halo iha kada tipo analyse mak:
 😥descriptive analyse - objetivo atu hatene "saida mak akontese"  iha data ne'e rasik.

    data preprocessing minimal liu ona 
        muda amount sira ba hotu iha int ka ba iha float
        date troka ba iha datetime atu nune'e bele analisis tren(mak cara atu haree perubahan ka perkembangan sesuatu dari waktu ke waktu)
        product, country and sales person bele nafatin sai string tamba descriptive analysis bele show frekuensi count.

        Contoh preprocessing untuk Descriptive Analysis:
        df['Amount'] = pd.to_numeric(df['Amount'], errors='coerce')
        df['Date'] = pd.to_datetime(df['Date'])

😒diagnostic analyse - objetivu atu hatene "kenapa sesuatu terjadi".
    ita presiza halo mak:
        preprocessing atu hanesan mos ho descriptive analyse
        bele aumenta encoding atu kategori se hakarak analiza statistic ka korelasi
            ex: Product di-encode untuk korelasi numerik atau model statistik.

🍫predictive analyse - objetivo mak saida mak sei akontese iha futuru.
🥰prescriptive analyse - fo recomendasaun terbaik based on data no prediksaun.

overview
🧱 Urutan logika dalam Data Science (dari dasar ke mahir)

Data Preprocessing → Menyiapkan data (ini langkah pertama dan paling penting).

Descriptive Analysis → Mengetahui isi data.

Diagnostic Analysis → Menemukan pola & penyebab.

Predictive Analysis → Menggunakan Machine Learning untuk memprediksi.

Prescriptive Analysis → Mengambil keputusan terbaik dari hasil prediksi.

