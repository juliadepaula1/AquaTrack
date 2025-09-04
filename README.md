<!DOCTYPE html>
    <html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Aquatrack</title>
    </head>
    <body>
        <section class="dashboard">
            <h2>Status do Sistema</h2>

            <!-- Tanque aqui -->
            <div class="tanque">
                <div class="onda"></div>
            </div>

        </section>
    </html>

    .tanque {
  width: 300px;
  height: 150px;
  background-color: #29abe2; /* Cor da água */
  border: 5px solid #1c2c4c; /* Cor da borda */
  border-top: none; /* Sem borda superior */
  border-radius: 0 0 30px 30px; /* Borda inferior arredondada */
  position: relative;
  overflow: hidden;
}

.onda {
  position: absolute;
  top: -10px;
  left: 0;
  width: 100%;
  height: 20px;
  background: url('data:image/svg+xml;utf8,<svg viewBox="0 0 1440 320" xmlns="http://www.w3.org/2000/svg"><path fill="%231c2c4c" fill-opacity="1" d="M0,64L48,69.3C96,75,192,85,288,80C384,75,480,53,576,69.3C672,85,768,139,864,138.7C960,139,1056,85,1152,74.7C1248,64,1344,96,1392,112L1440,128L1440,0L1392,0C1344,0,1248,0,1152,0C1056,0,960,0,864,0C768,0,672,0,576,0C480,0,384,0,288,0C192,0,96,0,48,0L0,0Z"></path></svg>') repeat-x;
  background-size: cover;
}
