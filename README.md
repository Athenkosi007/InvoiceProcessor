# InvoiceProcessor (SRP Example)

This C# console app demonstrates the **Single Responsibility Principle (SRP)** from SOLID design principles.

## ✅ Structure

- `Invoice`: holds the invoice data.
- `InvoiceProcessor`: contains logic to process invoices (e.g., save, validate).
- `InvoiceReporter`: prints invoice reports.

Each class has **one reason to change**:
- Changing invoice data affects `Invoice`.
- Changing processing rules affects `InvoiceProcessor`.
- Changing report format affects `InvoiceReporter`.
