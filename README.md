# IsrailStore

Selamat Datang!!! 
<html>
<head>
    <title>Form Pembayaran</title>
    <style>
        .container {
            max-width: 400px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 5px;
        }

        .form-group input {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .form-group select {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .form-group button {
            background-color: #04AA6D;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Form Pembayaran</h2>
        <form action="https://api.whatsapp.com/send?phone=082245184223" method="POST">
            <div class="form-group">
                <label for="nama">Nama</label>
                <input type="text" id="nama" name="nama" required>
            </div>
            <div class="form-group">
                <label for="nomor">Nomor</label>
                <input type="nomor" id="nomor" name="nomor" required>
            </div>
            <div class="form-group">
                <label for="jumlah">Nominal</label>
                <input type="number" id="jumlah" name="jumlah" required>
            </div>
            <div class="form-group">
                <label for="metode">Metode Pembayaran</label>
                <select id="metode" name="metode" required>
                    <option value="transfer">Minjem</option>
                    <option value="tunai">Tunai</option>
                </select>
            </div>
            <div class="form-group">
                <button type="submit">Kirim Pembayaran</button>
            </div>
        </form>
    </div>
</body>
</html>
