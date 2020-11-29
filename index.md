## Ruby dari Nol

Bergabung ke [Grup Telegram](https://t.me/RubyDariNol)

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
        [YouTube]({{ video.link }})
        <a href="{{ video.link }}">wow</a>
      </td>
    </tr>
  {% endfor %}
</table>

### Aturan

- Kita akan membuat learning path segala pengetahuan yang dibutuhkan untuk membuat Rails dari nol.
- Kita tidak akan membahas topik yang sama dua kali. Silahkan merujuk ke episode yang pernah dibuat.
