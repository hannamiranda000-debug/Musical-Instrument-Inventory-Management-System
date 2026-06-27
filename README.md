# 🎸 Musical Instrument Inventory Management System

A robust tracking system designed to manage, categorize, and audit musical instruments. This application helps music shops, schools, or collectors keep a real-time log of their gear, conditions, and valuations.

## ✨ Features
*   **CRUD Operations:** Add, view, update, and delete instruments seamlessly.
*   **Categorization:** Filter inventory by instrument families (Strings, Brass, Woodwinds, Percussion, Keys).
*   **Status Tracking:** Monitor gear availability (Available, In Repair, Rented out, Sold).
*   **Financial Summary:** Automatically calculate total inventory value and depreciation.

## 🛠️ Tech Stack
*   **Language:** Python 3.x
*   **Database:** SQLite / PostgreSQL *(Choose one)*
*   **Libraries used:** Pandas (for data manipulation), Tabulate (for terminal formatting)

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed on your machine.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Navigate to the project directory:
   ```bash
   cd musical-instrument-inventory
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application
Execute the main script to launch the system:
```bash
python main.py
```

## 📊 Sample Data Structure
Each instrument record contains the following attributes:
*   `ID`: Unique identifier (UUID or Auto-incrementing Integer)
*   `Name`: e.g., Fender Stratocaster
*   `Category`: e.g., Strings / Electric Guitar
*   `Serial Number`: Unique manufacturer code
*   `Condition`: New / Excellent / Good / Fair / Poor
*   `Price`: Acquisition and retail cost

## 🤝 Contributing
Contributions are welcome! Please fork this repository and open a pull request with your suggested changes.

## 📄 License
This project is open-source and available under the MIT License.
