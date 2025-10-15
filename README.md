# 🧠 Memory Access Pattern Modeling (Windows)

This project collects **Windows memory access traces** using **Windows Performance Recorder (WPR)** and analyzes them to understand memory access patterns.  
We process the traces into a dataset and evaluate simple memory replacement algorithms like **FIFO** and **LRU**.

---

## ⚙️ Setup

### 1️⃣ Install Tools

- Download and install **Windows Performance Toolkit**  
  👉 [Microsoft ADK Download Page](https://learn.microsoft.com/en-us/windows-hardware/get-started/adk-install)
- Run the file **adkwptsetup.exe**
- After install, verify it works:

```powershell
wpr -?
wpa
