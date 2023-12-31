# Game "Jack In The Woods"
## 1.1 Latar Belakang
  <p> Banyaknya game yang saat ini dimainkan oleh banyak orang, sudah sangat modern atau sangat canggih dengan grafik yang memukau dengan jauhnya perkembangan zaman, game retro menghadirkan nuansa nostalgia pada pemainnya. Ditambah game yang dimainkan oleh orang orang saat ini terlalu penuh tekanan atau stress, game retro rpg ini membawakan perasaan anti-stress atau chill saat dimainkan. </p>
 <p> Bisa dikatakan game ber-genre MOBA, FPS sudah sangat sering ditemukan di sekitar kita, baik di lingkungan universitas maupun di lingkungan masyarakat. Dan tidak sedikit dari mereka yang frustasi, stress dan istilahnya "terjebak" dalam game saat mengalami kekalahan yang beruntun dan sulit meraih kemenangan. Game ini bisa menghadirkan suasana baru bagi para gamers yang merasa butuh environtment atau lingkungan baru untuk beralih sejenak dari game yang dirasa terlalu stress.</p>

## 1.2. Deksripsi Teknologi Informasi
  Game "Jack In The Woods" ini merupakan game retro rpg yang membawakan perasaan chill saat bermain dengan experience
no stress. Game ini bercerita tentang seorang anak laki-laki yang berkelana ke hutan karena bosan dengan lingkungan kota, saat dia berada di hutan semua hal yang ia lakukan benar-benar bebas dan tidak terikat aturan "kota". Dia menetap di sebuah
rumah di desa dalam hutan. Dia bisa membantu warga menyelesaikan tugas, seperti menebang pohon di hutan, membawa sebuah
benda milik warga yang tertinggal, atau bisa bercocok tanam tanpa ada suruhan dari warga, atau juga bisa mengeksplor
map yang ada. Inti dari game ini player dapat melakukan tugas yang mana saja tanpa ada urutan yang tetap. Diharapkan
para player, bermain game ini sebagai sarana penghilang stress yang sederhana.

## 1.3. Branding
### 1.3.1. Nama/Merk Game :
Jack In The Woods
### 1.3.2. Tagline :
Gaming and chill without stress
### 1.3.3. Target User :
- Usia 15 tahun ke atas
- Gamer yang mencari ketenangan saat bermain game
- Gamer yang ingin bernostalgia dengan retro game
- Penikmat game indie
- Gamer yang penat dengan game kompetitif
### 1.3.4. Genre :
Indie retro RPG, Simulation
### 1.3.5. Poster :
![poster](https://github.com/fadligg/fadligg.github.io/assets/144420686/04beebea-8cb0-4f53-b610-9910cbf0302d)
### 1.3.6 Inspirasi Design :
<img width="635" alt="image" src="https://github.com/fadligg/fadligg.github.io/assets/144420686/b05dfd5c-d1b7-4ba0-be41-9ed402b7f62d">

![pokemon-game-maker](https://github.com/fadligg/fadligg.github.io/assets/144420686/85480254-bf2e-47d3-91d1-0470723b6103)

![42747c86db7ac0cd53797a635573a236-1200-80](https://github.com/fadligg/fadligg.github.io/assets/144420686/3161a71b-c90d-4ef6-a3a6-220f05790ea0)


## 2. User Story

Sebagai | Saya Ingin Bisa | Sehingga | Prioritas
---|---|---|---
PLayer | Bergerak ke mana saja | Bisa mengeksplorasi | ⭐⭐⭐⭐⭐
Player | Menabrak objek | Bisa berinteraksi dengan objek tertentu | ⭐⭐⭐⭐⭐
Player | Berinteraksi dengan NPC | Bisa menyelesaikan quest yang diberi | ⭐⭐⭐⭐⭐
Player | Bermain dengan musik berjalan di background | Nuansa chill / anti-stress tercipta | ⭐⭐⭐⭐⭐
Player | Menyimpan barang ke inventory | Bisa menyimpan barang | ⭐⭐⭐⭐
Player | Menebang pohon | Menyelesaikan quest menebang pohon | ⭐⭐⭐
Player | Memancing | Bisa tenang | ⭐⭐⭐
Player | Save data | Data terakhir bisa tersimpan | ⭐⭐⭐
Player | Load data | Memuat data terakhir | ⭐⭐⭐
Player | Berpindah map | Bisa bereksplorasi | ⭐⭐⭐
Player | Masuk ke rumah | Bisa bereksplorasi | ⭐⭐⭐


## 3. Struktur Data

```mermaid
erDiagram
    User ||--|{ Start : Mulai_Game
   
    Start ||--|{ In-Game : User_In_The_Game
    In-Game{
png character
png NPCs
png object_tile
png inventory
txt map
wav music
}

User ||--|{ Settings : Menyesuaikan
    Settings{
        checkbox fullscreen
        slider music
        slider sound_effect
    }

User ||--|{ Exit : Keluar_Game

In-Game ||--|{ Jack : In-Game_Character
In-Game ||--|{ NPCs: In-Game_NPCs
In-Game ||--|{ Music: In-Game_Music
Music {
    wav background_music
    wav sound_effect
}
In-Game ||--|{ object_tile: In-Game_Object
object_tile{
    png tree
    png wall
    png grass
    png sand
    png water
    png door
}


  
    

```

## 4. Arsitektur Sistem

```mermaid
flowchart TD
    A[Database : mySQL] <-->B[Web Application : Spring - Spring Boot]
    B <--> C[Web Server : Spring - Tomcat]
    C <--> D[Application Website PC : Spring - Java]
```

## 5. Teknologi, Library, dan Framework
- Teknologi yang saya gunakan untuk membuat game yang satu ini adalah IDE berupa Visual Studio Code dengan bahasa pemrograman java, database mySQL, Spring.
- Library yang saya gunakan adalah Java Standard Libraries (Java Swing, Java awt, dsb.)
- Framework yang akan saya gunakan adalah Spring framework

## 6. Desain User Experience dan User Interface
![Start](https://github.com/fadligg/fadligg.github.io/assets/144420686/4f6b1e6e-22b7-413f-9b63-62eda599d444)

## 7. Demonstrasi Video

[Link To My Youtube](https://youtu.be/taWaZuo58I4)

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

[In Progress]

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

[In Progress]

## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

[In Progress]

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?

[In Progress]
