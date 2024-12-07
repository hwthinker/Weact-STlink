# Wiring connection pada STM32F411CEU6
![img](./assets/AD_4nXf_giVThItyTsc8c-MU8mRg5hHzE4wsU1PuMeXtxR_Qp_xRtRivqY0nLkfkxW2uYsUm5lnzhM3c1wuZHE4kyMUyu4xuTAEgHesc82vdHYpacjZt86B4LCyZk2bsko1gnYpVhnYueHa09qWhcXFULWYPk4QW.png)

# Wiring connection pada STM32F411CEU6

**![img](./assets/AD_4nXd7gt9n4btHs68xyqUBi5hwMOwqU8aKI85TEDrwCE0zSc9Q4uW6eCNDv8mDsTyzbKTSdBb4q-TC5lSz3OUhVvAvNR8FIbMii1Hd1sdsleldv-Hs1Dcv0ftAUPbiB09UaRld41jnKwxHCTtUagF04LfEkWwj.png)**



****

# Cara mengaktifkan konfigurasi mass storage di stlink 2.1

1. Jalankan stm32cube ide
2. Pada menu editor klik Help -> STlink -> Stlink upgrade
     ![](./assets/image-20241207130916874.png)
3. Klik Refresh Device list
4. klik Open in update mode
5. Centang change type
6. Pilih STM32 Debug Mass Storage + VCP
     ![image-20241207131108120](./assets/image-20241207131108120.png)
7. Klik upgrade

8. Tunggu sampai proses upgrade selesai
    ![image-20241207131419763](./assets/image-20241207131419763.png)
9. Bila sudah selesai coba klik refresh dan lihat apakah fitur mass storage telah aktif
![image-20241207131454279](./assets/image-20241207131454279.png)
11. Coba cek di file explorer harusnya terdapat drive mass storage dari stlink

# Cara upload program menggunakan mode mass storage

\- Upload program stm32 yang berupa file intel hexa (*.hex) ke drive tersebut dengan cara copy paste atau drag and drop ke folder tersebut