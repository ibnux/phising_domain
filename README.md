# Daftar Domain Phising di Indonesia

List domain yang banyak digunakan oleh penipu

Jika punya tambahan silahkan Pull Request

Jika merasa itu bukan Phising domain silahkan kirim Issues

# Format AdGuard

- `||example.org^` :blokir akses ke example.org dan seluruh subdomainnya;
- `@@||example.org^` :buka blokir akses ke domain example.orf dan seluruh subdomainnya;
- `127.0.0.1 example.org` :merespons dengan 127.0.0.1 untuk example.org (tetapi tidak untuk subdomainnya);
- `! Komentar di sini.` :hanya sebuah komentar;
- `# Untuk diisi Komentar` :hanya sebuah komentar;
- `/REGEX/`: blokir akses ke domain yang cocok dengan ekspresi reguler yang ditentukan.
