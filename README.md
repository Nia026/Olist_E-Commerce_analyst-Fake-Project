Tahapan Cleaning Setiap Dataset: 

1. Dataset Customers
   Pembersihan dataset dilakukan dengan beberapa step diantaranya:
   - Pengecekan data duplikat
   - Pengecekan missing value
   - Membuat mapping yang berisi kode negara dan nama negaranya
   - Mengubah value kolom "customer_state" dari setiap kode negara menjadi nama negara

2. Dataset Geolocation
   Pembersihan dataset dilakukan dengan beberapa step diantaranya:
   - Pengecekan data duplikat
   - Pengecekan missing value
   - Membuat mapping yang berisi kode negara dan nama negaranya
   - Mengubah value kolom "geolocation_state" dari setiap kode negara menjadi nama negara

3. Dataset Order
   Pembersihan dataset dilakukan dengan beberapa step diantaranya:
   - Pengecekan data duplikat
   - Pengecekan missing value
   - Melakukan standarisasi tipe data dan format pada kolom "order_purchase_timestamp", "order_approved_at", "order_delivered_carrier_date", "order_delivered_customer_date", "order_estimated_delivery_date"

4. Dataset Order Items
   Pembersihan dataset dilakukan dengan beberapa step diantaranya:
   - Pengecekan data duplikat
   - Pengecekan missing value
   - Melakukan standarisasi tipe data dan format pada kolom "shipping_limit_date"

5. Dataset Order Payments
   Pembersihan dataset dilakukan dengan beberapa step diantaranya:
   - Pengecekan data duplikat
   - Pengecekan missing value
   - Melakukan standarisasi format dengan menghapus tanda "_" pada kolom "payment_type" 

6. Dataset Order Review
   Pembersihan dataset dilakukan dengan beberapa step diantaranya:
   - Pengecekan data duplikat
   - Pengecekan missing value
   - Melakukan pengisian missing value pada kolom "review_comment_title" menjadi "No Comment Title"
   - Melakukan pengisian missing value pada kolom "review_comment_message" menjadi "No Comment Message"
   - Melakukan standarisasi tipe data dan format pada kolom "review_creation_date", "review_answer_timestamp"   

7. Dataset Product Category
   Pembersihan dataset dilakukan dengan beberapa step diantaranya:
   - Pengecekan data duplikat
   - Pengecekan missing value
   - Melakukan standarisasi format dengan menghapus tanda "_" pada kolom "product_category_name", "product_category_name_english" 

8. Dataset Products
   Pembersihan dataset dilakukan dengan beberapa step diantaranya:
   - Pengecekan data duplikat
   - Pengecekan missing value
   - Melakukan pengisian missing value pada kolom "product_category_name" menjadi "Unknown Category Name"
   - Melakukan pengisian missing value pada kolom "product_name_lenght", "product_description_lenght", "product_photos_qty" menjadi 0
   - Melakukan pengisian missing value pada kolom "product_weight_g", "product_length_cm", "product_height_cm", "product_width_cm" menjadi rata-rata value pada setiap kolom
   - Melakukan standarisasi tipe data pada kolom "product_name_lenght", "product_description_lenght", "product_photos_qty" menjadi integer
   - Melakukan standarisasi format dengan menghapus tanda "_" pada kolom "product_category_name"

9. Dataset Sellers
   Pembersihan dataset dilakukan dengan beberapa step diantaranya:
   - Pengecekan data duplikat
   - Pengecekan missing value
   - Membuat mapping yang berisi kode negara dan nama negaranya
   - Mengubah value kolom "seller_state" dari setiap kode negara menjadi nama negara