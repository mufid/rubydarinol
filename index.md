## Ruby dari Nol

Zoom Interaktif dwimingguan dengan tujuan akhir: membuat *framework* seperti Rails.
Secara umum, acara ini diselenggarakan oleh [Muhammad Mufid Afif](https://mufid.github.io).

Untuk info episode interaktif selanjutnya, silahkan bergabung ke
[Grup Telegram](https://t.me/RubyDariNol).

Anda mungkin pernah mendengar upaya serupa bernama [Rebuilding Rails](http://rebuilding-rails.com/).
Buku ini diketahui setelah Mufid menyelenggarakan episode 4. "Apa iya di dunia ini belum
pernah ada upaya serupa?" Setelah Googling, ternyata ada! Meskipun secara konsep
serupa, Mufid belum pernah membaca buku Rebuilding Rails.

### Episode Mendatang

<ul>
{% for episode in site.episodes %}
<li><a href="{{ episode.url }}">{{ episode.title }}</a></li>
{% endfor %}
</ul>

### Rekaman

<table>
  <thead>
    <th>&#35; Eps</th>
    <th>Judul</th>
    <th>Tautan</th>
  </thead>
  {% for video in site.data.videos %}
    <tr>
      <td>{{ video.eps_num }}</td>
      <td>{{ video.title }}</td>
      <td>
        <a href="{{ video.link }}">YouTube</a>
      </td>
    </tr>
  {% endfor %}
</table>

### Catatan

- Kita akan membuat learning path segala pengetahuan yang dibutuhkan untuk membuat Rails dari nol.
- Kita tidak akan membahas topik yang sama dua kali. Silahkan merujuk ke episode yang pernah dibuat.
- Kita hanya akan menerbitkan video dalam Bahasa Indonesia.
- Materi yang disampaikan bisa saja salah karena dibahas secara impromptu. Saksikanlah
  keseluruhan episode karena barangkali di episode selanjutnya ada koreksi.

### FAQ

**WHY?**

Ini berawal dari episode 001.

Awalnya, sekelompok orang (yang sebagian adalah mantan asisten lab dari
Universitas Indonesia) ingin mengadakan pertemuan mingguan/dwimingguan yang membahas
tentang perkembangan perangkat lunak terkini. Dulunya saat bekerja bersama
(dan selepas meninggalkan lab), kami rutin melakukan ini. Wiki internal kami menamakan
aktivitas ini sebagai "Peentalk" (jangan dipisah!). Jadi, akan sangat baik kalau
kultur ini kita berdayakan lagi, meski tidak sedang bekerja bersama.

Terciptalah episode 001: "Ruby dari nol". Kami membahas secara interaktif, bersama-sama,
bagaimana Ruby bekerja. Episode 001 sangat menarik. Saksikanlah jika Anda belum!

Awalnya, episodenya sangat fleksibel dan bisa membahas tentang apapun. Kelanjutan
pertemuan ini tidak kunjung terlaksana karena berbagai macam hal. Saya melakukan
inisiatif untuk *test the water* apakah "pengajian" dwimingguan adalah sebuah
konsep yang menarik di publik. Ternyata ya! Akhirnya saya putuskan untuk membuka
aktivitas ini ke publik dan mulai menyelenggarakan acara ini secara rutin. Pada
saat FAQ ini ditulis, sudah ada dua puluh enam peserta di grup Telegram.

**Mengapa Topiknya Rails?**

Saya memiliki pengalaman 7+ tahun mengembangkan aplikasi dengan Ruby on Rails.
Karena pekerjaan saya mengharuskan saya melihat bagaimana secara internal
Ruby bekerja dan Rails bekerja, saya memiliki wawasan yang cukup berkaitan
dengan membedah Ruby.
