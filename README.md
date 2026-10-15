# Kuis 1 PAW 2 - REST API Manajemen Jadwal Kuliah (Express ESM + MongoDB)

## Menjalankan
1. `npm install`
2. Edit `.env`, ganti nama database menjadi `nama_lengkap_jadwal_kuliah`
3. `npm start` (atau `npm run dev`)

## Endpoint
| Method | Endpoint | Deskripsi |
|---|---|---|
| POST | /api/jadwal-kuliah | Tambah data |
| GET | /api/jadwal-kuliah | Semua data |
| GET | /api/jadwal-kuliah/:id | Detail data |
| PUT | /api/jadwal-kuliah/:id | Update data |
| DELETE | /api/jadwal-kuliah/:id | Hapus data |

Field: `mata_kuliah` (String), `dosen` (String), `jam_mulai` (String, format HH:mm).
Collection: `jadwal_kuliah`. Postman collection ada di folder `collection-api`.
