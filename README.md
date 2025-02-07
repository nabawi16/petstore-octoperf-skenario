# petstore-octoperf-skenario

## Test Case Table

| No | Project | Issue Type | Test ID | Summary | Description | Assignee | Test Repository Path | Action | Data | Expected Result | Test Plan | Test Execution | Labels | Label2 |
|----|---------|------------|---------|---------|-------------|----------|----------------------|--------|------|----------------|----------|---------------|--------|--------|
| 1  | Repo | Feature | TC-001 | User Created / Add New data list petstore |  |  | Repo-TC-001 | 1. Login petstore sebagai User 2. Pilih 'Created / add New petstore' 3. Klik 'Create / Add New petstore' 4. Isi mandatory field pada form 'New data petstore' 5. Klik 'Save' | 1. Product ID 2. Name | 1. Berhasil menambahkan data petstore |  |  | Positive, petstore, created | Testing1 |
| 2  | Repo | Feature | TC-002 | User Update data list petstore |  |  | Repo-TC-002 | 1. Login petstore sebagai User 2. Pilih 'Update data petstore' 3. Klik 'Update' 4. Isi mandatory field pada form 'data petstore' 5. Klik 'Save' | 1. Product ID 2. Name | 1. Berhasil merubah data petstore |  |  | Positive, petstore, Update | Testing1 |
| 3  | Repo | Feature | TC-003 | User Delete data list petstore |  |  | Repo-TC-003 | 1. Login petstore sebagai User 2. Pilih 'Delete data petstore' 3. Klik 'Delete' 4. Klik 'OK' Popup | 1. Product ID 2. Name | 1. Berhasil manghapus data petstore |  |  | Positive, petstore, Delete | Testing1 |


## Laporan Bug

| No  | Description                                     | Action                                                               | Expected Result                                            | Actual Result                                                   |
|-----|---------------------------------------------------|------------------------------------------------------------------------------------------|------------------------------------------------------------------|---------------------------------------------------------------|
| 1   | Kesalahan Tipografi dalam Pesan Promosi           | 1. Buka situs web https://petstore.octoperf.com/actions/Catalog.action.                 2. Gulir ke bagian bawah halaman utama.                     | Pesan promosi seharusnya "Elevate your load-testing with OctoPerf!"  | Pesan promosinya "Elevate you load-testing with OctoPerf!" |
| 2   | Alt Text untuk Gambar Hilang                      | 1. Buka situs web https://petstore.octoperf.com/actions/Catalog.action.                 2. Inspect gambar di halaman utama menggunakan developer tool browser. | Setiap gambar harus memiliki alt text deskriptif untuk meningkatkan aksesibilitas. | Gambar-gambar tersebut tidak memiliki alt text.                       |
| 3   | Gaya Font yang Tidak Konsisten di Menu Navigasi   | 1. Buka situs web https://petstore.octoperf.com/actions/Catalog.action.                 2. Amati gaya font di menu navigasi di sisi kiri halaman utama. | Gaya font harus konsisten untuk nama kategori dan subkategori. | Nama kategori dalam font tebal dan miring, sedangkan nama subkategori dalam font biasa.   |
