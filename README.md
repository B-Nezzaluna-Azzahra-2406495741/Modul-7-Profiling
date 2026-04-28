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

## Kesimpulan Pengujian JMeter

Saya membandingkan hasil JMeter sebelum dan sesudah refactor dengan fokus pada average response time, karena metrik ini paling mudah dibandingkan antar pengukuran.

### All Student

Sebelum refactor, endpoint `all-student` memiliki average response time `52855 ms`. Setelah refactor, average response time turun menjadi `2282 ms`. Persentase peningkatan dari sisi response time adalah sekitar `95.7%` lebih cepat. Ini berarti endpoint `all-student` mengalami improvement yang sangat jelas setelah optimasi.

### All Student Name

Sebelum refactor, endpoint `all-student-name` memiliki average response time `1670 ms`. Setelah refactor, average response time menjadi `89 ms`. Persentase peningkatan dari sisi response time adalah sekitar `94.7%` lebih cepat. Ini berarti endpoint `all-student-name` mengalami improvement yang jelas setelah optimasi.

### Highest GPA

Sebelum refactor, endpoint `highest-gpa` memiliki average response time `44 ms`. Setelah refactor, average response time menjadi `21 ms`. Persentase peningkatan dari sisi response time adalah sekitar `52.3%` lebih cepat. Ini berarti endpoint `highest-gpa` mengalami improvement yang cukup terlihat setelah optimasi.

### Kesimpulan Akhir

Secara umum, hasil JMeter menunjukkan improvement pada semua endpoint setelah refactor. Endpoint `all-student` mengalami peningkatan paling besar, sedangkan `all-student-name` dan `highest-gpa` juga tetap menunjukkan perbaikan yang cukup jelas. Jadi, optimasi yang dilakukan berhasil meningkatkan performa aplikasi, walaupun besar peningkatannya berbeda pada tiap endpoint.
