<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Piano di Produzione Gelato - Avanzato</title>
    <style>
        /* Configurazione per il foglio orizzontale e stile generale */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 20px;
            background-color: #f4f7f6;
            color: #333;
        }

        .container {
            max-width: 1300px;
            margin: 0 auto;
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        h1 {
            text-align: center;
            color: #2c3e50;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        h2 {
            color: #2c3e50;
            border-bottom: 2px solid #34495e;
            padding-bottom: 5px;
            margin-top: 30px;
        }

        /* Sezione Gestione Gusti e Inserimento in griglia */
        .sezione-comandi {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 20px;
            margin-bottom: 30px;
        }

        .box-gestione {
            background: #eef2f3;
            padding: 15px;
            border-radius: 6px;
        }

        .form-group {
            display: flex;
            flex-direction: column;
            margin-bottom: 10px;
        }

        .form-inline {
            display: flex;
            gap: 10px;
            align-items: flex-end;
        }

        .form-inline .form-group {
            flex: 1;
            margin-bottom: 0;
        }

        label {
            font-size: 0.9rem;
            font-weight: bold;
            margin-bottom: 5px;
            color: #555;
        }

        input, select {
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 1rem;
        }

        /* Pulsanti */
        button {
            padding: 9px 15px;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 0.95rem;
            font-weight: bold;
            transition: background 0.2s;
        }

        .btn-success { background-color: #27ae60; }
        .btn-success:hover { background-color: #219653; }
        .btn-primary { background-color: #2980b9; }
        .btn-primary:hover { background-color: #2471a3; }
        .btn-danger { background-color: #e74c3c; }
        .btn-danger:hover { background-color: #c0392b; }
        .btn-warning { background-color: #f39c12; color: #fff; }
        .btn-warning:hover { background-color: #d35400; }

        /* Lista Gusti */
        .lista-gusti-container {
            margin-top: 10px;
            max-height: 120px;
            overflow-y: auto;
            background: white;
            border: 1px solid #ddd;
            border-radius: 4px;
            padding: 5px;
        }

        .gusto-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 4px 8px;
            border-bottom: 1px solid #eee;
            font-size: 0.9rem;
        }

        /* Tabella Orizzontale */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
            background: white;
        }

        th, td {
            border: 1px solid #bdc3c7;
            padding: 10px;
            text-align: left;
        }

        th {
            background-color: #34495e;
            color: white;
            font-weight: 600;
        }

        tr:nth-child(even) {
            background-color: #f9f9f9;
        }

        .totale-riga {
            font-weight: bold;
            background-color: #eaeded;
        }

        .Azioni {
            text-align: center;
            width: 140px;
        }

        .table-btn {
            padding: 4px 8px;
            font-size: 0.8rem;
            margin: 0 2px;
        }

        /* CSS Specifico per la Stampa */
        @media print {
            @page {
                size: landscape;
                margin: 1cm;
            }
            body {
                background: white;
                margin: 0;
            }
            .sezione-comandi, .btn-primary, .Azioni, th:last-child {
                display: none !important; /* Nasconde comandi e colonna azioni in stampa */
            }
            .container {
                box-shadow: none;
                padding: 0;
                max-width: 100%;
            }
            th {
                background-color: #34495e !important;
                color: white !important;
                -webkit-print-color-adjust: exact;
                print-color-adjust: exact;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Giornale di Produzione Gelato 🍦</h1>
    
    <button class="btn-primary" style="margin-bottom: 15px;" onclick="window.print()">🖨️ Stampa / Salva in PDF</button>

    <div class="sezione-comandi">
        <div class="box-gestione">
            <h3>1. Gestione Lista Gusti</h3>
            <div class="form-group">
                <label for="nuovo-gusto">Nuovo Gusto</label>
                <div style="display: flex; gap: 5px;">
                    <input type="text" id="nuovo-gusto" placeholder="Es. Stracciatella" style="flex: 1;">
                    <button class="btn-success" onclick="aggiungiGusto()">Aggiungi</button>
                </div>
            </div>
            <label>Gusti Attuali (Fai clic sulla X per eliminare):</label>
            <div class="lista-gusti-container" id="lista-gusti">
                </div>
        </div>

        <div class="box-gestione">
            <h3>2. Inserisci Produzione</h3>
            <div class="form-inline" style="margin-bottom: 10px;">
                <div class="form-group">
                    <label for="data">Data Produzione</label>
                    <input type="date" id="data">
                </div>
                <div class="form-group">
                    <label for="gusto-select">Gusto</label>
                    <select id="gusto-select">
                        </select>
                </div>
                <div class="form-group">
                    <label for="formato">Formato</label>
                    <select id="formato">
                        <option value="Piccola (2.5 kg)">Piccola (2.5 kg)</option>
                        <option value="Grande (4.5 kg)">Grande (4.5 kg)</option>
                    </select>
                </div>
            </div>
            <div class="form-inline">
                <div class="form-group">
                    <label for="quantita">N° Vaschette</label>
                    <input type="number" id="quantita" min="1" value="1">
                </div>
                <div class="form-group">
                    <label for="lotto">Lotto Ingredienti</label>
                    <input type="text" id="lotto" placeholder="Es. L2304">
                </div>
                <button class="btn-success" id="btn-salva-prod" onclick="salvaProduzione()">Registra Produzione</button>
            </div>
        </div>
    </div>

    <h2>Registro Giornaliero</h2>
    <table id="tabella-produzione">
        <thead>
            <tr>
                <th>Data</th>
                <th>Gusto</th>
                <th>Formato Vaschetta</th>
                <th>Quantità (Pezzi)</th>
                <th>Lotto Base/Ingredienti</th>
                <th>Note / Firma</th>
                <th class="Azioni">Azioni</th>
            </tr>
        </thead>
        <tbody id="corpo-tabella">
            </tbody>
        <tfoot>
            <tr class="totale-riga">
                <td colspan="3" style="text-align: right;">Totale Vaschette Prodotte:</td>
                <td id="totale-pezzi">0</td>
                <td colspan="3"></td>
            </tr>
        </tfoot>
    </table>
</div>

<script>
    // --- STATO INIZIALE DEI DATI (Caricamento da localStorage) ---
    let gusti = JSON.parse(localStorage.getItem('gelato_gusti')) || ["Fiordilatte", "Cioccolato", "Nocciola", "Pistacchio"];
    let produzioni = JSON.parse(localStorage.getItem('gelato_produzioni')) || [];
    let indiceModifica = -1; // -1 significa che stiamo inserendo una nuova riga, altrimenti contiene l'indice della riga da modificare

    // Imposta la data di oggi sul calendario
    document.getElementById('data').valueAsDate = new Date();

    // Avvia l'applicazione caricando i dati salvati
    aggiornaInterfacciaGusti();
    renderTabellaProduzione();

    // --- FUNZIONI PER I GUSTI ---
    function aggiornaInterfacciaGusti() {
        const listaContainer = document.getElementById('lista-gusti');
        const selectGusto = document.getElementById('gusto-select');
        
        listaContainer.innerHTML = '';
        selectGusto.innerHTML = '';

        // Ordina i gusti alfabeticamente
        gusti.sort();

        gusti.forEach((gusto, index) => {
            // Aggiungi alla lista di gestione
            const div = document.createElement('div');
            div.className = 'gusto-item';
            div.innerHTML = `<span>${gusto}</span> <button class="btn-danger table-btn" onclick="eliminaGusto(${index})">X</button>`;
            listaContainer.appendChild(div);

            // Aggiungi al menu a tendina della produzione
            const option = document.createElement('option');
            option.value = gusto;
            option.textContent = gusto;
            selectGusto.appendChild(option);
        });

        // Salva la lista aggiornata
        localStorage.setItem('gelato_gusti', JSON.stringify(gusti));
    }

    function aggiungiGusto() {
        const input = document.getElementById('nuovo-gusto');
        const nuovoGusto = input.value.trim();

        if(nuovoGusto === "") return alert("Inserisci un nome valido!");
        if(gusti.includes(nuovoGusto)) return alert("Questo gusto esiste già!");

        gusti.push(nuovoGusto);
        input.value = "";
        aggiornaInterfacciaGusti();
    }

    function eliminaGusto(index) {
        if(confirm(`Vuoi davvero eliminare il gusto "${gusti[index]}" dalle opzioni? (Le produzioni passate rimarranno salvate)`)) {
            gusti.splice(index, 1);
            aggiornaInterfacciaGusti();
        }
    }


    // --- FUNZIONI PER LA PRODUZIONE ---
    function renderTabellaProduzione() {
        const tbody = document.getElementById('corpo-tabella');
        tbody.innerHTML = '';
        let totale = 0;

        produzioni.forEach((prod, index) => {
            const tr = document.createElement('tr');
            tr.innerHTML = `
                <td>${formattaData(prod.data)}</td>
                <td><strong>${prod.gusto}</strong></td>
                <td>${prod.formato}</td>
                <td>${prod.quantita}</td>
                <td><code>${prod.lotto}</code></td>
                <td></td>
                <td class="Azioni">
                    <button class="btn-warning table-btn" onclick="avviaModificaProduzione(${index})">Modifica</button>
                    <button class="btn-danger table-btn" onclick="eliminaProduzione(${index})">Elimina</button>
                </td>
            `;
            tbody.appendChild(tr);
            totale += parseInt(prod.quantita);
        });

        document.getElementById('totale-pezzi').innerText = totale;
        localStorage.setItem('gelato_produzioni', JSON.stringify(produzioni));
    }

    function salvaProduzione() {
        const data = document.getElementById('data').value;
        const gusto = document.getElementById('gusto-select').value;
        const formato = document.getElementById('formato').value;
        const quantita = parseInt(document.getElementById('quantita').value);
        const lotto = document.getElementById('lotto').value.trim() || "-";

        if (!data || isNaN(quantita) || quantita <= 0 || !gusto) {
            alert("Compila tutti i campi correttamente prima di salvare.");
            return;
        }

        const oggettoProduzione = { data, gusto, formato, quantita, lotto };

        if (indiceModifica === -1) {
            // Nuovo inserimento
            produzioni.push(oggettoProduzione);
        } else {
            // Modifica di una riga esistente
            produzioni[indiceModifica] = oggettoProduzione;
            indiceModifica = -1; // Resetta lo stato di modifica
            document.getElementById('btn-salva-prod').innerText = "Registra Produzione";
            document.getElementById('btn-salva-prod').className = "btn-success";
        }

        // Svuota i campi inserimento
        document.getElementById('quantita').value = 1;
        document.getElementById('lotto').value = "";
        
        renderTabellaProduzione();
    }

    function avviaModificaProduzione(index) {
        const prod = produzioni[index];
        
        // Riporta i dati nei campi del modulo per essere modificati
        document.getElementById('data').value = prod.data;
        document.getElementById('gusto-select').value = prod.gusto;
        document.getElementById('formato').value = prod.formato;
        document.getElementById('quantita').value = prod.quantita;
        document.getElementById('lotto').value = prod.lotto === "-" ? "" : prod.lotto;

        // Cambia la modalità del pulsante in "Modifica"
        indiceModifica = index;
        const btn = document.getElementById('btn-salva-prod');
        btn.innerText = "Applica Modifiche";
        btn.className = "btn-warning";
        
        // Scorre la pagina verso l'alto per mostrare il modulo di modifica
        window.scrollTo({ top: 0, behavior: 'smooth' });
    }

    function eliminaProduzione(index) {
        if(confirm("Sei sicuro di voler cancellare questa riga di produzione?")) {
            produzioni.splice(index, 1);
            // Se stavamo modificando proprio quella riga, annulla la modifica
            if(indiceModifica === index) {
                indiceModifica = -1;
                document.getElementById('btn-salva-prod').innerText = "Registra Produzione";
                document.getElementById('btn-salva-prod').className = "btn-success";
            }
            renderTabellaProduzione();
        }
    }

    function formattaData(dataString) {
        const d = new Date(dataString);
        return d.toLocaleDateString('it-IT');
    }
</script>

</body>
</html>
