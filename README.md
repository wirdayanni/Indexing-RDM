##Text Indexing (Swish-e)
1.	Instal Swish-e. Sintaks: `sudo apt-get install swish-e`
    ![1](/Screenshot/swish-e/1.png)
2.	Membuat file project.conf, kemudian diisi dengan sintaks `IndexDir ./project-rdm`
    ![2](/Screenshot/swish-e/2.png)
3.	Membuat file file.txt, kemudian diisi dengan beberapa kata agar dapat diindeks
    ![3](/Screenshot/swish-e/3.png)
4.	Menjalankan program text indexing. `Sintaks: swish-e -c project.conf`
    ![4](/Screenshot/swish-e/4.png)
5.	Mencari salah satu kata. Sintaks: `swish-e -w <kata>`
    ![5](/Screenshot/swish-e/5.png)


##Image Indexing
1.	Clone repository dari github. Sumber : https://github.com/kudeh/image-search-engine.
    ![1](/Screenshot/image-indexing/Screenshot_1.png)
2.	Melakukan update dengan sintaks: `sudo apt-get update`
3.	Melakukan upgrade dengan sintaks:  `sudo apt-get upgarde`
4.	Instal python. Sintaks: `sudo apt-get install python3-pip`
    ![4](/Screenshot/image-indexing/Screenshot_4.png)
5.	Menginstal modul python. Sintaks: `pip3 install -r requirements.txt`
    ![5](/Screenshot/image-indexing/Screenshot_5.png)
6.	Dalam folder image-search-ingine, masuk ke folder app kemudian jalankan program. Sintaks: `python3 index.py --dataset static/images --index index.csv`
    ![6](/Screenshot/image-indexing/Screenshot_6.png)
7.	Melihat hasil image indexing dengan sintaks: `pico index.csv`

Sumber
1.	Text-Indexing: Swish-e (Package on Ubuntu).
2.	Image-Indexing: https://github.com/kudeh/image-search-engine.
