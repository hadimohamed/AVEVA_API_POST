# AVEVA JSON Data Bridge (DLL)

This repository contains a **C# .NET DLL** that integrates external JSON data into **AVEVA System Platform (ArchestrA)**.  
The DLL fetches live values from a local REST API and makes them available to AVEVA attributes.

---

## 🚀 Features
- Reads JSON from `http://localhost:9595/Data`
- Supports multiple values (`val01`, `val02`, …)
- Lightweight – just plug the DLL into AVEVA
- Error handling for missing or invalid JSON

---

## ⚙️ Requirements
- Windows 10/11  
- .NET Framework 4.7.2 (or compatible with your AVEVA version)  
- AVEVA System Platform (ArchestrA)  
- A local API providing JSON data  

---

## 📜 Example JSON Input
```json
{
  "val01": 28,
  "val02": 5,
  "val03": 37,
  "val04": 50
}
