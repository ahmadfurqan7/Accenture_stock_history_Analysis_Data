# Accenture Stock History
Pda kesempatan kali ini yaitu project analisa data accenture stock history.

## Step by Step
- **Data** -- Cari data/sheet yang akan dilakukan analisa
	link data [Accenture_stock_history](https://github.com/anomalyco/opencode).
- **Cleaning data** -- Memperbaiki dan menghapus bagian data yang tidak diperlukan misal kita hanya butuh data 2 tahun terakhir, hapus tahun" sebelumnya.
- **Forecasting data** -- membuat prediksi nilai data selanjutnya untuk open price,  dimasa depan menggunakan formula.
```bash
=FORECAST(x, known_ys, known_xs)
```
Forecasting formula for `open/high/low/close/volume` prices values.
| `x` | The date of the value to be searched (lock) |
| `known_ys` | All value from the previous `open/high/low/close/volume` values |
| `known_xs` | All dates from the previous values (lock) |

- **Exploratory Data** -- Membuat charts mendefinisikan hasil dari forecasting
Membuat trend line untuk menunjukkan arah atau tren umum dari pergerakan data tersebut. Garis ini berfungsi untuk memvisualisasikan apakah data sedang naik, turun, atau mendatar.
Melihat keakuratan menggunakan nilai R kuadrat dari trendline.
