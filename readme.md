# Ultimate Bill Splitter

A feature-rich, single-page web application designed to make splitting bills and tracking expenses among friends effortless. Everything runs securely in your browser with offline auto-saving.

## Main File
To run this application, simply visit **https://antarikdawn.github.io/Ultimate-Bill-Splitter-by-Antarik-Dawn/** or open the **index.html** file in any modern web browser.

## Key Features

* **No Backend Required:** Runs entirely client-side. Data is auto-saved locally in your browser using `localStorage`.
* **Dynamic Expense Splitting:** Split items evenly or by specific quantities/shares.
* **Direct Payments:** Log direct transfers (e.g., UPI, Cash) between individuals mid-trip.
* **Smart Settlement Algorithm:** Automatically calculates the most optimized way to settle all debts with the fewest number of transactions.
* **Individual Bills:** Generate and share personalized breakdown bills for each person.
* **Import & Export:** 
  * Export all data to an Excel file.
  * Import an existing Excel summary back into the app.
* **Sharing Options:**
  * Copy summary or individual bills directly to WhatsApp.
  * Download a clean PDF summary of the entire event.

## How to Use

1. **Setup Party:** Launch `index.html`. Enter an event name, optional dates, and the number of people splitting the bill.
2. **Enter Names:** Provide a name for each participant.
3. **Add Expenses:** Log what was bought, how much it cost, who paid for it, and who shared it. Use the "Edit Quantities" toggle if someone had more or less of a shared item.
4. **Log Payments:** If someone pays someone else directly during the trip, log it in the "Direct Payment" section.
5. **Settle Up:** Check the "Optimized Settlement Plan" at the bottom to see exactly who owes whom to clear all balances.
6. **Share:** Use the "WhatsApp Text" or "Download PDF" buttons at the top, or click the individual "Share" buttons next to each person's name in the summary table.

## Technologies Used

* **HTML/CSS/JavaScript:** Core application logic and styling.
* **SheetJS (xlsx):** Used for importing and exporting Excel files.
* **html2pdf.js:** Used for generating downloadable PDF summaries.
