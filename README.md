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
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="container">
        <form action="https://wa.me/6282245184223" method="get">
            <div class="form-group">
                <label for="name">Nama</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="amount">Nominal</label>
                <input type="number" id="amount" name="amount" required>
            </div>
            <div class="form-group">
                <label for="payment-method">Metode Pembayaran</label>
                <select id="payment-method" name="payment-method" required>
                    <option value="minjem dulu">Minjem Dulu</option>
                    <option value="e-wallet">E-Wallet</option>
                    <option value="cod">COD</option>
                </select>
            </div>
            <div class="form-group">
                <input type="hidden" name="phone" value="082245184223">
                <button type="submit">Kirim Pembayaran</button>
            </div>
        </form>
    </div>
</body>
</html>
