# PROGRAM FILTERING PERNAFASAN PASIEN CORONA

Program yang saya tulis disini merupakan filtering pada pernafasan manusia yang berkisat dari 3000 hingga 6000Hz. Dari situ saya menganalisa perbedaan antara frekuensi yang paling aktif pada pasien sehat dan pasien pengidap corona.


# Data
Berikut adalah data - data yang saya gunakan untuk melakukan analisa ini:

## Pasien Sehat
![image](https://github.com/rayhannarindran/psd_filtering/assets/88973632/7d763e24-69ce-4432-828d-6d6af0f80ba8)

## Pasien Corona Tingkat Rendah
![image](https://github.com/rayhannarindran/psd_filtering/assets/88973632/d12f1810-599c-4eb2-ba04-e9c466c8e823)

## Pasien Corona Tingkat Sedang
![image](https://github.com/rayhannarindran/psd_filtering/assets/88973632/5eee5879-3f38-4d9a-9f8d-454a43e24736)

# Filtering Data
Kemudian data - data tersebut digunakan untuk difilter sehingga didapatkan frekuensi yang dicari, pada analisa ini, pernafasan manusia berkisar dari 3000 - 6000 Hz. Digunakan metode *bandpass* untuk melihat frekuensi - frekuensi tersebut. Berikut data - data yang telah difilter.

## Pasien Sehat Filtered
![image](https://github.com/rayhannarindran/psd_filtering/assets/88973632/c532c7cc-a6d3-4352-9c54-2ffdcb7762c8)

## Pasien Corona Tingkat Rendah
![image](https://github.com/rayhannarindran/psd_filtering/assets/88973632/ecb47143-78d6-4cb4-ae31-7e07843bf654)

## Pasien Corona Tingkat Sedang
![image](https://github.com/rayhannarindran/psd_filtering/assets/88973632/d4b45ebc-1666-4ad4-866f-393853fee635)
