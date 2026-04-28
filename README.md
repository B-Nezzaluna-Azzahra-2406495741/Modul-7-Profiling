# Modul 7 Profiling

## Test Plan 1

### CLI Test

![Test Plan 1 CLI Test](public/image/test_plan_1_cli_test.png)

After refactor:

![Test Plan 1 CLI Test Refactor](public/image/test_plan_1_cli_test_refactor.png)

### Summary Report

![Test Plan 1 Summary Report](public/image/test_plan_1_summary_report.png)

After refactor:

![Test Plan 1 Summary Report Refactor](public/image/test_plan_1_summary_report_refactor.png)

### Graph Results

![Test Plan 1 Graph Results](public/image/test_plan_1_graph_results.png)

After refactor:

![Test Plan 1 Graph Results Refactor](public/image/test_plan_1_graph_results_refactor.png)

### View Results in Table

![Test Plan 1 View Results in Table](public/image/test_plan_1_view_results_in_table.png)

After refactor:

![Test Plan 1 View Results in Table Refactor](public/image/test_plan_1_view_results_in_table_refactor.png)

### View Results Tree

![Test Plan 1 View Results Tree](public/image/test_plan_1_view_results_tree.png)

After refactor:

![Test Plan 1 View Results Tree Refactor](public/image/test_plan_1_view_results_tree_refactor.png)

## Test Plan 2

### CLI Test

![Test Plan 2 CLI Test](public/image/test_plan_2_cli_test.png)

After refactor:

![Test Plan 2 CLI Test Refactor](public/image/test_plan_2_cli_test_refactor.png)

### Summary Report

![Test Plan 2 Summary Report](public/image/test_plan_2_summary_report.png)

After refactor:

![Test Plan 2 Summary Report Refactor](public/image/test_plan_2_summary_report_refactor.png)

### Graph Results

![Test Plan 2 Graph Results](public/image/test_plan_2_graph_results.png)

After refactor:

![Test Plan 2 Graph Results Refactor](public/image/test_plan_2_graph_results_refactor.png)

### View Results in Table

![Test Plan 2 View Results in Table](public/image/test_plan_2_view_results_in_table.png)

After refactor:

![Test Plan 2 View Results in Table Refactor](public/image/test_plan_2_view_results_in_table_refactor.png)

### View Results Tree

![Test Plan 2 View Results Tree](public/image/test_plan_2_view_results_tree.png)

After refactor:

![Test Plan 2 View Results Tree Refactor](public/image/test_plan_2_view_results_tree_refactor.png)

## Test Plan 3

### CLI Test

![Test Plan 3 CLI Test](public/image/test_plan_3_cli_test.png)

After refactor:

![Test Plan 3 CLI Test Refactor](public/image/test_plan_3_cli_test_refactor.png)

### Summary Report

![Test Plan 3 Summary Report](public/image/test_plan_3_summary_report.png)

After refactor:

![Test Plan 3 Summary Report Refactor](public/image/test_plan_3_summary_report_refactor.png)

### Graph Results

![Test Plan 3 Graph Results](public/image/test_plan_3_graph_results.png)

After refactor:

![Test Plan 3 Graph Results Refactor](public/image/test_plan_3_graph_results_refactor.png)

### View Results in Table

![Test Plan 3 View Results in Table](public/image/test_plan_3_view_results_in_table.png)

After refactor:

![Test Plan 3 View Results in Table Refactor](public/image/test_plan_3_view_results_in_table_refactor.png)

### View Results Tree

![Test Plan 3 View Results Tree](public/image/test_plan_3_view_results_tree.png)

After refactor:

![Test Plan 3 View Results Tree Refactor](public/image/test_plan_3_view_results_tree_refactor.png)

## Hasil Profiling

### All Student

Before refactor:

![All Student Before Refactor](public/image/all-student_before_refactor.png)

After refactor:

![All Student After Refactor](public/image/all-student_after_refactor.png)

### Highest GPA

Before refactor:

![Highest GPA Before Refactor](public/image/highest-gpa_before_refactor.png)

After refactor:

![Highest GPA After Refactor](public/image/highest-gpa_after_refactor.png)

### All Student Name

Before refactor:

![All Student Name Before Refactor](public/image/all-student-name_before_refactor.png)

After refactor:

![All Student Name After Refactor](public/image/all-student-name_after_refactor.png)

## Conclusion

Saya membandingkan hasil JMeter sebelum dan sesudah refactor dengan fokus pada average response time, karena metrik ini paling mudah dibandingkan antar pengukuran.

### All Student

Sebelum refactor, endpoint all-student memiliki average response time 52855 ms. Setelah refactor, average response time turun menjadi 2282 ms. Persentase peningkatan dari sisi response time adalah sekitar 95.7% lebih cepat. Ini berarti endpoint all-student mengalami improvement yang jelas setelah optimasi.

### All Student Name

Sebelum refactor, endpoint all-student-name memiliki average response time 1670 ms. Setelah refactor, average response time menjadi 89 ms. Persentase peningkatan dari sisi response time adalah sekitar 94.7% lebih cepat. Ini berarti endpoint all-student-name mengalami improvement yang jelas setelah optimasi.

### Highest GPA

