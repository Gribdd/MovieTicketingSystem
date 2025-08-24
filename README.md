# 🎬 WinWin Cinema Desktop
A desktop movie ticketing application built using **.NET MAUI**.  
This project allows customers to book movie tickets, choose seats, and make payments, while administrators can create malls, assign cinemas, and manage users.  

Since database systems (DBMS) and APIs were not yet covered at the time of development, the project uses **JSON serialization** for data storage. 

![WinWin Cinema Desktop](https://i.postimg.cc/HLshNLgh/Software-Development-2-1.png)

---

## 🌟 Highlights
- 🎟️ Ticket booking with seat selection  
- 🏢 Admin rights for mall and cinema management  
- 👥 Customer account creation for booking history  
- 💳 Payment simulation  
- 📦 Local JSON serialization for data persistence  

---
## 💻 Tech Stack

| Layer           | Technology       |
|-----------------|------------------|
| Language        | C#               |
| Framework       | .NET MAUI        |
| Storage         | JSON Serialization |
| IDE             | Visual Studio 2022 |

## ⬇️ Installation
You’ll need **Git**, and **Visual Studio 2022** with the **.NET desktop development workload** installed.  

### Git  
- Download and install Git from the official website: [Git Downloads](https://git-scm.com/downloads)  
- Verify the installation:  
  ```bash
  git --version
  ```
### Visual Studio 2022 IDE Download
Download Visual Studio 2022 from the official website: Visual Studio Downloads.

### .NET SDK & MAUI Workload  
- Download and install the .NET SDK (7.0 or later) from the official website: [.NET Downloads](https://dotnet.microsoft.com/en-us/download)  
- Install the MAUI workload:  
  ```bash
  dotnet workload install maui
  ```
- Verify the installation:  
  ```bash
  dotnet --version
  ```
  
## ⚡ Running the Project  
1. Clone the repository:
   ```bash
   git clone https://github.com/Gribdd/MovieTicketingSystem.git
   cd MovieTicketingSystem
   ```
  
2. Restore and build the project:
   ```bash
   dotnet restore
   dotnet build
   ```
3. Run the project:
   ```bash
   dotnet run
   ```

## 🤝 Contributing  

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.  

---

## 📜 License  

This project is licensed under the MIT License.  












   
