<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pencatatan Keuangan</title>
    <subtitle>versi 3.1</subtitle>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 20px;
        }
        h1 {
            color: #2a52be;
            text-align: center;
            margin-bottom: 30px;
        }
        .nav-tabs {
            display: flex;
            background-color: white;
            border-radius: 8px 8px 0 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin-bottom: 0;
        }
        .nav-tab {
            flex: 1;
            padding: 15px;
            text-align: center;
            cursor: pointer;
            border-bottom: 3px solid transparent;
            transition: all 0.3s ease;
        }
        .nav-tab.active {
            background-color: #2a52be;
            color: white;
            border-bottom-color: #1e3d8f;
        }
        .nav-tab:hover:not(.active) {
            background-color: #f0f0f0;
        }
        .tab-content {
            display: none;
        }
        .tab-content.active {
            display: block;
        }
        .card {
            background-color: white;
            border-radius: 0 0 8px 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            padding: 20px;
            margin-bottom: 20px;
        }
        .card:not(.main-card) {
            border-radius: 8px;
        }
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
        }
        input, select, button {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border-radius: 4px;
            border: 1px solid #ddd;
            box-sizing: border-box;
        }
        input::placeholder {
            color: #ccc;
        }
        button {
            background-color: #2a52be;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 16px;
            padding: 12px;
        }
        button:hover {
            background-color: #1e3d8f;
        }
        .section-title {
            font-size: 20px;
            margin-bottom: 15px;
        }
        .summary {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
        }
        .saldo-info {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }
        .saldo-item {
            font-weight: bold;
        }
        .green {
            color: #28a745;
        }
        .blue {
            color: #007bff;
        }
        .orange {
            color: #ffc107;
        }
        .red {
            color: #dc3545;
        }
        .table-container {
            overflow-x: auto;
            margin: 15px 0;
        }
        .table-summary {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 15px;
            padding: 10px;
            background-color: #f9f9f9;
            border-radius: 4px;
        }
        table {
            width: 100%;
            min-width: 800px;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            text-align: left;
            border-bottom: 1px solid #ddd;
            white-space: nowrap;
        }
        th {
            background-color: #f2f2f2;
            position: sticky;
            top: 0;
        }
        .action-buttons {
            display: flex;
            gap: 10px;
            margin-bottom: 15px;
            flex-wrap: wrap;
        }
        .dropdown {
            position: relative;
            width: 200px;
        }
        .dropdown summary {
            background-color: #2a52be;
            color: white;
            padding: 12px;
            border-radius: 4px;
            cursor: pointer;
            text-align: center;
        }
        .dropdown-content {
            display: none;
            position: absolute;
            background-color: white;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
            border-radius: 4px;
            width: 100%;
            z-index: 1;
            padding: 10px;
        }
        .dropdown[open] .dropdown-content {
            display: block;
        }
        .dropdown-content button, .dropdown-content .file-input-wrapper {
            margin-bottom: 10px;
        }
        .reset-btn {
            background-color: #dc3545;
        }
        .reset-btn:hover {
            background-color: #c82333;
        }
        .export-btn {
            background-color: #28a745;
        }
        .export-btn:hover {
            background-color: #218838;
        }
        .import-btn {
            background-color: #17a2b8;
        }
        .import-btn:hover {
            background-color: #138496;
        }
        .pending-btn {
            background-color: #ffc107;
            color: #212529;
        }
        .pending-btn:hover {
            background-color: #e0a800;
        }
        .edit-btn {
            background-color: #ffc107;
            color: #212529;
            padding: 5px 10px;
            font-size: 12px;
            margin-right: 5px;
        }
        .edit-btn:hover {
            background-color: #e0a800;
        }
        .delete-btn {
            background-color: #dc3545;
            padding: 5px 10px;
            font-size: 12px;
        }
        .delete-btn:hover {
            background-color: #c82333;
        }
        .transfer-btn {
            background-color: #6f42c1;
            padding: 5px 10px;
            font-size: 12px;
            margin-right: 5px;
        }
        .transfer-btn:hover {
            background-color: #5a32a3;
        }
        .action-cell button {
            width: auto;
            margin: 0;
        }
        .chart-container {
            margin-top: 10px;
            height: 250px;
            width: 100%;
            max-width: 500px;
            position: relative;
            margin-left: auto;
            margin-right: auto;
        }
        canvas {
            width: 100% !important;
            height: 100% !important;
        }
        .modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.5);
        }
        .modal-content {
            background-color: white;
            margin: 5% auto;
            padding: 20px;
            border-radius: 8px;
            width: 90%;
            max-width: 500px;
        }
        .close-btn {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
            cursor: pointer;
        }
        .close-btn:hover {
            color: black;
        }
        .form-row {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
            justify-content: center;
        }
        .form-row > div {
            flex: 1;
        }
        .status-indicator {
            padding: 5px 10px;
            border-radius: 4px;
            font-size: 12px;
            margin-left: 10px;
        }
        .status-saved {
            background-color: #d4edda;
            color: #155724;
        }
        .status-unsaved {
            background-color: #f8d7da;
            color: #721c24;
        }
        .kategori-badge {
            padding: 3px 8px;
            border-radius: 12px;
            font-size: 11px;
            font-weight: bold;
            text-transform: uppercase;
        }
        .kategori-parkir { background-color: #e3f2fd; color: #1976d2; }
        .kategori-sekolah { background-color: #f3e5f5; color: #7b1fa2; }
        .kategori-jajan { background-color: #fff3e0; color: #f57c00; }
        .kategori-uang-mingguan { background-color: #e8f5e8; color: #388e3c; }
        .kategori-shopping { background-color: #fce4ec; color: #c2185b; }
        .kategori-lainnya { background-color: #f5f5f5; color: #616161; }
        .kategori-pending { background-color: #fff3cd; color: #856404; }
        .search-container {
            margin-bottom: 20px;
        }
        .search-row {
            display: flex;
            gap: 10px;
            align-items: end;
        }
        .search-row > div {
            flex: 1;
        }
        .search-row button {
            max-width: 100px;
            margin-bottom: 15px;
        }
        .recurring-checkbox {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 15px;
        }
        .recurring-checkbox input[type="checkbox"] {
            width: auto;
            margin: 0;
        }
        .recurring-options {
            display: none;
            margin-bottom: 15px;
        }
        .currency-format {
            position: relative;
        }
        .currency-format::before {
            content: 'Rp ';
            position: absolute;
            left: 10px;
            top: 50%;
            transform: translateY(-50%);
            color: #666;
            pointer-events: none;
        }
        .currency-format input {
            padding-left: 35px;
        }
        .file-input-wrapper {
            position: relative;
            display: inline-block;
            width: 100%;
        }
        .file-input {
            display: none;
        }
        .file-input-label {
            display: block;
            padding: 12px;
            background-color: #17a2b8;
            color: white;
            text-align: center;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .file-input-label:hover {
            background-color: #138496;
        }
        .pending-item {
            background-color: #fff3cd;
            border: 1px solid #ffeaa7;
            border-radius: 8px;
            padding: 15px;
            margin-bottom: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .pending-info {
            flex: 1;
        }
        .pending-actions {
            display: flex;
            gap: 10px;
        }
        .pending-actions button {
            width: auto;
            margin: 0;
            padding: 5px 10px;
            font-size: 12px;
        }
        .transfer-history-item {
            background-color: #e0f2f7;
            border: 1px solid #b3e5fc;
            border-radius: 8px;
            padding: 10px 15px;
            margin-bottom: 8px;
            font-size: 14px;
        }
        .transfer-history-item strong {
            color: #01579b;
        }

        .progress-container {
            width: 100%;
            background-color: #f3f3f3;
            border-radius: 5px;
            margin-top: 10px;
            margin-bottom: 15px;
        }

        .progress-bar {
            width: 0%;
            height: 25px;
            background-color: #4CAF50;
            border-radius: 5px;
            text-align: center;
            line-height: 25px;
            color: white;
            font-weight: bold;
            transition: width 0.5s ease-in-out;
        }

        .insight-item {
            padding: 10px 15px;
            background-color: #e8f5e8;
            border-left: 5px solid #28a745;
            border-radius: 4px;
            margin-bottom: 10px;
            font-size: 15px;
        }
        .insight-item.warning {
            background-color: #fff3cd;
            border-left-color: #ffc107;
        }
        .insight-item.danger {
            background-color: #f8d7da;
            border-left-color: #dc3545;
        }


        @media (max-width: 768px) {
            .summary {
                flex-direction: column;
                align-items: flex-start;
            }
            .action-buttons {
                flex-direction: column;
            }
            .form-row, .search-row {
                flex-direction: column;
            }
            table {
                min-width: 900px;
            }
            .nav-tabs {
                flex-direction: column;
            }
            .chart-container {
                height: 200px;
                max-width: 100%;
                margin-bottom: 15px;
            }
            .section-title {
                font-size: 16px;
                margin-bottom: 10px;
            }
            .summary {
                font-size: 14px;
            }
        }
    </style>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.9.1/chart.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/fuse.js/6.6.2/fuse.min.js"></script>
</head>
<body>
    <h1>Pencatatan Keuangan Juli 2025<span id="status-indicator" class="status-indicator status-saved">Saved</span></h1>
    
    <div class="nav-tabs">
        <div class="nav-tab active" onclick="switchTab('transactions')">💰 Transaksi</div>
        <div class="nav-tab" onclick="switchTab('pending')">🔄 Transfer & Pending</div>
    </div>

    <div id="transactions-tab" class="tab-content active">
        <div class="card main-card">
            <div class="section-title">Tambah Transaksi</div>
            
            <div class="form-row">
                <div>
                    <label for="tanggal">Tanggal</label>
                    <input type="date" id="tanggal" name="tanggal">
                </div>
                <div>
                    <label for="jenis-akun">Jenis Akun</label>
                    <select id="jenis-akun" name="jenis-akun">
                        <option value="cash">💵 Cash</option>
                        <option value="saldo">🪪 Saldo</option>
                    </select>
                </div>
            </div>
            
            <div class="form-row">
                <div class="currency-format">
                    <label for="pemasukan">Pemasukan</label>
                    <input type="text" id="pemasukan" name="pemasukan" placeholder="0">
                </div>
                <div class="currency-format">
                    <label for="pengeluaran">Pengeluaran</label>
                    <input type="text" id="pengeluaran" name="pengeluaran" placeholder="0">
                </div>
            </div>
            
            <label for="kategori">Kategori</label>
            <select id="kategori" name="kategori">
                <option value="lainnya">Lainnya</option>
                <option value="parkir">🅿️ Parkir</option>
                <option value="sekolah">🎓 Sekolah</option>
                <option value="jajan">🍭 Jajan</option>
                <option value="uang-mingguan">💰 Uang Mingguan</option>
                <option value="shopping">🛍️ Shopping</option>
            </select>
            
            <label for="keterangan">Alasan/Keterangan</label>
            <input type="text" id="keterangan" name="keterangan" placeholder="Keterangan transaksi">
            
            <div class="recurring-checkbox">
                <input type="checkbox" id="is-recurring">
                <label for="is-recurring">Transaksi Berulang</label>
            </div>
            
            <div class="recurring-options" id="recurring-options">
                <label for="recurring-type">Jenis Pengulangan</label>
                <select id="recurring-type">
                    <option value="weekly">Mingguan</option>
                    <option value="monthly">Bulanan</option>
                    <option value="daily">Harian</option>
                </select>
                
                <label for="recurring-count">Jumlah Pengulangan</label>
                <input type="number" id="recurring-count" min="1" max="52" value="4" placeholder="Berapa kali diulang">
            </div>
            
            <button id="tambah-btn">Tambah Transaksi</button>
        </div>
        
        <div class="card">
            <div class="summary">
                <div class="section-title">Ringkasan Keuangan</div>
                <div class="saldo-info">
                    <div class="saldo-item">Saldo: <span class="green">Rp <span id="saldo-bank">0</span></span></div>
                    <div class="saldo-item">Cash: <span class="blue">Rp <span id="saldo-cash">0</span></span></div>
                    <div class="saldo-item">Pending: <span class="orange">Rp <span id="saldo-pending">0</span></span></div>
                    <div class="saldo-item">Total: <span id="total-saldo">Rp 0</span></div>
                </div>
            </div>
        </div>
        
        <div class="card">
            <div class="section-title">Daftar Transaksi</div>
            
            <div class="search-container">
                <div class="search-row">
                    <div>
                        <label for="search-text">Cari Transaksi</label>
                        <input type="text" id="search-text" placeholder="Cari berdasarkan keterangan...">
                    </div>
                    <div>
                        <label for="search-category">Filter Kategori</label>
                        <select id="search-category">
                            <option value="">Semua Kategori</option>
                            <option value="parkir">🅿️ Parkir</option>
                            <option value="sekolah">🎓 Sekolah</option>
                            <option value="jajan">🍭 Jajan</option>
                            <option value="uang-mingguan">💰 Uang Mingguan</option>
                            <option value="shopping">🛍️ Shopping</option>
                            <option value="lainnya">Lainnya</option>
                        </select>
                    </div>
                    <div>
                        <label for="search-date-from">Dari Tanggal</label>
                        <input type="date" id="search-date-from">
                    </div>
                    <div>
                        <label for="search-date-to">Sampai Tanggal</label>
                        <input type="date" id="search-date-to">
                    </div>
                    <div>
                        <button id="clear-search-btn">Clear</button>
                    </div>
                </div>
            </div>
            
            <div class="action-buttons">
                <details class="dropdown">
                    <summary>Aksi</summary>
                    <div class="dropdown-content">
                        <button class="reset-btn" id="reset-btn">Reset Data</button>
                        <button class="export-btn" id="export-btn">Export CSV</button>
                        <div class="file-input-wrapper">
                            <input type="file" id="import-file" class="file-input" accept=".json,.csv">
                            <label for="import-file" class="file-input-label">Import Data</label>
                        </div>
                        <button class="pending-btn" id="add-pending-btn">Tambah Pending</button>
                    </div>
                </details>
            </div>
            
            <div class="table-container">
                <table id="transaksi-table">
                    <thead>
                        <tr>
                            <th>Tanggal</th>
                            <th>Jenis</th>
                            <th>Kategori</th>
                            <th>Pemasukan</th>
                            <th>Pengeluaran</th>
                            <th>Keterangan</th>
                            <th>Saldo Bank</th> <th>Cash</th> <th>Aksi</th>
                        </tr>
                    </thead>
                    <tbody id="transaksi-body">
                    </tbody>
                </table>
                <div class="table-summary">
                    <div class="saldo-item">Total Pemasukan: <span class="green">Rp <span id="total-pemasukan">0</span></span></div>
                    <div class="saldo-item">Total Pengeluaran: <span class="orange">Rp <span id="total-pengeluaran">0</span></span></div>
                    <div class="saldo-item">Total Saldo Net: <span id="total-table-saldo">Rp 0</span></div>
                </div>
            </div>
        </div>

        <div class="card">
            <div class="section-title">📊 Grafik Harian</div>
            <div class="chart-container">
                <canvas id="dailyChart"></canvas>
            </div>
        </div>

        <div class="card">
            <div class="section-title">📈 Statistik Keuangan</div>
            <div id="insights-section">
                <h3>Insights Otomatis</h3>
                <div id="insights-content">
                    <p style="text-align: center; color: #666;">Memuat insights...</p>
                </div>
            </div>
            <hr>
            <div class="form-row">
                <div class="chart-container">
                    <div class="section-title">Kategori Pengeluaran</div>
                    <canvas id="categoryChart"></canvas>
                </div>
                <div class="chart-container">
                    <div class="section-title">Transaksi Mingguan/Bulanan</div>
                    <select id="period-selector">
                        <option value="weekly">Mingguan</option>
                        <option value="monthly">Bulanan</option>
                    </select>
                    <canvas id="periodChart"></canvas>
                </div>
            </div>
            <div class="summary">
                <div class="saldo-item">Rata-rata Pemasukan Harian: <span class="green">Rp <span id="avg-pemasukan">0</span></span></div>
                <div class="saldo-item">Rata-rata Pengeluaran Harian: <span class="orange">Rp <span id="avg-pengeluaran">0</span></span></div>
            </div>
        </div>

        <div class="card">
            <div class="section-title">🎯 Target Tabungan</div>
            <div>
                <label for="savings-target-desc">Deskripsi Target</label>
                <input type="text" id="savings-target-desc" placeholder="Contoh: Beli Gadget Baru">
            </div>
            <div class="currency-format">
                <label for="savings-target-amount">Jumlah Target</label>
                <input type="text" id="savings-target-amount" placeholder="0">
            </div>
            <div>
                <label for="savings-target-date">Target Tanggal</label>
                <input type="date" id="savings-target-date">
            </div>
            <button id="set-savings-target-btn">Tetapkan Target</button>

            <div id="current-savings-target" style="margin-top: 20px;">
                <p style="text-align: center; color: #666;">Belum ada target tabungan yang ditetapkan.</p>
            </div>
        </div>

    </div>

    <div id="pending-tab" class="tab-content">
        <div class="card">
            <div class="section-title">💰 Uang Pending</div>
            <div id="pending-list">
            </div>
        </div>

        <div class="card">
            <div class="section-title">🔄 Transfer Uang</div>
            
            <div class="form-row">
                <div>
                    <label for="transfer-from">Dari</label>
                    <select id="transfer-from">
                        <option value="cash">Cash</option>
                        <option value="saldo">Saldo</option>
                        <option value="pending">Pending</option>
                    </select>
                </div>
                <div>
                    <label for="transfer-to">Ke</label>
                    <select id="transfer-to">
                        <option value="saldo">Saldo</option>
                        <option value="cash">Cash</option>
                    </select>
                </div>
            </div>
            
            <div class="currency-format">
                <label for="transfer-amount">Jumlah Transfer</label>
                <input type="text" id="transfer-amount" placeholder="0">
            </div>
            
            <label for="transfer-note">Catatan Transfer</label>
            <input type="text" id="transfer-note" placeholder="Catatan transfer (opsional)">
            
            <button id="transfer-btn">Transfer</button>
        </div>

        <div class="card">
            <div class="section-title">📋 Riwayat Transfer</div>
            <div id="transfer-history-list">
                <p style="text-align: center; color: #666;">Belum ada riwayat transfer.</p>
            </div>
        </div>
    </div>

    <div id="editModal" class="modal">
        <div class="modal-content">
            <span class="close-btn">×</span>
            <h3>Edit Transaksi</h3>
            
            <div class="form-row">
                <div>
                    <label for="edit-tanggal">Tanggal</label>
                    <input type="date" id="edit-tanggal">
                </div>
                <div>
                    <label for="edit-jenis-akun">Jenis Akun</label>
                    <select id="edit-jenis-akun">
                        <option value="saldo">Saldo</option>
                        <option value="cash">Cash</option>
                    </select>
                </div>
            </div>
            
            <div class="form-row">
                <div class="currency-format">
                    <label for="edit-pemasukan">Pemasukan</label>
                    <input type="text" id="edit-pemasukan" placeholder="0">
                </div>
                <div class="currency-format">
                    <label for="edit-pengeluaran">Pengeluaran</label>
                    <input type="text" id="edit-pengeluaran" placeholder="0">
                </div>
            </div>
            
            <label for="edit-kategori">Kategori</label>
            <select id="edit-kategori">
                <option value="lainnya">Lainnya</option>
                <option value="parkir">🅿️ Parkir</option>
                <option value="sekolah">🎓 Sekolah</option>
                <option value="jajan">🍭 Jajan</option>
                <option value="uang-mingguan">💰 Uang Mingguan</option>
                <option value="shopping">🛍️ Shopping</option>
            </select>
            
            <label for="edit-keterangan">Keterangan</label>
            <input type="text" id="edit-keterangan" placeholder="Keterangan transaksi">
            
            <button id="save-edit-btn">Simpan Perubahan</button>
        </div>
    </div>

    <div id="pendingModal" class="modal">
        <div class="modal-content">
            <span class="close-btn" id="close-pending-modal">×</span>
            <h3>Tambah Uang Pending</h3>
            
            <label for="pending-description">Deskripsi</label>
            <input type="text" id="pending-description" placeholder="Contoh: Uang jajan mingguan">
            
            <div class="currency-format">
                <label for="pending-amount">Jumlah</label>
                <input type="text" id="pending-amount" placeholder="0">
            </div>
            
            <label for="pending-date">Tanggal Diharapkan</label>
            <input type="date" id="pending-date">
            
            <button id="add-pending-confirm-btn">Tambah Pending</button>
        </div>
    </div>

    <script>
        let transaksiList = [];
        let pendingList = [];
        let transferHistory = []; // New array for transfer history
        let savingsTarget = null; // Object for savings target
        let saldoBank = 0;
        let saldoCash = 0;
        let saldoPending = 0;
        let editingIndex = -1;
        let dailyChart = null;
        let categoryChart = null;
        let periodChart = null;
        let filteredTransaksi = [];
        
        const kategoriLabels = {
            'parkir': '🅿️ Parkir',
            'sekolah': '🎓 Sekolah',
            'jajan': '🍭 Jajan',
            'uang-mingguan': '💰 Uang Mingguan',
            'shopping': '🛍️ Shopping',
            'lainnya': 'Lainnya',
            'pending': '⏳ Pending'
        };
        
        const tanggalInput = document.getElementById('tanggal');
        const jenisAkunInput = document.getElementById('jenis-akun');
        const pemasukanInput = document.getElementById('pemasukan');
        const pengeluaranInput = document.getElementById('pengeluaran');
        const kategoriInput = document.getElementById('kategori');
        const keteranganInput = document.getElementById('keterangan');
        const isRecurringInput = document.getElementById('is-recurring');
        const recurringOptions = document.getElementById('recurring-options');
        const recurringTypeInput = document.getElementById('recurring-type');
        const recurringCountInput = document.getElementById('recurring-count');
        const tambahBtn = document.getElementById('tambah-btn');
        const resetBtn = document.getElementById('reset-btn');
        const exportBtn = document.getElementById('export-btn');
        const importFileInput = document.getElementById('import-file');
        const addPendingBtn = document.getElementById('add-pending-btn');
        const transaksiBody = document.getElementById('transaksi-body');
        const saldoBankDisplay = document.getElementById('saldo-bank');
        const saldoCashDisplay = document.getElementById('saldo-cash');
        const saldoPendingDisplay = document.getElementById('saldo-pending');
        const totalSaldoDisplay = document.getElementById('total-saldo');
        const statusIndicator = document.getElementById('status-indicator');
        const pendingList_DOM = document.getElementById('pending-list');
        const transferHistoryList_DOM = document.getElementById('transfer-history-list'); // DOM for transfer history
        
        const searchTextInput = document.getElementById('search-text');
        const searchCategoryInput = document.getElementById('search-category');
        const searchDateFromInput = document.getElementById('search-date-from');
        const searchDateToInput = document.getElementById('search-date-to');
        const clearSearchBtn = document.getElementById('clear-search-btn');
        
        const transferFromInput = document.getElementById('transfer-from');
        const transferToInput = document.getElementById('transfer-to');
        const transferAmountInput = document.getElementById('transfer-amount');
        const transferNoteInput = document.getElementById('transfer-note');
        const transferBtn = document.getElementById('transfer-btn');

        const insightsContent = document.getElementById('insights-content'); // For insights
        
        const editModal = document.getElementById('editModal');
        const pendingModal = document.getElementById('pendingModal');
        const closeBtn = document.querySelector('.close-btn');
        const closePendingBtn = document.getElementById('close-pending-modal');
        const saveEditBtn = document.getElementById('save-edit-btn');
        const addPendingConfirmBtn = document.getElementById('add-pending-confirm-btn');

        const savingsTargetDescInput = document.getElementById('savings-target-desc');
        const savingsTargetAmountInput = document.getElementById('savings-target-amount');
        const savingsTargetDateInput = document.getElementById('savings-target-date');
        const setSavingsTargetBtn = document.getElementById('set-savings-target-btn');
        const currentSavingsTargetDiv = document.getElementById('current-savings-target');
        
        function formatCurrency(value) {
            const numbers = String(value).replace(/\D/g, '');
            return numbers.replace(/\B(?=(\d{3})+(?!\d))/g, '.');
        }
        
        function parseCurrency(value) {
            return parseInt(String(value).replace(/\D/g, '')) || 0;
        }
        
        function setupCurrencyInputs() {
            const currencyInputs = [
                pemasukanInput, pengeluaranInput, transferAmountInput,
                document.getElementById('edit-pemasukan'),
                document.getElementById('edit-pengeluaran'),
                document.getElementById('pending-amount'),
                savingsTargetAmountInput
            ];
            
            currencyInputs.forEach(input => {
                if (input) {
                    input.addEventListener('input', (e) => {
                        const formatted = formatCurrency(e.target.value);
                        e.target.value = formatted;
                    });
                    
                    input.addEventListener('blur', (e) => {
                        const value = parseCurrency(e.target.value);
                        e.target.value = value > 0 ? formatCurrency(value.toString()) : '';
                    });
                }
            });
        }
        
        function switchTab(tabName) {
            document.querySelectorAll('.tab-content').forEach(tab => {
                tab.classList.remove('active');
            });
            document.querySelectorAll('.nav-tab').forEach(tab => {
                tab.classList.remove('active');
            });
            
            document.getElementById(tabName + '-tab').classList.add('active');
            // Find the clicked tab, it's not always event.target in all scenarios, so better to find it
            document.querySelector(`.nav-tab[onclick="switchTab('${tabName}')"]`).classList.add('active');
            
            if (tabName === 'pending') {
                updatePendingList();
                updateTransferHistoryList(); // Update transfer history when switching tab
            }
        }
        
        const today = new Date();
        const formattedDate = today.toISOString().substr(0, 10);
        tanggalInput.value = formattedDate;
        
        tambahBtn.addEventListener('click', tambahTransaksi);
        resetBtn.addEventListener('click', resetData);
        exportBtn.addEventListener('click', exportToCSV);
        importFileInput.addEventListener('change', importData);
        addPendingBtn.addEventListener('click', () => pendingModal.style.display = 'block');
        addPendingConfirmBtn.addEventListener('click', addPending);
        transferBtn.addEventListener('click', transferMoney);
        closeBtn.addEventListener('click', closeModal);
        closePendingBtn.addEventListener('click', () => pendingModal.style.display = 'none');
        saveEditBtn.addEventListener('click', saveEdit);
        setSavingsTargetBtn.addEventListener('click', setSavingsTarget);
        
        searchTextInput.addEventListener('input', filterTransactions);
        searchCategoryInput.addEventListener('change', filterTransactions);
        searchDateFromInput.addEventListener('change', filterTransactions);
        searchDateToInput.addEventListener('change', filterTransactions);
        clearSearchBtn.addEventListener('click', clearSearch);
        
        isRecurringInput.addEventListener('change', (e) => {
            recurringOptions.style.display = e.target.checked ? 'block' : 'none';
        });
        
        document.getElementById('period-selector').addEventListener('change', updatePeriodChart);
        
        window.addEventListener('click', (e) => {
            if (e.target === editModal) {
                closeModal();
            }
            if (e.target === pendingModal) {
                pendingModal.style.display = 'none';
            }
        });
        
        function tambahTransaksi() {
            const tanggal = tanggalInput.value;
            const jenisAkun = jenisAkunInput.value;
            const pemasukan = parseCurrency(pemasukanInput.value);
            const pengeluaran = parseCurrency(pengeluaranInput.value);
            const kategori = kategoriInput.value;
            const keterangan = keteranganInput.value;
            const isRecurring = isRecurringInput.checked;
            
            if (!tanggal || (!pemasukan && !pengeluaran)) {
                alert('Harap isi tanggal dan minimal salah satu dari pemasukan atau pengeluaran!');
                return;
            }
            
            if (isRecurring) {
                const recurringType = recurringTypeInput.value;
                const recurringCount = parseInt(recurringCountInput.value) || 1;
                
                for (let i = 0; i < recurringCount; i++) {
                    const currentDate = new Date(tanggal);
                    
                    if (recurringType === 'weekly') {
                        currentDate.setDate(currentDate.getDate() + (i * 7));
                    } else if (recurringType === 'monthly') {
                        currentDate.setMonth(currentDate.getMonth() + i);
                    } else if (recurringType === 'daily') {
                        currentDate.setDate(currentDate.getDate() + i);
                    }
                    
                    const formattedDate = currentDate.toISOString().substr(0, 10);
                    const suffix = i > 0 ? ` (${i + 1}/${recurringCount})` : '';
                    
                    const transaksi = {
                        id: Date.now() + i,
                        tanggal: formattedDate,
                        jenisAkun: jenisAkun,
                        pemasukan: pemasukan,
                        pengeluaran: pengeluaran,
                        kategori: kategori,
                        keterangan: keterangan + suffix
                    };
                    
                    transaksiList.push(transaksi);
                }
            } else {
                const transaksi = {
                    id: Date.now(),
                    tanggal: tanggal,
                    jenisAkun: jenisAkun,
                    pemasukan: pemasukan,
                    pengeluaran: pengeluaran,
                    kategori: kategori,
                    keterangan: keterangan
                };
                
                transaksiList.push(transaksi);
            }
            
            updateAllDisplays(); // Consolidated update function
            clearForm();
            saveToLocalStorage();
            showSaveStatus();
        }
        
        function clearForm() {
            pemasukanInput.value = '';
            pengeluaranInput.value = '';
            keteranganInput.value = '';
            isRecurringInput.checked = false;
            recurringOptions.style.display = 'none';
            recurringCountInput.value = '4';
        }
        
        function updateSaldo() {
            saldoBank = 0;
            saldoCash = 0;
            
            transaksiList.forEach(transaksi => {
                if (transaksi.jenisAkun === 'saldo') {
                    saldoBank += transaksi.pemasukan - transaksi.pengeluaran;
                } else if (transaksi.jenisAkun === 'cash') {
                    saldoCash += transaksi.pemasukan - transaksi.pengeluaran;
                }
            });
            
            saldoPending = pendingList.reduce((total, item) => total + item.amount, 0);
            
            saldoBankDisplay.textContent = formatCurrency(saldoBank.toString());
            saldoCashDisplay.textContent = formatCurrency(saldoCash.toString());
            saldoPendingDisplay.textContent = formatCurrency(saldoPending.toString());
            const totalSaldo = saldoBank + saldoCash;
            const totalClass = totalSaldo < 0 ? 'red' : 'green';
            totalSaldoDisplay.innerHTML = `<span class="${totalClass}">Rp ${totalSaldo < 0 ? '-' : ''}${formatCurrency(Math.abs(totalSaldo).toString())}</span>`;
        }
        
        function updateTransaksiTable() {
            const tableBody = transaksiBody;
            tableBody.innerHTML = '';
            
            const dataToShow = filteredTransaksi.length > 0 ? filteredTransaksi : transaksiList;
            const sortedData = [...dataToShow].sort((a, b) => new Date(b.tanggal) - new Date(a.tanggal));
            
            let totalPemasukan = 0;
            let totalPengeluaran = 0;
            
            // To get accurate running balances for each transaction row:
            // Calculate running balances by re-processing all transactions up to that point
            const chronologicalList = [...transaksiList].sort((a, b) => new Date(a.tanggal).getTime() - new Date(b.tanggal).getTime() || a.id - b.id);

            sortedData.forEach(transaksi => {
                let currentRunningBank = 0;
                let currentRunningCash = 0;
                
                for (const t of chronologicalList) {
                    if (new Date(t.tanggal).getTime() < new Date(transaksi.tanggal).getTime() || 
                       (new Date(t.tanggal).getTime() === new Date(transaksi.tanggal).getTime() && t.id <= transaksi.id)) {
                        if (t.jenisAkun === 'saldo') {
                            currentRunningBank += t.pemasukan - t.pengeluaran;
                        } else if (t.jenisAkun === 'cash') {
                            currentRunningCash += t.pemasukan - t.pengeluaran;
                        }
                    } else if (new Date(t.tanggal).getTime() > new Date(transaksi.tanggal).getTime()) {
                        // Optimization: if we've passed the current transaction's date, no need to go further for running balance
                        break; 
                    }
                }
                
                totalPemasukan += transaksi.pemasukan;
                totalPengeluaran += transaksi.pengeluaran;
                
                const saldoBankClass = currentRunningBank < 0 ? 'red' : 'green';
                const saldoCashClass = currentRunningCash < 0 ? 'red' : 'green';
                
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td>${formatDate(transaksi.tanggal)}</td>
                    <td>${transaksi.jenisAkun === 'saldo' ? '💳 Saldo' : '💵 Cash'}</td>
                    <td><span class="kategori-badge kategori-${transaksi.kategori}">${kategoriLabels[transaksi.kategori]}</span></td>
                    <td class="green">${transaksi.pemasukan > 0 ? 'Rp ' + formatCurrency(transaksi.pemasukan.toString()) : '-'}</td>
                    <td class="orange">${transaksi.pengeluaran > 0 ? 'Rp ' + formatCurrency(transaksi.pengeluaran.toString()) : '-'}</td>
                    <td>${transaksi.keterangan}</td>
                    <td class="${saldoBankClass}">Rp ${currentRunningBank < 0 ? '-' : ''}${formatCurrency(Math.abs(currentRunningBank).toString())}</td>
                    <td class="${saldoCashClass}">Rp ${currentRunningCash < 0 ? '-' : ''}${formatCurrency(Math.abs(currentRunningCash).toString())}</td>
                    <td class="action-cell">
                        <button class="edit-btn" onclick="editTransaksi(${transaksi.id})">Edit</button>
                        <button class="delete-btn" onclick="deleteTransaksi(${transaksi.id})">Hapus</button>
                    </td>
                `;
                tableBody.appendChild(row);
            });
            
            document.getElementById('total-pemasukan').textContent = formatCurrency(totalPemasukan.toString());
            document.getElementById('total-pengeluaran').textContent = formatCurrency(totalPengeluaran.toString());
            const totalSaldoNet = totalPemasukan - totalPengeluaran;
            const totalSaldoClass = totalSaldoNet < 0 ? 'red' : 'green';
            document.getElementById('total-table-saldo').innerHTML = `<span class="${totalSaldoClass}">Rp ${totalSaldoNet < 0 ? '-' : ''}${formatCurrency(Math.abs(totalSaldoNet).toString())}</span>`;
        }
        
        function formatDate(dateString) {
            const date = new Date(dateString);
            const options = { 
                weekday: 'short', 
                year: 'numeric', 
                month: 'short', 
                day: 'numeric' 
            };
            return date.toLocaleDateString('id-ID', options);
        }
        
        function editTransaksi(id) {
            const transaksi = transaksiList.find(t => t.id === id);
            if (!transaksi) return;
            
            editingIndex = transaksiList.findIndex(t => t.id === id);
            
            document.getElementById('edit-tanggal').value = transaksi.tanggal;
            document.getElementById('edit-jenis-akun').value = transaksi.jenisAkun;
            document.getElementById('edit-pemasukan').value = transaksi.pemasukan > 0 ? formatCurrency(transaksi.pemasukan.toString()) : '';
            document.getElementById('edit-pengeluaran').value = transaksi.pengeluaran > 0 ? formatCurrency(transaksi.pengeluaran.toString()) : '';
            document.getElementById('edit-kategori').value = transaksi.kategori;
            document.getElementById('edit-keterangan').value = transaksi.keterangan;
            
            editModal.style.display = 'block';
        }
        
        function saveEdit() {
            if (editingIndex === -1) return;
            
            const editedTransaksi = {
                ...transaksiList[editingIndex],
                tanggal: document.getElementById('edit-tanggal').value,
                jenisAkun: document.getElementById('edit-jenis-akun').value,
                pemasukan: parseCurrency(document.getElementById('edit-pemasukan').value),
                pengeluaran: parseCurrency(document.getElementById('edit-pengeluaran').value),
                kategori: document.getElementById('edit-kategori').value,
                keterangan: document.getElementById('edit-keterangan').value
            };
            
            transaksiList[editingIndex] = editedTransaksi;
            
            updateAllDisplays();
            closeModal();
            saveToLocalStorage();
            showSaveStatus();
        }
        
        function deleteTransaksi(id) {
            if (confirm('Apakah Anda yakin ingin menghapus transaksi ini?')) {
                transaksiList = transaksiList.filter(t => t.id !== id);
                updateAllDisplays();
                saveToLocalStorage();
                showSaveStatus();
            }
        }
        
        function closeModal() {
            editModal.style.display = 'none';
            editingIndex = -1;
        }
        
        function resetData() {
            if (confirm('Apakah Anda yakin ingin menghapus semua data? Tindakan ini tidak dapat dibatalkan!')) {
                transaksiList = [];
                pendingList = [];
                transferHistory = [];
                savingsTarget = null;
                updateAllDisplays();
                saveToLocalStorage();
                showSaveStatus();
                updateSavingsTargetDisplay(); // Clear savings display
            }
        }
        
        function exportToCSV() {
            if (transaksiList.length === 0) {
                alert('Tidak ada data untuk diekspor!');
                return;
            }
            
            const headers = ['Tanggal', 'Jenis Akun', 'Kategori', 'Pemasukan', 'Pengeluaran', 'Keterangan'];
            const csvContent = [
                headers.join(','),
                ...transaksiList.map(t => [
                    t.tanggal,
                    t.jenisAkun,
                    t.kategori,
                    t.pemasukan,
                    t.pengeluaran,
                    `"${t.keterangan ? t.keterangan.replace(/"/g, '""') : ''}"`
                ].join(','))
            ].join('\n');
            
            const blob = new Blob([csvContent], { type: 'text/csv;charset=utf-8;' });
            const link = document.createElement('a');
            link.href = URL.createObjectURL(blob);
            link.download = `keuangan_${new Date().toISOString().substr(0, 10)}.csv`;
            link.click();
        }
        
        function importData(event) {
            const file = event.target.files[0];
            if (!file) return;
            
            const reader = new FileReader();
            reader.onload = function(e) {
                try {
                    let importedData;
                    
                    if (file.name.endsWith('.json')) {
                        const data = JSON.parse(e.target.result);
                        importedData = data.transaksiList || data;
                        if (data.pendingList) pendingList = data.pendingList;
                        if (data.transferHistory) transferHistory = data.transferHistory;
                        if (data.savingsTarget) savingsTarget = data.savingsTarget;

                    } else if (file.name.endsWith('.csv')) {
                        const lines = e.target.result.split('\n');
                        // Assuming CSV format: Tanggal,Jenis Akun,Kategori,Pemasukan,Pengeluaran,Keterangan
                        const headers = lines[0].split(','); // This is just for reference, not strictly used
                        
                        importedData = lines.slice(1)
                            .filter(line => line.trim())
                            .map(line => {
                                const values = line.split(/,(?=(?:(?:[^"]*"){2})*[^"]*$)/); // Split by comma outside quotes
                                return {
                                    id: Date.now() + Math.random(),
                                    tanggal: values[0]?.trim() || '',
                                    jenisAkun: values[1]?.trim() || 'saldo',
                                    kategori: values[2]?.trim() || 'lainnya',
                                    pemasukan: parseCurrency(values[3]),
                                    pengeluaran: parseCurrency(values[4]),
                                    keterangan: values[5]?.replace(/"/g, '').trim() || ''
                                };
                            });
                    }
                    
                    if (importedData && Array.isArray(importedData)) {
                        if (confirm(`Ditemukan ${importedData.length} transaksi. Apakah Anda ingin menggabungkan dengan data yang ada?`)) {
                            transaksiList = [...transaksiList, ...importedData];
                        } else {
                            transaksiList = importedData;
                        }
                        
                        updateAllDisplays();
                        saveToLocalStorage();
                        showSaveStatus();
                        alert('Data berhasil diimpor!');
                    }
                } catch (error) {
                    alert('Error saat mengimpor data. Pastikan format file benar: ' + error.message);
                    console.error('Import Error:', error);
                }
            };
            reader.readAsText(file);
        }
        
        function addPending() {
            const description = document.getElementById('pending-description').value;
            const amount = parseCurrency(document.getElementById('pending-amount').value);
            const date = document.getElementById('pending-date').value;
            
            if (!description || !amount || !date) {
                alert('Harap isi semua field!');
                return;
            }
            
            const pending = {
                id: Date.now(),
                description: description,
                amount: amount,
                date: date,
                created: new Date().toISOString().substr(0, 10)
            };
            
            pendingList.push(pending);
            updateAllDisplays();
            saveToLocalStorage();
            showSaveStatus();
            
            document.getElementById('pending-description').value = '';
            document.getElementById('pending-amount').value = '';
            document.getElementById('pending-date').value = '';
            pendingModal.style.display = 'none';
        }
        
        function updatePendingList() {
            const container = pendingList_DOM;
            container.innerHTML = '';
            
            if (pendingList.length === 0) {
                container.innerHTML = '<p style="text-align: center; color: #666; margin: 20px 0;">Tidak ada uang pending.</p>';
                return;
            }
            
            pendingList.forEach(pending => {
                const item = document.createElement('div');
                item.className = 'pending-item';
                item.innerHTML = `
                    <div class="pending-info">
                        <div><strong>${pending.description}</strong></div>
                        <div>Jumlah: <span class="green">Rp ${formatCurrency(pending.amount.toString())}</span></div>
                        <div>Tanggal: ${formatDate(pending.date)}</div>
                        <div><small>Dibuat: ${formatDate(pending.created)}</small></div>
                    </div>
                    <div class="pending-actions">
                        <button class="transfer-btn" onclick="realizePending(${pending.id})">Realisasi</button>
                        <button class="delete-btn" onclick="deletePending(${pending.id})">Hapus</button>
                    </div>
                `;
                container.appendChild(item);
            });
        }
        
        function realizePending(id) {
            const pending = pendingList.find(p => p.id === id);
            if (!pending) return;
            
            const choice = confirm(`Realisasi "${pending.description}" sebesar Rp ${formatCurrency(pending.amount.toString())}?\n\nKlik OK untuk menambah ke Saldo Bank, Cancel untuk menambah ke Cash.`);
            const jenisAkun = choice ? 'saldo' : 'cash';
            
            const transaksi = {
                id: Date.now(),
                tanggal: new Date().toISOString().substr(0, 10),
                jenisAkun: jenisAkun,
                pemasukan: pending.amount,
                pengeluaran: 0,
                kategori: 'pending',
                keterangan: `Realisasi: ${pending.description}`
            };
            
            transaksiList.push(transaksi);
            
            pendingList = pendingList.filter(p => p.id !== id);
            
            updateAllDisplays();
            saveToLocalStorage();
            showSaveStatus();
        }
        
        function deletePending(id) {
            if (confirm('Apakah Anda yakin ingin menghapus item pending ini?')) {
                pendingList = pendingList.filter(p => p.id !== id);
                updateAllDisplays();
                saveToLocalStorage();
                showSaveStatus();
            }
        }
        
        function transferMoney() {
            const fromAccount = transferFromInput.value;
            const toAccount = transferToInput.value;
            const amount = parseCurrency(transferAmountInput.value);
            const note = transferNoteInput.value || 'Transfer antar akun';
            
            if (!amount || amount <= 0) {
                alert('Jumlah transfer harus lebih dari 0!');
                return;
            }
            
            if (fromAccount === toAccount) {
                alert('Akun tujuan harus berbeda dengan akun sumber!');
                return;
            }
            
            let sourceBalance = 0;
            if (fromAccount === 'saldo') {
                sourceBalance = saldoBank;
            } else if (fromAccount === 'cash') {
                sourceBalance = saldoCash;
            } else if (fromAccount === 'pending') {
                sourceBalance = saldoPending;
            }
            
            if (sourceBalance < amount) {
                alert(`Saldo ${fromAccount} tidak mencukupi! Saldo tersedia: Rp ${formatCurrency(sourceBalance.toString())}`);
                return;
            }
            
            const today = new Date().toISOString().substr(0, 10);
            
            if (fromAccount !== 'pending') {
                const withdrawalTransaction = {
                    id: Date.now(),
                    tanggal: today,
                    jenisAkun: fromAccount,
                    pemasukan: 0,
                    pengeluaran: amount,
                    kategori: 'lainnya', // Using 'lainnya' for transfers
                    keterangan: `Transfer ke ${toAccount}: ${note}`
                };
                transaksiList.push(withdrawalTransaction);
            } else {
                 // Adjust pending amounts if transferring from pending
                let amountToDeduct = amount;
                const newPendingList = [];
                for (let i = 0; i < pendingList.length; i++) {
                    let p = pendingList[i];
                    if (amountToDeduct > 0) {
                        if (p.amount <= amountToDeduct) {
                            amountToDeduct -= p.amount;
                        } else {
                            p.amount -= amountToDeduct;
                            amountToDeduct = 0;
                            newPendingList.push(p);
                        }
                    } else {
                        newPendingList.push(p);
                    }
                }
                pendingList = newPendingList.filter(p => p.amount > 0);
            }
            
            if (toAccount !== 'pending') {
                const depositTransaction = {
                    id: Date.now() + 1,
                    tanggal: today,
                    jenisAkun: toAccount,
                    pemasukan: amount,
                    pengeluaran: 0,
                    kategori: 'lainnya', // Using 'lainnya' for transfers
                    keterangan: `Transfer dari ${fromAccount}: ${note}`
                };
                transaksiList.push(depositTransaction);
            }
            
            // Record transfer history
            transferHistory.push({
                id: Date.now(),
                date: today,
                from: fromAccount,
                to: toAccount,
                amount: amount,
                note: note
            });

            updateAllDisplays();
            saveToLocalStorage();
            showSaveStatus();
            
            transferAmountInput.value = '';
            transferNoteInput.value = '';
            
            alert(`Transfer berhasil! Rp ${formatCurrency(amount.toString())} telah ditransfer dari ${fromAccount} ke ${toAccount}.`);
        }

        function updateTransferHistoryList() {
            const container = transferHistoryList_DOM;
            container.innerHTML = '';

            if (transferHistory.length === 0) {
                container.innerHTML = '<p style="text-align: center; color: #666; margin: 20px 0;">Belum ada riwayat transfer.</p>';
                return;
            }

            const sortedHistory = [...transferHistory].sort((a, b) => new Date(b.date) - new Date(a.date));

            sortedHistory.forEach(transfer => {
                const item = document.createElement('div');
                item.className = 'transfer-history-item';
                item.innerHTML = `
                    <strong>${formatDate(transfer.date)}</strong>: Transfer Rp ${formatCurrency(transfer.amount.toString())} dari <strong>${transfer.from === 'saldo' ? 'Saldo Bank' : transfer.from === 'cash' ? 'Cash' : 'Pending'}</strong> ke <strong>${transfer.to === 'saldo' ? 'Saldo Bank' : 'Cash'}</strong>.
                    ${transfer.note ? ` (${transfer.note})` : ''}
                `;
                container.appendChild(item);
            });
        }
        
        function filterTransactions() {
            const searchText = searchTextInput.value.toLowerCase();
            const searchCategory = searchCategoryInput.value;
            const searchDateFrom = searchDateFromInput.value;
            const searchDateTo = searchDateToInput.value;
            
            let results = transaksiList;
            
            if (searchText) {
                const fuse = new Fuse(transaksiList, {
                    keys: ['keterangan', 'kategori', 'jenisAkun'], // Search across more fields
                    threshold: 0.4,
                    ignoreLocation: true
                });
                results = fuse.search(searchText).map(result => result.item);
            }
            
            filteredTransaksi = results.filter(transaksi => {
                const matchCategory = !searchCategory || transaksi.kategori === searchCategory;
                const matchDateFrom = !searchDateFrom || transaksi.tanggal >= searchDateFrom;
                const matchDateTo = !searchDateTo || transaksi.tanggal <= searchDateTo;
                
                return matchCategory && matchDateFrom && matchDateTo;
            });
            
            updateTransaksiTable();
        }
        
        function clearSearch() {
            searchTextInput.value = '';
            searchCategoryInput.value = '';
            searchDateFromInput.value = '';
            searchDateToInput.value = '';
            filteredTransaksi = [];
            updateTransaksiTable();
        }
        
        function updateChart() {
            updateDailyChart(); // Renamed function for clarity
            updateCategoryChart();
            updatePeriodChart();
            updateAverageDaily();
            updateInsights(); // New function for insights
        }

        function updateDailyChart() { // Renamed from updateChart
            const ctx = document.getElementById('dailyChart').getContext('2d');
            
            const dailyData = {};
            const last30Days = [];
            
            for (let i = 29; i >= 0; i--) {
                const date = new Date();
                date.setDate(date.getDate() - i);
                const dateStr = date.toISOString().substr(0, 10);
                last30Days.push(dateStr);
                dailyData[dateStr] = { pemasukan: 0, pengeluaran: 0, net: 0 };
            }
            
            transaksiList.forEach(transaksi => {
                if (dailyData[transaksi.tanggal]) {
                    dailyData[transaksi.tanggal].pemasukan += transaksi.pemasukan;
                    dailyData[transaksi.tanggal].pengeluaran += transaksi.pengeluaran;
                    dailyData[transaksi.tanggal].net += (transaksi.pemasukan - transaksi.pengeluaran);
                }
            });
            
            const labels = last30Days.map(date => {
                const d = new Date(date);
                return d.toLocaleDateString('id-ID', { day: '2-digit', month: '2-digit' });
            });
            
            const pemasukanData = last30Days.map(date => dailyData[date].pemasukan);
            const pengeluaranData = last30Days.map(date => dailyData[date].pengeluaran);
            const netData = last30Days.map(date => dailyData[date].net);
            
            if (dailyChart) {
                dailyChart.destroy();
            }
            
            dailyChart = new Chart(ctx, {
                type: 'line',
                data: {
                    labels: labels,
                    datasets: [{
                        label: 'Pemasukan',
                        data: pemasukanData,
                        borderColor: '#28a745',
                        backgroundColor: '#28a745', // For filled area
                        fill: false,
                        tension: 0.1
                    }, {
                        label: 'Pengeluaran',
                        data: pengeluaranData,
                        borderColor: '#dc3545',
                        backgroundColor: '#dc3545', // For filled area
                        fill: false,
                        tension: 0.1
                    }, {
                        label: 'Net',
                        data: netData,
                        borderColor: '#007bff',
                        backgroundColor: '#007bff', // For filled area
                        fill: false,
                        tension: 0.1
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: true,
                    animation: {
                        duration: 500
                    },
                    scales: {
                        y: {
                            beginAtZero: true,
                            ticks: {
                                font: { size: 10 },
                                callback: function(value) {
                                    return 'Rp ' + formatCurrency(value.toString());
                                }
                            }
                        },
                        x: {
                            ticks: {
                                font: { size: 10 },
                                maxRotation: 45,
                                minRotation: 45
                            }
                        }
                    },
                    plugins: {
                        legend: {
                            labels: {
                                font: { size: 10 }
                            }
                        },
                        tooltip: {
                            callbacks: {
                                label: function(context) {
                                    return context.dataset.label + ': Rp ' + formatCurrency(context.parsed.y.toString());
                                }
                            },
                            titleFont: { size: 12 },
                            bodyFont: { size: 10 }
                        }
                    }
                }
            });
        }
        
        function updateCategoryChart() {
            const ctx = document.getElementById('categoryChart').getContext('2d');
            
            const categoryData = {};
            Object.keys(kategoriLabels).forEach(kategori => {
                categoryData[kategori] = 0;
            });
            
            transaksiList.forEach(transaksi => {
                if (transaksi.pengeluaran > 0) {
                    categoryData[transaksi.kategori] += transaksi.pengeluaran;
                }
            });
            
            const labels = Object.keys(categoryData).filter(k => categoryData[k] > 0);
            const data = labels.map(k => categoryData[k]);
            
            if (categoryChart) {
                categoryChart.destroy();
            }
            
            categoryChart = new Chart(ctx, {
                type: 'pie',
                data: {
                    labels: labels.map(k => kategoriLabels[k]),
                    datasets: [{
                        data: data,
                        backgroundColor: [
                            '#1976d2', '#7b1fa2', '#f57c00', '#388e3c', '#c2185b', '#616161', '#856404'
                        ]
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: true,
                    animation: {
                        duration: 500
                    },
                    plugins: {
                        legend: {
                            position: 'bottom',
                            labels: {
                                font: { size: 10 },
                                generateLabels: function(chart) {
                                    return chart.data.labels.map((label, i) => ({
                                        text: `${label} (Rp ${formatCurrency(chart.data.datasets[0].data[i].toString())})`, // Show amount in legend
                                        fillStyle: chart.data.datasets[0].backgroundColor[i],
                                        font: { size: 10 }
                                    }));
                                }
                            }
                        },
                        tooltip: {
                            callbacks: {
                                label: function(context) {
                                    const total = context.dataset.data.reduce((sum, val) => sum + val, 0);
                                    const percentage = total > 0 ? ((context.parsed / total) * 100).toFixed(2) : 0;
                                    return `${context.label}: Rp ${formatCurrency(context.parsed.toString())} (${percentage}%)`;
                                }
                            },
                            titleFont: { size: 12 },
                            bodyFont: { size: 10 }
                        }
                    }
                }
            });
        }
        
        function updatePeriodChart() {
            const period = document.getElementById('period-selector').value;
            const ctx = document.getElementById('periodChart').getContext('2d');
            
            const periodData = {};
            const labels = [];
            
            if (period === 'weekly') {
                for (let i = 3; i >= 0; i--) {
                    const weekStart = new Date();
                    weekStart.setDate(weekStart.getDate() - (weekStart.getDay() + 7 - 1) % 7 + (i * 7 * -1)); // Adjust to start of the week (Monday)
                    weekStart.setHours(0, 0, 0, 0);

                    const weekEnd = new Date(weekStart);
                    weekEnd.setDate(weekEnd.getDate() + 6);
                    weekEnd.setHours(23, 59, 59, 999);

                    const label = `Minggu ${weekStart.toLocaleDateString('id-ID', { day: '2-digit', month: 'short' })}`;
                    labels.unshift(label); // Add to the beginning to maintain chronological order
                    periodData[label] = { pemasukan: 0, pengeluaran: 0 };
                }
                
                transaksiList.forEach(transaksi => {
                    const transDate = new Date(transaksi.tanggal);
                    transDate.setHours(12,0,0,0); // Avoid timezone issues

                    for (let i = 0; i < labels.length; i++) {
                        const weekLabel = labels[i];
                        const weekStart = new Date(weekLabel.substring(weekLabel.indexOf(' ') + 1)); // Parse date from label
                        const weekEnd = new Date(weekStart);
                        weekEnd.setDate(weekEnd.getDate() + 6);
                        weekEnd.setHours(23, 59, 59, 999);
                        
                        if (transDate >= weekStart && transDate <= weekEnd) {
                            periodData[weekLabel].pemasukan += transaksi.pemasukan;
                            periodData[weekLabel].pengeluaran += transaksi.pengeluaran;
                            break; // Stop once found the correct week
                        }
                    }
                });
            } else { // Monthly
                for (let i = 3; i >= 0; i--) {
                    const monthStart = new Date();
                    monthStart.setMonth(monthStart.getMonth() - i, 1); // Set to 1st of the month
                    monthStart.setHours(0, 0, 0, 0);

                    const label = monthStart.toLocaleDateString('id-ID', { month: 'short', year: 'numeric' });
                    labels.unshift(label);
                    periodData[label] = { pemasukan: 0, pengeluaran: 0 };
                }
                
                transaksiList.forEach(transaksi => {
                    const transDate = new Date(transaksi.tanggal);
                    transDate.setHours(12,0,0,0); // Avoid timezone issues

                    for (let i = 0; i < labels.length; i++) {
                        const monthLabel = labels[i];
                        const monthStart = new Date(monthLabel); // This will parse month and year
                        monthStart.setDate(1);
                        monthStart.setHours(0, 0, 0, 0);

                        const monthEnd = new Date(monthStart);
                        monthEnd.setMonth(monthEnd.getMonth() + 1, 0); // Last day of the month
                        monthEnd.setHours(23, 59, 59, 999);
                        
                        if (transDate >= monthStart && transDate <= monthEnd) {
                            periodData[monthLabel].pemasukan += transaksi.pemasukan;
                            periodData[monthLabel].pengeluaran += transaksi.pengeluaran;
                            break; // Stop once found the correct month
                        }
                    }
                });
            }
            
            const pemasukanData = labels.map(label => periodData[label].pemasukan);
            const pengeluaranData = labels.map(label => periodData[label].pengeluaran);
            
            if (periodChart) {
                periodChart.destroy();
            }
            
            periodChart = new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: labels,
                    datasets: [{
                        label: 'Pemasukan',
                        data: pemasukanData,
                        backgroundColor: '#28a745'
                    }, {
                        label: 'Pengeluaran',
                        data: pengeluaranData,
                        backgroundColor: '#dc3545'
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: true,
                    animation: {
                        duration: 500
                    },
                    scales: {
                        y: {
                            beginAtZero: true,
                            ticks: {
                                font: { size: 10 },
                                callback: function(value) {
                                    return 'Rp ' + formatCurrency(value.toString());
                                }
                            }
                        },
                        x: {
                            ticks: {
                                font: { size: 10 },
                                maxRotation: 45,
                                minRotation: 45
                            }
                        }
                    },
                    plugins: {
                        legend: {
                            position: 'bottom',
                            labels: {
                                font: { size: 10 }
                            }
                        },
                        tooltip: {
                            callbacks: {
                                label: function(context) {
                                    return context.dataset.label + ': Rp ' + formatCurrency(context.parsed.y.toString());
                                }
                            },
                            titleFont: { size: 12 },
                            bodyFont: { size: 10 }
                        }
                    }
                }
            });
        }
        
        function updateAverageDaily() {
            const uniqueDays = [...new Set(transaksiList.map(t => t.tanggal))];
            const totalPemasukan = transaksiList.reduce((sum, t) => sum + t.pemasukan, 0);
            const totalPengeluaran = transaksiList.reduce((sum, t) => sum + t.pengeluaran, 0);
            
            const avgPemasukan = uniqueDays.length > 0 ? totalPemasukan / uniqueDays.length : 0;
            const avgPengeluaran = uniqueDays.length > 0 ? totalPengeluaran / uniqueDays.length : 0;
            
            document.getElementById('avg-pemasukan').textContent = formatCurrency(Math.round(avgPemasukan).toString());
            document.getElementById('avg-pengeluaran').textContent = formatCurrency(Math.round(avgPengeluaran).toString());
        }
        
        function updateInsights() {
            const now = new Date();
            // Get current week's start (Sunday)
            const currentWeekStart = new Date(now);
            currentWeekStart.setDate(now.getDate() - now.getDay());
            currentWeekStart.setHours(0, 0, 0, 0);

            // Get previous week's start
            const lastWeekStart = new Date(currentWeekStart);
            lastWeekStart.setDate(lastWeekStart.getDate() - 7);

            let currentWeekExpenses = 0;
            let lastWeekExpenses = 0;
            const categoryExpenses = {};
            let totalOverallExpenses = 0;

            transaksiList.forEach(t => {
                const transDate = new Date(t.tanggal);
                if (t.pengeluaran > 0) {
                    totalOverallExpenses += t.pengeluaran;

                    if (transDate >= currentWeekStart) {
                        currentWeekExpenses += t.pengeluaran;
                    } else if (transDate >= lastWeekStart && transDate < currentWeekStart) {
                        lastWeekExpenses += t.pengeluaran;
                    }
                    categoryExpenses[t.kategori] = (categoryExpenses[t.kategori] || 0) + t.pengeluaran;
                }
            });

            insightsContent.innerHTML = ''; // Clear previous insights

            // Insight 1: Weekly Expense Comparison
            let weeklyInsightText = '';
            let weeklyInsightClass = '';
            if (currentWeekExpenses === 0 && lastWeekExpenses === 0) {
                weeklyInsightText = 'Tidak ada pengeluaran tercatat untuk dua minggu terakhir.';
            } else if (lastWeekExpenses === 0) {
                weeklyInsightText = `Pengeluaran minggu ini: Rp ${formatCurrency(currentWeekExpenses.toString())}. Belum ada data pengeluaran minggu lalu.`;
                weeklyInsightClass = 'warning';
            } else {
                const percentageChange = ((currentWeekExpenses - lastWeekExpenses) / lastWeekExpenses) * 100;
                if (percentageChange > 0) {
                    weeklyInsightText = `Pengeluaranmu minggu ini <strong>naik ${percentageChange.toFixed(2)}%</strong> (Rp ${formatCurrency(currentWeekExpenses.toString())}) dibanding minggu lalu (Rp ${formatCurrency(lastWeekExpenses.toString())}). Perhatikan pengeluaranmu!`;
                    weeklyInsightClass = 'danger';
                } else if (percentageChange < 0) {
                    weeklyInsightText = `Pengeluaranmu minggu ini <strong>turun ${Math.abs(percentageChange).toFixed(2)}%</strong> (Rp ${formatCurrency(currentWeekExpenses.toString())}) dibanding minggu lalu (Rp ${formatCurrency(lastWeekExpenses.toString())}). Bagus!`;
                    weeklyInsightClass = 'green';
                } else {
                    weeklyInsightText = `Pengeluaranmu minggu ini sama dengan minggu lalu: Rp ${formatCurrency(currentWeekExpenses.toString())}.`;
                }
            }
            insightsContent.appendChild(createInsightItem(weeklyInsightText, weeklyInsightClass));

            // Insight 2: Top Spending Category
            let topCategory = null;
            let maxExpense = 0;
            Object.keys(categoryExpenses).forEach(cat => {
                if (categoryExpenses[cat] > maxExpense) {
                    maxExpense = categoryExpenses[cat];
                    topCategory = cat;
                }
            });

            if (topCategory && totalOverallExpenses > 0) {
                const categoryPercentage = (maxExpense / totalOverallExpenses) * 100;
                let categoryInsightClass = '';
                if (categoryPercentage > 50) categoryInsightClass = 'danger';
                else if (categoryPercentage > 30) categoryInsightClass = 'warning';
                
                insightsContent.appendChild(createInsightItem(`Kategori <strong>${kategoriLabels[topCategory]}</strong> mendominasi <strong>${categoryPercentage.toFixed(2)}%</strong> (Rp ${formatCurrency(maxExpense.toString())}) dari total pengeluaranmu.`, categoryInsightClass));
            } else if (totalOverallExpenses === 0) {
                insightsContent.appendChild(createInsightItem('Belum ada pengeluaran tercatat untuk menganalisis kategori.'));
            }
        }

        function createInsightItem(text, className = '') {
            const div = document.createElement('div');
            div.className = `insight-item ${className}`;
            div.innerHTML = text;
            return div;
        }

        function setSavingsTarget() {
            const description = savingsTargetDescInput.value;
            const amount = parseCurrency(savingsTargetAmountInput.value);
            const targetDate = savingsTargetDateInput.value;

            if (!description || !amount || !targetDate) {
                alert('Harap isi semua detail target tabungan!');
                return;
            }

            savingsTarget = {
                description: description,
                amount: amount,
                targetDate: targetDate,
                startDate: new Date().toISOString().substr(0, 10)
            };
            saveToLocalStorage();
            updateSavingsTargetDisplay();
            alert('Target tabungan berhasil ditetapkan!');
            savingsTargetDescInput.value = '';
            savingsTargetAmountInput.value = '';
            savingsTargetDateInput.value = '';
        }

        function updateSavingsTargetDisplay() {
            if (!savingsTarget) {
                currentSavingsTargetDiv.innerHTML = '<p style="text-align: center; color: #666;">Belum ada target tabungan yang ditetapkan.</p>';
                return;
            }

            let totalSavingsToDate = 0;
            // Sum net positive contributions from transactions towards savings
            // This is a simplified calculation: all net income goes towards savings.
            // A more complex system would require marking specific transactions as savings.
            // For now, let's use the total current balance.
            totalSavingsToDate = saldoBank + saldoCash; // Combined available balance

            const progress = Math.max(0, Math.min(100, (totalSavingsToDate / savingsTarget.amount) * 100));
            const remainingAmount = Math.max(0, savingsTarget.amount - totalSavingsToDate);
            const remainingDays = Math.ceil((new Date(savingsTarget.targetDate) - new Date()) / (1000 * 60 * 60 * 24));
            
            let message = '';
            let progressClass = '';
            if (progress >= 100) {
                message = `Selamat! Target "${savingsTarget.description}" (Rp ${formatCurrency(savingsTarget.amount.toString())}) telah **tercapai!**`;
                progressClass = 'green';
            } else if (remainingDays <= 0) {
                message = `Target "${savingsTarget.description}" (Rp ${formatCurrency(savingsTarget.amount.toString())}) **belum tercapai**, target tanggal ${formatDate(savingsTarget.targetDate)} telah terlewati! Kurang Rp ${formatCurrency(remainingAmount.toString())}.`;
                progressClass = 'danger';
            } else {
                message = `Target "${savingsTarget.description}" (Rp ${formatCurrency(savingsTarget.amount.toString())}) progres: **${progress.toFixed(2)}%**. Kurang Rp ${formatCurrency(remainingAmount.toString())} dalam ${remainingDays} hari.`;
                if (progress > 75) progressClass = 'green';
                else if (progress > 50) progressClass = 'blue';
                else if (progress > 25) progressClass = 'orange';
                else progressClass = 'red';
            }

            currentSavingsTargetDiv.innerHTML = `
                <p><strong>${message}</strong></p>
                <div class="progress-container">
                    <div class="progress-bar ${progressClass}" style="width: ${progress}%;">
                        ${progress.toFixed(2)}%
                    </div>
                </div>
                <small>Ditetapkan pada: ${formatDate(savingsTarget.startDate)}</small>
            `;
        }

        function saveToLocalStorage() {
            const data = {
                transaksiList: transaksiList,
                pendingList: pendingList,
                transferHistory: transferHistory, // Save transfer history
                savingsTarget: savingsTarget, // Save savings target
                lastSaved: new Date().toISOString()
            };
            
            try {
                localStorage.setItem('keuanganData', JSON.stringify(data));
                showSaveStatus(true);
            } catch (error) {
                console.error('Error saving to localStorage:', error);
                showSaveStatus(false);
            }
        }
        
        function loadFromLocalStorage() {
            try {
                const data = localStorage.getItem('keuanganData');
                if (data) {
                    const parsedData = JSON.parse(data);
                    transaksiList = parsedData.transaksiList || [];
                    pendingList = parsedData.pendingList || [];
                    transferHistory = parsedData.transferHistory || []; // Load transfer history
                    savingsTarget = parsedData.savingsTarget || null; // Load savings target
                    
                    updateAllDisplays(); // Consolidated update function
                    showSaveStatus(true);
                }
            } catch (error) {
                console.error('Error loading from localStorage:', error);
                showSaveStatus(false);
            }
        }
        
        function showSaveStatus(success = true) {
            if (success) {
                statusIndicator.className = 'status-indicator status-saved';
                statusIndicator.textContent = 'Saved';
            } else {
                statusIndicator.className = 'status-indicator status-unsaved';
                statusIndicator.textContent = 'Error';
            }
        }

        function updateAllDisplays() {
            updateSaldo();
            updateTransaksiTable();
            updatePendingList();
            updateTransferHistoryList(); // Update transfer history display
            updateChart(); // This already calls all chart updates including insights
            updateSavingsTargetDisplay(); // Update savings target display
        }
        
        setInterval(() => {
            if (transaksiList.length > 0 || pendingList.length > 0 || transferHistory.length > 0 || savingsTarget) {
                saveToLocalStorage();
            }
        }, 30000);
        
        function init() {
            setupCurrencyInputs();
            loadFromLocalStorage();
            
            transferFromInput.value = 'cash';
            transferToInput.value = 'saldo';
        }
        
        init();
    </script>
</body>
</html>