Sebelum refactor, endpoint highest-gpa memiliki average response time 44 ms. Setelah refactor, average response time menjadi 21 ms. Persentase peningkatan dari sisi response time adalah sekitar 52.3% lebih cepat. Ini berarti endpoint highest-gpa mengalami improvement yang cukup terlihat setelah optimasi.

### Kesimpulan Akhir

Secara umum, hasil JMeter menunjukkan improvement pada semua endpoint setelah refactor. Endpoint all-student mengalami peningkatan paling besar, sedangkan all-student-name dan highest-gpa juga tetap menunjukkan perbaikan yang cukup jelas. Jadi, optimasi yang dilakukan berhasil meningkatkan performa aplikasi, walaupun besar peningkatannya berbeda pada tiap endpoint.

## Reflection

1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?  
   JMeter adalah tools untuk performance testing yang menguji aplikasi dari perspektif end-user dengan mensimulasikan multiple concurrent users dan mengukur response time, throughput, dan load handling capacity. Sedangkan IntelliJ Profiler adalah tools untuk profiling yang menganalisis kode dari dalam, menunjukkan method execution time, memory usage, dan CPU consumption pada level kode. Kedua tools ini saling melengkapi, profiler membantu menemukan bottleneck spesifik di kode (seperti N+1 queries atau inefficient loops), sedangkan JMeter memverifikasi apakah optimasi tersebut memberikan dampak pada user experience level.

2. How does the profiling process help you in identifying and understanding the weak points in your application?  
   Profiling dengan IntelliJ Profiler membantu mengidentifikasi weak points dengan menunjukkan berapa lama setiap method mengkonsumsi waktu execution. Dari program ini, saya bisa melihat bahwa method getAllStudentsWithCourses() menghabiskan waktu terlalu lama karena melakukan multiple queries ke database (N+1 problem), sedangkan joinStudentNames() tidak efisien karena menggunakan string concatenation dalam loop. Profiler memberikan visibility yang jelas tentang mana bagian kode yang paling boros resources, sehingga optimasi bisa difokuskan ke area yang paling berdampak.

3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?  
   Menurut saya, IntelliJ Profiler efektif untuk mengidentifikasi bottleneck. Dalam kasus ini, profiler berhasil menunjukkan dengan jelas bahwa tiga method tertentu adalah penyebab utama lag dalam aplikasi. Visualisasi data execution time yang disajikan profiler memudahkan saya memahami flow kode dan menemukan pain points. Selain itu, profiler juga bisa menunjukkan memory allocation dan garbage collection patterns, yang memberikan insight mendalam tentang runtime behavior aplikasi.

4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?  
   Salah satu tantangan utama saya adalah memastikan kondisi testing yang konsisten antara profiling dan JMeter testing, karena perbedaan environment atau data dapat mempengaruhi hasil. Untuk mengatasi ini, saya memastikan testing dilakukan dengan dataset yang sama dan kondisi load yang terkontrol. Challenge lain adalah menginterpretasi hasil profiling dengan benar – tidak semua method dengan execution time tinggi berarti perlu dioptimasi jika hanya dipanggil sekali. Saya mengatasi ini dengan fokus pada method yang dipanggil berkali-kali atau memiliki O(n) complexity yang tinggi, seperti yang terjadi dengan database queries dalam loop.

5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?  
   Keuntungan utamanya adalah visibility penuh terhadap runtime behavior aplikasi. Profiler menunjukkan exact bottleneck tanpa perlu guesswork, sehingga optimasi bisa lebih targeted dan efektif. Dalam program ini, profiling membantu saya menemukan N+1 query problem dan inefficient string operations yang tidak akan terdeteksi dengan mudah hanya dengan code review. Selain itu, profiler juga membantu memverifikasi bahwa optimasi yang dilakukan benar-benar mengurangi execution time, bukan hanya theoretical improvements.

6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?  
   Ketika ada inkonsistensi antara profiling dan JMeter, saya coba pahami akar permasalahannya, bisa berupa perbedaan disebabkan oleh perbedaan dataset, warm-up period, atau JVM optimization yang berbeda antara dua testing. Dalam program ini, misalnya, beberapa endpoint di JMeter testing menunjukkan performa yang tidak sesuai ekspektasi dari profiling, yang kemungkinan disebabkan oleh load testing effects atau database connection pooling behavior. Untuk mengatasi ini, saya repeat testing dengan kondisi yang lebih terkontrol dan fokus pada trend improvement.

7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?  
   Strategi optimasi yang saya terapkan adalah menggerakkan logic ke database level dengan JPQL queries yang lebih efisien (misalnya join-fetch untuk menghindari N+1 problem) daripada application-level processing. Selain itu, menggunakan built-in Java features seperti Stream API dan Collectors untuk operasi collection yang lebih efisien. Kemudian saya memanfaatkan ORM features seperti @Query annotations untuk custom queries yang optimal. Untuk memastikan tidak ada functional changes, saya selalu memverifikasi bahwa output dari method yang dioptimasi tetap sama, baik dilihat dari return value maupun side effects. Dalam kasus ini, semua refactoring hanya mengubah implementation detail tanpa mengubah contract method, sehingga tidak perlu mengupdate calling code.
