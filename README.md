<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Dokumentasi Instalasi Laragon & Laravel</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.7;
            padding: 20px;
            max-width: 800px;
            margin: auto;
            background-color: #f5f5f5;
        }
        h1, h2 {
            color: #333;
        }
        code {
            background: #eee;
            padding: 2px 5px;
            border-radius: 4px;
        }
        pre {
            background: #eee;
            padding: 10px;
            border-radius: 4px;
            overflow-x: auto;
        }
        .author {
            margin-top: 30px;
            padding: 10px;
            background: #ddd;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <h1>📄 Dokumentasi Instalasi Laragon & Laravel</h1>

    <h2>📌 Instalasi Laragon</h2>
    <ol>
        <li>Download Laragon di <a href="https://laragon.org/download/" target="_blank">https://laragon.org/download/</a></li>
        <li>Install Laragon seperti biasa</li>
        <li>Jalankan Laragon</li>
        <li>Pastikan <strong>Apache</strong> & <strong>MySQL</strong> aktif</li>
        <li>Buka Terminal di Laragon</li>
    </ol>

    <h2>📌 Instalasi Laravel</h2>
    <ol>
        <li>Buka Terminal di Laragon</li>
        <li>Cek Composer:
            <pre><code>composer --version</code></pre>
            Kalau belum ada, install Composer di <a href="https://getcomposer.org/download/" target="_blank">https://getcomposer.org/download/</a>
        </li>
        <li>Install Laravel:
            <pre><code>composer create-project laravel/laravel nama_project</code></pre>
        </li>
        <li>Masuk ke folder project:
            <pre><code>cd nama_project</code></pre>
        </li>
        <li>Jalankan Laravel:
            <pre><code>php artisan serve</code></pre>
        </li>
        <li>Buka browser di <code>http://localhost:8000</code></li>
    </ol>

    <h2>📌 Upload ke GitHub</h2>
    <ol>
        <li>Buat repository baru di GitHub</li>
        <li>Clone repository ke komputer:
            <pre><code>git clone https://github.com/username/nama-repo.git</code></pre>
        </li>
        <li>Copy file dokumentasi & project Laravel kalau diminta</li>
        <li>Lakukan commit & push:
            <pre><code>
git add .
git commit -m "add dokumentasi instalasi laragon & laravel"
git push origin main
            </code></pre>
        </li>
    </ol>

    <div class="author">
        <strong>Nama:</strong> [Nama Kamu]<br>
        <strong>Kelas:</strong> [Kelas Kamu]<br>
        <strong>Mata Kuliah:</strong> [Nama Matkul]
    </div>

</body>
</html>
