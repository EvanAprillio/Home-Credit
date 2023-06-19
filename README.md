__Nama :__ Evan Aprillio Bursiano  
__Batch :__ RMT-019  
__Project Title :__ Modelling dengan menggunakan House Credit dataset tanpa menggunakan imputasi data dalam bentuk apapun
__Project Description :__ Saya pernah membaca bahwa pembuatan machine learning dengan menggunakan data sintetis(data buatan) dapat membuat model
menghasilkan nilai yang bias dan juga menghasilkan model yang bagus hanya dalam lingkungan lab saja, oleh karena itu di project kali ini saya ingin
mencoba membuat sebuah model dengan cara tidak ada imputasinya sama sekali, baik berupa imput nilai null atau oversampling.
Oleh karena itu dalam project ini saya melakukan pemodelan dengan data null yang di drop, dan ternyata yang di drop sangat banyak sehingga menghasilkan
data berkurang sebanyak lebih dari 70 persen. untuk model saya melakukannya dengan XGBoost,CatBooost,lgmBoost,dan GradientBoostingClassifier.
dan metric yang saya lihat adalah f1Score,ROC AUC, dan accuracy karena setelah saya melakukan undersampling, saya setting agar target yang bernilai 0 hanya 1.5 kali lebih besar dibandingkan dengan nilai 1
dan saat saya evaluasi nilai nilai dari ke 4 model tersebut hampir mirip semua yaitu   
__f1score sebesar 0.72-0.73,__  
__Accuracy sebesar 0.73-0.75__  
__ROC AUC sebesar 0.74-0.75__  
tetapi ada beberapa model yang lumayan overfitting.  
__Conclussion=__ Pemodelan tanpa menggunakan data inputasi di data ini dapat dilakukan meskipun mengorbankan nilai score yang lebih rendah
tetapi dengan pemilihan fitur yang lebih tepat, saya memperkirakan bahwa model akan dapat masuk ke nilai f1score sebesar 0.8
dan model yang dibuat dengan cara seperti ini mempunyai kelebihan akan mempunya peforma yang sama ketika di deploy atau diimplementasikan

