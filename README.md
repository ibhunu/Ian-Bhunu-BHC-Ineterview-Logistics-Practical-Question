# Ian-Bhunu-BHC-Ineterview-Logistics-Practical-Question
Project Description

This project automates warehouse storage operations, ensuring efficient management of warehouses, racks, lines, pallets, and packages. It supports different package types (loose and cartons) and enforces constraints on package placement and storage. The system facilitates package loading, offloading, and capacity management while tracking package history and warehouse utilization. Additionally, it implements search functionality by serial number and supports different offloading order strategies (Oldest/Newest first).

Features:

Warehouse Management: Handles multiple warehouses, racks, and storage lines.

Package Tracking: Monitors packages based on serial numbers and history.

Automated Storage Rules: Enforces constraints on package placement.

Load & Offload Operations: Supports package movement with different order strategies.

Utilization Monitoring: Tracks warehouse space and usage.

Search Functionality: Enables searching for packages by serial number.

Installation:
Clone the repository: git clone https://github.com/ibhunu/logistics-automation.git
cd logistics-automation

Set up a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

Install dependencies:
pip install -r requirements.txt

Run the main script:
python main.py

Usage Instructions

Adding Packages: Use the provided functions to store packages in appropriate storage locations.

Searching Packages: Query packages by their serial number.

Offloading Packages: Choose between oldest-first or newest-first retrieval.

Capacity Monitoring: Check warehouse space utilization.

Project Structure
logistics-automation/
│── storage_manager.py  # Core logic for managing storage
│── warehouse.py        # Warehouse and rack handling
│── package.py          # Package representation and tracking
│── main.py             # Entry point for the project
│── requirements.txt    # Dependencies (if any)
│── README.md           # Project documentation

Contributors
Ian Bhunu - Developer

License

This project is for interview purposes only  and is not licensed for commercial use. It is for the BHC Company in Harare Zimbabwe
