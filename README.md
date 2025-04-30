# Telecom Customer Churn
*Memprediksi apakah seorang customer akan berhenti berlangganan atau tidak.*

Customer (pelanggan) dalam perusahaan berperan sebagai salah satu sumber pendapatan utama dan faktor keberhasilan perusahaan. Perlu dicari tahu apa saja hal-hal yang berpotensi mengakibatkan customer berhenti berlangganan (customer churn).

### Deskripsi Dataset
Dataset menggambarkan customer pada suatu perusahaan telekomunikasi, yang terdiri atas:
- Karakteristik customer (Gender, SeniorCitizen, Partner, dan Dependents)
- Service/Layanan yang digunakan (PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies)
- Paket langganan yang dipilih (Contract, PaymentMethod, PaperlessBilling)

Setiap baris merepresentasikan karakteristik customer dengan layanan dan paket yang dipilihnya. Terdapat total 7,043 customer dan 21 atribut. 

### Problem Statement
Dari total 7,043 customer, terdapat 1,869 customer (26.54%) yang memutuskan untuk berhenti berlangganan. 

### Goals and Objectives
Akan dilakukan eksplorasi untuk mengetahui apa saja yang berpengaruh terhadap keputusan customer untuk berhenti berlangganan.
- Menganalisa apa saja yang mempengaruhi customer untuk tetap bertahan atau berhenti
- Membangun model untuk memprediksi apakah customer akan berhenti berlangganan atau tidak (metrics: recall dan ROC AUC)
