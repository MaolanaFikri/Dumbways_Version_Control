# Dumbways_Version_Control

1. Git adalah sebuah tools untuk para developers dalam mengembangkan suatu aplikasi atau produk. dimana git ini bisa digunakan untuk menyimpan suatu file, folder, atau lainnya dan para developers bisa bekerja sama untuk mengembangkan suatu aplikasi atau produk dengan menggunakan git. karena di git ini bisa melihat siapa saja yang telah melakukan perubahan dan di file atau folder mana saja yang mengalami perubahan.

2. pertama, kita masuk ke directori /etc/netplan, kita create file, lalu kita edit menggunakan editor nano, dengan perintah dibawah

![Screenshot from 2022-11-21 10-44-11](https://user-images.githubusercontent.com/118157585/202961798-afaceeb0-0a71-4571-aa9d-cf98bac78de2.png)

nah lalu, kita bikin ip sesuai yang kita mau seperti gambar dibawah

![Screenshot from 2022-11-21 10-39-33](https://user-images.githubusercontent.com/118157585/202961791-1d0c4764-c545-49da-96b2-ccde9e29abba.png)

![Screenshot from 2022-11-21 10-35-53](https://user-images.githubusercontent.com/118157585/202961924-494f1083-9ef3-4f43-aeab-8d492ab3c543.png)
![Screenshot from 2022-11-21 10-34-45](https://user-images.githubusercontent.com/118157585/202961936-99fd5acc-02f2-43e9-8041-bcb365618460.png)
![Screenshot from 2022-11-21 10-36-17](https://user-images.githubusercontent.com/118157585/202961782-f1a1b9fa-0694-4e22-806d-16a7fc91b8f4.png)
![Screenshot from 2022-11-21 10-39-33](https://user-images.githubusercontent.com/118157585/202961791-1d0c4764-c545-49da-96b2-ccde9e29abba.png)

3. dapatkan ssh key nya dahulu, perintahnya seperti gambar dibawah

![Screenshot from 2022-11-20 23-37-23](https://user-images.githubusercontent.com/118157585/202915168-fbb34c9c-522d-4fef-a673-90d270e2b38e.png) 

Jika kalian sudah menjalankan perintah sebelumnya maka kalian sudah berhasil untuk men-generate SSH key yang akan kalian gunakannya. Untuk lokasi SSH key yang sudah kalian generate tadi berada di .ssh/id_rsa.pub. Jika sudah lakukan copy pada SSH-key tersebut.

![Screenshot from 2022-11-20 23-38-47](https://user-images.githubusercontent.com/118157585/202915169-8b3f739d-4ae3-4b0b-b9c5-d8bc26a2f3fb.png)

lalu setelah kita dapet kode ssh nya, kita langsung hubungin ke github kita, dengan cara seperti dibawah

![Screenshot from 2022-11-20 23-40-05](https://user-images.githubusercontent.com/118157585/202915171-0ab3ee6d-318e-4759-b802-6a6711da043f.png)

kita add github kita di local, setalah berhasil, lalu push commit kita ke github, bisa loihat gambar dibawah.

![Screenshot from 2022-11-19 10-30-16](https://user-images.githubusercontent.com/118157585/202915160-1da1fa05-f722-4d63-b5a5-f67a6704b1c4.png)

nah ini tampilan di github yg sudah kita push dari local, [fikri]

![Screenshot from 2022-11-19 10-30-39](https://user-images.githubusercontent.com/118157585/202915155-d15a67cc-152f-45c2-a62c-cfcb5b7c1b8e.png)
4. untuk membuat  branch baru, kalian bisa mengetikan perintah git branch nama_branch.

lalu cara lihat branch kita tinggal ketik perintah git branch, lalu muncul nama branch kita.
![Screenshot from 2022-11-21 09-05-39](https://user-images.githubusercontent.com/118157585/202945380-e3dbc2e1-379d-4962-a71e-c5c80960c16c.png)
