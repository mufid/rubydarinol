## Ruby dari Nol

Bergabung ke [Grup Telegram](https://t.me/RubyDariNol)

### Rekaman

{% for video in site.data.videos %}
  <table>
    <thead>
      <th>&#35; Eps</th>
      <th>Judul</th>
      <th>Tautan</th>
    </thead>
    <tr>
      <td>{{ video.eps_num }}</td>
      <td>{{ video.title }}</td>
      <td><a href={{ video.link }}>YouTube</a></td>
    </tr>
  </li>
{% endfor %}

### Aturan

- Kita akan membuat learning path segala pengetahuan yang dibutuhkan untuk membuat Rails dari nol.
- Kita tidak akan membahas topik yang sama dua kali. Silahkan merujuk ke episode yang pernah dibuat.
