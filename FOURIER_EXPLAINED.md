## 🌍 Languages / Limbi / Lingue

<div style="display: flex;">
  <div style="text-align: center;">
    <h3>🇬🇧 **English**</h3>
    <a href="#english">Go to English</a>
  </div>

  <div style="text-align: center;">
    <h3>🇷🇴 **Romanian**</h3>
    <a href="#romana">Go to Romanian</a>
  </div>

  <div style="text-align: center;">
    <h3>🇮🇹 **Italian**</h3>
    <a href="#italiano">Go to Italian</a>
  </div>
</div>


# 📊 Fourier Transform in JavaScript: Bitcoin Price Analysis

The **Fourier Transform (FT)** is a powerful mathematical technique that allows decomposing a signal into its component frequencies. This approach is fundamental for analyzing **cyclical patterns** and **periodicity** in data, such as those related to cryptocurrency market movements.

---

## 🔍 What is the Fourier Transform?

The FT converts a time series (such as Bitcoin prices) into a sum of sinusoids with specific frequencies. It allows you to:

- **Decompose complex signals** into simpler components.
- **Identify dominant frequencies**, i.e., regular periods in the data.
  
This technique is useful for discovering **hidden cycles** and **recurring patterns** that are not visible in the time domain.

---

## ⚡️ How Does FFT Work in JavaScript?

In JavaScript, we use the **Fast Fourier Transform (FFT)**, an optimized version of the Fourier Transform, to analyze time series data. The **fft.js** library is a great solution for this purpose.

### Steps:

1. **Collect Data**: Obtain historical Bitcoin price data (e.g., hourly or daily).
2. **Apply FFT**: Use `fft.js` to apply the FFT to the numerical data.
3. **Analyze Frequencies**: Identify the dominant frequencies and analyze the cyclical patterns in the data.

---

## 📈 Practical Application: Bitcoin Price Analysis

### 🎯 Goal

The goal is to **discover hidden cyclical patterns** in Bitcoin's price behavior to improve trading predictions.

### 🧠 How It Works

1. **Data Collection**:
   - Obtain historical Bitcoin prices organized as a time series.

2. **Applying FFT**:
   - Use the `fft.js` library to apply the FFT to the data and extract the dominant frequencies.

3. **Frequency Analysis**:
   - Look for frequencies that appear repeatedly, such as weekly, monthly, etc. These peaks may reveal cycles in the prices.

4. **Predictions and Correlations**:
   - **Evaluate** whether the identified frequencies align with external events, such as market fluctuations, economic changes, or news.
   - Use these **cyclical patterns** to predict future price movements.

---

## 💡 What Can You Gain from This Analysis?

- **Cyclic Pattern Detection**: Identify regular periods in Bitcoin prices, such as weekly or monthly fluctuations.
- **Trading Optimization**: Predict market movements based on historical cycles and trends.
- **Advanced Analysis**: Analyze the impact of external events on the cycles, such as economic or political news.

---

## 🚀 Getting Started with `fft.js`

1. **Install fft.js**:
   ```bash
   npm install fft.js


# 📊 Trasformata di Fourier in JavaScript: Analisi dei Prezzi di Bitcoin

La **Trasformata di Fourier (FT)** è una potente tecnica matematica che permette di decomporre un segnale in frequenze componenti. Questo approccio è fondamentale per l'analisi di **pattern ciclici** e **periodicità** nei dati, come quelli relativi ai movimenti di mercato delle criptovalute.

---

## 🔍 Cos'è la Trasformata di Fourier?

La FT converte una sequenza temporale (come i prezzi del Bitcoin) in una somma di sinusoidi con frequenze specifiche. Permette di:

- **Scomporre segnali complessi** in componenti più semplici.
- **Identificare frequenze dominanti**, cioè periodi regolari nei dati.
  
Questa tecnica è utile per scoprire **cicli nascosti** e **pattern ricorrenti** che non sono visibili nel dominio del tempo.

---

## ⚡️ Come Funziona la FFT in JavaScript?

In JavaScript, utilizziamo la **Fast Fourier Transform (FFT)**, una versione ottimizzata della Trasformata di Fourier, per analizzare serie temporali. La libreria **fft.js** è un'ottima soluzione per questo scopo.

### Passaggi:

1. **Raccolta Dati**: Ottieni i dati storici dei prezzi del Bitcoin (ad esempio, ogni ora o giorno).
2. **Applicazione FFT**: Usa `fft.js` per applicare la FFT sui dati numerici.
3. **Analisi delle Frequenze**: Individua le frequenze dominanti e analizza i pattern ciclici nei dati.

---

## 📈 Applicazione Pratica: Analisi dei Prezzi di Bitcoin

### 🎯 Obiettivo

L'obiettivo è **scoprire pattern ciclici nascosti** nel comportamento dei prezzi di Bitcoin per migliorare le previsioni di trading.

### 🧠 Come Funziona?

1. **Acquisizione Dati**:
   - Ottieni i prezzi storici di Bitcoin, organizzati come serie temporale.

2. **Applicazione della FFT**:
   - Usa la libreria `fft.js` per applicare la FFT ai dati e ottenere le frequenze dominanti.

3. **Analisi delle Frequenze**:
   - Cerca frequenze che appaiono ripetutamente, ad esempio settimanali, mensili, ecc. Questi picchi possono rivelare cicli nei prezzi.

4. **Previsioni e Correlazioni**:
   - **Valuta** se le frequenze individuate si allineano con eventi esterni, come fluttuazioni del mercato, cambiamenti economici o notizie.
   - Usa questi **pattern ciclici** per prevedere movimenti futuri dei prezzi.

---

## 💡 Cosa Puoi Ottenere da Questa Analisi?

- **Rilevazione di Pattern Ciclici**: Identifica periodi regolari nei prezzi del Bitcoin, come fluttuazioni settimanali o mensili.
- **Ottimizzazione del Trading**: Prevedi movimenti del mercato basandoti su cicli e tendenze storiche.
- **Analisi Avanzata**: Analizza l'impatto di eventi esterni sui cicli, come notizie economiche o politiche.

---

## 🚀 Come Iniziare con `fft.js`

1. **Installa fft.js**:
   ```bash
   npm install fft.js
